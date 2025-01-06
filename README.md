# Source
https://coffeeaddict.dev/how-to-manage-dotfiles-with-git-bare-repo/

# Install on new machine
```bash
git clone --bare git@github.com:ajhoekst/dotfiles.git $HOME/.dot
git --git-dir=$HOME/.dot --work-tree=$HOME checkout
```
