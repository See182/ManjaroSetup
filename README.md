ManjaroSetup

Install Guide for my personal Manjaro Gnome Minimal Setup

1. sudo pacman -Syu

2. Remove Manjaro Hello / Application Utility
    sudo pacman -R manjaro-hello

3. Install yay
    sudo pacman -S yay

4. Install TimeShift
    sudo pacman -S timeshift
    Create System Point

5. Install zsh and OMZ
https://github.com/Powerlevel9k/powerlevel9k#installation

https://www.freecodecamp.org/news/jazz-up-your-zsh-terminal-in-seven-steps-a-visual-guide-e81a8fd59a38/

https://medium.com/@alex285/get-powerlevel9k-the-most-cool-linux-shell-ever-1c38516b0caa

ZSH_THEME="powerlevel9k/powerlevel9k"
POWERLEVEL9K_MODE="nerdfont-complete"

POWERLEVEL9K_DISABLE_RPROMPT=true
#POWERLEVEL9K_PROMPT_ON_NEWLINE=true
#POWERLEVEL9K_MULTILINE_LAST_PROMPT_PREFIX="▶ "
#POWERLEVEL9K_MULTILINE_FIRST_PROMPT_PREFIX=""

POWERLEVEL9K_LEFT_PROMPT_ELEMENTS=(custom_icon context dir vcs)

POWERLEVEL9K_CUSTOM_ICON="echo  "
POWERLEVEL9K_CUSTOM_ICON_BACKGROUND=069
POWERLEVEL9K_CUSTOM_ICON_FOREGROUND=015

6. instlal Screenfetch
install Firefox, Evolution, Spotify, Visual Code Studio, Gitkraken, Enpass, Java JDK, MEGASync

install powershell openjdk

7. Install BalenaEtcher, Lutris, Remmina

8. Install LightDM

Theme: https://aur.archlinux.org/packages/lightdm-webkit-theme-aether/

TODO:
Nautilus pimpen
USB Tools format and creator