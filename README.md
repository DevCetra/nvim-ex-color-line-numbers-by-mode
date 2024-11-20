# NeoVim Extension

## nvim-color-line-numbers-by-mode

A plugin for NeoVim to color the line numbers based on the current mode to help you better see the mode you're in. The line colors correspond to the default mode colors of NeoVim.

## Installing with Lazy

```lua
return {
  {
    "DevCetra/nvim-color-line-numbers-by-mode",
    lazy = false, --load during startup
    config = function()
      require("nvim-color-line-numbers-by-mode").setup()
    end,
  },
}
```
