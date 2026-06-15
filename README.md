# Hidden and Dangerous Remaster

## What's that

H&D Remaster is a version of H&D Deluxe which is mixed with H&D Original files and others improvement made by the community and me. The aim of this version is to create a fluid game experience playable on modern OS and hardware using moderns drivers without any bugs.

## Improvement list

**binary improvements (thanks to Daemonsteufel):**

- patched enemies fast fire bug

- added save in addons

- added save in multiplayer

- removed advertising splash screen

- removed ad screen for HD2

- FFF weapons can be chose in addons

- AI can't shot friend by error

- friend AI don't change weapon without order

- friend AI don't chase enemy without order

- weapons centered in fps view

- doors can be closed again

- **cheat-codes** **newlife** and **fullhands** usable in multiplayer

- **nightvision** cheat-code

- wide screen correction

- added a third enemy group civil running away when there is explosion

- some game editor additional functions

- new briefing system

- a lot more mission-editing features to improve the game-engine

- inventory glitch fixed

- fix for human stuck in the ground / in crouch

- a function to prevent AI seeing through foliage

- configurable grenade explosions

**General improvement**:

- uncensored the game

- uncensored the game menus

- patched the multiplayer on modern windows (applied [HDDMultiplayerPatch](https://github.com/WJLiddy/HDDMultiplayerPatch))

- Original opus musics

- added gun holes

- added body gibs

- changed knife animations

- added an auto-updater which ask for an update

- changed the game icon to the original

- Added the right 3ds max plugins files in the game directory

- removed dead body optimization in Germany6 due to the performances of new computers

- Added [DXVK](https://github.com/doitsujin/dxvk) which permit the game to be played on modern graphic cards with Vulkan

- added individual allied faces from H&D Original

- reworked the setup to made the game standalone of the original game

- added a launcher which allow advanced functionalities like language change, auto-login and auto-host

## Download

1. Download .7z archive [here](https://mega.nz/file/ID0XBCpK#AAs6fzo9pHT7QIlp5tvl6390yXdHA2JbdWVqWRIKWbE)

### Antivirus troubleshooting

The installer of the remaster was created using bat2exe converter, so game.exe is not signed by Microsoft and it can cause some mistakes. If you won't bypass your antivirus, just launch the game by hde.exe (please keep in mind that this method don't allow you to have custom languages or custom user auto-login)

## Install on an existing Hidden and Dangerous Deluxe installation

Download the archive in the download section, extract it (if asked the extracted files must replace the existing) into your h&d deluxe directory (for me: C:\\Program Files (x86)\\Take2\\Hidden and Dangerous Deluxe). This must be extracted next to the bin and data folders.

After this, you can launch the game with game.exe and not \\bin\\hde.exe, I let you create the shortcut.

Please consider that this installation procedure may cause some conflicts because it's installed in an admin-righted folder but the program is launch with user permissions.

## External Settings (language & username)

The files in \\bin\\startconfig\\ are configuration files which stores the language settings and the username.

### Language

Here a list of supported language (just replace English by another languages in this list):

- English

- German

- French

- Spanish

- Italian

### Username

The username file set the username will be used to launch the game and it also set the multiplayer username

### DoAutoHost

Settings not really useful, may cause some bugs. You can use it to launch the game directly in host mode. Replace it by another text than "No" and it will be taken as a "Yes"

# For the modders

## 3DS Max 5.0 Retired version for free

- 5.0 run on 64 bits Windows (XP/7/8/10/11)

You can have this version [here](https://mega.nz/file/oDMg1TYY#dzxXwq7gDOJtkdwIoA5CUibJY3qFBqoOiyD0ckIrnbg), please, follow the instructions in the README.txt file.

→ if at launch 3DS Max give you an error of license, don’t panic ! Go to the license selector of 3DS Max (can be found in the start menu) and select network license again.

## 3DS Max i3d plugins

If you seek for the original i3d plugins written by the developers, I give the 3DS Max 3.0 and the 3DS Max 5.0 versions in the file of HD-Remaster in the \\editor\\plugins folder

Please, do not forget to add the DLL present in the \\editor\\plugins\\DLL folder next to the 3DS Max .exe


# Credits

[Michal Bačík](https://github.com/mice777), original developper of the game engine

NilsZ/Daemonsteufel for [his improvement](https://www.moddb.com/mods/hidden-and-dangerous-extended/downloads/binary-patch-052023-coop-saving) of the game engine

[HDDMultiplayerPatch](https://github.com/WJLiddy/HDDMultiplayerPatch)

[DXVK](https://github.com/doitsujin/dxvk)
