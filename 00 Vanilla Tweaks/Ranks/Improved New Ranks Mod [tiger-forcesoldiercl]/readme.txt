-Module:
Improved New Ranks Mod [tiger-forcesoldiercl]

----------------------------------------------------------
-Compatibility:
NOTE: You still need the original mod. Disable the file
gamedata/configs/gameplay/character_desc_escape.xml

and the folders
gamedata/configs/creatures
gamedata/configs/gameplay

----------------------------------------------------------
-Explanation:

DTXL and DXML conversion.
The DXML conversion affects the rank increases of the Cordon NPCs, which could conflict with changes from mods like Storylines.
It won't help with other rank overhauls.

Some min and max ranks for random NPCs spawns seemed outta wack. I've no idea if it was intended or not, so I tweaked back into something sensible judging by context.

The NPC loadouts patches have been trimmed and fixed, and now they only work with the new ranks.
They were repeating the already existing loadout sections, meaning they risked duplication crashes.
Also, the Monolith file repeated the contents of the legend rank section for all its new rank sections, which is redundant. It also attempts to add the Shard of the Monolith as an extra item to the new ranks for NPCs. However, those extra items sections are meant for weapons such as grenades, and this is not the way to add an item, much less a quest item. And those new extra sections weren't assigned to any ranks anyway.

----------------------------------------------------------
-Patches:

----------------------------------------------------------
-Known issues:

Some of the existing patches may need fine tuning.