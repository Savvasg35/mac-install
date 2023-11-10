# Macbook setup

**Apps**

1. [1Password](https://1password.com/)
2. [iTerm](https://iterm2.com/)
3. [Raycast](https://www.raycast.com/)
4. [Slack](https://slack.com/intl/en-gb)
5. [Insomnia](https://insomnia.rest/)
6. [Shottr](https://shottr.cc/)
7. [VsCode](https://code.visualstudio.com/)
8. Goland
9. [Xcode](https://apps.apple.com/gb/app/xcode/id497799835?mt=12)
10. [Docker](https://www.docker.com/)
11. [Logi Options](https://www.logitech.com/en-gb/software/options.html)
12. [Spotify](https://www.spotify.com/de-en/download/mac/)
13. [Fig](https://fig.io/)

**Terminal config**

1. Import my-profile.json in iterm
2. **Install brew** - https://brew.sh/
3. **Install git** - `brew install git`
4. **Install zsh**
   1. `brew install zsh`
   2. `sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"`
5. **Install zsh-autosuggestions**

   1. `git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions`
   2. `vim ~/.zshrc`

   ```
   plugins=(
       # other plugins...
       zsh-autosuggestions
   )
   ```

6. **Install nvm**
   1. `brew install nvm`
   2. Add `source $(brew --prefix nvm)/nvm.sh` to **~/.zshrc**
7. **Install syntax highlighting**
   1. `brew install zsh-syntax-highlighting`
   2. `echo "source $(brew --prefix)/share/zsh-syntax-highlighting/zsh-syntax-highlighting.zsh" >> ${ZDOTDIR:-$HOME}/.zshrc`
