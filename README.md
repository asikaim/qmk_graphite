# Graphite Layout for QMK Firmware
QMK implementation of the [Graphite](https://github.com/rdavison/graphite-layout) layout for the [Moonlander](https://www.zsa.io/moonlander/) keyboard with some Scandic changes.

Oryx version available [here](https://configure.zsa.io/moonlander/layouts/p6jab/latest/0)

## Usage (For Moonlander MK1)
Process is just about the same for regular QMK firmware as well.

- Clone QMK Firmware (for ZSA you can find it [here](https://github.com/zsa/qmk_firmware)).
- Copy paste [graphite](./graphite/) directory into `/keyboards/zsa/moonlander/keymaps/`

## Changes
The position of Ö, Ä and Å are optimal for typing in Finnish. For Swedish switching Å with Ä would probably be better.


## TODO
- Add a magic key similar to [this](https://github.com/Ikcelaks/keyboard_layouts/blob/main/magic_sturdy/magic_sturdy.md)
- Fix some special character bindings
- Better Multi-OS support (autodetect the OS)
