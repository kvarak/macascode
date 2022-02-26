
# Setup the Mac

1. Set bash as default
- chsh -s /bin/bash

2. Install Homebrew
- Installing Xcode’s Command Line Tools
`xcode-select --install`
- Installing and Setting Up Homebrew
`curl -fsSL -o install.sh https://raw.githubusercontent.com/Homebrew/install/master/install.sh`
`/bin/bash install.sh`
Add Homebrew's executable directory to the front of the PATH in ~/.bash_profile
`export PATH=/usr/local/bin:$PATH`

3. Get the profile files
- .ssh
- .bash_profile
- .gitconfig
- synergy.conf

4. Tools
brew update
# base
brew install git
brew install python
brew install r
brew install v8
brew install wireguard-tools
brew install --cask rstudio
brew install --cask docker
brew install --cask visual-studio-code
brew install --cask the-unarchiver
brew install postgresql@12   # brew services start postgresql@12
# extra
brew install wget
brew install ansible
brew install --cask synergy
brew install --cask slack
brew install --cask brave-browser   #Create profiles, setup sync for each profile
brew install --cask firefox
brew install --cask google-drive
brew install --cask steam
brew install --cask skype
brew install --cask dropbox
brew install --cask discord
brew install --cask remarkable
# making
brew install --cask ultimaker-cura
brew install --cask balenaetcher
brew install --cask arduino
brew install platformio
brew install swi-prolog
brew install libgit2
# coding
xcode-select --install
brew install azure-cli

5. Settings
Code from commandline?

# ???
arduino

6. Ruby

brew update
brew upgrade ruby
brew install ruby-build
brew install rbenv

rbenv install 3.0.1
rbenv global 3.0.1

