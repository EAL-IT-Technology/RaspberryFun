---
layout: page
title: Installing Raspberry
---

For this project we will use raspbarian, which is a debian distribution designed for the rasberry platform.

Initial installation
----------------------

The official installation instructions are found [here](https://www.raspberrypi.org/documentation/installation/installing-images/). 

Start by downloading the latest [Raspbian Jessie](https://downloads.raspberrypi.org/raspbian_latest), and then follow the installation instructions from the official guide.


Post-installation steps
------------------------

1. Refresh the packages

    > sudo apt-get update
    >
    > sudo apt-get upgrade


2. Change the hostname

    > sudo nano /etc/hostname

    change it to `raspberryXX`, where XX is your groupnumber


3. Change your password

    > passwd

    (notice that we are *not* using `sudo` for this)

4. Reboot

    >    sudo reboot


You should now be able to access your raspberry by hostname, ie. `ping raspberryXX`.
