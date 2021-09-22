# Exile-Loottable-Helper

This is a simple helper written in JavaScript and helps you create the loottable config.
You can create something completely new or import an existing part of your config and edit it.

## How to use
- Open the index.html in a browser of your choice
- Add Entry: Add a new field to your list
- Generate: Compiles all your inputs and creates a list you can put into your loottable config
- Import: Copy and paste your loottable config and click on "Import Data"

## Import Example

The code you want to be imported need to follow an exact pattern or else the import won't work correctly. The only thing that can be ignored are whitespaces and the code is allowed to contain comments behind the classname or groupname (as shown in the LootItemGroups example). 

**LootItemGroups Example:**
```
3, Exile_Item_CookingPot
5, Exile_Item_CanOpener
5, Exile_Item_Matches
3, Exile_Item_EMRE						// 75% Hunger
6, Exile_Item_GloriousKnakworst			// 60% Hunger
7, Exile_Item_Surstromming				// 55% Hunger
7, Exile_Item_SausageGravy				// 50% Hunger
```

**LootTables Example:**
```
1, Restraints
3, PistolAttachments
3, ShotgunAmmo
3, SMGAmmo
3, SMGAttachments
4, Shotguns
4, SMG
5, CivilianVests
5, PistolAmmo
```
