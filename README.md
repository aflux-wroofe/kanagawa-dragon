# Kanagawa & Kanso

VS Code colour themes based on [Kanagawa](https://github.com/rebelot/kanagawa.nvim) by rebelot and [Kanso](https://github.com/webhooked/kanso.nvim) by webhooked.

## Variants

### Kanagawa (`themes/kanagawa/`)

- **Kanagawa Wave**: the standard dark theme, deep blue ink
- **Kanagawa Dragon**: dark and earthy
- **Kanagawa Lotus**: light, warm paper

### Kanso (`themes/kanso/`)

A calmer, more minimal take on Kanagawa: muted syntax, grey operators and punctuation, flat backgrounds.

- **Kanso Zen**: the darkest, near-black
- **Kanso Ink**: dark, the Kanso default
- **Kanso Mist**: dark with a softer, lighter grey background
- **Kanso Pearl**: light

## Install

Install from the packaged VSIX:

```
code --install-extension kanagawa-1.2.0.vsix
```

Or in VS Code: **Extensions** → `...` menu → **Install from VSIX...**

Then choose the theme: `Ctrl+K Ctrl+T` → pick a Kanagawa or Kanso variant.

## Build

```
npx @vscode/vsce package
```

## Credits

The palettes come from [kanagawa.nvim](https://github.com/rebelot/kanagawa.nvim) (MIT) and [kanso.nvim](https://github.com/webhooked/kanso.nvim) (MIT).
