# linas-st
My version of the st-0.8.5 terminal.

## st - simple terminal
[st](https://st.suckless.org/) is a simple terminal emulator for X which sucks less.

From the great guys at [suckless](https://suckless.org/)

## Patches
- [xresources](https://st.suckless.org/patches/xresources/)
- [blinking cursor](https://st.suckless.org/patches/blinking_cursor/)
- [ligatures](https://st.suckless.org/patches/ligatures/)
- [alpha](https://st.suckless.org/patches/alpha/)
- [swapmouse](https://st.suckless.org/patches/swapmouse/)
- [xclearwin](https://st.suckless.org/patches/xclearwin/)
- [charoffsets](https://st.suckless.org/patches/charoffsets/)


## Requirements
In order to build st you need the Xlib header files and Harfbuzz library and headers.

## Installation
Edit config.mk to match your local setup (st is installed into
the /usr/local namespace by default).

Afterwards enter the following command to build and install st (if
necessary as root):

    make clean install


## Running st
If you did not install st with make clean install, you must compile
the st terminfo entry with the following command:

    tic -sx st.info

See the man page for additional details.

## Credits
Based on Aurélien APTEL <aurelien dot aptel at gmail dot com> bt source code.

