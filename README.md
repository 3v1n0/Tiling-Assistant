# Tiling assistant for GNOME

An extension which adds a Windows-like snap assist to GNOME. It also changes GNOME's 2 column tiling design to a 2x2 grid (i.e. 4 quadrants) **and more**.

## Table of Contents
- [Supported GNOME Versions](#Supported-GNOME-Versions)
- [Usage and Features](#Usage-and-Features)
- [Preview](#Preview)
- [Installation](#Installation)
- [Translations](#Translations)
- [License](#License)

## Supported GNOME Versions

- 3.36
- 3.38
- 40

## Usage and Features

- **Do NOT use GNOME's tiling keybindings. Instead use the keybindings from this extension's settings. By default, the keybindings for tiling are `Super`+`NUM_PAD`.**

- **Tiling Popup**: This is the popup, which shows up when a window is tiled and there is an (unambiguous) free screen rectangle. It lists all open windows on the current workspace. Activating one of the popup's icons will tile the window to fill the remaining screen space.

- **Tile Groups**: Tiled windows are considered in a group, if they don't overlap each other and aren't interrupted by non-tiled windows. If one of the windows is focused, the rest of the group will be raised to the foreground as well. A Tile Group also resizes together.

- **Layouts**: A layout is a list of arbitrary rectangles. When activating one with its keybinding the Tiling Popup asks you which of the open windows you want at which spot of your layout. The `layout selector` is a popup, which will lists all defined layouts by name. This way you don't have to remember the layouts' keybindings.

- **Pie Menu**: `Super` + `RMB` on a window will open a simple pie menu.

- ...

Please see the ![Guide](GUIDE.md) for a detailed explanation of every feature.

## Preview

![Preview](media/preview.gif)

## Installation

You can install it via https://extensions.gnome.org. Alternatively (or if you want an up-to-date version), download `tiling-assistant@leleat-on-github` and move it to your extensions folder. Local extensions are in `~/.local/share/gnome-shell/extensions/`. After moving the folder to the correct location, restart the GNOME shell (`Alt`+`F2` -> enter `r`. On **Wayland** you need to logout).

## Translations

Translations (even just partial ones) are very welcome!
If you are already familiar with how it works, feel free to directly open a pull request with a `YOUR_LANG.po` file at `translations/`.
Don't worry, in case you don't know how to create a `.po` file. Just open an issue and I'll set everything up. You'll only need a text editor and your language skills :)

## License

This extension is distributed under the terms of the GNU General Public License, version 2 or later. See the license file for details.
