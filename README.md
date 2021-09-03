## dotfiles

The repository to store my dotfiles.

### Installation

```bash
git clone --recurse-submodules git://github.com/Chan-ZJU/dotfiles ~/dotfiles
cd ~/dotfiles
bash install.sh
```

If git clone oh-my-zsh failed, run the following commands:

```bash
git submodule update --init
```

After running `install.sh`, you need to reboot to change the login shell to zsh.
