# These are things I install after OS install
- make sure youve installed updates as well as zsh
  - install zsh via brew, yum or apt...
- oh.my.zsh = `sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"`
- zsh-syntax-highlighting = `git clone https://github.com/zsh-users/zsh-syntax-highlighting.git`
`echo "source ${(q-)PWD}/zsh-syntax-highlighting/zsh-syntax-highlighting.zsh" >> ${ZDOTDIR:-$HOME}/.zshrc`
  - after i install zsh-syntax-highlighting i then edit my ~/.zshrc file
- zsh-autosuggestions = `git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions`
- i also add my standard zsh them to the ~/.zshrc file
  - `ZSH_THEME='half-life'`
- 