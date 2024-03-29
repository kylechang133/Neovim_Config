# My Neovim Configuration

## Features/Plugins
- Lazy.nvim Package Manager
- Catpuccin Color Theme
- Git Functionality
- GitHub Copilot
- Telescope
- Treesitter
- Neotree
- Lualine
- None_ls
- Lsp Config Support (Includes Mason LSP Manager)

## File Structure
```
~/.config/nvim
├── lua/
│   ├── core/
│   │   ├── keymaps.lua
│   │   ├── options.lua
│   ├── plugins.lua
│   └── plugins/
│       ├── catpuccin.lua
│       ├── completion.lua
│       ├── git.lua
│       ├── lsp_config.lua
│       ├── lualine.lua
│       ├── neotree.lua
│       ├── none_ls.lua
│       ├── telescope.lua
│       └── treesitter.lua
├── lazy-lock.json
└── init.lua
```

## Installation Instructions
1. Install [Neovim](https://neovim.io) using the package manager of your choice (I use [Homebrew](https://brew.sh) on MacOS)
2. cd into the .config directory
3. Remove the pre-existing `nvim` directory
4. Clone this repository
5. ***NOTE:*** This Neovim configuration has the [GitHub Copilot](https://github.com/github/copilot.vim) plugin installed; if you want to use it, make sure you have [node.js](https://nodejs.org/en) installed on your machine. Otherwise, remove the plugin from the `completion.lua` file.
6. ***NOTE:*** This Neovim configuration also has the [Catpuccin](https://github.com/catppuccin/catppuccin) Color Theme installed; in order to get the color theme to work properly, you need to have a terminal emulator that has full color support installed (I recommend [Kitty](https://sw.kovidgoyal.net/kitty/)(MacOS/Linux) or [iTerm2](https://iterm2.com)(MacOS))
