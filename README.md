# Maple Font (WIP)

Open source monospace & nerd font with round corner and ligatures.

Base on `Jetbrains Mono`, and **much "Opinioned"**

## Features

- Round corner
- New shape of `@ $ % & Q a` and cursive italic `f i j k l x y`
- Large amount of ligatures
  - equal variants: `==` / `===` / `!=` / `!==` / `>=` / `<=`...
  - arrow variants: `->` / `=>` / `-->` / `==>` / `<->` / `<=>`...
  - xml variants: `</` / `/>` / `<>` / `</>` / `<!--`...
  - flow variants: `|>` / `||>` / `|||>` / `|||>` / `>=>` / `=>>`...
  - same characters: `++` / `--` / `&&` / `||` / `!!` / `??` / `..` / `::` / `########`...
  - plain text tag: `[TODO]` / `todo))` / `[FIXME]` / `fixme))`
    - for logger: `[TRACE]` / `[DEBUG]` / `[INFO]` / `[WARN]` / `[ERROR]` / `[FATAL]`
- Font features
  - zero: dot style `0`
  - cv01: normal `@ $ & Q`
  - cv02: normal `a`
  - cv03: normal `i`
  - cv04: normal `l`
  - cv98: full width `…`(ellipsis) and `—`(emdash) support for Maple Mono NF CN
  - cv99: manually set TW punctuations for Maple Mono NF CN
  - ss01: normal italic `f l i j x y`
  - ss02: splited `==` / `===` / `!=` / `!==` / `=/=`
  - ss03: arbitrary plain text tags

## Build

### Browser

WIP

### Local

run it in your local machine.

You can change config in `build.py`

Make sure you have `python3` and `pip` installed

- for custom `font-patcher` args, `font-forge` (and maybe `python3-fontforge` as well) is needed
- for `Ubuntu` or `Debian`, maybe `python-is-python3` is needed as well

```shell
pip install foundrytools-cli
python build.py
```

If you have trouble to install the dependencies, just create a new Github codespace on `variable` branch and run the commands there

## credit

- [Jetbrains Mono](https://github.com/JetBrains/JetBrainsMono)
- [Roboto Mono](https://github.com/googlefonts/RobotoMono)
- [Fira Code](https://github.com/tonsky/FiraCode)
- [Victor Mono](https://github.com/rubjo/victor-mono)
- [Commit Mono](https://github.com/eigilnikolajsen/commit-mono)
- [Code Sample](https://github.com/TheRenegadeCoder/sample-programs-website)
- [Nerd Font](https://github.com/ryanoasis/nerd-fonts)

## License

SIL Open Font License 1.1
