# HexFlow-Launcher-Unofficial-Custom
Releases page: https://github.com/BlackSheepBoy69/HexFlow-Launcher-Unofficial-Custom/releases

A 3d coverflow like launcher for PS Vita.
<p><img src="/Media/screen_03.png" width="800" title="screen-03"></p>
<p>Display and launch your games and homebrews in style.<br /><strong>HexFlow Launcher</strong> features a 3d user interface to display your games with their box art and supports many customization options like custom covers and backgrounds.</p>
<p>Launching a game/app from <strong>HexFlow Launcher</strong> will close the launcher automaticaly without asking.</p>
<h2>Custom Covers</h2>
<p>Place your custom covers in "<em>ux0:/data/HexFlow/COVERS/PSVITA/</em>"</p>
<p>Cover images must be in <strong>png</strong> format and file name must match the <strong>App ID</strong> or the <strong>App Name</strong> of each app (recomended resolution 256x256px). <a href="https://live.staticflickr.com/7176/6885249717_738e8ee187_n.jpg" target="_blank" rel="noopener">Sample image</a></p>
<h3>Download Covers and Backgrounds</h3>
<p>From v0.3 covers can be downloaded automatically from the settings menu (Start button). You can also download covers and backgrounds manually from the link below. A big thanks to <b>astuermer</b> for his contribution.</p>
<p><a href="https://github.com/andiweli/hexflow-covers" target="_blank" rel="noopener">https://github.com/andiweli/hexflow-covers</a></p>
<h3>Custom Background</h3>
<p>Place your <strong>Background.png</strong> or <strong>Background.jpg</strong> image in "<em>ux0:/data/HexFlow/</em>" (recomended resolution 1280x720px or less). Some custom backgrounds are available <a href="https://github.com/andiweli/hexflow-covers/tree/main/Backgrounds">HERE</a></p>
<h3>Custom Music</h3>
<p>Place your  <strong>Music.mp3</strong> file in "<em>ux0:data/HexFlow/</em>" (music will play automaticaly when the "Sounds" option is enabled)</p>
<p>&nbsp;</p>
<h2>AutoBoot</h2>
<p>If you want to auto-launch <strong>HexFlow Launcher</strong> every time your PS Vita boots up you can use the <a href="https://vitadb.rinnegatamante.it/#/info/261" target="_blank" rel="noopener"><strong>AutoBoot</strong></a> plugin by Rinnegatamante.</p>
<p>&nbsp;</p>
<p><img src="/Media/screen_01.jpg" width="800" title="screen-01"></p>
<h2>Controls</h2>
<p>Navigate your library using the <strong>DPad</strong> or the <strong>Left Stick</strong> or with the <strong>Touch Screen</strong>.</p>
<p><strong>R/L triggers</strong>: Skip 5 items</p>
<p><strong>Cross</strong>: Select/Launch game/app</p>
<p><strong>Square</strong>: Change Category</p>
<p><strong>Triangle</strong>: Game Details</p>
<p><strong>Circle</strong>: Change View/Cancel</p>
<p><strong>Start</strong>: Settings menu</p>
<p>&nbsp;</p>
<h3>IMPORTANT</h3>
<p>For PSP or PS1 bubbles generated by Adrenaline Bubbles Manager you must set the value of <strong>BubbleID</strong> to <strong>TitleID</strong> in the settings menu of ABM tool.</p>
<p>For PSX2PSP, game folder name must match with the GameID. For example "ux0:pspemu/PSP/GAME/<strong>SLES01234</strong>".</p>
<p><strong>Subfolders and psp categories plugin are not supported</strong>.</p>
<h1>Downloads</h1>
<p>Grab the latest version from the Releases page: https://github.com/BlackSheepBoy69/HexFlow-Launcher-Unofficial-Custom/releases
<p>&nbsp;</p>
<h3>Credits</h3>
<p>Programming/UI: <strong>Sakis RG</strong></p>
<p>Developed with <a href="http://rinnegatamante.github.io/lpp-vita/" target="_blank" rel="noopener">Lua Player Plus</a> by <strong>Rinnegatamante</strong></p>
<h3>Special Thanks</h3>
<p><strong>Creckeryop</strong></p>
<p><strong>andiweli</strong> (<a href="https://github.com/andiweli/hexflow-covers" target="_blank" rel="noopener">HEXFlow Covers database</a>)</p>
<h3>Translations</h3>
<p>French - @chronoss</p>
<p>German - @stuermerandreas</p>
<p>Spanish - @kodyna91</p>
<p>Italian - @TheheroGAC</p>
<p>Russian - @_novff</p>
<p>Swedish - @Spoxnus86</p>
<p>&nbsp;</p>
<h2>Support</h2>
<p>If you want to support my work you can become a <a href="https://www.patreon.com/vitahex">Patron</a>.</p>
<p>PayPal option is also available <a href="https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&amp;hosted_button_id=RM8ECMVYMTXGJ&amp;source=url">HERE</a></p>
<p><a href="https://twitter.com/VitaHex">VitaHEX Twitter</a></p>
<p><a href="https://vitahex.weebly.com/">VitaHEX Official Page</a></p>

# HexLauncher Custom
- Revamp mod for VitaHEX's HexFlow Launcher

Releases page: https://github.com/BlackSheepBoy69/HexFlow-Launcher-Unofficial-Custom/releases

I made a Github finally.
When you start the app (for the first time in v0.8/9, everytime in v0.6-0.7) or refresh cache (v0.8/9) it will generate "applist.dat" in your data files like this: ux0:/data/HexFlow/applist.dat
You must rename it to "customsort.dat" and when you edit it with a unix based text editor like VitaShell or gVim, you can rearrange the titles how you like. This will be your "custom" category. This replaces the "all" category in V0.6, but later versions it gets its own category.

Take the sourcecode and name it to "index.lua" and put it in like this: ux0:/app/HXLC00001/index.lua
Or put it in the vpk (openable with Winrar) to replace the index.lua there.


Known bugs:

⚫It freezes/crashes every now and then, but it doesn't seem to happen while "sounds" are set to "Off"

⚫Default override doesn't really do anything lol.

⚫PS Vita games that are overridden to Homebrew keep their covers and vise versa. (Note: some homebrews actually have covers to download if you override them to Vita first)

^All the above bugs are also present in VitaHEX's HexFlow Launcher 0.5



Planned features for upcoming updates:

⚫Instant inline cache update when downloading covers/overriding category. (like Retroflow 3.x)✔️Done for cover download, an attempt of instant inline cache update for overrides is in v0.9

⚫Emu-launch, as seen in Retroflow. Either using Retroflow's rom identification, Adrenaline Bubble Manager's rom identification, and/or "MD5/CDC32 scraping" rom identification. Hopefully not slowing down loading times for people uninterested in Emu-launch.✔️Done but too buggy for release right now

⚫An option in the settings menu to pretend everything is homebrew for better performance and a "cleaner" look, and/or make there be only 2 categories: Custom and All.✔️Done, unreleased for some reason.

⚫Ability to use Adrenaline Bubble Manager, Adrenaline Launcher, and Retroarch for PSP/PS1 where possible, all at once if you so feel like it. ✔️ framework for this - "pspemu_translation_table" is included in v0.9 but Adrenaline Launcher capabilities are not added.

⚫"Rolling Refresh" using a verification file that says 1: Current HexLauncher version, 2: # of entries in ux0:app folder and/or rom folders, 3: whether the last cache refresh was finished successfully. If any are untrue (ex: if you uninstall/install a new app), it will attempt a quick cache update - a "rolling refresh". ✔️Done but too buggy for release right now

⚫New Emu-launch categories, on top of Retroflow's: Nintendo DS Category (✔️Done, coming when Retroflow integration is added to public HexLauncher Custom release), Dreamcast Category (low priority), ScummVM Category (low priority), Playstation Mobile Category (low priority), Pico8 (low priority but easy to program).

⚫ PSVShell and the "L..." overclocking program integration. AKA the ability to launch an app at 500 overclock through triangle menu.✔️Done, coming when Retroflow integration is added to public HexLauncher Custom release

⚫Select+R1(?) or R2(?) to jump to the next letter of game, alphabetically. Select+L1(?) or L2(?) to go to previous letter of game. This will only be added if Emu-launch is added. Not 100% sure what buttons will be used, so I say "(?)"

⚫Absolute full translation for everything, including msg boxes (like retroflow)(easy but low priority)

⚫The option for playing gameboy original games in color. More than likely just a switch that messes with retroarch settings. This would be great for games that were retroactively given color such as Super Mario Land, Super Mario Land 2, QIX, Hyper Lode Runner, DrMario, Metroid 2, etc)(low priority and this will be hard to program).

⚫Extra smooth cover size adjusting, like the XBox "Aurora" coverflow app, you can see it at about 9 minute, 15 seconds into this video: https://www.youtube.com/watch?v=Kqvruf8q3J0

⚫Rename a game via the triangle menu. Great for japanese-translated-to-English games where the translators were too lazy to translate the app title in the param.sfo (low priority).

⚫Genres categories and an easy way to get there (from settings menu?) similar to the one in "Dig - Emulator Front-End" for android. ex: you could have a "Puzzles" folder and a "Mario" folder and can put "Mario Picross" in both (through triangle menu?)

⚫Settings menu gui more like minecraft's menu, so more settings can be added. Especially for the On/Off settings. "Advanced options" button at the bottom for even more? (easy)

⚫Setting for "livearea replacement mode: enables a loading screen image similar to the Enso "Molecule" image. This planned setting may also autoboot you into HexLauncher Custom. This will only be added if "advanced options" button is added. (easy)

⚫The ability to uninstall a game (via the triangle menu?). For now for that, you could technically use triangle menu to get app ID and delete it manually from ux0:app if you want. (easy, but this will only be added if "livearea replacement mode" is added)

⚫Setting to read from any rom location such as "ux0:Retroarch_Roms". This will only be added if "MD5/CDC32 scraping" rom identification is added.

⚫Setting to change between soundsets and background music (currently a hidden feature in VitaHEX's HexFlow Launcher v0.5 and all versions of HexLauncher Custom). May involve taking some code from Retroflow, which has more polished music code though still a hidden in that app too.

⚫Setting to change the category text color (on the top left of the screen) for when you're using a bright background (low priority)

⚫Setting to show system apps such as PSN store, Browser, Camera, Gallery, and Settings from within the launcher (or maybe at the app background screen, for that including Vitashell?)

⚫Setting to let you use the touchscreen to touch the "X Launch" on the bottom right of the screen to launch a game starting 1 second after you start HexLauncher Custom. (low priority). Any other touch features probably won't be added because when the screen gets wet it touches random places for you and also because I'm a lazy.

⚫Setting (or not as a setting just adding it normally?) of "recently played", "most played", and/or "search". Setting to rename "Custom" to "Favorites".

⚫The ability to quickly add an app to "Custom" (through triangle menu?). High priority if "rolling refresh" is added.

⚫Setting to combine all PCEngine categories (or just have it combined by default, like psp and psp minis?). Setting to combine all gameboy categories.

⚫Setting for multi-memory card users to scan roms from all memory cards. Note: running PSP games on secondary memory cards - uma0: - requires the special hacked version of adrenaline, and running vita games on secondary memory cards might not be possible. (low priority)

❌video/media category. Seems like an over-reach, just use MVPlayer.

Releases page: https://github.com/BlackSheepBoy69/HexFlow-Launcher-Unofficial-Custom/releases
