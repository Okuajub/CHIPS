#--
# IMPORTANT
#--
Please note: The included character illustrations are not intended for redistribution and should be replaced with your own images. They are for example purposes only.

#-- Introduction
Hello! This is the CHIPS Kawari Template, version '1.0.0'.

If you are new to Ghosts, welcome!
Ghosts are desktop agents, originally aimed at keeping the user company by conversing with a secondary character or the user themself. 
Ghosts are programmed in many languages, including Kawari.
Kawari is a programming language made for Ghosts, distinguished by it's unique "entry" system. This is what you'll be writing in, as it is the language used in this template.
A Sakura is the primary character of the ghost, while the secondary character is the Kero. The Sakura for this Ghost is "Sentinel" and the Kero is "Chip".
Surfaces are a ghost's sprites/illustrations that can change when given cues. The illustrations packaged together are known as a Shell. 
A Ghost can have multiple Shells to be swapped at any time.
A baseware is the program which runs Ghosts, as Ghosts can't run on their own. The most popular baseware is SSP.

There are multiple Ghost templates available, but CHIPS is built with the specific purpose of making writing easy.
CHIPS should give you a good starting place to develop your Ghost, as I have done my best to make the process easy and straightforward. 
If you are a more advanced user, CHIPS also comes packaged with many pre-written and example scripts, which can be found in the "Optional Files" folder in the initial .zip.

#-- Setup
Before we start editing any files, there are a couple things we need to do.
CHIPS is designed to be run on SSP. SSP has a 'Preferences' menu which you'll want to open up. 
When you first open CHIPS, it'll ask you if you want to open the preferences menu, which you can say yes to if you'd like. 
Otherwise, right click any Ghost's main character and navigate to 'Options > Preferences'.
In the first section of the preferences menu, 'General', you should tick the last box labeled 'Enable functions for developers. (Caution!)'.
This will allow you to access the Developer Palette from CHIPS' right-click menu under 'Utilities'. You can also open it up with the shortcut 'ctrl-shift-d'.

With the Dev. Palette open, you now have access to some handy tools. My most commonly used are:
Script Input - Lets you test dialogue without having to trigger it inside the Ghost.
Surface Test - Lets you preview your Ghost's appearance, and see what certain sprites corrospond to.
Reload... - Allows you to reload parts of the Ghost without rebooting the whole program.
Open... - The top three options open the file explorer to your Ghost's files.

You can leave this menu alone for now, but I wanted to make you aware of it. It makes testing your Ghost much easier!

#-- Next Steps
To get started, open up the file 'ghost-aitalk.kis' which is inside the 'ghost\master' folder. That's two folders deeper than where this readme is.
If you want to start with artwork, as I understand a lot of people interested in Ghosts come in as artists, you can also start in the 'shell\master' folder.

#-- File reference

readme.txt - A text file that will pop up when your Ghost is installed. Make sure to fill it out!

developer_options.txt- This file makes packing up your Ghost for distribution easier. But if you're having issues with it, go ahead and delete it. All it does is tell SSP to ignore your save data when packing up your Ghost. (OPTIONAL)

thumbnail.png - An image file that will show up when your Ghost's name is hovered over in the Call/Change Ghost menu option. Very helpful for distinguishing Ghosts when you have a lot of them. (OPTIONAL)

thumbnail.pna - An image file that informs the transparency of 'thumbnail.png'. If you  want transparency in your thumbnail, you'll need to make a '.pna' file to go with it! (OPTIONAL)

profile\dict-bakdata.txt and profile\dict-savedata.txt - If you see these in your profile folder, they're your Ghost's save data! You can check to see if data you add is getting saved properly here.

descript.txt - This describes the very basics of your Ghost to your baseware. You should fill it out because it contains important information, like credit to the author (you!), the name of your Ghost, and what balloon they use (if any). If you're not sure what you can replace without breaking anything, just fill out the 'name' sections, replace my name (Okuajub) with yours, and delete the website link.

ghost-*.kis - Any file prefixed with 'ghost-' is intended to be filled out for your Ghost.

dict-*.kis  - The middleware files intended only for developers. If you're primarily a writer and not a coder, you can safely ignore these files.

icon.ico - The icon for your ghost that shows up in the task tray. Needs to be an '.ico' file. (OPTIONAL)

kawari.log - A log file automatically created when your Ghost boots. If you're having issues with something, 'kawari.log' will log any errors and all the events that were sent to the Ghost.

kawarirc.kis - A file which defines which files in this folder Kawari should pay attention to. 'kawarirc.kis' is always read first.

kosui.exe - A debugging program normally bundled with Kawari's source code. It's usage has been detailed in the Kawari documentation.

shiori.dll - Kawari itself! This file is what interprets all of the code you write in Kawari. So don't delete it unless you know what you're doing!