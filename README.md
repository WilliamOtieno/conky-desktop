# conky-desktop
This is a pre-set configuration for conky for Linux users to customize their desktops

#installation

For debian based systems like ubuntu, mint, elementary os..etc
Run the following commands:
  sudo apt update && sudo apt upgrade
  sudo apt install conky-all

For Arch based systems like Manjaro, Arch linux...
Run the following commands:
  sudo pacman -Syu
  sudo pamac install conky
  
 After installing conky, create a directory in ~/.config and name it conky
 In ~/.config/conky copy and paste the config file provided
 
 Open terminal and run this command in sudo
   conky -C > ~/.config/conky/conky.conf
   
  This makes conky read the contents of that file
  
  After that enable conky as one of the startup commands so that it may run eternally in your system
  
  You may alter the contents of the config file according to your preferences by editing it in your favourite text editor
  Enjoy
  
