It's fresh computer time!

# First things

- Sign in
- Check for system updates
- Install and run XCode from App Store
- Install Magnet from App Store
- Remove all icons from Dock, and any unused bloatware
- XCode CLI tools: `xcode-select --install`
- Homebrew: https://brew.sh

# Iterm2 and Shell stuff

- Install: `brew install --cask iterm2`
- Install the themes from `./iterm_themes`
- z: https://github.com/rupa/z
- Oh My Zsh: https://ohmyz.sh/
- PowerLevel10k: https://github.com/romkatv/powerlevel10k#oh-my-zsh

# VSCode

- Install: `brew install --cask visual-studio-code`
- Install themes from `./vscode_themes` (.vsix file)
- Sign in with GitHub

Extensions:

- Vim
- Prettier
- Quill Icons
- Catppuccin Icons
- AWS Toolkit
- Insert GUID
- Any language / framework related plugins

# Misc

- Node: `brew install nvm`
  - Then follow the instructions to add to PATH etc
- Firefox: `brew install --cask firefox`
- Chrome: `brew install --cask google-chrome`
- ImageOptim: `brew install --cask imageoptim`
- SF Symbols: `brew install --cask sf-symbols`
- Get wallpapers from `./wallpapers`
- Install fonts from font repo
- `brew tap homebrew/cask-fonts`
- `brew install --cask font-ubuntu-mono`
- `brew install --cask font-jetbrains-mono`
- `brew install --cask font-source-code-pro`
- `brew install --cask font-hack`
- `brew install --cask font-sf-mono`

# Others

- Neovim: https://github.com/alisterg/dotfiles
- Slack: `brew install --cask slack`

---

<details>
<summary>VSCode settings</summary>

```json
{
  "telemetry.telemetryLevel": "off",
  "window.commandCenter": false,
  "editor.fontLigatures": true,
  "editor.wordWrap": "on",
  "editor.defaultFormatter": "esbenp.prettier-vscode",
  "workbench.tree.indent": 22,
  "debug.onTaskErrors": "debugAnyway",
  "git.autofetch": true,
  "editor.minimap.showSlider": "always",
  "breadcrumbs.enabled": false,
  "editor.rulers": [120],
  "terminal.integrated.defaultProfile.osx": "zsh",
  "css.lint.unknownAtRules": "ignore",
  "editor.cursorSmoothCaretAnimation": "on",
  "editor.cursorBlinking": "smooth",
  "editor.cursorSurroundingLines": 3,
  "editor.fontFamily": "consolas ligaturized v3, iosevkata, ubuntu mono",
  "workbench.iconTheme": "catppuccin-frappe",
  "editor.guides.indentation": false,
  "files.exclude": {
    "node_modules": true,
    "package-lock.json": true,
    "**/.git": true,
    "**/.svn": true,
    "**/.hg": true,
    "**/CVS": true,
    "**/.DS_Store": true,
    "**/Thumbs.db": true
  },
  "aws.telemetry": false,
  "aws.codeWhisperer.shareCodeWhispererContentWithAWS": false,
  "diffEditor.codeLens": true,
  "csharp.referencesCodeLens.enabled": false,
  "[csharp]": {
    "editor.defaultFormatter": "ms-dotnettools.csharp"
  },
  "workbench.colorTheme": "A-Ok",
  "workbench.activityBar.visible": false,
  "editor.folding": false,
  "workbench.colorCustomizations": {
    "editorBracketHighlight.foreground1": "#E77838bb",
    "editorBracketHighlight.foreground2": "#41A2C0bb",
    "editorBracketHighlight.foreground3": "#91A62Abb",
    "editorBracketHighlight.foreground4": "#D25C60bb"
  },
  "editor.fontSize": 13
}
```

</details>
