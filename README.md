# bluewery.vim

:large_blue_diamond: Blue-based vim colorscheme :beer:

## bluewery

![dark_sample](./misc/figures/dark/sample.png)

| Mode    | Status line image                                |
| ---     | ---                                              |
| NORMAL  | ![dark_normal](./misc/figures/dark/NORMAL.png)   |
| INSERT  | ![dark_insert](./misc/figures/dark/INSERT.png)   |
| VISUAL  | ![dark_visual](./misc/figures/dark/VISUAL.png)   |
| REPLACE | ![dark_replace](./misc/figures/dark/REPLACE.png) |

## bluewery-light

![light_sample](./misc/figures/light/sample.png)

| Mode    | Status line image                                 |
| ---     | ---                                               |
| NORMAL  | ![dark_normal](./misc/figures/light/NORMAL.png)   |
| INSERT  | ![dark_insert](./misc/figures/light/INSERT.png)   |
| VISUAL  | ![dark_visual](./misc/figures/light/VISUAL.png)   |
| REPLACE | ![dark_replace](./misc/figures/light/REPLACE.png) |


## Installation

Using [vim-plug](https://github.com/junegunn/vim-plug),

```vim
Plug 'relastle/bluewery.vim'
```

Add following lines into your `.vimrc`.

```vim
" For dark
colorscheme bluewery
let g:lightline = { 'colorscheme': 'bluewery' }

" For light
colorscheme bluewery-light
let g:lightline = { 'colorscheme': 'bluewery_light' }
```

## Features

- [x] True-color based color scheme.
- [x] Supporting lightline colorscheme.
- [x] `Dark` and `Light` version schemes.
- [ ] Supporting airline colorscheme.

## pallete

This color scheme is created for `truecolor` environment,
but you can use it in non-truecolor environment by configuring
you terminal as following color pallete.

### Dark

<!-- Autogenerated-pallete start dark -->
|color_name      |color_code|color                                                      |color_name      |color_code|color                                                      |
|---             |---       |---                                                        |---             |---       |---                                                        |
|black (normal)  |`#07242c` |![#07242c](https://placehold.it/50x20/07242c/000000?text=+)|black (bright)  |`#142c35` |![#142c35](https://placehold.it/50x20/142c35/000000?text=+)|
|red (normal)    |`#fc6195` |![#fc6195](https://placehold.it/50x20/fc6195/000000?text=+)|red (bright)    |`#fc81a5` |![#fc81a5](https://placehold.it/50x20/fc81a5/000000?text=+)|
|green (normal)  |`#5AC6A1` |![#5AC6A1](https://placehold.it/50x20/5AC6A1/000000?text=+)|green (bright)  |`#233439` |![#233439](https://placehold.it/50x20/233439/000000?text=+)|
|yellow (normal) |`#fff1ac` |![#fff1ac](https://placehold.it/50x20/fff1ac/000000?text=+)|yellow (bright) |`#DF7353` |![#DF7353](https://placehold.it/50x20/DF7353/000000?text=+)|
|blue (normal)   |`#296873` |![#296873](https://placehold.it/50x20/296873/000000?text=+)|blue (bright)   |`#6FaEaF` |![#6FaEaF](https://placehold.it/50x20/6FaEaF/000000?text=+)|
|magenta (normal)|`#85919b` |![#85919b](https://placehold.it/50x20/85919b/000000?text=+)|magenta (bright)|`#364f6b` |![#364f6b](https://placehold.it/50x20/364f6b/000000?text=+)|
|cyan (normal)   |`#04a7a7` |![#04a7a7](https://placehold.it/50x20/04a7a7/000000?text=+)|cyan (bright)   |`#94e7e7` |![#94e7e7](https://placehold.it/50x20/94e7e7/000000?text=+)|
|white (normal)  |`#c4c7c7` |![#c4c7c7](https://placehold.it/50x20/c4c7c7/000000?text=+)|white (bright)  |`#dafafc` |![#dafafc](https://placehold.it/50x20/dafafc/000000?text=+)|
<!-- Autogenerated-pallete end dark -->

### Light

<!-- Autogenerated-pallete start light -->
|color_name      |color_code|color                                                      |color_name      |color_code|color                                                      |
|---             |---       |---                                                        |---             |---       |---                                                        |
|black (normal)  |`#07242c` |![#07242c](https://placehold.it/50x20/07242c/000000?text=+)|black (bright)  |`#234f5c` |![#234f5c](https://placehold.it/50x20/234f5c/000000?text=+)|
|red (normal)    |`#bb627d` |![#bb627d](https://placehold.it/50x20/bb627d/000000?text=+)|red (bright)    |`#d65b7f` |![#d65b7f](https://placehold.it/50x20/d65b7f/000000?text=+)|
|green (normal)  |`#4c8d77` |![#4c8d77](https://placehold.it/50x20/4c8d77/000000?text=+)|green (bright)  |`#b5ab95` |![#b5ab95](https://placehold.it/50x20/b5ab95/000000?text=+)|
|yellow (normal) |`#978f65` |![#978f65](https://placehold.it/50x20/978f65/000000?text=+)|yellow (bright) |`#d16545` |![#d16545](https://placehold.it/50x20/d16545/000000?text=+)|
|blue (normal)   |`#2b5860` |![#2b5860](https://placehold.it/50x20/2b5860/000000?text=+)|blue (bright)   |`#428182` |![#428182](https://placehold.it/50x20/428182/000000?text=+)|
|magenta (normal)|`#7b8791` |![#7b8791](https://placehold.it/50x20/7b8791/000000?text=+)|magenta (bright)|`#c7c1aa` |![#c7c1aa](https://placehold.it/50x20/c7c1aa/000000?text=+)|
|cyan (normal)   |`#007777` |![#007777](https://placehold.it/50x20/007777/000000?text=+)|cyan (bright)   |`#b7c1aa` |![#b7c1aa](https://placehold.it/50x20/b7c1aa/000000?text=+)|
|white (normal)  |`#cdc7b0` |![#cdc7b0](https://placehold.it/50x20/cdc7b0/000000?text=+)|white (bright)  |`#dad4bd` |![#dad4bd](https://placehold.it/50x20/dad4bd/000000?text=+)|
<!-- Autogenerated-pallete end light -->

## Thanks

This colorscheme is inspired by

- [iceberg](https://github.com/cocopon/iceberg.vim/)
- [gotham](https://github.com/whatyouhide/vim-gotham)
- [solarized](https://github.com/altercation/vim-colors-solarized)

## [License](LICENSE)

The MIT License (MIT)
