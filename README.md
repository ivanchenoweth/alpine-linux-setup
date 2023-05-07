# alpine-linux-setup
Alpine Linux Setup

# Alpine Linux
## Base Installation
* download iso from internet

[https://dl-cdn.alpinelinux.org/alpine/v3.15/releases/x86_64/](https://dl-cdn.alpinelinux.org/alpine/v3.15/releases/x86_64/)

* create vm, boot
* run `setup-alpine` script
* `reboot`

## Auto Personalization (web apps)
* login as `root`
* `apk add git`
* `git clone https://github.com/ivanchenoweth/alpine-linux-setup`
* `cd alpine-linux-setup`
* `git checkout headless-noroot`
* `./setup.sh`
* type noroot password while installing ...
* `cd ..`
* `rm -rf alpine-linux-setup`
* `reboot`

## To create dev containers:
* `git clone https://github.com/ivanchenoweth/alpine-linux-setup`
* `cd alpine-linux-setup`

## Execute code-server container
* `cd dev-containers`
* `./code-server.sh`

## Manual Personalization for branches w/noroot rootless user 
* login as `noroot`
* `ssh-keygen`


````
eval `ssh-agent -s`
ssh-add
````

## YouTube Video where I was based:
* https://youtu.be/X_T-cKum8dc
