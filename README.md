# Upgrade-Your-Terminal/LINUX
This guide provides comprehensive instructions and recommendations for enhancing your Linux command-line experience. Learn how to transform your default terminal emulator into a powerful, visually appealing and highly efficient workspace. We cover updates regarding switching your default shell (BASH) to (ZSH) installing modern, faster command-line utilities and customizing the aesthetic appeal with themes and fonts. Discover tools that streamline workflows, automate tasks and significantly boost your productivity.


<img width="1343" height="698" alt="Screenshot from 2025-08-09 13-41-52" src="https://github.com/user-attachments/assets/a71e31e2-1b9b-4544-9fa8-95cdb0a517ff" />


## Install-ZSH
Use the command below to install ZSH in your Terminal

`sudo apt install zsh`

<img width="798" height="170" alt="Screenshot from 2025-08-09 12-55-33" src="https://github.com/user-attachments/assets/cdbad753-1af9-4421-b192-901f1b9a00e6" />

## Set-ZSH-as-Default-SHell
Use the command below to set ZSH as your default shell

`chsh -s $(which zsh)`

<img width="797" height="109" alt="Screenshot from 2025-08-09 12-57-45" src="https://github.com/user-attachments/assets/50df6593-fbe6-49a7-85bb-e73257a0019c" />

## Install-ohmyzsh
Use the following command to install ohmyzsh in the Terminal

`sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"`

## ZSH-Default-Themes

https://github.com/ohmyzsh/ohmyzsh/wiki/Themes

To change themes of your ZSH use the following command in the Terminal

`nano .zshrc`

<img width="809" height="525" alt="Screenshot from 2025-08-09 13-01-00" src="https://github.com/user-attachments/assets/bea90fc7-6e75-47c7-bf35-0b0b96af6992" />


Find the theme section in your terminal and write the name of the theme that you want to use in your Terminal. LIke:

ZSH_THEME="jonathan"


## ZSH-Autosuggestions-Plugin
Use the following command to install ZSH autosuggestions plugin in the Terminal

`git clone https://github.com/zsh-users/zsh-autosuggestions.git $ZSH_CUSTOM/plugins/zsh-autosuggestions`

## ZSH-Syntax-Highlighting-Plugin
Use the following command to install ZSH syntax highlighting plugin in the Terminal

`git clone https://github.com/zsh-users/zsh-syntax-highlighting.git $ZSH_CUSTOM/plugins/zsh-syntax-highlighting`

## More-Plugins-for-ohmyzsh

`https://github.com/ohmyzsh/ohmyzsh/wiki/Plugins`


