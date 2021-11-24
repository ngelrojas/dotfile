### vim
- copy .vimrc in directory root user like "~/"
- copy link in your teminal
-- git clone https://github.com/VundleVim/Vundle.vim.git ~/.vim/bundle/Vundle.vim

- and run vim
- if a plugin youcompleteme fails, in ~/.vim/plugged/youcompleteme
- run python3 install.py or
- run sh install.sh or
- run . install.sh

### zsh
- install oh-my-zsh for SO
-- https://ohmyz.sh/

- copy .zshrc in your directory root user like "~/"
- if you want to default zsh make this:
- for your user
- sudo chsh -s $(which zsh)
- if you want to default zsh for root user make this:
- sudo chsh -s $(which zsh) root

### config neovim
- copy nvim file in: your-user/.config/
- install balck using the current doc: https://black.readthedocs.io/en/stable/integrations/editors.html#vim
- then:
-- :PlugInstall
-- extra help command
-- :PlugUpdate
