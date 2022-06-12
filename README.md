# Manual Setup
1. Install `homebrew`
2. Install `1password-cli` and `1password`
3. Enable `Reduce Motion` in Macos Accessibility preferences.
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