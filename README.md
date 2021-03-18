# Brewfile for @t0m0120

## 利用方法


```bash

# homebrew をインストール
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)"

# このファイルをDL
curl -L https://raw.githubusercontent.com/t0m0120/Brewfile/master/Brewfile > ./Brewfile

# インストール
brew bundle
```

```
$ git clone --recursive https://github.com/sorin-ionescu/prezto.git "${ZDOTDIR:-$HOME}/.zprezto"

$ setopt EXTENDED_GLOB
for rcfile in "${ZDOTDIR:-$HOME}"/.zprezto/runcoms/^README.md(.N); do
  ln -s "$rcfile" "${ZDOTDIR:-$HOME}/.${rcfile:t}"
done'

$ brew tap sanemat/font
$ brew install ricty
$ brew reinstall --with-powerline --with-patch-in-place ricty
$ cp -f /usr/local/opt/ricty/share/fonts/Ricty*.ttf ~/Library/Fonts/
$ fc-cache -vf

```

gcc
```
.zshrc add
    source '/usr/local/Caskroom/google-cloud-sdk/latest/google-cloud-sdk/path.zsh.inc'
    source '/usr/local/Caskroom/google-cloud-sdk/latest/google-cloud-sdk/completion.zsh.inc'

```
