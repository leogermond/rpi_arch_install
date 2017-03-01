# RPi Arch install scripts
Scripts and resources for installing and maintaining an Arch distro on raspberry-pi

The install\_image script is not much more than a copy/paste from [https://archlinuxarm.org/platforms/armv6/raspberry-pi]

These script are working on the current directory, using the following paths:

- img For storing and loading images
- root For mounting the raspberry pi root
- boot For mounting the raspberry pi root

Be careful all commands will ask you to have a root access, as they are manipulating images while keeping the permissions intact: lots of files belonging to root on it!
