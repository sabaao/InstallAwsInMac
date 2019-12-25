# InstallAwsInMac

## Install Aws cli on Mac
```sh
brew install awscli
```

## Install Docker
you can download here
[Docker](https://docs.docker.com/docker-for-mac/install/)

## Install Kubectl
```sh
brew install kubectl 
```

## Install Eksctl
```sh
brew tap weaveworks/tap
brew install weaveworks/tap/eksctl
```

If you arleady installed, you can upgrade use this command
```sh
brew upgrade eksctl && brew link --overwrite eksctl
```

test eksctl
```sh
eksctl version
```

