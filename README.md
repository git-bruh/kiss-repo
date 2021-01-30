# kiss-repo

## Repository structure

`optim` Packages built with `PGO` or `LTO`.

`overrides` Forked packages, mostly to use `netbsd-curses` instead of `ncurses`

`repo` *Actually* useful packages such as [matrix](https://matrix.org) related packages, `pihole`, `GTK` stuff etc.

## Usage

Create a symlink at the top level of this git repo pointing to your main KISS repository:
```sh
cd path/to/kiss-repo
ln -sf /path/to/main-repo ./kiss-repo
```

`optim` `overrides` repos must take precedence over other repos in `KISS_PATH`

[KISS Hook](https://github.com/git-bruh/dotfiles/blob/master/kiss-hook)

[Build Flags](https://github.com/git-bruh/dotfiles/blob/master/.profile)
