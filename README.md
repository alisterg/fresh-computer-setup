It's fresh computer time!

# First things

- Sign in
- Check for system updates
- Install and run XCode from App Store
- Remove all icons from Dock, and any unused bloatware
- XCode CLI tools: `xcode-select --install`
- Homebrew: https://brew.sh

# Iterm2 and Neovim

- iterm2: `brew install --cask iterm2`
- Install the profiles from `./iterm_profiles`
- Oh My Zsh: https://ohmyz.sh/
- PowerLevel10k: https://github.com/romkatv/powerlevel10k#oh-my-zsh
- neovim:
  - `brew install neovim`
  - Copy dotfiles from `dotconfig` to `~/.config/nvim`
  - Vim-plug: https://github.com/junegunn/vim-plug#neovim
  - CoC plugins, eg. `:CocInstall coc-tsserver coc-json coc-html coc-css coc-prettier`

# Misc

- Node:
  - `brew install nvm`
  - Then follow the instructions to add to PATH etc
- z: `brew install z`
- tree: `brew install tree`
- Firefox: `brew install --cask firefox`
- Chrome: `brew install --cask google-chrome`
