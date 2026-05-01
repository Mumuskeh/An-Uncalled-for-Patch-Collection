-Module:
Hunter Survival Crafting [unwary]
https://www.moddb.com/mods/stalker-anomaly/addons/hunter-survival-crafting

----------------------------------------------------------
-Compatibility:
NOTE: You still need the original mods. Disable the configs and textures/ui folders.

IMPORTANT: If you were already using this mod in a current save, a new game is required.

Banjaji's Crafting System Improvement:
required for the recipes, as they are too complex for the vanilla system.

Hunter's Kit - A Butchery Engine:
Currently both mods conflict. Have Hunter's Kit on a higher priority than HSC in your load order, so its rework of the ui_mutant_loot.script file takes priority. Or disable this mod and module's ui_mutant_loot.script

----------------------------------------------------------
-Explanation:

-Items and crafting
DLTX conversion of several files that hadn't been done so by the original mod yet, and un-DLTX'fying of several items that didn't need it.
The crafted medkits and stimpack are supposed to be inferior improvisations of the vanilla imported items. They will all now be cheaper and heavier than the vanilla items (the heavy medkit having a value of 8500 roubles above was just silly). The stimpack has also been nerfed to heal less.
Small text corrections.
Mipmapped some textures that could use it.
The FDDA patch has been integrated into the main files.

Added default actor effects configs.

-Unique NPC Loot
DLTX conversion. Still requires the items above.
Turned its copy of itms_manager.script into a monkey patch.
Updated its copy of hxf_tough_important_npcs.script to the last version of "Tougher Important NPCs and Companions". Remove that file if you don't want that feature.


-Unique NPC Loot - Everyone is hostile
Unavailable for now. (also, feature creep?)

----------------------------------------------------------
-Patches:

Original patches have been DLTX'd where possible and needed.


Fillable Canteens
Cook flasks, tea, and tactical tuna.

Placeable Campfires
Craft campfires.

Syringes from medkits
After using a medkit, you'll receive a spare empty syringe. This affects both the new and the vanilla medkits.
In addition to the medkits, now the improvised morphine and stimpacks also provides a syringe.
Do not use with the More drops from drugs patch below, as its redundant.

More drops from drugs (DLTX Minimod)
The new meds will provide discarded parts when used just like other drugs as per the mod.

NPCs Limping and Healing

Cold System
Patch updated for v0.72.
It could use some monkey patching instead of copying the main script file, but maybe another time.

----------------------------------------------------------
-Known issues:
