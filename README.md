# Things to do after installing Linux (Debian, Ubuntu distros)

### System updates, Application updates, Package auto cleaning

  ```bash
  sudo apt update ; sudo apt upgrade -y ; sudo apt dist-upgrade -y ; sudo apt autoremove -y ; sudo apt autoclean -y
  ```
  
### Remove unwanted application & it's packages

  ```bash
  sudo apt remove gnome-weather gnome-contacts totem* gnome-maps gnome-mahjongg aisleriot gnome-2048 five-or-more four-in-a-row quadrapassel rhythmbox* tali swell-foop shotwell* hitori gnome-klotski gnome-chess gnome-mines gnome-music lightsoff gnome-robots gnome-nibbles gnome-sudoku gnome-tetravex gnome-taquin evolution*  -y
  ```
  
### System updates, Application updates, Package auto cleaning

  ```bash
  sudo apt update ; sudo apt upgrade -y ; sudo apt dist-upgrade -y ; sudo apt autoremove -y ; sudo apt autoclean -y
  ```
  
### Install wanted applications and services

  ```bash
  sudo apt install gnome-shell figlet lolcat neofetch -y
  ```
  
  + Optional
      ```bash
      sudo apt install fprintd -y
      ```
  
### System updates, Application updates, Package auto cleaning

  ```bash
  sudo apt update ; sudo apt upgrade -y ; sudo apt dist-upgrade -y ; sudo apt autoremove -y ; sudo apt autoclean -y
  ```
  
### Restart the system

  ```bash
  sudo reboot
  ```
