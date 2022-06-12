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
After installation enable `Biometric unlock for 1Password CLI`
![biometric-unlock](./assets/op-biometric-unlock.png?raw=true "Biometric Unlock")
## chezmoi
```bash
brew install chezmoi
```
## Reduce Motion
Enable it from  Accessibility preferences.
![reduce-motion](./assets/reduce-motion.png?raw=true "Accessibility")
# TODO
- [ ] Add logic to handle work laptop
- [ ] Add logic for linux
- [ ] Look into adding `asdf`
- [ ] Proper management for `kubeconfig` files