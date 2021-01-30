# PocketGo S30 Add-On Pack 
by onionsaregross (http://retrogamecorps.com)

<b>To download, click on the green "Code" button at the top-right of this page, and then select "Download Zip".</b>

## Introduction

This add-on pack will create new wallpapers for all of your systems, increase the number of systems available on your device, and organize the menu into a logical hierarchy: Nintendo systems (by order of release and consoles before handhelds), Sega systems, Sony systems, NEC systems, then outlying handhelds (Neo Geo Pocket, Wonderswan, etc) and other systems.

This pack also includes updated emulators (RetroArch cores) with pre-configured screen settings and ideal aspect ratios for emulation accuracy.

This add-on pack assumes that you have already backed up the stock SD card that came with your device.  The user accepts all responsibility for exploded microSD cards or S30 devices.

<b>PocketGo S30 Starter Guide</b>, which includes accepted game file types and a video walkthrough: https://retrogamecorps.com/2021/01/08/pocketgo-s30-starter-guide/

If you would rather download an fresh copy of the original SD card contents (+ the v1.7 add-on pack pre-loaded), and paste into a brand new SD card, you can find it here.  Note that you must format the new card to FAT32, and this does not include any ROM or BIOS files, so you will need to add those yourself. https://drive.google.com/file/d/1-C9SkaPAZx7EfABEA6QXyaSk4c0FynQQ/view?usp=sharing

## Credit

Default wallpaper images based on ckau-book Batocera theme by CkauNui
https://github.com/CkauNui/ckau-book<br>
game_bg.png image by VinceHase<br>
Futura theme by Baguette Crusader<br>
Futura (alternate) theme by victoriemini<br>
ckau theme by Cartman
epicnoir theme by TetrisSQC
save shutdown solution by DaMikki

## Instructions

1. Insert your S30 microSD card into your computer.
2. UPDATE WALLPAPERS:  On your SD card, remove the skins/Default folder, and remove the 'wallpapers' folder.  Place the new 'wallpapers' folder from this pack into the skins/Default folder.  If you'd like, you'll find subfolders with other themes (Futura, ckau, epicnoir, etc.), and you can use those instead -- just move the images into the skins/Default folder.  Some of these alternate themes have their own font; if you find a font.ttf file in the subfolder, move it to the skins/Default folder and replace the font.ttf file that's already in there.  If they do not contain the "poweroff.png" image in their skins collection, continue to use the default image.
3. UPDATE LAUNCH FILES:  On your SD card, go to the 'sections' folder, and remove the 'emulators' folder.  Place the new 'emulators' folder from this pack in the 'sections' folder.
4. MOVE 'SAVES' FOLDER.  Move the 'saves' folder in this package to the main (root) directory of your SD card.
5. MOVE 'SOFTSHUTDOWN' FOLDER.   Move the 'softshutdown' folder in this package to the 'emus' directory of your SD card.
5. UPDATE EMULATORS.  On your SD card, go to the 'emus' folder, and remove the 'retro' folder.  You can store it on your computer for safe-keeping if you'd like.  Place the new 'retro' folder from this pack into the emus folder.  Then, unzip the file named "unzip_and_add_to_retro_folder.zip", and add its contents to the new retro folder on your SD card.
6. VERIFY ROMS FOLDERS: On your SD card, go to the 'roms' folder and change the folder names so they are as follows (minus the information in the parenthesis).  Also, delete the folder named "npg", this is an unecessary folder.  You will need to create new folders for some systems, and rename some others:

32x (new)<br>
atari2600 (new)<br>
c64 (new)<br>
dc (no change)<br>
fbn (previously named "fba")<br>
fds (new)<br>
gb (no change)<br>
gba (no change)<br>
gbc (no change)<br>
genesis (previously named "md")<br>
gg (new)<br>
gw (new)<br>
lynx (new)<br>
mame (no change)<br>
neogeo (new)<br>
nes (previously named "fc")<br>
ngpc (previously named "ngp")<br>
psp (previously named "ppsspp")<br>
psx (previously named "ps")<br>
segacd (new)<br>
sms (new)<br>
snes (previously named "sfc")<br>
tg16 (previously named "pce")<br>
tgcd (new)<br>
tic80 (new)<br>
vb (new)<br>
wsc (previously named "ws")<br>
zxspectrum (new)<br>

7. ADD BIOS FILES:  Ensure you have the following BIOS files in the appropriate locations on the SD card.  These BIOS files are not part of the add-on pack, you will need to find them yourself.

- Game Boy Advance: place the gba_bios.bin BIOS file in the bios folder
- PlayStation: place scph1001.bin BIOS file in the emus/pcsx4all/bios folder
- Sega Dreamcast: place dc_boot.bin and dc_flash.bin BIOS files in the bios/dc folder
- Neo Geo: place the neogeo.zip BIOS file in the bios folder
- Famicom Disk System: place the disksys.rom BIOS file in the bios folder
- Sega CD: place the bios_CD_E.bin, bios_CD_J.bin, and bios_CD_U.bin BIOS files in the bios folder
- TurboGrafx-CD: place the syscard1.pce, syscard2.pce, and syscard3.pce files in the bios folder
- Atari Lynx: place the lynxboot.img BIOS file in the bios folder

## Supported Systems

FINALBURN NEO<br>
MAME 2003<br>
NEO GEO<br>
NINTENDO ENTERTAINMENT SYSTEM<br>
FAMICOM DISK SYSTEM<br>
SUPER NINTENDO ENTERTAINMENT SYSTEM<br>
NINTENDO VIRTUAL BOY<br>
NINTENDO GAME & WATCH<br>
NINTENDO GAME BOY<br>
NINTENDO GAME BOY COLOR<br>
NINTENDO GAME BOY ADVANCE<br>
SEGA MASTER SYSTEM<br>
SEGA GENESIS<br>
SEGA CD<br>
SEGA 32X<br>
SEGA DREAMCAST<br>
SEGA GAME GEAR<br>
SONY PLAYSTATION<br>
SONY PSP<br>
TURBOGRAFX-16 (PC ENGINE)<br>
TURBOGRAFX-CD (PC ENGINE CD)<br>
NEO GEO POCKET / COLOR<br>
ATARI LYNX<br>
WONDERSWAN / COLOR<br>
COMMODORE 64<br>
ZX SPECTRUM<br>
TIC-80<br>
ATARI 2600<br>

- To delete a system from your device, simply go into the sections/emulators folder and delete the undesired system launch file.

## Notes and Known Issues

- Be sure to use the new "safe shutdown" method.  If you cycle through your available systems, you will see a screen with a power switch icon and the word 'shutdown'.  Press the A button to safely shutdown your system without using your power button.  The best way to think of this is that you will use the POWER button to turn ON your system, and the shutdown icon to power OFF your system.  This will ensure that your saves and configuration files persist.  
- If you power down the system without using the safe shutdown method, the retroarch-core-options.cfg file may get overwritten, and you will lose some functionality (green colorization in GB, high resolution in Dreamcast).  If this happens to you, paste this code in the emus/retro/retroarch-core-options.cfg file on your SD card: https://github.com/retrogamecorps/s30-add-on-pack/blob/main/retro/retroarch-core-options.cfg 
- L2 and R2 are not assigned in RetroArch, and I cannot figure out how to assign them since we're locked out of the RetroArch menu.  For this reason, I am still using the PS1 emulator that shipped with the S30 device.
- If you are not satisfied by the full-screen aspect ratio for every system, you can change it yourself relatively easily.  Check out my writen guide for detailed instructions: https://retrogamecorps.com/2021/01/08/pocketgo-s30-starter-guide/
- If you are interested in adding your own RetroArch cores to this device, they are running cores from this repo: https://github.com/Retro-Arena/ARES-Binaries/tree/master/buster/odroid-xu/kms/libretrocores

## Changelog

<b>v1.7 (29JAN2021)</b><br>

- New safe shutdown method to preserve saves and configuration files.  Thank you to DaMikki for the solution.
- Added epicnoir theme to optional themes, thank you to TetrisSQC for the work.
- Added 'v1.7' to Settings background image to indicate Add-On Pack version.

For users coming from v1.6 of this pack, you need to perform the following steps to implement safe shutdown:

- Move the 'softshutdown' folder in this package to the 'emus' directory of your SD card.
- Move the emulators/99 shutdown (System) file from this pack to the sections/emulators directory of your SD card
- Move the wallpapers/poweroff.png file from this pack to the skins/Default/wallpapers directory of your SD card

Users coming from v1.5 or earlier, be sure to also perform the steps indicated on the v1.6 update.

<b>v1.6 (25JAN2021)</b><br>
This update fixes a number of issues related to aspect ratio and Dreamcast buttons.

- If you are coming straight over from stock settings, follow the instructions in the ReadMe file.
- If you'd like, you can also download the fresh image file, unzip, and drag into a new SD card that is FAT32 formatted.

If you are running a previous version of this add-on pack (like v1.5), you only need to do two steps:

1. Replace the cfg files found in the emus/retro/ folder on your SD card with the cfg files found in the retro folder in this package.
2. Replace the contents of the sections/emulators folder with the contents of the emulators folder found in this package.

Uopdates from previous release:<br>

- Fixed aspect ratios across the board. They aren't perfect, but they will look less stretched. Aspect ratios are not logical with this device, so I had to make the best guess based on how it looked to my eye.
- Added shoulder buttons to Dreamcast (L1 and R1 function as triggers).
- Changed retroarch-core-options.cfg to a read-only file in hopes that it won't get overwritten. This mean that Dreamcast should remain at 640x480 resolution and Game Boy should keep a green shader coloring. If either of these features disappear, download and paste this code in the emus/retro/retroarch-core-options.cfg file on your SD card. https://github.com/retrogamecorps/s30-add-on-pack/blob/main/retro/retroarch-core-options.cfg
- Added tweak to savestate_auto_index in config files to allow more than one save state per core.
- Steamlined retroarch.cfg files to serve specific purposes, mostly concerning aspect ratio.
1. retroarch.cfg = full-screen aspect ratio
2. retroarch-arcade.cfg = should be an automatically adjusting ratio based on game
3. retroarch-dc.cfg = adds shoulder buttons to the Dreamcast emulator
4. retroarch-gb.cfg = handheld aspect ratio (somewhere between 1:1 and 8:7)
5. retroarch-gba.cfg = full-screen aspect ratio with no smoothing for GBA, WSC, and Lynx
6. retroarch-nes.cfg = console aspect ratio (somewhere between 4:3 and 3:2)

<b>v1.5 (15JAN2021)</b>
- added alternative themes from the community
- fixed save games/states persistence issue
- fixed naming of sections/emulators

<b>v1.4 (11JAN2021)</b>
- reverted PS1 emulator to stock emulator to accommodate L2/R2 function
- added Commodore 64, ZX Spectrum, Tic-80, and Atari 2600

<b>v1.3 (08JAN2021)</b>
- added Atari Lynx and Virtual Boy

<b>v1.2 (08JAN2021)</b>
- fixed Arcade aspect ratio
- updated RetroArch core settings
- fullscreen fix for most emulators

<b>v1.1 (05JAN2021)</b>
- added RetroArch cores, game & watch, and game gear

<b>v1.0 (24DEC2020)</b>
- release
