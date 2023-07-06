
# CHIPS
The CHIPS Kawari Template is an Ukagaka/Ghost template for the programming language Kawari.<br>
Kawari is a programming language popular in many early Japanese Ghosts, however it has seen little use in the English community due to the prominence of YAYA.<br>
This template is intended to provide a unique option out of the currently available English templates, which, as of writing, require a notable amount of programming knowledge to use.<br>
CHIPS is designed as a 'middleware', which means there is a layer of software which interprets the events one's baseware sends to the Ghost. This allows the User to focus primarily on writing dialogue and not code.<br><br>

## Getting Started
CHIPS is a template for a 'Ghost', a type of Desktop agent. All Ghosts run on a baseware program. To use CHIPS, you must have one of these baseware programs. SSP (Sakura Script Player) is the most popular and up-to-date applications for running Ghosts.<br>
### Installation
To use CHIPS, download the latest release of your choice and unzip it. A '.nar' file containing CHIPS should be included. This is a self-installing archive. Drag and drop the '.nar' file included onto a currently running Ghost.<br>
CHIPS will install itself as a Ghost in the baseware, and should be selectable from the menu. You can now edit the files at 'ssp_[version-number]\ghost\CHIPS_Template' and start development of your Ghost. Don't forget to check the readme!
### Manual Installation
If you need to manually install CHIPS, unzip the '.nar' file itself into its own folder. Move this folder to your baseware's Ghost folder. In SSP, this is normally at 'ssp_[version-number]\ghost'. Once this is done, CHIPS should be installed. If you don't see CHIPS in the Ghost selection menu, reload your baseware. You can now edit the files in the folder you created and start development of your Ghost.

## Updating CHIPS-based Ghosts' Middleware
To update the middleware, download the latest release of CHIPS of your choice. Unzip the '.nar' file as you would to manually install CHIPS. Then, navigate to the 'ghost\master' folder, and copy the 'dict' folder from CHIPS to your Ghost. Please also review any changelogs included with CHIPS, in the case that adjustment of the 'ghost-*.kis' files is necessary.