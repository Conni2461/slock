# slock fork - simple screen locker

[simple screen locker](https://tools.suckless.org/slock) utility for X.


## Requirements

In order to build slock you need the Xlib header files.


## Installation

Edit config.mk to match your local setup (slock is installed into
the /usr/local namespace by default).

Afterwards enter the following command to build and install slock
(if necessary as root):

	make clean install


## Running slock

Simply invoke the 'slock' command. To get out of it, enter your password.

## Applied Patches

- [Blurpixelatedscreen](https://tools.suckless.org/slock/patches/blur-pixelated-screen/slock-blur_pixelated_screen-1.4.diff)
- [Message](https://tools.suckless.org/slock/patches/message/slock-message-20191002-b46028b.diff)
- [Terminalkeys](https://tools.suckless.org/slock/patches/terminalkeys/slock-terminalkeys-1.4.diff)
- [Mediakeys](https://tools.suckless.org/slock/patches/mediakeys/)
