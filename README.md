## st - simple terminal
This is pinosaur's patched fork of st from suckless.

The following patches are applied:
- [xresources](https://st.suckless.org/patches/xresources/)
- [blinking cursor](https://st.suckless.org/patches/blinking\_cursor/)
- [vim browse](https://st.suckless.org/patches/vim\_browse/)
- [w3m](https://st.suckless.org/patches/w3m/)
- [newterm](https://st.suckless.org/patches/newterm/)
- [plumb-keybind](https://gist.githubusercontent.com/MrPicklePinosaur/f393f660223f721b20da561e47c5ae07/raw/774e0339f53665e6a305f1aa69989d694b6cc674/st_simple_plumb_keybind.diff): modified rightclickplumb that allows a key binding to plumb

### Requirements
In order to build st you need the Xlib header files.

### Installation (make)
Edit config.mk to match your local setup (st is installed into
the /usr/local namespace by default).

Then run the following:
```
make && sudo make clean install
```

### Installation (ebuild)
For Gentoo users, an ebuild will be up on my website sometime.
The `savedconfig` use flag will be available.

