# osaka-jade.nvim

A Neovim port of the [Osaka Jade](https://github.com/Justikun/omarchy-osaka-jade-theme) theme by [Justin Lowry](https://github.com/Justikun), originally created for [Omarchy](https://github.com/basecamp/omarchy).

![Neovim](https://img.shields.io/badge/Neovim-0.8+-green?logo=neovim&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-blue)

## Features

- Dark theme with jade/teal accent colors
- Full Treesitter support
- LSP semantic highlighting
- Support for popular plugins:
  - Telescope
  - Neo-tree
  - WhichKey
  - nvim-cmp
  - Lazy.nvim
  - Mason
  - Noice
  - Notify
  - Flash
  - Trouble
  - Navic
  - And more...

## Requirements

- Neovim >= 0.8.0
- `termguicolors` enabled

## Installation

### [lazy.nvim](https://github.com/folke/lazy.nvim)

```lua
{
  "st-eez/osaka-jade.nvim",
  lazy = false,
  priority = 1000,
  config = function()
    vim.cmd.colorscheme("osaka-jade")
  end,
}
```

### [LazyVim](https://www.lazyvim.org/)

```lua
return {
  { "st-eez/osaka-jade.nvim", lazy = false, priority = 1000 },
  {
    "LazyVim/LazyVim",
    opts = {
      colorscheme = "osaka-jade",
    },
  },
}
```

### [packer.nvim](https://github.com/wbthomason/packer.nvim)

```lua
use {
  "st-eez/osaka-jade.nvim",
  config = function()
    vim.cmd.colorscheme("osaka-jade")
  end,
}
```

## Color Palette

| Color      | Hex       | Usage                |
| ---------- | --------- | -------------------- |
| Background | `#111c18` | Primary background   |
| Foreground | `#C1C497` | Primary text         |
| Cyan       | `#2DD5B7` | Keywords, accents    |
| Green      | `#549e6a` | Strings              |
| Blue       | `#509475` | Functions            |
| Yellow     | `#E5C736` | Types, warnings      |
| Red        | `#FF5345` | Errors, exceptions   |
| Magenta    | `#D2689C` | Numbers, booleans    |
| Comment    | `#53685B` | Comments, muted text |

## Credits

Color palette by [Justin Lowry](https://github.com/Justikun) from his [Osaka Jade](https://github.com/Justikun/omarchy-osaka-jade-theme) theme for [Omarchy](https://github.com/basecamp/omarchy).

## License

MIT
