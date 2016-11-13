# RainCoat

>Just a mininmal color scheme for iTerm2 and simple ZSH theme for OH-MY-ZSH. 

#### Inspiration
The iTerm2 color scheme is inspired by the [Seti_UX color scheme for Sublime Text 3](https://github.com/ctf0/Seti_UX)

The ZSH theme is inspired by the `robbyrussel` theme and the `poncho` and original `rain_coat` themes ([oh-my-zsh-poncho](https://github.com/RainyDayMedia/oh-my-zsh-poncho)) but I added support of [ZSH Syntax Highlighting](https://github.com/zsh-users/zsh-syntax-highlighting) and [ZSH Autocomplete](https://github.com/zsh-users/zsh-autosuggestions) You'll want to check out [my dotfiles](https://github.com/ginfuru/dotfiles) to get more info on those particular configurations. RainCoat is git aware and does support the usage of the Powerline fonts.

### Screenshots

![error handling and git support](https://raw.githubusercontent.com/ginfuru/RainCoat/master/images/error-handle-with-git-support.png)
![zsh autocomplete and directory colors](https://raw.githubusercontent.com/ginfuru/RainCoat/master/images/zsh-autocomplete-with-dir-colors.png)
![iterm color settings](https://raw.githubusercontent.com/ginfuru/RainCoat/master/images/iterm2-colors.png)
![iterm text settings](https://github.com/ginfuru/RainCoat/blob/master/images/iterm2-text.png)

### Installation

Installing is pretty straight forward and simple. 

**step 1**

```zsh
    git clone https://github.com/ginfuru/RainCoat.git ~/.oh-my-zsh/custom/themes/RainCoat
```

**step 2** edit your `.zshrc` file

```zsh
    ZSH_THEMS="RainCoat"
```

**step 3**
Double click `RainCoat.itermcolors` to install the iTerm2 color scheme

##### Updating

Just run 

```zsh 
    cd ~/.oh-my-zsh/custom/themes/RainCoat && git pull --rebase
```
