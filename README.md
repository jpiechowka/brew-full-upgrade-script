# Homebrew full upgrade script
Homebrew - full upgrade of dependencies with cleanup script

Add to ```~/.bash_profile``` if using bash or ```~/.zshrc``` if using zsh
```
alias brew-full-upgrade="brew update -v && brew upgrade -v && brew cleanup -v"
```

### Usage
```brew-full-upgrade```
