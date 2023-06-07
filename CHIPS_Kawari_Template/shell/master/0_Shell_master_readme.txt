Hello! This is the place where you'll put all the visuals for your Ghost. These images are intended to be replaced. Please do not redistribute them without permission.

If you are familiar with SERIKO coding (shell coding), then this will be very easy for you. If not, I'll point you to some helpful resources when it comes to SERIKO.

https://ukagakadreamteam.com/wiki/info/seriko is a brief overview of what SERIKO is. I suggest reading it even if you don't want to do anything complex.

https://www.ashido.com/ukagaka/makingimages.html is the beginning of the Shell portion of the Girl and Triangle template walkthrough. If you just want the basics and don't want to get too complicated, this is perfect for that. Be aware, though, that this walkthrough uses the old definition for SERIKO coding. If you'd like to know the difference between the old definition and the new definition, you can check out this guide here: https://zichqec.github.io/s-the-skeleton/olddef_vs_newdef

https://ssp.shillest.net/ukadoc/manual/descript_shell_surfaces.html If you'd like to do more complicated work, this page is the official documentation for SERIKO and should hold all the information you need. You can run it through a translator if you don't understand Japanese (which is understandable considering the audience for this template), but if it looks like too much for you, then that's OK. The walkthrough listed before this one is a great point to go from and you can do a lot with the info it gives you.

Or, if you're not particularly an artist or a coder, you can find what's called a 'freeshell'. If you're willing to go through machine translation (or wander blindly), the Japanese freeshell wiki https://wikiwiki.jp/feeshell/ (yes, it's 'feeshell', lol!) has a plentiful selection of free art, many of these art packs coming with pre-written code, for you to use!

Now, for an overview of all the files in this folder.

profile (folder) - This is a folder that holds your specialized profile information, such as the position of the Ghost and its balloons. You don't need to do anything with it, unless you're distributing your Ghost.

readme.txt - This is the readme for your shell. When someone installs a shell, this will pop up. For master shells, this is normally only seen when the user looks for it. Readmes are a great place to put credit and notices of ownership, if someone else made your shell art or coding.

descript.txt - This file describes your shell to the baseware (most likely SSP), and holds important information such as the credit to the author (you!), the shell's name, the shell's menu text colors, any dressup menu items, and some default values.

surfaces.txt - Another definition file. This informs the baseware what surfaces corrospond to what, and what animations exist, among other things. It is coded in SERIKO. You can also have multiple surfaces.txt files, as long as they start with 'surfaces'. This is really helpful if you have characters with a lot of animations, a lot of different characters, or so on.

surfacetable.txt - This file describes names and groups for surfaces in the developer menu under 'Surface Test'. Extremely handy if you have a lot of surfaces and animatons or have a hard time remembering what numbers corrospond to what emotions.

menu_*.png - All of these files are used to create the right click menus for your Ghost. You can create a pretty unique looking menu if you want! I used a cute bone pattern as an example, but you could use realistic images, sketches of your Ghost, or solid colors too. The sky is the limit.

surface*.png - These are the images for your Ghost. surface0 and surface10 are special. All other surfaces can be deleted, if so desired.

surface0.png - The default Sakura (main character) surface. You need to have this, or the Ghost won't run.

surface10.png - The default Kero (side character) surface. You need to have this, or the Ghost won't run. If you don't want a Kero, you can make the image blank. BUT! Please make it small and remember to use the \s[-1] command in the SakuraScript of your Ghost, or else an invisible Kero will cause weird bugs. It can trigger overlapping dialogue when there isn't supposed to be a Kero, or trigger events in other Ghosts despite the fact it's not supposed to exist. An invisible Kero cannot be moved by the user normally, so its up to you to make sure it doesn't interfere with functioning.

thumbnail.png - The thumbnail that'll be displayed when someone hovers over the shell in the menu. Handy to show the user what the different shells look like without changing them manually.

And that's it! Honestly, it's a lot less scary than it may seem. If you're done with this file, you can get rid of it, too.