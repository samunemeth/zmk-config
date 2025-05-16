# ZMK config for Ferris Sweep BT

<!-- TODO: Include design files. -->

## Premise

A [Ferris Sweep](https://github.com/davidphilipbarr/Sweep) inspired
34-key Bluetooth split keyboard.

## Layout

The layout is based on a [Dvorak layout](https://en.wikipedia.org/wiki/Dvorak_keyboard_layout), but the symbols and numbers are custom-placed.
There are no home row modifiers, and a minimum amount of combos, as they
bother me.

The layers are accessible with a *"ladder"* style momentary layer setup.
If all keys are let go, the keyboard returns to the default layer.

<!-- TODO: Explain ladder style. -->

![Layout Image](https://raw.githubusercontent.com/samunemeth/zmk-config/refs/heads/master/visual/keymap.svg?sanitize=true)

The layout visualization is created with [keymap-drawer](https://github.com/caksoylar/keymap-drawer) by [*Cem Aksoylar*](https://github.com/caksoylar), with the help
of the [`./visual/keymap.yaml`](visual/keymap.yaml) configuration.

## Key explanations

**Clear mods**: Sends an `F17` key, that does not trigger any keyboard
shortcuts, and clears all sticky modifiers.

**Alt+Tab**: Indicated with a stacked layers symbol. Triggers the window
switcher menu.

<!-- TODO: PowerToys run; Ctrl+Alt+Delete; Bluetooth; Regular WIN. -->