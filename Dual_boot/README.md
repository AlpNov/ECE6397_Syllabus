# University of Houston | ECE                                                                                 
# ECE 5397/6397: Introduction to Robotics                                                                      
# Spring 2016

* **Instructor**:  Dr. Aaron T. Becker
* **Teaching Assistant**: Li Huang
* **Author**: An Nguyen, [anguyen43@uh.edu][alpnov-email] 

# DUAL BOOTING UBUNTU 14.04 WITH WINDOWS/MAC
# FOR ROS INDIGO AND SWARMATHON ROS

## **NOTES**:

* This guide is meant to minimize the amount of work and time we spent at the install night. Instructions followed are from personal experience (except for the Mac portions, which came from Google). The instructions are also to minimize the chance of losing precious data from your only storage media, as no responsibility will be taken by anybody except yourself if that happens due to a [PEBCAK][PEBCAK-link] error.

* If you do not bring a 2 GB+ USB drive you are willing to overwrite with you to the install night, I might not be able to help you install Ubuntu.

* Install Ubuntu 14.04, i.e. the current Long Term Support (LTS) distribution, ROS Indigo doesn't install easily on newer distribution

## **Requirement**:

* If you're buying a new laptop, choose your hardware according to [this requirement thread][hardware-req]

* Generally an i5 processor or higher without integrated graphic card would be good

* **A large external hard drive to back up your current data with. So you won't lose your precious homeworks.**

* **At least a 2GB, high quality/speed usb drive to use as the installation medium. You will have to overwrite the USB's content so back this one up to.**

* **An Ethernet cable incase your wifi card firmware isn't already installed**

* Ubuntu 14.04.01/2/3, not newer (not 15.04 or 15.10)

* ROS Indigo, not newer or older (not Hydro or Jade)

## **BEFORE the install night, I.E. do this at home**:

### Shrink your partition, we need some space for Ubuntu
1. Defragment your main partition if needed (Windows only)
1. Srhink your main partition to get about 30-50 GB of unpartitioned free space on your hard drive
	1. [On Windows][win-shrink] (1GB = 1024MB or ~1000MB)
	1. [On Mac][mac-shrink]

### Create a live USB for Ubuntu
1. Download [Ubuntu 14.04 amd64][ubuntu-14.04] (amd64 = 64 bit), *ROS Swarmathon will not run on 32 bit due to library conflict*
1. [Create the live USB stick On Windows][win-usb]
1. [Create the live USB stick on Mac][mac-usb]

### Boot from the USB stick to test
1. On Windows, you will have to look up the specific key that will let you boot from the USB. A search on google for "boot from usb [brand]" should do the trick
1. [On a Mac][mac-boot] (This link also gives the rest of the installation steps on a mac)
1. Once the USB boots up, select "Try Ubuntu" [link][ubuntu-try]. Try to connect to a wireless network to know whether your wifi card works.

### **So the USB boots, what's next?**

At this point, if you feel confident enough, go ahead and [install ubuntu][ubuntu-install]. If not, shut down ubuntu and go along your day until the install night. Following is the instruction to install ROS Indigo and Swarmathon ROS code. These are the steps we will at the install night.

* [Install ROS Indigo][ros-install]
* [Install Swarmathon ROS][swarm-install] Don't follow the pdf, but the documentation page in the repository (README.md)
	

<!-- Links -->
[alpnov-email]:mailto:anguyen43@uh.edu
[hardware-req]:http://swarmathon.discussion.community/post/hardware-requirements-7838700?pid=1290165556
[win-shrink]:http://www.howtogeek.com/howto/windows-vista/resize-a-partition-for-free-in-windows-vista/
[mac-shrink]:http://osxdaily.com/2009/11/20/resize-partitions-in-mac-os-x-with-disk-utility/
[ubuntu-14.04]:http://releases.ubuntu.com/14.04/
[win-usb]:http://www.ubuntu.com/download/desktop/create-a-usb-stick-on-windows
[mac-usb]:http://www.ubuntu.com/download/desktop/create-a-usb-stick-on-mac-osx
[mac-boot]:http://askubuntu.com/questions/462360/macbook-air-how-to-install-a-dual-bootable-ubuntu-14-04-lts
[ubuntu-try]:http://www.ubuntu.com/download/desktop/try-ubuntu-before-you-install
[ubuntu-install]:http://www.ubuntu.com/download/desktop/install-ubuntu-desktop
[ros-install]:http://wiki.ros.org/indigo/Installation/Ubuntu
[swarm-install]:https://github.com/BCLab-UNM/Swarmathon-ROS
[PEBCAK-link]:http://www.catb.org/jargon/html/P/PEBKAC.html
