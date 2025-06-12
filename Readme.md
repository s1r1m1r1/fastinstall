.vimrc brew config for asdf and flutter

```
eval "$(/opt/homebrew/bin/brew shellenv)"


. /opt/homebrew/opt/asdf/libexec/asdf.sh
if type brew &>/dev/null
then
  FPATH="$(brew --prefix)/share/zsh/site-functions:${FPATH}"

  autoload -Uz compinit
  compinit
fi
export FLUTTER_ROOT="$(asdf where flutter)"
```


```
brew install asdf
```
```
brew install --cask google-chrome 
```
```
brew install --cask android-studio
```
