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

- [Terminalkeys](https://tools.suckless.org/slock/patches/terminalkeys/slock-terminalkeys-1.4.diff)
- [Mediakeys](https://patch-diff.githubusercontent.com/raw/phenax/bslock/pull/1.diff)
