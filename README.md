# Things to do after installing Linux (Debian, Ubuntu distros)

  ``Follow step-wise``

## 1. System updates, Application updates, Package auto cleaning

  ```bash
  sudo apt update ; sudo apt upgrade -y ; sudo apt dist-upgrade -y ; sudo apt autoremove -y ; sudo apt autoclean -y
  ```
  
## 2. Remove unwanted application & it's packages

  ```bash
  sudo apt remove gnome-weather gnome-contacts totem* gnome-maps gnome-mahjongg aisleriot gnome-2048 five-or-more four-in-a-row quadrapassel rhythmbox* tali swell-foop shotwell* hitori gnome-klotski gnome-chess gnome-mines gnome-music lightsoff gnome-robots gnome-nibbles gnome-sudoku gnome-tetravex gnome-taquin iagno* evolution* gdm* -y
  ```
  
## 3. System updates, Application updates, Package auto cleaning

  ```bash
  sudo apt update ; sudo apt upgrade -y ; sudo apt dist-upgrade -y ; sudo apt autoremove -y ; sudo apt autoclean -y
  ```
  
## 4. Install wanted applications and services

  ```bash
  sudo apt install gnome-session gnome-core gnome-shell gnome-calendar gnome-browser-connector locales nano figlet lolcat neofetch snap snapd firmware-* libreoffice locate mlocate gnome-shell-extension-manager gdm3* seahorse thunderbird vlc linux-image-$(uname -r) nano network-manager gnome-shell vim nano wget curl net-tools ifupdown iproute2 bash-completion grub-pc -y
  ```
  
  + Optional
      ```bash
      sudo apt install fprintd inkscape -y
      ```

  
## 5. Install wanted applications and services

  ```bash
  sudo apt remove --purge gnome-contacts totem* -y
  ```

## 6. System updates, Application updates, Package auto cleaning

  ```bash
  sudo apt update ; sudo apt upgrade -y ; sudo apt dist-upgrade -y ; sudo apt autoremove -y ; sudo apt autoclean -y
  ```
  
## 7. Restart the system

  ```bash
  sudo reboot
  ```
