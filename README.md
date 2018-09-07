# Useful_Linux_Stuff
Stuff that I use with Linux that I've made to make things easier for myself.

___

# How to install my scripts?
Place a downloaded script into /usr/local/bin/
Once placed you can use the script by typing the name of it in terminal, ezpz!
You can also send a keybind to the script by using your built in settings custom shortcut

___

### Screenshot_Region: A code to help people easily screenshot things on their screen.
Screenshot_Region is an automated screenshot helper built for the linux platform, in relation to something like ShareX on windows
Upon first start, if you don't have the packages required, that's OK! The script is built to automatically detect and let you choose what you want downloaded. Sadly, if you choose not to download one of the required packages, it will end.
Once you have the packages up, the tool will take a screenshot with scrot, send it to feh as a frozen display, use gnome-screenshot to take the shot, end feh with xdotool and copy it to your clipboard with xclip. If you use ubuntu or debian like systems there's also a notify-send at the end but I choose not to really care for it to be honest, it's not required.
##### **Required Packages**:
######  scrot xdotool gnome-screenshot xclip feh

___

### xboxdrv_hlpr: created for the purpose to help out people who use xboxdrv
###### My personal favorite creation I've made on Linux and python both.
xboxdrv doesn't have builtin autodetection, easy selection or vice versa. This is here to help with that <br/>
xboxdrv_hlpr will detect your plugged in USBs and give you an output to select the device you want, to make xboxdrv much easier then it already is and with built in auto-detection in the case that you change USBs. <br/> <br/>
**TESTED ON PYTHON 2.7 and UP** <br/>
*Use --help for more information while using*
