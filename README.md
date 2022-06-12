# Manual Setup
##  homebrew
```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```
## 1Password 8
Should be installed from the App Store
## 1password-cli
```bash
brew install 1password-cli
```
## chezmoi
```bash
brew install chezmoi
```
## Reduce Motion
Enable it from  Accessibility preferences.
![reduce-motion](./assets/reduce-motion.png?raw=true "Accessibility")

# Requirements
## 1Password CLI
Get it [here](https://1password.com/downloads/command-line/) or run the following command
```sh
brew install 1password-cli
```

After installation and the initial signin run this if the sesssion expires
```sh
eval $(op signin)
```
## Tasks
- [ ] Add logic to handle work laptop
- [ ] Add logic for linux
- [ ] Look into adding `asdf`
- [ ] Proper management for `kubeconfig` files