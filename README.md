# FFXIV Bash Script to install Centzilius's FFXIV Proton Fix
A script designed to install XIVLauncher and run it on Steam on linux. 

This script also has support for non-steam account holders who want to launch XIVLauncher from the FFXIV Free Trial page on Steam

# NOTE: This script deletes your FFXIV prefix, please ensure you have backed up your config files before allowing the script to delete your prefix

# Instructions


Commands:

- git clone https://github.com/Moosatronic/LinuxFFXIVProtonFix.git
- cd LinuxFFXIVProtonFix
- chmod +x ffxivfix.sh
- ./ffxivfix.sh



# What does this script do?

It installs Centzilius's game fix located in this repository as well as all of its dependencies to either FFXIV or FFXIV's free trial on Steam so that you can run XIVLauncher from Steam. This fix is necessary for Steam FFXIV account players to play FFXIV on Linux.

# Dependencies

- Git
- Curl
- Steam
- Proton 5 (installed in steam)
- Proton-6.21-GE-2


# Troubleshooting

## Compatibilitytools.d
Currently the script may run into an error if compatibilitytools.d, a folder that usually exists in your steam install isnt present. This can be resolved by simply making the folder in your steam install and running the script again.

## Steam Deck
It is unclear if this script can be run on a Steam Deck without turning off read only mode. If you have a Steam Deck and you can run this script and start XIVLauncher without turning read only mode then please leave a comment saying same in this repository.

## "I get a write free space error when trying to get XIVLauncher to download FFXIV Launcher"

If you get a long error that has some section stating "Util.GetDIskFreeSpace" then you may find success by setting a different FFXIV install directory, particularly one outside of your virtual wine "C://" drive.

![](https://i.imgur.com/cOSre5H.png)

![](https://i.imgur.com/nXvwk7I.png)






If you are able to launch XIVLauncher, any further issues running FFXIV can be troubleshooted at [FFXIVLauncher's support page](https://goatcorp.github.io/faq/xl_troubleshooting.html). 



# Credits

Glorious Eggroll for his wonderful Proton-GE
Centzilius for creating the protonfix used in this repository.
HereInPlainSight for providing additional improvements.

# TO DO

- have script check for compatibilitytools.d
- improve documentation
