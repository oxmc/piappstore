# piappstore
This is a app store for the raspberry pi.
# Installation
```
wget -0 - https://raw.githubusercontent.com/oxmc/piappstore/main/install.sh | bash
```
# Use
To use the piappstore goto Accessories and click PiAppstore
that's it!
# Apps
To install apps you can search in the gui or in terminal type the name of the application after the caommand.
ie.
```
sudo piappstore install apmss
```
This will install apmss to your pi at the apps directory.
# Add your own app Part 1
To add your own app to the store i have to approve them they must meet these requirements:
1. Content must be sutible for all ages.
2. Must not download files without user knowing.
3. Must have a manifest saying what it does in a folder named info 
ie. /apps/apmss
             |
            info
            |
            manifest.dbf
Inside manifest.dbf
```
Title="Appache2PhpMariadbServerServer"
Desc="Hosts a website on a raspberry pi with apahe2, php, and mariadbserver"
Ver="beta"
```
# Add your own app part 2
after that make a zip folder of all files needed, then send it to me at sethlelandolivarez@gmail.com with the subject line of "PiAppStore"
