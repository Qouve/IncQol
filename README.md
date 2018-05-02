# IncQol
# Increased Quality of Life Addon for GW2

This is a release without a source.

This addon is literally a hack like arcDPS and should not be public source.

It does nothing harmful and you can reverse engineer or decompile my .dll

The .dll is not obfuscated and there is no internet traffic(except TP api if enabled) going outwards or vice versa.
You can do whatever you want with the .dll

### If you get an error in the game while using the addon, don't send a report to ANet. 

# How to Install?

Just put the d3d9.dll in your bin64 folder.

The d3d9.dll has a function to chainload other .dlls. To do this, simply rename the other .dll "d3d9_incqol_chain.dll" (default)

This addon can also be chainloaded (tested with arcDPS)

# What does it do?

- Filter items from your inventory
- Sell filtered items when pressing "Sell Junk" in any vendor tab
- Export / Import custom filters
- Customizing the addon
- Drag and drop filter
- more soon?

At default, the addon will never filter three rarities (junk,ascended,legendary), ascended can be unlocked in the config(for securitiy purposes).

# Additional infos

If you are creating a filter, make sure you are filtering the correct items. For a new user I always recommend to enable TP 

After the first start, there are different config/log files under "%installation-path%\addons\incqol\"
The configs can be modified in the game.
The log is just to there to find out where something went wrong.
When you find bugs or your game crashes I need the .log and if you know how to reproduce the bug/crash.

The addon doesn't need to be updated after every patch(just like arcDPS), when something is not working the addon will tell you in the options window and the addon won't do anything.

If you have ideas for more quality of life improvements, just tell me and I will look at it.

If you need help with something then just message me on reddit (u/Qouve) / ingame (Qeve.5743)

# Tutorial for a simple runes/sigils filter

1. Copy the d3d9.dll in your bin64 folder
2. Start your game
3. You will see the following screen:

![options](https://user-images.githubusercontent.com/37458063/39544349-18c1d542-4e4e-11e8-8986-328e7fa417c1.png)

4. That is the option window where you can customize the addon, you can close it for now with the top right button. (To get it back press shift+alt+1)

5. Press shift+alt+2 to open the filter window

![filterwindow](https://user-images.githubusercontent.com/37458063/39545189-b6391298-4e50-11e8-8620-367fcbf1dcd3.png)

6. Now you can create your runes/sigils filter. To start, Left-Click on "Root Filter" and navigate to "Add Filter->Basic Filters->Group Filter"

![groupfilter](https://user-images.githubusercontent.com/37458063/39545158-9e93bbfc-4e50-11e8-8a29-92e4209daad5.png)

7. Left-Click on "Group Filter"

8. Left-Click on the created filter will open it, you will see different attributes (inverted,name,operation).

![groupfilter2](https://user-images.githubusercontent.com/37458063/39545200-be725384-4e50-11e8-88ab-42d5703b2d17.png)

9. Right-Click on the created filter header (marked red on the picture above) and navigate to "Add Filter->Basic Filters->Type Filter" and perform a Left-Click

10. Change the value of the created type filter to UpgradeComponent

![typefilter](https://user-images.githubusercontent.com/37458063/39545217-c987b7d2-4e50-11e8-9809-9258dfef09a1.png)

11. Right-Click on the type filter header and perform a Left-Click on "Add Sub Filter"

12. Change the value of the created sub type filter to Rune

11. Right-Click on the type filter header and perform a Left-Click on "Add Sub Filter"

12. Change the value of the created sub type filter to Sigil

13. Change the operation of the type filter to "Or"

![subtypesfilter](https://user-images.githubusercontent.com/37458063/39545221-ca5e0314-4e50-11e8-89ee-7ff2972e77fb.png)

14. Right-Click on the group filter and navigate to "Add Filter->Range Filters->Rarity Filter" and perform a Left-Click

![groupfilter3](https://user-images.githubusercontent.com/37458063/39545252-e0b29684-4e50-11e8-827f-74d06fa6be88.png)

15. Change the boundaries to "Masterwork" and "Rare"

![rarityfilter](https://user-images.githubusercontent.com/37458063/39545251-dff01a96-4e50-11e8-9fee-a80b7d7c292a.png)


16. You can close the window via the top right button and you are done.

### Video Showcase

https://www.youtube.com/watch?v=AqnaMiHAJdo

# FAQ
### How to create filters?
You can Left-Click on "Root Filter" button to create filters 

You can Right-Click on any filter and click the "Add Filter" button to add a child filter

### Where can I reset the configs?
If you want to reset your configs, you can delete the config files in the "%installation-path%\addons\incqol\" folder

### How can I disable selling/filtering?
You can disable the selling/filtering in the config or remove the d3d9.dll completely

### Why can't I save a filter?
Make sure you have the rights to create and save files in the filters folder

### I don't see anything? What are the default hotkeys?
Shift+Alt+1 to open the options window, where you can see all hotkeys

Shift+Alt+2 to open the filter window

Shift+Alt+3 to open the small filter window

Shift+Alt+4 to add a filter with the current hovered item

### Adding the current hovered item is useless, since I have to recreate the filter inside the correct group?

You can drag and drop the created filter into a group filter

### Some hotkeys are wrong?
It can happen that some hotkeys are not correctly displayed, but they will work.

Something like that happened when I had my OS language on german.

### What if Gw2 gets patched?
Normally the addon will still functioning correctly, but if something big changes and the addon can not start/work correctly it will tell you.

If the addon is not functioning correctly you should not use it (disable selling in options or completely remove it from bin64 folder if its crashing your game and wait for an update).

### Can I use it on the 32-Bit client?
No I only support the 64-Bit client

### Does the addon connect to a server in any way?
Technically yes(tradingpost api if activated), but no other than gw2 servers.

### Can I get banned using this addon?
Probably not, it does the same that arcDPS build templates does. 
You do not gain any advantages over another player(build templates). 
The addon will NOT sell anything without user input.

https://en-forum.guildwars2.com/discussion/352/policy-third-party-programs-multi-boxing-macros

### Can this addon delete or sell wrong items?
Not when the correct version is used. And pretty unlikely when something changes.

### My game crashes everytime when I do X. What should I do?
Rename/Remove the .dll from your bin64 folder and send me the .log file generated in the "%installation-path%\addons\incqol\" folder. Tell me how to reproduce the crash so I can look into it.

I tested the addon a long time (play testing all game modes, let other people test the tool,other OS, play through 6+ hours).
It never deleted an item nor did it sell a wrong one.

# Disclaimer
I am NOT responsible if items are deleted / sold by mistake or wrong configuration. Use at your own risk.
