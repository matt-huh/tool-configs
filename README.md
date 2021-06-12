# Dev Environment

## Tool Configurations

- Git
- Visual Studio Code
- iTerm2
- Oh My Zsh

## Oh My Zsh

### Install Zsh
```
brew install zsh zsh-completions
```

### Install Oh My Zsh

(from [Oh My Zsh](https://github.com/ohmyzsh/ohmyzsh))
#### via curl
```
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```

#### via wget
```
sh -c "$(wget -O- https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```

### Add theme
1. Download mattizer.zsh-theme to `~/.oh-my-zsh/themes`
2. Open `~/.zshrc` with a text editor
3. Change the value of `ZSH_THEME`, which will then look like:
```
ZSH_THEME="mattizer"
```

