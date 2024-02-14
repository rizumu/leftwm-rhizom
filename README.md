# Rhizom
A [leftwm](https://github.com/leftwm/leftwm) theme based upon the
[Zenburn](https://en.wikipedia.org/wiki/Wikipedia:Zenburn) and
[Nord](https://nordtheme.com) color palettes.

Modeled after [Ascent](https://github.com/mwalrus/Ascent).

## Screenshots
![Emacs, urxvt](https://raw.githubusercontent.com/rizumu/leftwm-rhizom/main/themes/Rhizom/leftwm-rhizom.png)

## Dependencies
- leftwm
- polybar
- feh
- picom _(optional)_
- rofi _(optional)_
- dunst _(optional)_
- librewolf _(dunst default browser)_

## Installing
1. `git clone https://github.com/rizumu/leftwm-rhizom.git ~/.config/leftwm`
2. `mkdir ~/.config/rofi && ln -s ~/.config/leftwm/themes/Rhizom/config.rasi ~/config/rofi/config.rasi`
3. `mkdir ~/.config/dunst && ln -s ~/.config/leftwm/themes/Rhizom/dunstrc ~/config/dunst/dunstrc`
4. `leftwm-theme update`
5. `leftwm-command SoftReload`
