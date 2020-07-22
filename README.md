# vim-material
This repo is a fork of [hzchirs/vim-material](https://github.com/hzchirs/vim-material). I'm a big fan of [Mattia Astorino](https://github.com/material-theme/vsc-material-theme)'s material theme and especially the darker variant. I've ported the missing darker variant to this repo for vim/nvim users.

**Note:** support true color terminal and gvim only

Screenshot
------------

**Dark**
![Dark](https://imgur.com/xfGYwwc.jpg)

**Darker**
![Darker](https://user-images.githubusercontent.com/21971773/88160350-246d6d80-cc2c-11ea-9a6b-8621bd51d339.png)

**Light**
![Light](https://user-images.githubusercontent.com/4735528/42131913-8c1b0d68-7d3f-11e8-935a-4c10181127d9.png)

**Palenight**
![Palenight](https://user-images.githubusercontent.com/4735528/42134016-056046f4-7d66-11e8-9ea0-c96a59a5b7b0.png)

**Oceanic**
![Oceanic](https://user-images.githubusercontent.com/4735528/47250634-6ebe2b00-d457-11e8-92d7-dabb871f60f1.png)

Installation
------------

* [vim-plug](https://github.com/junegunn/vim-plug)
```vim
Plug 'shiroryuu/vim-material'

" Dark
set background=dark
colorscheme vim-material

" Darker
let g:material_style='darker'
set background=dark
colorscheme vim-material

" Palenight
let g:material_style='palenight'
set background=dark
colorscheme vim-material

" Oceanic
let g:material_style='oceanic'
set background=dark
colorscheme vim-material

" Light
set background=light
colorscheme vim-material
```

### Airline
Colorscheme also include an [Airline](https://github.com/vim-airline/vim-airline) theme

```vim
let g:airline_theme='material'
```

License
---
MIT
