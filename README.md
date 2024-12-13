# Things to do after installing Linux (Debian, Ubuntu distros)

+ Follow step-wise

### 1. System updates, Application updates, Package auto cleaning

  ```bash
  sudo apt update ; sudo apt upgrade -y ; sudo apt dist-upgrade -y ; sudo apt autoremove -y ; sudo apt autoclean -y
  ```
  
### 2. Remove unwanted application & it's packages

  ```bash
  sudo apt remove gnome-weather gnome-contacts totem* gnome-maps gnome-mahjongg aisleriot gnome-2048 five-or-more four-in-a-row quadrapassel rhythmbox* tali swell-foop shotwell* hitori gnome-klotski gnome-chess gnome-mines gnome-music lightsoff gnome-robots gnome-nibbles gnome-sudoku gnome-tetravex gnome-taquin iagno* evolution* -y
  ```
  
### 3. System updates, Application updates, Package auto cleaning

  ```bash
  sudo apt update ; sudo apt upgrade -y ; sudo apt dist-upgrade -y ; sudo apt autoremove -y ; sudo apt autoclean -y
  ```
  
### 4. Install wanted applications and services

  ```bash
  sudo apt install gnome-shell figlet lolcat neofetch snap snapd firmware-* libreoffice locate mlocate gnome-shell-extension-manager -y
  ```
  
  + Optional
      ```bash
      sudo apt install fprintd -y
      ```
  
### 5. System updates, Application updates, Package auto cleaning

  ```bash
  sudo apt update ; sudo apt upgrade -y ; sudo apt dist-upgrade -y ; sudo apt autoremove -y ; sudo apt autoclean -y
  ```
  
### 6. Restart the system

  ```bash
  sudo reboot
  ```
