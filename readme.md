## Overview

Custom color schemes for Sublime Text. Dark and light variants. Made for the Adaptive theme.

## Installation

Clone the repo and symlink it to your Sublime packages directory. Example for MacOS:

    git clone https://github.com/mitranim/sublime-themes.git
    cd sublime-themes
    ln -sf "$(pwd)" "$HOME/Library/Application Support/Sublime Text 3/Packages/"

To find the packages directory on your system, use Sublime Text menu → Preferences → Browse Packages.

Activate:

    Command Palette -> UI: Select Color Scheme -> Role Dark
    Command Palette -> UI: Select Color Scheme -> Role Light
    Command Palette -> UI: Select Color Scheme -> Nether
    Command Palette -> UI: Select Color Scheme -> Cloud

Use the built-in Adaptive theme to match the color scheme:

    Command Palette -> UI: Select Theme -> Adaptive

## Modification

`make.py` automatically rebuilds the themes on changes in `src`.

## WIP Notes

Missing but planned features for Role:

* Support for numeric literals (color choice is hard).
* Support for `source.diff`, `markup.deleted`, `markup.inserted`.

## License

https://unlicense.org
