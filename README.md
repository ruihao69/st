# Ruihao's Build of st - the suckless terminal emulator

source: [suckless/st](https://st.suckless.org)

you can get a copy yourself

```shell
git clone https://git.suckless.org/st
```

### logs

- 20210713: changed the fontsize to 22 pt.

### TODOs

- add scroll function to st

---

## This is the original `README`

st - simple terminal
--------------------
st is a simple terminal emulator for X which sucks less.


Requirements
------------
In order to build st you need the Xlib header files.


Installation
------------
Edit config.mk to match your local setup (st is installed into
the /usr/local namespace by default).

Afterwards enter the following command to build and install st (if
necessary as root):

```shell
make clean install
```


Running st
----------
If you did not install st with make clean install, you must compile
the st terminfo entry with the following command:

    tic -sx st.info

See the man page for additional details.

Credits
-------
Based on Aurélien APTEL <aurelien dot aptel at gmail dot com> bt source code.

