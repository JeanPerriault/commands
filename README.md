# Commands

## NVM update

### Check latest nvm version at https://github.com/nvm-sh/nvm
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.35.1/install.sh | bash

### List available node version
nvm ls-remote

### Get latest node version, reinstall packages
nvm install 12.13.1 --reinstall-packages-from=10.16.0

### + get latest npm
nvm install 12.13.1 --reinstall-packages-from=10.16.0 --latest-npm

### get latest npm 'only'
npm i npm@latest -g

