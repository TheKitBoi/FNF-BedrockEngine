# Friday Night Funkin' - Bedrock Engine!
a fork of Psych Engine which adds a bunch of features from Pull Requests around the Main Branch, and even other forks!
Credits:
* CerBor - Difficulty Drop Down on Chart Menu - https://github.com/ShadowMario/FNF-PsychEngine/pull/2896
* HiroMizuki - Pixel Note Splashes - https://github.com/ShadowMario/FNF-PsychEngine/pull/1792
* i-winxd - Kade Engine (Complex) Accuracy - https://github.com/ShadowMario/FNF-PsychEngine/discussions/2917
* lemz1 - Play as Opponent - https://github.com/ShadowMario/FNF-PsychEngine/pull/2770
* l1ttleO - Made ProjectFNF 2.X, Original Hit Sound Code, Miss Sounds Toggle - https://github.com/l1ttleO/ProjectFNF
* magnumsrtisswag - Stage Editor, Credits Warning - https://github.com/ShadowMario/FNF-PsychEngine/pull/3502
* Starmapo - Time Signatures - https://github.com/ShadowMario/FNF-PsychEngine/pull/3428
* Stilic - Freeplay Bump, Max Optimization, Menu Animations, Automatic Controller Detection - https://github.com/ShadowMario/FNF-PsychEngine/pull/1809
* Verwex - made Mic'd Up Engine, Winning Icons - https://github.com/Verwex/Funkin-Mic-d-Up-SC
* XtraXD1 - Show/Hide Weeks temporally + Getting/Setting on Source Code - https://github.com/ShadowMario/FNF-PsychEngine/pull/3192
* Yoshubs - made Forever Engine, Main Inspiration - https://github.com/Yoshubs/Forever-Engine-Legacy

# Current Plans

* Updating this entire file because it's outdated at the moment lol

# Compiling

> ### Dependencies

- Git
- Haxel (LATEST VERSION, STOP USING 4.1.5!!!!)
- VS Community (windows only!)

> ### OPTIONAL Dependencies 

- Visual Studio Code (for modifying the code itself)

> ### Recommended VS Code Extensions

- Lime
- Bracket Pair Colorizer 2
- HXCPP Debugger
- Tabline

# Downloads

### Git 
for Windows and Mac: https://git-scm.com/downloads
* **after installing, open a Command Prompt or Terminal, and type in:**
haxelib setup

- Linux (Ubuntu and Debian based Distros): 

* sudo apt-get update
* sudo apt-get install git -y

Linux (Arch based Distros): 

* sudo pacman -Sy git --noconfirm

### Haxe

- for Windows and Mac: https://haxe.org/download/

- Linux (Ubuntu and Debian based distros):

* sudo add-apt-repository ppa:haxe/releases -y
* sudo apt-get update
* sudo apt-get install haxe -y
* mkdir ~/haxelib && haxelib setup ~/haxelib

- Linux (Arch based distros)

* sudo pacman -Sy haxe --noconfirm

### VS Community
https://my.visualstudio.com/Downloads?q=visual%20studio%202017&wt.mc_id=o~msft~vscom~older-downloads

> ### VS Community Setup

once you download and install VS Community, on the "Workloads" tab, select "Desktop Development with C++"

near the "Install" button, there's a Drop-Down menu, click on it, Select "Download first, then Install"

now wait until it finishes, it is recommended to reboot your PC once it finishes, but it's not needed at all

# Terminal Setup & Compiling Game

- on Windows: press "Windows+R" and type in "cmd", if you don't like cmd, or you just use something different, open that program instead
cmd is usually faster, that's why I'm recommending it!

- on some Linux Distros: Press "CTRL+ALT+T" and a Terminal window should open -- although, if you are on linux, you probably know that already
- on other Linux Distros: Usually in your applications menu, or press Ctrl+Alt+2-6, Ctrl+Alt+7 usually get you back to your desktop

- on Mac: Press cmd+space and type "Terminal" into spotlight or open Launchpad and look for Terminal
type in these commands

* haxelib git discord_rpc https://github.com/Aidan63/linc_discord-rpc
* haxelib git linc_luajit https://github.com/nebulazorua/linc_luajit.git
* haxelib git hxvm-luajit https://github.com/nebulazorua/hxvm-luajit
* haxelib git faxe https://github.com/uhrobots/faxe
* haxelib git polymod https://github.com/MasterEric/polymod.git
* haxelib git extension-webm https://github.com/KadeDev/extension-webm
* haxelib install lime 7.9.0
* haxelib install openfl
* haxelib install flixel
* haxelib install flixel-tools
* haxelib install flixel-ui
* haxelib install hscript
* haxelib install flixel-addons
* haxelib install actuate
* haxelib run lime setup
* haxelib run lime setup flixel
* haxelib run flixel-tools setup 

***read carefully*** when it prompts for you to do anything (like: setup the lime command, setup flixel tools, etc)

once it's done, do this command to compile the game

### Windows

lime test windows

### Linux

lime test linux

### Mac
lime test mac

### for Debug Builds

add a "-debug" flag at the end of "lime test <platform>"

### VS Code Installation
- Windows and Mac: https://code.visualstudio.com/Download

Linux (Ubuntu and Debian based distros):
* sudo apt install software-properties-common apt-transport-https wget
* wget -q https://packages.microsoft.com/keys/microsoft.asc -O- | sudo apt-key add -
* sudo add-apt-repository "deb [arch=amd64] https://packages.microsoft.com/repos/vscode stable main"
* sudo apt install code

Linux (Arch based distros):
* sudo pacman -Sy code

In case you don't want your mod to be able to run .lua scripts, delete the "LUA_ALLOWED" line on Project.xml

# Current Features

## All Psych Engine Features!
Being a Psych Engine fork has it's Perks
* https://github.com/ShadowMario/FNF-PsychEngine

## Menu Animations and Freeplay Bump

https://user-images.githubusercontent.com/45212377/147199518-663ddd81-288a-4228-8d75-6fa6bccbc378.mp4

## Hit Sounds

https://user-images.githubusercontent.com/45212377/147199769-1146c459-1448-4b33-b0c4-63319513c49e.mp4

## More Perfomance Options
some more Performance Options for the game to run smoothly on older hardware

* Hide Girlfriend

it's in the name!
![image](https://user-images.githubusercontent.com/45212377/150618541-b4fc137a-723a-400c-b0a3-0763a547c21a.png)

![image](https://user-images.githubusercontent.com/45212377/150618560-6bba9889-afc0-4606-bd44-252c7467a2b2.png)

this also comes with special dialogue for Week 6!

![image](https://user-images.githubusercontent.com/45212377/150618678-b245789d-3700-41ec-a258-3d6e63965953.png)

* Simple Main Menu

![image](https://user-images.githubusercontent.com/45212377/150618723-5585b1d0-43e5-4a2d-817f-537f0cc839e1.png)

this option makes it so the menu doesn't use Image Assets, but rather, make it use only text entries, decreasing loading times

![image](https://user-images.githubusercontent.com/45212377/150618902-cf012187-63a4-489b-82aa-9fb7e459c6d9.png)

* Max Optimization

![image](https://user-images.githubusercontent.com/45212377/150618767-e2e4524c-669b-480c-85ff-b095ef106623.png)

this disables everything related to backgrounds and characters, leaving only the HUD and Note Splashes!

![image](https://user-images.githubusercontent.com/45212377/150618792-8be1b189-5603-4743-b23a-0b07df877576.png)

## Letter Grading System!

![image](https://user-images.githubusercontent.com/45212377/147283059-d8555266-2e55-4e5d-9979-dd316c7004e7.png)

* S+  100% Accuracy.
* S   99.9% Accuracy.
* AAA 99.1% Accuracy.
* AA 	98.6% Accuracy.
* B   80% Accuracy.
* C   70% Accuracy.
* D   40% Accuracy or below.

## Opponent Mode

https://user-images.githubusercontent.com/45212377/147809658-3ef98953-4329-4c10-ac76-eec3d52ccbd7.mp4

can be enabled on the Gameplay Changers menu

## Pixel Note Splashes

https://user-images.githubusercontent.com/45212377/147283320-2cad2193-d1e9-42ee-b8d9-3ab4a267112b.mp4

## Judgement Skins
You can now Change your Judgements' Appearance with the new UI Skins

![image](https://user-images.githubusercontent.com/45212377/150618407-b18087c6-96d1-4968-9b4f-c4e3e20ab859.png)
![image](https://user-images.githubusercontent.com/45212377/150618450-f25e5a73-2b2d-4304-ace9-5ae346a65c37.png)

right now this feature is hardcoded, but I plan to make it softcoded soon

## Winning Icons

![s](https://user-images.githubusercontent.com/45212377/150619108-936004be-898a-49d3-b6b3-da6efa5d115a.png)

## and more!
I will keep updating this fork as much as possible for it to be in sync with the main repository, and adding more features to it in the future!

# Future Plans
* Softcoded Judgement Skins
* Noteskins on Options Menu
* Separated Noteskins for each Player (already possible with lua so...)
* Fix all current issues with Opponent Mode
