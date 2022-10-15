# Sandyflip Keyboard Layout (aka Keymap)
Evolution of [NoTwive](https://github.com/fractalysid/Notwive)

ZMK and QMK files available.

ZMK config files are for the [Lucy](https://github.com/fractalysid/Lucy-Keyboard) v0.2 keyboard.

A sample bash script to compile the firmware is provided, compile_example.sh. Remember to edit it modifying the variables.

[Here](https://github.com/fractalysid/qmk_firmware) you can find my fork of [QMK](https://github.com/qmk/qmk_firmware) with the layout for the ferris sweep (it is a modified version where the keys in the right half are in reverse order). You can also find the keymap.json in the QMK directory.

## Goals
All my previous layouts were focused on the idea of avoiding combos and make heavy use of layers.
Sandflip flips the game. It is highly experimental, using combos and macros.
After 1 minute of use I found out that I don't like using a combo for backspace. I hope I can get accustomed to
using it in the utility layer

## Design principles
- Make NoTwive better by using combos and macros
- Remove backspace from the base layer and add ' and -

### Details about layers and modifiers triggering
- Modifiers: Positional hold-tap, "tap-preferred" with 160ms tapping term
- Right thumb: default layer-toggle timings
- Left thumb: "Balanced" with only 125ms tapping term for quick access while typing text

![Sandyflip_Layout](https://github.com/fractalysid/Notwive/blob/main/Notwive.png?raw=true)
