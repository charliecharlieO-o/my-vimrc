## Packages used

  - NERDTree
  - NERDTree-git
  - GitGutter
  - VimVue

## Install Pathogen

```
mkdir -p ~/.vim/autoload ~/.vim/bundle && \
curl -LSso ~/.vim/autoload/pathogen.vim https://tpo.pe/pathogen.vim
```

## Install the required plugins

```
cd ~/.vim/bundle
git clone https://github.com/scrooloose/nerdtree
git clone https://github.com/Xuyuanp/nerdtree-git-plugin.git
git clone https://github.com/airblade/vim-gitgutter
git clone https://github.com/posva/vim-vue.git
```

That's it, just clone the vimrc file into your home folder and change the name to .vimrc
