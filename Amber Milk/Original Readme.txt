RG35XXPLUS Theme customization tool
==========================

function
=====
1. This template provides the necessary material resources for customized themes
2. Can serve as a template for customized themes
3. Can be used to restore the official default theme

Customized methods
==============

File and folder description：
1. Theme-TCT. sh - Theme installation script
This file is the theme installation script, which is used to install the theme.
Important reminder: To ensure successful installation of the theme, the content of the file should not be changed. 
The file name can be changed freely, but it must be consistent with the theme resource folder name! Stay consistent! Stay consistent!
For example, the theme installation script file name is "Theme-ABC. sh", and the theme resource folder name is "Theme-ABC" (pay attention to capitalization).

2. Theme-TCT - Theme Resource Folder
Contains all resource files corresponding to the theme, and the folder name can be modified freely, but it must be consistent with the theme installation script file name! Stay consistent! Stay consistent!

Internal folder description:
Boot: The second screen logo image displayed when the host starts
Charge_ Mode: Animated image displayed during shutdown and charging
Desktop_ Res: Game hall interface material images (where the HDMI folder corresponds to the images displayed when connecting to an external TV, and the LCD folder corresponds to the images displayed on the host screen, the same below)
Game_ Menu: Front end main interface material image
Game_ Overlay: Picture of the border of some emulators in the game hall
Loading: The logo image displayed during game loading and exiting
Retro: RA game interface icon image
Setjoy: Key setting image
Setkey: Button setting image
Shutdown: shutdown display image and warning image when low battery
Sound: Key sound effect file
Test: Key test material image
Theme: Front end main interface icon image
Wallpapers: Front end background image
WiFi: WiFi prompt material image

Important reminder:
① When making modifications, please follow the file format, resolution, transparency effect, file name, and other parameters of the original material images to avoid display errors!
② The main interface icon and background image contain ten resource folders numbered "0-9". After modification, please select the corresponding number in the host settings.

3. Imgs - Preview image folder
There is only one PNG format image file in this folder, which is a preview image of the corresponding theme installation script. It can be used as a preview theme effect in the console game list.
Important note: The image file name must be exactly the same as the theme installation script file name. For example, if the script file name is "Theme ABC. sh", the preview image file name should be "Theme ABC. png".

Installation method
=============

After completing the customization, please copy the "Theme-TCT. sh", "Theme-TCT", and "Imgs" script files and two folders together to the "Roms/APPS" folder in the game partition of Card 1 or Card 2. After booting up, enter "RA Games - APPS" to see the "Theme-TCT" function. After running, complete the theme installation.

Enjoy!