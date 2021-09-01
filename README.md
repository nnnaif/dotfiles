```
cd ~
alias dotfiles="git --git-dir=$HOME/git/dotfiles/ --work-tree=$HOME
git clone --bare git@github.com:nnnaif/dotfiles.git $HOME/git/dotfiles
dotfiles config --local status.showUntrackedFiles no
dotfiles checkout -f
```
