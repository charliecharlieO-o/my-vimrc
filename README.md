## Packages used

Used neovim instead of vim.

  - NERDTree
  - NERDTree-git
  - GitGutter

## Install Pathogen

```
mkdir -p ~/.config/nvim/autoload ~/.config/nvim/bundle
curl -LSso ~/.config/nvim/autoload/pathogen.vim https://tpo.pe/pathogen.vim
```

## Install the required plugins

```
cd ~/.vim/bundle
git clone https://github.com/scrooloose/nerdtree
git clone https://github.com/Xuyuanp/nerdtree-git-plugin.git
git clone https://github.com/airblade/vim-gitgutter
```

That's it, just clone the vimrc file into your home folder and change the name to .vimrc
