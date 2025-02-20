# Dotfiles setup
## Setup 

- First clone the repo:
```git clone --bare <your_remote_dotfiles_repo_url> $HOME/.dotfiles```
- Create alias:
```alias dotfiles='git --git-dir=$HOME/.dotfiles/ --work-tree=$HOME```
- checkout the files:
```dotfiles checkout```
- Initialize submodules:
```dotfiles submodule update --init --recursive```

