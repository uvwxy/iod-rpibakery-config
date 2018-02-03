# iod-rpibakery-config
Config file to create custom SD Card with [PiBakery](http://www.pibakery.org) tuned for SD-Card.

This is the config for my raspberry pi based sensor network, i.e. the "core". It will run the stack via docker.

I added a few things I found online to maybe increase the life and performance of the SD card.

## First Boot

- disable swap
- set /var/log to 4mb tmpfs
- minimal gpu_mem
- install docker
- install git
- install docker-compose
- disable vnc
- disable login via GPIO serial
- change ssh host keys
- boot to console
- set host name to iod-core
- set user password ⚠️️️️CHANGE THIS⚠️
- disable ext4 journal

## Every Boot

- start ssh