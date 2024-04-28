#--
# IMPORTANT
#--
Please note: The included character illustrations are not intended for redistribution and should be replaced with your own images. They are for example purposes only.

#-- Introduction
Hello! This is the CHIPS Kawari Template, version '1.0.1'.

If you are new to Ghosts, welcome!
Ghosts are desktop agents, originally aimed at keeping the user company by conversing with a secondary character or the user themself. Ghosts speak in speech bubbles, also known as Balloons.
Ghosts are programmed in many programming languages, including Kawari.
Kawari is a programming language made for Ghosts, distinguished by it's unique "entry" system. Kawari is what you'll be writing in, as it is the language used in this template.
A Sakura is the primary character of the ghost, while the secondary character is the Kero. The Sakura for this Ghost is "Sentinel" and the Kero is "Chip".
Surfaces are a ghost's sprites/illustrations that can change when given cues. The illustrations packaged together are known as a Shell. 
A Ghost can have multiple Shells to be swapped at any time.
A baseware is the program which runs Ghosts, as Ghosts can't run on their own. The most popular baseware is SSP.

There are multiple Ghost templates available, but CHIPS is built with the specific purpose of making writing easy.
CHIPS should give you a good starting place to develop your Ghost, as I have done my best to make the process easy and straightforward. 
If you are a more advanced user, CHIPS also comes packaged with many pre-written and example scripts, which can be found in the "Optional Files" folder in the initial .zip.

#-- Setup
Before we start editing any files, there are a couple things I'd like to touch on.

You will most likely want to use a text editor designed for programming. The default text editor of most systems is useable, but there are conveniences in having a dedicated code editor.
Visual Studio Code is a user friendly text editor developed by Microsoft and the most popular choice of programmers. It comes prebundled with highlighting for multiple languages and offers many extensions. It also has a Kawari extension.
Notepad++ is an open source text editor which comes prebundled with highlighting for multiple languages. It's also quite popular and is more lightweight than VS Code.
Both of these are perfectly good options and which editor you choose (if any) depends on what is most comfortable for you.

We also need to enable Developer Mode inside of SSP. SSP has a 'Preferences' menu which you'll want to open up. 
When you first open CHIPS, it'll ask you if you want to open the preferences menu, which you can say yes to if you'd like. 
Otherwise, right click any Ghost's main character and navigate to 'Options > Preferences'.
In the first section of the preferences menu, 'General', you should tick the last box labeled 'Enable functions for developers. (Caution!)'.
This will allow you to access the Developer Palette from CHIPS' right-click menu under 'Utilities'. You can also open it up with the shortcut 'ctrl-shift-d'.

With the Dev. Palette open, you now have access to some handy tools. My most commonly used are:
Script Input - Lets you test dialogue without having to trigger it inside the Ghost.
Surface Test - Lets you preview your Ghost's appearance, and see what certain surfaces and animations corrospond to.

Reload... - Allows you to reload the Ghost (partially or fully) without rebooting SSP.
Reload > Balloon - Reloads the balloon your Ghost is using.
Reload > SHIORI - Reloads the Ghost's code scripts.
Reload > Ghost - Reloads the Ghost as a whole.
Reload > Shell - Reloads the Ghost's surfaces.

Open... - The top three options open the file explorer to your Ghost's files.
Open > Balloon - Opens the folder for the Ghost's currently selected balloon.
Open > Ghost - Opens the ghost\master folder, where the scripts are held.
Open > Shell - Opens the folder of the currently selected shell.

You can leave this menu alone for now, but I wanted to make you aware of it. It makes testing your Ghost much easier!

#-- Next Steps
To get started, open up the file 'ghost-aitalk.kis' which is inside the 'ghost\master' folder. That's two folders deeper than where this readme is.
If you want to start with artwork, you can also start in the 'shell\master' folder.

#-- File reference

readme.txt - A text file that will pop up when your Ghost is installed. Make sure to fill it out!

developer_options.txt- This file makes packing up your Ghost for distribution easier. But if you're having issues with it, go ahead and delete it. All it does is tell SSP to ignore your save data when packing up your Ghost. (OPTIONAL)

thumbnail.png - An image file that will show up when your Ghost's name is hovered over in the Call/Change Ghost menu option. Very helpful for distinguishing Ghosts when you have a lot of them. (OPTIONAL)

thumbnail.pna - An image file which provides the alpha (transparency) channel of 'thumbnail.png'. If you want transparency in your thumbnail, you'll need to make a .pna file to go with it! (OPTIONAL)

profile\dict-bakdata.txt and profile\dict-savedata.txt - If you see these in your profile folder, they're your Ghost's save data! You can check to see if data you add is getting saved properly here.

descript.txt - This describes the very basics of your Ghost to your baseware. You should fill it out because it contains important information, like credit to the author (you!), the name of your Ghost, and what balloon they use (if any). If you're not sure what you can replace without breaking anything, just fill out the 'name' sections. Replace the name 'dummy' with yours, and delete the website link.

ghost-*.kis - Any file prefixed with 'ghost-' is intended to be filled out for your Ghost.

dict-*.kis  - The middleware files intended only for developers. If you're primarily a writer and not a coder, you can safely ignore these files.

icon.ico - The icon for your ghost that shows up in the task tray. Needs to be an '.ico' file. (OPTIONAL)

kawari.log - A log file automatically created when your Ghost boots. If you're having issues with something, 'kawari.log' will log any errors and all the events that were sent to the Ghost.

kawarirc.kis - A file which defines which files in this folder Kawari should pay attention to. 'kawarirc.kis' is always read first.

kosui.exe - A debugging program normally bundled with Kawari's source code. It's usage has been detailed in the Kawari documentation.

shiori.dll - Kawari itself! This file is what interprets all of the code you write in Kawari. So don't delete it unless you know what you're doing!