# alpine-linux-setup
Alpine Linux Setup

# Alpine Linux
## Base Installation
* download iso from internet
* create vm, boot
* run `setup-alpine` script
* `reboot`

## Auto Personalization
* login as `root`
* `apk add git`
* `git clone https://github.com/ivanchenoweth/alpine-linux-setup`
* `cd alpine-linux-setup`
* `git checkout headless`
* `./setup.sh`
* type cheno password
* `cd ..`
* `rm -rf alpine-linux-setup`
* `reboot`
* 
* `git clone https://github.com/ivanchenoweth/alpine-linux-setup`
* `cd alpine-linux-setup`

## Execut container code-server 
* `cd dev-containers`
* `./code-server.sh`


## Manual Personalization for branches w/cheno noroot user
* login as `cheno`
* `ssh-keygen`

## Manual Personalization for branches w/ibuetler noroot  user
* login as `ibuetler`
* `ssh-keygen`

````
eval `ssh-agent -s`
ssh-add
````
## YouTube Video
* https://youtu.be/X_T-cKum8dc
