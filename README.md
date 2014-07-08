ansible-rpi
======

My [Ansible](http://www.ansible.com/) configuration for [Raspberry Pi](http://www.raspberrypi.org/). This allows me to provision Raspberry Pis to carry out a specific set of roles, having [installed Raspbian](http://www.raspberrypi.org/documentation/installation/installing-images/README.md) and running the Raspberry Pi setup script after first boot.

# Roles

## wifi
Sets up the Raspberry Pi to use a wi-fi network.

## core
Installs OS updates and some useful packages.

## camera
Sets up the Raspberry Pi camera module.

## eyefi_host
Sets up an image download host for the [Eye-Fi SD cards](http://www.eyefi.com/) using [node-eyefi](https://github.com/komola/node-eyefi).

## mpd_host
Sets up an MPD music playing host.

## retropie
Sets up RetroPie emulators.
