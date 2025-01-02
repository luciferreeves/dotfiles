# dotfiles

Since, I am a Linux user now, here is the obligatory dotfiles repository.

I am using [GNU Stow](https://www.gnu.org/software/stow/) to manage my dotfiles. 

## Installation

```bash
git clone https://github.com/luciferreeves/dotfiles.git ~/.dotfiles
cd ~/.dotfiles
stow -t ~ *
```

## Uninstallation

```bash
cd ~/.dotfiles
stow -t ~ -D *
```

## License

[MIT](LICENSE)
```

