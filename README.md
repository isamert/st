# st
This is my st fork.

# Applied patches
- [alpha](https://st.suckless.org/patches/alpha/)
- [externalpipe](https://st.suckless.org/patches/externalpipe/)
- [keyboard_select](https://st.suckless.org/patches/keyboard_select/)
- [scrollback](https://st.suckless.org/patches/scrollback/) (all variations)
- [vertcenter](https://st.suckless.org/patches/vertcenter/)
- [xresources](https://st.suckless.org/patches/xresources/)
- [premultiply_rgb](https://github.com/gnotclub/xst/pull/42)

# Rationale
I really like st but it requires `tmux` to be usable. Because I'm a tilling wm
user, `tmux` is an overkill for most of the situations. This patches makes st
usable standalone. `xresources` patch is also convinient to have because I
change stuff frequently.

# TODO
- [ ] Add documentation
    - [ ] Shortcuts
    - [ ] XResources
- [ ] Extend xresources
- [X] Add urlviewer
- [ ] Expose some properties as CLI args
    - [ ] Transperancy
- [ ] Provide a PKGBUILD
    - [ ] Add it to AUR
