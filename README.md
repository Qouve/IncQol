# IncQol
# Increased Quality of Life Addon for GW2

This is a release without a source.

This addon is literally a hack like arcDPS and should not be public.

It does nothing harmful and you can reverse engineer or decompile my .dll

The .dll is not obfuscated and there is no internet traffic(except TP api if enabled) going outwards or vice versa.
You can do whatever you want with the .dll

### If you get an error in the game while using the addon, don't send a report to ANet. 

# How to Install?

Just put the d3d9.dll in your bin64 folder.

The d3d9.dll has a function to chainload other .dlls. To do this, simply rename the other .dll "d3d9_incqol_chainload.dll" (default)

This addon can also be chainloaded (tested with arcDPS)

# What does it do?

- Filter items from your inventory
- Sell filtered items when pressing "Sell Junk" in any vendor tab
- Export / Import custom filters
- Customizing the addon
- more soon?

At default, the addon will never filter three rarities (junk,ascended,legendary), ascended can be unlocked in the config(for securitiy purposes).

# Additional infos

If you are creating a filter, make sure you are filtering the correct items. For a new user I always recommend to enable TP 

After the first start, there are different config/log files under "%installation-path%\addons\incqol\"
The configs can be modified in the game.
The log is just to there to find out where something went wrong.
When you find bugs or your game crashes I need the .log and if you know how to reproduce the bug/crash.

The addon doesn't need to be updated after every patch(just like arcDPS), when something is not working either the addon will tell you in the options window and the addon won't do anything.

If you have ideas for more quality of life improvements, just tell me and I will look at it.

If you need help with something then just message me on reddit (u/Qouve) / ingame (Qeve.5743)

# FAQ
### Where can I reset the configs?
If you want to reset your configs, you can delete the config files in the "%installation-path%\addons\incqol\" folder

### How can I disable selling/filtering?
You can disable the selling/filtering in the config or remove the d3d9.dll completely

### I dont see anything? What are the default hotkeys?
Shift+Alt+1 to open the options window, where you can see all hotkeys

Shift+Alt+2 to open the filter window

### Some hotkeys are wrong?
It can happen that some hotkeys are not correctly displayed.

Something like that happened when I had my OS language on german.

### Can I use it on the 32-Bit client?
No I only support the 64-Bit client

### Does the addon connect to a server in any way?
Technically yes(tradingpost api if activated), but no other than gw2 servers.

### Can I get banned using this addon?
Probably not, it does the same that arcDPS does. 
You do not gain any advantages (build templates). 
The addon will NOT sell anything without user input.

### Can this addon delete or sell wrong items?
Pretty unlikely when nothing changes.

### My game crashes everytime when I do X. What should I do?
Rename/Remove the .dll from your bin64 folder and send me the .log file generated in the "%installation-path%\addons\incqol\" folder. Tell me how to reproduce the crash so I can look into it.

I tested the addon a long time (play testing all game modes, let other people test the tool,other OS, play through 6+ hours).
It never deleted an item nor did it sell a wrong one.

# Disclaimer
I am NOT responsible if items are deleted / sold by mistake or wrong configuration. Use at your own risk.
