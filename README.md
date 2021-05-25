# kiss-repo

Personal KISS repository.

## Packages

* `arc-dark-gtk-theme`: GTK theme.

* `dendrite`: Matrix homeserver.

* `gomuks`: Matrix client.

* `gotify-server`: Notifications.

* `qogir-cursors`: GTK cursor.

* `slstatus`: Status monitor.

* `stagit`: Static site generator for `git` repos, patched for syntax highlighting.

## Wayland

* `bemenu`: Dynamic menu library and client program inspired by dmenu.

* `chromium`: Forked for building without X libs.

* `egl-wayland`, `eglexternalplatform`: NVIDIA `eglstreams` crap.

* `firefox`: Fork for building without X libs (extra patch), LTO'd aswell. For regular non-LTO builds just use `wayland.patch` and add `--with-default-toolkit=cairo-gtk3-wayland` along with `--disable-webrtc` to `.mozconfig`.

* `foot`: Terminal emulator.

* `grim`: Grab images from a Wayland compositor.

* `slurp`: Select a region in a Wayland compositor.

* `sway`: Tiling Wayland compositor.

* `swaybg`: Wallpaper tool for Wayland compositors.

* `wlroots`: Modular Wayland compositor library (Fork with `eglstreams` backend for NVIDIA).
