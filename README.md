# neovim_config

### Install Vim-Plug:
---
```
curl -fLo ~/.local/share/nvim/site/autoload/plug.vim --create-dirs https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim
```

### Import your vim configuration
```ln -s ~/.vimrc ~/.config/nvim/init.vim```

or create a seprate one instead of ln use cp 

### path for the files 
- ~/.config/nvim/init.vim
- ~/.vimrc
- ~/.config/nvim/coc-settings.json # change the user for the home directory

### Links
- [coc](https://github.com/neoclide/coc.nvim)
- [rust-analyzer](https://rust-analyzer.github.io/manual.html#installation)
- [vim-plug](https://github.com/junegunn/vim-plug)

### Commands after setup using nvim 
- :CocInstall coc-rust-analyzer #this is for rust
- :PlugInstall # to install the plugins 


