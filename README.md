# osx-bootstrap
Setup a new osx system

## Tasks
* Set default shell to ZSH `chsh -s /bin/zsh`
* Install Homebrew `/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"`
    - tmux `brew install tmux`
    - PostgreSQL `brew install postgresql`
    - REDIS `brew install redis`
    - Heroku Toolbelt `brew install heroku`
    - ssh-copy-id `brew install ssh-copy-id`
    - vim `brew install vim`
    - mas `brew install mas`
    - Node `brew install node`
* Install Homebrew Cask `brew tap caskroom/cask`
    - Chrome `brew cask install google-chrome`
    - VLC `brew cask install vlc`
    - Dropbox `brew cask install dropbox`
    - Transmission `brew cask install transmission`
    - Atom `brew cask install atom` 
    - Discord `brew cask install discord`
    - iterm2 `brew cask install iterm2`
* MAS Install
    - Keynote `mas install 409183694`
    - iStat Mini `mas install 927292435`
    - Evernote `mas install 406056744`
    - Caffeine `mas install 411246225`
    - Slack `mas install 803453959`
    - Pixelmator `mas install 407963104`
    - Paw `mas install 584653203`
    - BetterSnapTool `mas install 417375580`
    - Numbers `mas install 409203825`
    - Dash 3 `mas install 449589707`
* Setup Dotfiles `git clone ...`
* Add SSH key to Github `?`
* Install RVM `\curl -sSL https://get.rvm.io | bash -s stable`
* Latest Ruby `rvm install 2.3`
