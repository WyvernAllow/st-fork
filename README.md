# st - simple terminal
st is a simple terminal emulator for X which sucks less.

# About this fork
This is a fork of st. The original can be found at https://st.suckless.org/

# Requirements
In order to build st you need the Xlib header files.

# Installation
Edit config.mk to match your local setup (st is installed into
the /usr/local namespace by default).

Afterwards enter the following command to build and install st (if
necessary as root):

```shell
make clean install
```

# Running st
If you did not install st with make clean install, you must compile
the st terminfo entry with the following command:

```shell
tic -sx st.info
```

See the man page for additional details.

# Credits
- Forked from https://git.suckless.org/st
- Based on Aurélien APTEL <aurelien dot aptel at gmail dot com> bt source code.