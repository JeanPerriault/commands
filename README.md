- [Commands](#commands)
  * [Update Homebrew itself](#update-homebrew-itself)
  * [Update NVM itself](#update-nvm-itself)
  * [Update Node via NVM](#update-node-via-nvm)
  * [Update NPM itself](#update-npm-itself)


# Commands

## Update Homebrew itself
### Get current version
```brew --version```
### Check latest version available
See releases on https://github.com/Homebrew/brew/releases
### Update homebrew itself
```brew update```

## Update NVM itself
### Get current version
```nvm --version```
### Check latest version available
See releases on https://github.com/nvm-sh/nvm/releases
### Update using latest NPM version number
```curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.35.1/install.sh | bash```
### Restart terminal

## Update Node via NVM
### List available Node version
```nvm ls-remote```
### Get latest Node version, reinstall packages (NPM modules)
```nvm install 12.13.1 --reinstall-packages-from=10.16.0```
### + get latest NPM
```nvm install 12.13.1 --reinstall-packages-from=10.16.0 --latest-npm```
### Actually use new node version
```nvm use 12.13.1```

## Update npm itself
```npm i npm@latest -g```
