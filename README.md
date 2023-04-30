# vim-vsc-snippets

Sync VSCode snippets to Vim

This plugin is designed to synchronize the built-in Snippets in VSCode in order to be able to use them in Vim.

## Installation

Based on [LuaSnip](https://github.com/L3MON4D3/LuaSnip), make sure you have installed it.

I am using [LunarVim](https://www.lunarvim.org), which already has LuaSnip installed, and has [Lazy](https://github.com/folke/lazy.nvim) installed too. You can just add below lines in your `config.lua` in your `~/.config/lvim/` folder.

```lua
lvim.plugins = {
  { "xinleibird/vim-vsc-snippets" },
  ...
}
```

Or just install with Lazy.

```lua
require("lazy").setup({
  "xinleibird/vim-vsc-snippets",
  ...
})
```

If you use LunarVim, you can also turn off LunarVim's built-in [friendly_snippets](https://github.com/rafamadriz/friendly-snippets) if you wish.

```lua
lvim.builtin.luasnip.sources.friendly_snippets = false

```

Enjoy!
