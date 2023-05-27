Kawaii Ascii | Neofetch | Cowsay | Fortune 4 in 1
=================================================

be a QT pie and have a cool terminal

The ascii's in here are ones I've found off [here](https://emojicombos.com/cute-ascii-art)

### Install these

```sh
# by itself, it shows system specs with system logo
brew install neofetch
# makes things RAINBOW mode
brew install lolcat
# cowsay cuz cow says messages teehee
brew install cowsay
# for when ur minds blank on what to say
brew install fortune
```

### Put this in your conf file for shell

Mine's in ~/.zshrc

```sh
neofetch --ascii "$(fortune | cowsay -f ~/path/to/kawaii-term/penguin.cow -W 30)" | lolcat
```

CHU WELCOME
