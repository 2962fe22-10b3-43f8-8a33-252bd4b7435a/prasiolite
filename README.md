# prasiolite
A small neovim colorscheme inspired by the gem of the same name
## Screenshots
<img width="500" height="500" alt="image" src="https://github.com/user-attachments/assets/d11b25dd-94b5-473c-99d5-b9cf6af669a3" />

## Installation
Install using your favourite plugin manager:
```lua
{ -- using lazy.nvim:
  '2962fe22-10b3-43f8-8a33-252bd4b7435a/prasiolite',
  lazy = false,
},
```

Then, open your neovim config (`:e $MYVIMRC`)  
Add `vim.cmd "colorscheme prasiodark"` to the end of your `init.lua` to have this colorscheme to enabled at startup  

Restart neovim and enjoy!

- To install without a plugin manager:
  
  In the same directory as your `init.lua`, create a folder named `colors/`  
  Copy `colors/prasiodark.lua` into that folder.



## Coming ~soon~ eventually:
- Light mode
- Support for more languages
  - The languages I use (C, C++, Rust, Python, TSX) all work, but if something seems wrong with a language you use, please file an issue!
