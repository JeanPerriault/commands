# Commands

## Homebrew
### Update homebrew itself
```brew update```


## NVM update

### Update NVM itself
#### Get current version
```nvm --version```
#### Check latest nvm version
See releases on https://github.com/nvm-sh/nvm
#### Update using latest npm version number
```curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.35.1/install.sh | bash```
#### Restart terminal



### Update Node

#### List available node version
```nvm ls-remote```
#### Get latest node version, reinstall packages
```nvm install 12.13.1 --reinstall-packages-from=10.16.0```
#### + get latest npm
```nvm install 12.13.1 --reinstall-packages-from=10.16.0 --latest-npm```
#### get latest npm 'only'
```npm i npm@latest -g```
#### Actually use new node version
```nvm use 12.13.1```
