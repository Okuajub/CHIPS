Hey there! This is the location for all of your programming and writing that goes into the Ghost.
You can safely ignore the "dict" folder unless you're trying to learn how to program in Kawari. 
If you're just here as a writer, you're going to be mainly focused on the "ghost-*" files.
But, just to cover our bases, here's a little overview of all the files in this folder.

dict (folder) - This folder holds all of the developer dictionaries. If you're primarily a writer and not a coder, you can safely ignore these files.

profile (folder) - This folder holds files that your baseware (most likely SSP) uses. You can ignore it until you publish your Ghost, at which point you should delete it before you create their public files. developer_options.txt should make sure it's not included in .nars or update files, but it's just good practice.

profile\dict-bakdata.txt and profile\dict-savedata.txt - if you see these in your profile folder, they're your Ghost's save data! You can check to see if data you add is getting saved properly here.

descript.txt - This describes the very basics of your Ghost to your baseware. You should fill it out because it contains important information, like credit to the author (you!), the name of your Ghost, and what balloon they use (if any). If you're not sure what you can replace without breaking anything, just fill out the 'name' sections, replace my name (Okuajub) with yours, and delete the website link.

ghost-*.kis - Any file prefixed with 'ghost-' is where you're going to be! I highly suggest starting with 'ghost-aitalk', as it is a good primer on how to write dialogue in Kawari.

icon.ico - The icon for your ghost that shows up in the task tray. Needs to be an '.ico' file. (OPTIONAL)

kawari.log - A log file automatically created when your Ghost boots. If you're having issues with something, 'kawari.log' will log any errors and all the events sent to the Ghost.

kawarirc.kis - A file which defines which files in this folder Kawari should pay attention to. 'kawarirc.kis' is always read first.

kosui.exe - A debugging program normally bundled with Kawari's source code. You can find resources on how to work it in the Kawari documentation.

shiori.dll - Kawari itself! This file is what interprets all of the code you write in Kawari. So don't delete it unless you know what you're doing!

That covers most of what you'll find here. Oh, and of course... you can safely delete this file, 0_Ghost-master_readme.txt, if you'd like, too. It's here just for you, the creator!