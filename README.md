# Homebrew full upgrade script
Homebrew - full upgrade of dependencies with cleanup script

Add to ```~/.bash_profile```
```
alias brew-full-upgrade="brew update && brew upgrade && brew cask upgrade && brew cleanup"
```

### Uuage
```brew-full-upgrade```
