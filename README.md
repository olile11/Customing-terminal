# Customing your terminal with zsh and oh my zsh on ubuntu

* # Customing with zsh
## 1 - Install the zsh command interpreter  

`sudo apt install zsh`  

Obs: It's just enough to customize your terminal with zsh. If you want instal some plugins, like "zsh-autosuggestions", follow  
### 1.2 Install the plugin  

`git clone https://github.com/zsh-users/zsh-autosuggestions ~/.zsh/zsh-autosuggestions`

#### 1.3 Enable the plugin

source ~/.zsh/zsh-autosuggestions/zsh-autosuggestions.zsh

It is ready to work. Try type any command in your terminal.


* # Custom with "oh my zsh framework"
There are different ways to customize with Oh My Zsh. The easiest is to use the Powerlevel10k configuration.
## 2 - Install oh my zsh
`sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"`  
or `sh -c "$(wget https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh -O -)"` 

### 2.1 - Install powerlevel10k
`git clone --depth=1 https://github.com/romkatv/powerlevel10k.git ~/powerlevel10k                                          
echo 'source ~/powerlevel10k/powerlevel10k.zsh-theme' >>~/.zshrc`

#### 2.1.1 - configure the terminal
type ` p10k configure` and follow the instructions in th screen

# References
* [Oh my zsh](https://ohmyz.sh/#install)
* [powerlevel10k](https://github.com/romkatv/powerlevel10k?tab=readme-ov-file#installation)
* [autosuggestions](https://github.com/zsh-users/zsh-autosuggestions/blob/master/INSTALL.md)
