-Module:
Enhanced Toxic Air [bvcx, Drunk_Headcrab]

----------------------------------------------------------
-Compatibility:
Note: You still need the original mod. Let this overwrite it.

All options are standalone.

It *may* be compatible with Drunk' Enhanced + Breaker_oak's Radioactive Air, but I didn't test it. I recommend let Breaker_oak's files overwrite mine.

IMPORTANT: A new game is required if you were already using Toxic Air in a current savegame.

----------------------------------------------------------
-Explanation:

Internal IDs renamed such as [itemtype_tier_name], for better inventory organization. Filters won't be mixed among themselves without order, instead being ordered by tiers, so you should be able to differentiate different tiers more easily.

Consolidates the icon files. Instead of loading icons from two different files, all used icons are now kept in the ui_oxygen_tank.dds file, while ui_oxygen_tank2.dds is unused and keeps unused icons for reference or later use.
It also adjusts the icon for the FP-5 Filter (though it is unused. Maybe I'll enable it some time).

Reenables the oxygen tanks world models. The mod was using the camelback attachment's model instead of the included tank models for some reason.

FP-5 filter enabled. Heavier and less protective than other tier 3 filters, but lasts longer. Widely used by most factions who don't already have a tier 3 filter of their own.

N750-CS filter finished (I think?). The best protection, longevity, and weight. Extremely rare, Spore sells it only to players with high Clear Sky goodwill, and you can only rarely loot it from CS stalkers (not even worth going out of your way just for it, that's how rare).

Integration into:
Grok's Stash Overhaul
Lootboxes
PDA Interactive
TB's RF Receiver Hidden Package Sidequests + CookBook's QOL patch (requires the module in this package)

----------------------------------------------------------
-Patches:

Priler's Toxic Air v2.0 REDUX consistency patch
Use for compatibility with Priler's Redux. Make sure to apply this on top of the Main Files if you'll use Priler's Redux version.
Tested for the update of Dec 24th, 2025.

No Separated Helmets
This allows the use of air canisters for integrated outfits (SEVAs, SPPs, exos...) in games without the Separated Helmets mod.
I merely disabled three lines of code that check if you wear a helmet, I don't expect any trouble but tell if you do.
Includes option for Priler's Redux, but it may become outdated with further updates.
Shouldn't be needed with Breaker_Oak's Radioactive Air rework.



World models fix
Separate patch to reenables the oxygen tanks world models. You may use this if you're not interested in the changes in the main files.
This is redundant if you're also using Breaker_oak's Radioactive Air tweaks or Priler's Redux, as both include the same change.

----------------------------------------------------------
-Known issues:

Unused/unfinished items:
-The Continuous Air Supply Unit seems to be a "new oxygen tank for UNISG once I figure out how to make it able to take batteries." Seems like not an easy to solve problem.
-The FP-5 filter seems intended as the "worst" high tier filter and for the military, maybe?. I'm not too familiar with the values involved, but they seem fine to me, so the only issue seems to be the unaligned icon, but I've already fixed that, only thing left is to distribute it.
-The N750-CS filter seem to have been intended as the best and rarest filter, for Clear Sky members, requiring artefacts to craft. It only has the text done, which mentions no particular intended mechanic like the Continuous Air Supply Unit using batteries, so it could be made up fairly quickly.