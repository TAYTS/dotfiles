# Dotfiles

A collection of my personal configuration files.

## Contents

### Neovim (`nvim/`)

Neovim configuration built with [lazy.nvim](https://github.com/folke/lazy.nvim).

#### Plugins

| Category | Plugins |
|---|---|
| **UI** | tokyonight.nvim, lualine.nvim, bufferline.nvim, alpha-nvim, dressing.nvim, nvim-web-devicons, indent-blankline.nvim |
| **Navigation** | telescope.nvim, nvim-tree.lua, vim-tmux-navigator, vim-maximizer |
| **LSP** | nvim-lspconfig, mason.nvim, mason-lspconfig.nvim, mason-tool-installer.nvim, neodev.nvim |
| **Completion** | nvim-cmp, cmp-nvim-lsp, cmp-buffer, cmp-path, cmp_luasnip, lspkind.nvim, friendly-snippets |
| **Formatting & Linting** | conform.nvim, nvim-lint |
| **Treesitter** | nvim-treesitter, nvim-ts-autotag |
| **Editor** | nvim-autopairs, trouble.nvim, todo-comments.nvim, which-key.nvim |

## Setup

Clone this repo and symlink the configs to your config directory:

```sh
git clone https://github.com/<your-username>/dotfiles.git ~/dotfiles

# Neovim
ln -s ~/dotfiles/nvim ~/.config/nvim
```
