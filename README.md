## Packages used

Used neovim instead of vim.

Project structure view
  - NERDTree
  - NERDTree-git

Git diff viewer
  - GitGutter

Insanely fast fuzzy search
  - FZF
  - FZF.VIM

## Dependencies

```
brew install fzf
brew install ripgrep
```

## Install Pathogen

```
mkdir -p ~/.config/nvim/autoload ~/.config/nvim/bundle
curl -LSso ~/.config/nvim/autoload/pathogen.vim https://tpo.pe/pathogen.vim
```

## Install the required plugins

```
cd ~/.vim/bundle
git clone git@github.com:preservim/nerdtree.git 
git clone git@github.com:Xuyuanp/nerdtree-git-plugin.git
git clone git@github.com:airblade/vim-gitgutter.git
git clone git@github.com:junegunn/fzf.git
git clone git@github.com:junegunn/fzf.vim.git
git clone git@github.com:dmerejkowsky/vim-ale.git
git clone git@github.com:fatih/vim-go.git
```

## Docs

On searching:
  - https://github.com/junegunn/fzf.vim
  - https://jdhao.github.io/2018/10/07/nvim_fast_keyword_search/
  - https://blog.burntsushi.net/ripgrep/#methodology
