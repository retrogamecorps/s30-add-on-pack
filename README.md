# PocketGo S30 Add-On Pack 
by onionsaregross (http://retrogamecorps.com)

## Introduction

This add-on pack will create new wallpapers for all of your systems, increase the number of systems available on your device, and organize the menu into a logical hierarchy: Nintendo systems (by order of release and consoles before handhelds), Sega systems, Sony systems, NEC systems, then outlying handhelds (Neo Geo Pocket, Wonderswan).

This pack also includes updated emulators (RetroArch cores) with pre-configured screen settings and ideal aspect ratios for emulation accuracy.

This add-on pack assumes that you have already backed up the stock SD card that came with your device.  The user accepts all responsibility for exploded microSD cards or S30 devices.

To download, click on the green "Code" button at the top-right of this page, and then select "Download Zip".

PocketGo S30 Starter Guide, which includes accepted game file types and a video walkthrough: https://retrogamecorps.com/2021/01/08/pocketgo-s30-starter-guide/

If you would rather download an fresh copy of the original SD card contents (+ the v1.3 add-on pack pre-loaded), and paste into a brand new SD card, you can find it here.  Note that you must format the new card to FAT32, and this does not include any ROM or BIOS files, so you will need to add those yourself. https://retrogamecorps.files.wordpress.com/2021/01/s30_backup_1_4-1.zip

## Credit

Default wallpaper images based on ckau-book Batocera theme by CkauNui
https://github.com/CkauNui/ckau-book<br>
Futura theme by Baguette Crusader<br>
Futura (alternate) theme by victoriemini<br>
ckau theme by Cartman

## Instructions

1. Insert your S30 microSD card into your computer.
2. UPDATE WALLPAPERS:  On your SD card, go to the skins/Default/wallpapers folder, and remove those files.  You can store them on your computer for safe-keeping if you'd like.  Open the 'wallpapers' folder from this pack, and place the png files in the skins/Default/wallpapers folder.  If you'd like, you'll find subfolders with other themes (Futura, ckau, etc.), and you can use those instead.  Some of these alternate themes have their own font; if you find a font.ttf file in the subfolder, move it to the skins/Default/ folder and replace the font.ttf file that's already in there.
3. UPDATE LAUNCH FILES:  On your SD card, go to the sections/emulators folder, and remove those files.  You can store them on your computer for safe-keeping if you'd like.  Open the 'emulators' folder from this pack, and place the files in the sections/emulators folder.
4. UPDATE EMULATORS.  On your SD card, go to the 'emus' folder, and remove the 'retro' folder.  You can store it on your computer for safe-keeping if you'd like.  Place the new 'retro' folder from this pack into the emus folder.  Then, unzip the file named "unzip_and_add_to_retro_folder.zip", and add its contents to the new retro folder on your SD card.
5. VERIFY ROMS FOLDERS: On your SD card, go to the 'roms' folder and change the folder names so they are as follows (minus the information in the parenthesis).  Also, delete the folder named "npg", this is an unecessary folder.  You will need to create new folders for some systems, and rename some others:

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

6. ADD BIOS FILES:  Ensure you have the following BIOS files in the appropriate locations on the SD card.  These BIOS files are not part of the add-on pack, you will need to find them yourself.

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

- I recommend *not* powering off the system while mid-game.  Tap the power button and select "Close Content" to go to the main menu, then power down.  If you power down during a game, the retroarch-core-options.cfg file will get overwritten, and you will lose some functionality (green colorization in GB, high resolution in Dreamcast).  If this happens to you, paste this code in the emus/retro/retroarch-core-options.cfg file on your SD card: https://github.com/retrogamecorps/s30-add-on-pack/blob/main/retro/retroarch-core-options.cfg 
- L2 and R2 are not assigned in RetroArch, and I cannot figure out how to assign them since we're locked out of the RetroArch menu.  For this reason, I am still using the PS1 emulator that shipped with the S30 device.
- In-game saves with GBA Pokemon (and perhaps some other GBA games) appear to be erased upon powering off the device.
- If you are having problems saving games, eject your SD card and place it in a Windows PC.  You will be prompted to "scan and repair" the disk; follow those prompts and then re-insert the SD card into your PocketGo S30.  This may clear those write errors on your card.
- If you are interested in adding your own RetroArch cores to this device, they are running cores from this repo: https://github.com/bite-your-idols/Gamestarter/tree/master/packages/libretro-cores-RPi

## Changelog

v1.5 (14JAN2021)
- added alternative themes from the community

v1.4 (11JAN2021)
- reverted PS1 emulator to stock emulator to accommodate L2/R2 function
- added Commodore 64, ZX Spectrum, Tic-80, and Atari 2600

v1.3 (08JAN2021)
- added Atari Lynx and Virtual Boy

v1.2 (08JAN2021)
- fixed Arcade aspect ratio
- updated RetroArch core settings
- fullscreen fix for most emulators

v1.1 (05JAN2021)
- added RetroArch cores, game & watch, and game gear

v1.0 (24DEC2020)
- release
