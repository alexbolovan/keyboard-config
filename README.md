# Iris LM QMK Keymap

This workspace contains a starter QMK keymap for the Keebio Iris LM:

```text
keyboards/keebio/iris_lm/keymaps/current/
```

The keymap targets the shared Iris LM layout and should work for either hardware variant:

- `keebio/iris_lm/k1` for Iris LM-K, Kailh Choc V1/V2
- `keebio/iris_lm/g1` for Iris LM-G, Gateron KS-33

Build from a `qmk_firmware` checkout after copying this `current` keymap directory into the matching QMK path:

```sh
make keebio/iris_lm/k1:current
```

Flash:

```sh
make keebio/iris_lm/k1:current:flash
```

For the LM-G variant, replace `k1` with `g1` in those commands.

The current layout is based on QMK's default Iris LM layout and has three layers: `_QWERTY`, `_LOWER`, and `_RAISE`. Send your preferred base keymap when you have it and the layer contents can be swapped in directly.
