# clipboardMerge
forces neovim running on WSL2 to use yank / paste on windows clipboard

# How to Install

## Step #1
put file `mergeClipboards.lua` into: `~/.config/nvim/lua/<folder_name>/mergeClipboards.lua`

## Step #2
in `init.lua` file add: 
```lua
require("<folder_name>.mergeClipboards.lua")
```

## Step #3
restart neovim and follow printed instructions
