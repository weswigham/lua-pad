To quote DarKSunrise:

This project is now carried on by Levybreak

This is an in-game scripting environment with dynamically updating syntax highlighting for Lua. It basically means that if the server has WireMod installed, it also highlights the WireMod functions for you. Same goes with every mod you have installed (or the server). Please note, that if the server doesn't have Luapad, you'll only have cached server-side syntax highlighting, with only some basic serverside functions. However, this doesn't affect the syntax highlighting of client-side functions.

This 'script' can be used to code in-game, save the code, load it later, and most importantly: run it client-, and serverside. You can upload code in order to run it on the server, but only if the server has Luapad, and you're an admin. It currently only supports text-files inside the data-folder, because of your security. Maybe I'll add the support of direct Lua-files later, with rawio (Optional feature in v1.10).

It probably has some bugs, so tell me about them and I'll try to fix them. And yes, you can code an aimbot, or a wallhack in-game.

Credits go to the following persons:
Andreas "Syranide" Svensson for Wire Expression 2 Editor, which I heavily modified to work with Lua-syntax.
Narkaleptic for the VTF silk-icons used in this pack.
Garry's Mod Finland for beta-testing this.
Levybreak for the newest versions (up to from v.1.11), as I didn't have time for this project
Me for everything else.

Media:


Known bugs:
Gamemode-folder is always empty
No syntax-highlighting for multi-line comments or strings (I'll see if I can do these)
Lua-folder has files that are not really there, but instead in addons/AddonName/lua, and therefore making them unable to load (I'm open for suggestions here)

Planned features:
Feature where you could run the script on all current clients or a specific client
Sidebar remembering it's position
Autocomplete for functions
Using GZip to compress cache-files for syntax highlighting
Customizable colors on syntax highlighting

Downloads:
From the newest to the oldest. You should always download the one on the top, unless you want an old version for some reason.

YOU NEED GM\_RAWIO MODULE IF YOU WANT TO EDIT LUA-FILES, IT'S NOT INCLUDED


from: http://www.facepunch.com/showthread.php?t=776712