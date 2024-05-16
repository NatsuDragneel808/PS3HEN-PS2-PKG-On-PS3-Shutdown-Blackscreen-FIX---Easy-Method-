# PS3HEN-PS2-PKG-On-PS3-Shutdown-Blackscreen-FIX---Easy-Method-

As you all know, for quite a few years there has been a constant issue and debate on what's causing the ps3 to shut down after loading a ps2 game and how to fix it. Some say adjust config files in hdd0, some say to covert it and play on multi-man or webman. Executive squeel's about compatibility issues or that it's impossible etc. Some blame Hen for being bugged or incomplete. Whatever the case may be, I searched up tutorials, forums & videos for hours to no avail. This post (I consider) more of a workaround than a fix. No more shutdowns, black screens, or terrible emulation. But hopefully it will help some, if not all of you with this issue. Assuming you're already modded, just follow these steps -->

(REQ)
- PS2CM Store (Github) https://github.com/PS2ClassicsVault/ps2classicsvault.github.io/releases/tag/v1.34
- PSN Patch 2017.02/B (Brewology) https://store.brewology.com/ahomebrew.php?brewid=244
- Alt PSN Account (PSN) https://www.playstation.com/en-us/playstation-network/
- Filezilla FTP Client (FileZilla) https://filezilla-project.org/
- FAT32 USB (Rufus) https://rufus.ie/en/
- Unofficial multiMAN v04.84 HEN (Brewology) https://store.brewology.com/multiman.php

With downloads out of the way, I'm just trying my best to cover the basics, you should already have multiMAN installed when you first modded your console. I can make an update later with more precise instructions if it's not self-explanatory enough;

(USB Method)
- Format USB Drive using rufus. Nonebootable/MBR/FAT32
- Copy PS2CM & PSN Patch to USB
- Plugin to ps3
- On ps3 menu --> Game --> Package Manager --> Install Package Files --> Standard --> select pkg & install

(Filezilla Method) - Copy PS2CM Store & PSN Patch by Filezilla
- You'll need to load into multi-man and connect your filezilla client.
- Enter your PS3 IP address and port:21. "You can find your IP under system information on your PS3"
- Bottom right navigate to dev_hdd0 --> packages --> drag and drop pkg files
- Close connection
- On ps3 menu --> game --> package manager --> install package files --> ps3 system storage --> select pkg's and install

(PS2CM)
- Once you open the first time you'll probably be presented with an error about config files or a blank UI. If not, cool. Continue.
- Hit triangle, scroll down to refresh, and wait for it to update
- Locate your desired PS2 game (Normally will say (PS2CM) next to it. PS 1 games say PSX and PS3 games don't have anything next to them.
- Download your game
- Exit PS2CM when dl completed

(PSN_Patch) "You do not need to install rap+edit, unlock classics, or patch the games for this method"
- Game --> the PSN patch and hit x in the menu. Your console will refresh.
- After refresh, go login to your psn alt account. If you haven't made a new email & psn alt account, do that now.
- After signing in, navigate to your account --> system activation --> game
- navigate your menu to network --> Hybrid firmware tools --> restart --> full restart

(Finalize)
- Enable hen
- Navigate back to psn patch
- Hit x to activate in the menu and wait for refresh
- Open PS2 game (game update is optional)
- The controller will disconnect & press the home button to reconnect
- Enjoy!

Note: Do not press the home button in the game unless you're done playing. Doing so will result in the same crash on the initial without spoof. Spoofing the OFW is the only way to workaround without all the initial extra BS. No multiMan, nowebMAN, no extra conversions to run. You can run the game straight from the menu but remember that to use anything else, the psn patch is only for when you're playing PS3 games online, and booting a ps2 pkg. Other applications will not work at this time. You will need to run a PSN patch every time you boot a PS2 game just like when you're ready to play a PS3 game online. As far as I'm aware, something dealing with the ofw is the cause of the crash/black screens. Idk why this workaround works, it just does. You're welcome.


(My_Specs)
Model: CECHK01
FW: HFW 4.91.1
GLM: XMB Menu
