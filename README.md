# conky-desktop
This is a pre-set configuration for conky for Linux users to customize their desktops

#installation

For debian based systems like ubuntu, mint, elementary os..etc
Run the following commands:
  sudo apt update && sudo apt upgrade
  sudo apt install conky-all

For Arch based systems like Manjaro, Arch linux...
Run the following commands:
  sudo pacman -Syyuu
  pamac install conky or sudo pacman -S conky
  
 After installing conky, copy my config file into the location ~/.conky
This folder may be hidden so be sure to unhide it so that you can access the contents
 
 Open terminal and run this command in sudo
   conky -c > ~/.conky/conky.conf
   
  This makes conky read the contents of that file
  
  After that enable conky as one of the startup commands by first editing the contents of the conky-startup.sh file and replacing USER with your user then add that script as one of the startup commands so that it may run eternally in your system
  
  You may alter the contents of the config file according to your preferences by editing it in your favourite text editor
  Enjoy
  
