# dev-setup
Mac development setup notes

## Homebrew

A package manager for macOS (or Linux)

`/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"`

## Xcode

If you don't do this, other install steps (such as powerlevel10k) will fail.

`xcode-select --install`

## iterm 2

`brew install iterm2`

* [Iterm2 Color Schemes](https://iterm2colorschemes.com/)

## Fonts

`brew tap homebrew/cask-fonts`

`brew install font-fira-code`

## Oh My Zsh

https://github.com/ohmyzsh/ohmyzsh

### Install zsh packages

`brew install zsh-autosuggestions`

`brew install zsh-syntax-highlighting`

### Powerline Fonts

https://github.com/powerline/fonts

### [PowerLevel10K](https://github.com/romkatv/powerlevel10k#installation)


## QuickLook Plugins

Quicklook plugins previews in Finder.

`brew install qlcolorcode qlmarkdown quicklook-json qlprettypatch quicklook-csv qlimagesize webpquicklook quicklookase qlvideo`

## install wget, curl, tree, httpie

`brew install wget curl tree jq httpie`

## Visual Studio Code

`brew install visual-studio-code`






