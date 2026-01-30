-Module:
Toxic Air [bvcx, Drunk_Headcrab, Priler]

----------------------------------------------------------
-Compatibility:
Let this overwrite the original mod.

All options are standalone.

Compatible with either Drunk' Enhanced, and Priler's Redux.

It *may* be compatible with Drunk' Enhanced + Breaker_oak's Radioactive Air, but I didn't test it. I recommend let Breaker_oak's files overwrite mine.

----------------------------------------------------------
-Explanation:

Consolidates the icon files. Instead of loading icons from two different files, all used icons are now kept in the ui_oxygen_tank.dds file, while ui_oxygen_tank2.dds is unused and keeps unused icons for reference or later use.
It also adjusts the icon for the FP-5 Filter (though it is unused. Maybe I'll enable it some time).

Integration into:
Grok's Stash Overhaul
Lootboxes
PDA Interactive

----------------------------------------------------------
-Patches:

World models fix
Reenables the oxygen tanks world models. The mod was using the camelback attachment's model instead of the included tank models for some reason.
This is redundant if you're also using Breaker_oak's Radioactive Air tweaks or Priler's Redux, as both include the same change.


No Separated Helmets
This allows the use of air canisters for integrated outfits (SEVAs, SPPs, exos...) in games without the Separated Helmets mod.
I merely disabled three lines of code that check if you wear a helmet, I don't expect any trouble but tell if you do.
Includes option for Priler's Redux, but it may become outdated with further updates.
Shouldn't be needed with Breaker_Oak's Radioactive Air rework.

----------------------------------------------------------
-Known issues:
