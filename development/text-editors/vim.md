# Vim

Vim is the powerful highly configurable text editor with extensible plugin system and great documentation.

## Notes

### Plugin system

#### Install plugins

Vim 8+ have built-in plugin system.
`:help packages`

1. Make dir and clone plugin repository

```
mkdir ~/.vim/pack/plugins/start/

git clone https://github.com/prettier/vim-prettier ~/.vim/pack/plugins/start/vim-prettier
```

2. Enable auto load plugins at vim starts. In `.vimrc` add following command:

```
packloadall
```

#### Resize window

`:res +25`

#### Surround

`:%s/target/{\0} # {target}`

![vim cheatsheet](../../.gitbook/assets/vim-cheatsheet.png)

## Links

- [Check my .vimrc file](https://github.com/famiclone/dotfiles/blob/master/.vimrc)
- [https://www.vim.org](https://www.vim.org) - Official
- [https://www.vimgolf.com/](https://www.vimgolf.com/) - Vim challenges
- [https://vim.fandom.com/wiki/Vim_Tips_Wiki](https://vim.fandom.com/wiki/Vim_Tips_Wiki) - Vim tips wiki
- [pintovim.dev](https://pintovim.dev) - Vim color scheme generator
- [Vim Colors](https://vimcolors.org) - Another color scheme generator
