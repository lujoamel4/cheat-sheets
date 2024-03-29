# Oh my zsh.
## Install zsh
```
sudo apt install zsh
```

## Install with curl
```
sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
```

## Enabling Plugins (zsh-autosuggestions & zsh-syntax-highlighting)
 - Download zsh-autosuggestions by
 
 
```
git clone https://github.com/zsh-users/zsh-autosuggestions.git $ZSH_CUSTOM/plugins/zsh-autosuggestions
```
 
 - Download zsh-syntax-highlighting by
 
 
```
git clone https://github.com/zsh-users/zsh-syntax-highlighting.git $ZSH_CUSTOM/plugins/zsh-syntax-highlighting
```

 - 
```
nano ~/.zshrc` find `plugins=(git)
```
 
 - Append 
```
zsh-autosuggestions & zsh-syntax-highlighting
``` 
to  `plugins()` like this 
 
 
```
plugins=(git zsh-autosuggestions zsh-syntax-highlighting)
```

 - My favorite plugins are
 
 - Reopen terminal

### Ref
 - [oh-my-zsh](https://github.com/robbyrussell/oh-my-zsh)
 - [zsh-autosuggestions](https://github.com/zsh-users/zsh-autosuggestions)
 - [zsh-syntax-highlighting](https://github.com/zsh-users/zsh-syntax-highlighting)
 - [https://gist.github.com/kevin-smets/8568070](https://gist.github.com/kevin-smets/8568070)
 - [original gist](https://gist.github.com/dogrocker/1efb8fd9427779c827058f873b94df95)

## Current plugins


```
plugins=(git zsh-autosuggestions zsh-syntax-highlighting python tmux command-not-found debian)
```
