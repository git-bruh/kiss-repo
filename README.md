# kiss-repo

## Repository structure

`optim` Packages built with `PGO` or `LTO`.

`overrides` Forked packages, mostly to use `netbsd-curses` instead of `ncurses`.

`repo` *Actually* useful packages:
* `arc-dark-gtk-theme`: GTK theme.

* `axel`: Download accelerator.

* `cproc`: Compiler.

* `dendrite`: [Matrix](https://matrix.org) homeserver.

* `gomuks`: [Matrix](https://matrix.org) client.

* `netbsd-curses`: Curses library.

* `pi-hole`: DNS-level blocker.

* `qogir-cursors`: GTK cursor.

* `slstatus`: Status monitor.

* `stagit`: Static site generator for `git` repos.

* `yash`: Shell.


## Usage

Create a symlink at the top level of this git repo pointing to your KISS repositories:
```sh
cd /path/to/kiss-repo

ln -sf /path/to/main-repo      ./kiss-repo
ln -sf /path/to/community-repo ./kiss-community
```

`optim` `overrides` repos must take precedence over other repos in `KISS_PATH`.

[KISS Hook](https://github.com/git-bruh/dotfiles/blob/master/kiss-hook)

[Build Flags](https://github.com/git-bruh/dotfiles/blob/master/.profile)
