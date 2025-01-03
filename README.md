# [brewz](https://github.com/devpruthvi/brewz)

A [fzf](https://github.com/junegunn/fzf) terminal UI for [brew](https://github.com/Homebrew/brew)

VERSION: 0.1

# Usage

```text
Usage: $PROG [OPTS]

A fzf terminal UI for brew.

Multiple packages can be selected.

Keybindings:
  TAB                    Select
  Shift+TAB              Deselect

OPTS:
  -h, --help             Print this message

  All other options are passed to brew.
  Default: install

Examples:
  brewz neovim
  brewz install --cask
  brewz uninstall
```

# Requirements

- ZSH
- [fzf](https://github.com/junegunn/fzf)

# Installation

```sh
curl --output ~/.bin/brewz https://raw.githubusercontent.com/devpruthvi/brewz/master/brewz
chmod +x ~/.bin/brewz
```

# References

- [paruz](https://github.com/joehillen/paruz)
