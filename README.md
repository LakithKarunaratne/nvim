# Read me

## Commands

`:so` - Source the init file
`:PackerSync` - Get Updates

## Plugins Used

Reference :
[Primagen](https://github.com/ThePrimeagen/init.lua/tree/master/lua/theprimeagen)

[Packer](https://github.com/wbthomason/packer.nvim)
[Telescope](https://github.com/nvim-telescope/telescope.nvim)
[Rose-Pine Theme](https://github.com/rose-pine/neovim)
[Treesitter](https://github.com/nvim-treesitter/nvim-treesitter)
[Treesitter Playground : optional](https://github.com/nvim-treesitter/playground)
[Harpoon](https://github.com/ThePrimeagen/harpoon)
[Undo Tree](https://github.com/mbbill/undotree)
[Vim Fugitive](https://github.com/tpope/vim-fugitive)
[LSP Zero](https://github.com/VonHeikemen/lsp-zero.nvim)

## Reference 

For Lua MultiLine Comments
```
--[=====[ 
for k,v in pairs(t) do
   local d = fullToShort[k]
   local col = xColours[v[1]] -- It stops here!
   cecho(string.format(("<%s>%s ", col, d))
end
--]=====]
```

For LSP Config

[LSP zero List](https://github.com/williamboman/mason-lspconfig.nvim#available-lsp-servers)

To Alias

alias vi="nvim"
alias vim="nvim"
alias view="nvim -R"
alias vimdiff="nvim -d"
