# zsh config
Screenshot:

![](https://github.com/haccks/zsh-config/blob/master/images/final.png?raw=true)

Working terminal:

![](https://github.com/haccks/zsh-config/blob/master/images/final.gif?raw=true)

## Prerequisite:
Homebrew/macport should be installed. If not then [install](https://www.howtogeek.com/211541/homebrew-for-os-x-easily-installs-desktop-apps-and-terminal-utilities/) the lates version of homwbrew.

## A step by step guide to customize your zsh terminal:

### 1. [Install iTerm2](https://www.iterm2.com/)

iTerm2 is way better than OS X terminal. I would also recommend to install [shell integration](https://www.iterm2.com/documentation-shell-integration.html) for it.

### 2. [Install zsh](https://rick.cogley.info/post/use-homebrew-zsh-instead-of-the-osx-default/)

After installation of zsh, set it as login shell in iTerm2. You may need to run this command: `chsh -s $(which zsh)`. Logout from iTerm2 and then again launch it.
Type `echo $0` and you will see `zsh`. You can also use macports to install the `zsh`.

### 3. [Install oh-my-zsh](https://ohmyz.sh/) plugin

![](https://camo.githubusercontent.com/5c385f15f3eaedb72cfcfbbaf75355b700ac0757/68747470733a2f2f73332e616d617a6f6e6177732e636f6d2f6f686d797a73682f6f682d6d792d7a73682d6c6f676f2e706e67)  
<sub>Image credit: [oh-my-zsh](https://ohmyz.sh/)</sub>

Run the following command in the terminal to install it:  
`sh -c "$(curl -fsSL https://raw.github.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"`

### 4. [Install powerlevel9k](https://github.com/bhilburn/powerlevel9k) theme for oh-my-zsh

Run the following command in the terminal:  
`git clone https://github.com/bhilburn/powerlevel9k.git ~/.oh-my-zsh/custom/themes/powerlevel9k`

### 5. [Install a Nerd Font](https://github.com/ryanoasis/nerd-fonts)

Download [`Meslo LG L DZ Regular Nerd Font Complete.otf`](https://github.com/ryanoasis/nerd-fonts/blob/master/patched-fonts/Meslo/L-DZ/complete/Meslo%20LG%20L%20DZ%20Regular%20Nerd%20Font%20Complete.otf) and install it. Then go to *Open ITerm2 > Preferences > Profiles > Text* and open *Change Font* 
and select *Meslo LG L DZ Regular Nerd Font Complete* font.

![](https://github.com/haccks/zsh-config/blob/master/images/font.png)

### 6. Install a color scheme for iTerm2 

I choosed [material design theme](https://github.com/MartinSeeler/iterm2-material-design). Installation instructions are given at the given link.

### 7. Install two more plugins for zsh

+ `zsh` Syntax Highlighting Plugin:   
    `git clone https://github.com/zsh-users/zsh-syntax-highlighting.git $ZSH_CUSTOM/plugins/zsh-syntax-highlighting`

+  `zsh` AutoSuggestion Plugin:  
	`git clone https://github.com/zsh-users/zsh-autosuggestions $ZSH_CUSTOM/plugins/zsh-autosuggestions`

### 8. Replace `.zshrc` file 

Either dowload the given `.zshrc` file and replace your `.zshrc` file with this or copy the entire text from the given file to your `.zshrc` file.







