## Trimui Smart Pro VCMI(HOMM3) portmaster instructions

This repo was created to help setup HOMM3 using Portmaster on the Trimui Smart pro.
I have grouped information and steps for myself and others to help experience this retro classic on the go!

I was not involved in the development of VCMI for portmaster.

### Sources of information

Reddit post:
https://www.reddit.com/r/trimui/comments/1ewraav/heroes_of_might_and_magic_3/

Portmaster vcmi:
https://portmaster.games/detail.html?name=vcmi

GOG Heroes of Might and magic 3 complete edition:
https://www.gog.com/en/game/heroes_of_might_and_magic_3_complete_edition

Kloptops github:
https://github.com/kloptops/Portmaster-misc

## Before you start

Before you start check the following:
- [ ] Purchase a license at GOG for HOMM3 complete editon
- [ ] 3GB of free storage on SDcard
- [ ] (Optional but highly recommended) Have Crossmix for Trimui installed
- [ ] Have portmaster up to date (Start portmaster and allow updates)

<!-- GETTING STARTED -->
## Getting started

Follow the below steps 1 by 1 and enjoy Heroes of Might and Magic 3 complete edition on the Trimui Smart Pro.

### Step 1) Install VCMI
Start portmaster and install VCMI by kloptops. Once done, exit portmaster and power off your Trimui Smart Pro.<br/>
No need to try and starting VCMI yet, we need to transfer the game files first! 

### Step 2) Obtain the GOG installer files
Start your GOG desktop client.<br/>
Within the client, go to "Owned Games" > Heroes of Might and Magic 3 complete edition<br/>
On the game page at the very top press "Extras"<br/>
In the new shown list scroll down to the section labeled "OFFLINE BACKUP INSTALLERS"<br/>
Press the downward pointing errow at the right of the screen next to "Heroes of Might and Magic 3:Complete". This download is +- 960MB<br/>
Go to the 'Downloads' section on the left of screen in the GOG Launcher and wait for the download to finish<br/>
Press the 'Folder Icon' and your file explorer will show you the newly downloaded files. Keep this window open for Step 3<br/>

### Step 3) Transfer the needed files
There are multiple ways to transfer the file, but for everyone unfamiliar with SFTP, SCP and other transfer tools, the following will get you there as well:<br/>
Insert your Trimui SDcard into your pc<br/>
From the file explorer window in step 2, select and copy the files:<br/>
- setup_heroes_of_might_and_magic_3_complete_4.0_(3.2)_gog_0.1-(xxxxx).exe
- setup_heroes_of_might_and_magic_3_complete_4.0_(3.2)_gog_0.1_(77075)-1.bin
<!-- end of the list -->
<br/>

Copy these files to:<br/>
` 'Root SDcard'/Data/ports/vcmi/ `<br/>
Once done, safely eject the sdcard and insert it back into you Trimui

### Step 4) Emucleaner (optional)
Whenever adding or installing games on the Trimui, it's recommended to run 'EmuCleaner'.
You can find it in the 'Apps' section.

### Step 5) First time starting
Navigate to the Emulators/Ports section under emulators,<br/>
Now start VCMI and wait, as the initial installation is now taking place.<br/>
**!! This process can take a few minutes, be patient !!**<br/>
If all gone well, you will now be presented with the main menu of HOMM3, hooray!!<br/>
But you will soon notice the controls are wrong...<br/>
Keep Left shoulder button pressed and use the left analog stick to move the cursor to 'Exit'<br/>
While pressing the Left shoulder button, press the Y button on the D-pad to exit the game.<br/>

### Step 6) Transfer shortcutConfig
Fear not, after following the above steps, the final step will be to copy over a new shortcut config file.<br/>
Power down again your Trimui<br/>
Insert the SDcard into your pc<br/>
Download the file "shortcutsConfig.json" From the root of this repository<br/>
Copy this file to:<br/>
` 'Root SDcard'/Data/ports/vcmi/config/ `<br/>
Overwrite when asked!<br/>
Safely remove the SDcard from your pc and insert it again.<br/>
Start VCMI again...

### Step 7) Start + Select 
Whenever the game is started you will have to press **'start'** + **'select'** at the same time once to get the button behaviour correctly.
It seems to be a toggle for button mapping behaviour although I could not find the details about it.
<br/>
Enjoy and credits to everyone at portmaster for making this classic possible on the Trimui
