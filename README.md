# My Mac Os Dotfiles

# Preprare

## Install Home Brew
```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"

echo >> /Users/siavash/.zprofile
echo 'eval "$(/opt/homebrew/bin/brew shellenv)"' >> /Users/siavash/.zprofile
eval "$(/opt/homebrew/bin/brew shellenv)"
```
## Install Tools
```bash
#brew install --cask nikitabobko/tap/aerospace #on Ventura and above
#brew install --cask amethyst #works on BigSur, note alternative to both alfred and these two options is raycast.
#brew install --cask alfred

brew install --cask raycast #newer option

brew install --cask kitty

brew install yazi ffmpeg sevenzip jq poppler fd ripgrep fzf zoxide imagemagick font-symbols-only-nerd-font

brew install starship

brew install fzf #if not already as part of yazi

brew install neovim
brew install --cask sublime-text

brew install --cask zed
#note: trae isn't currently on brew, so need to install from: https://www.trae.ai/
brew install git
brew install lazygit

brew install btop
brew install dust
brew install tldr
brew install stow

brew install --cask google-chrome

brew install neofetch
```
