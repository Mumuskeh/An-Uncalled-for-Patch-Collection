-Module:
Emission Weathers fix for Weather mods, by Mumuskeh

----------------------------------------------------------
-Compatibility:
NOTE: You need the original mod. Disable the gamedata/configs/gameplay folder.

----------------------------------------------------------
-Explanation:
When transitioning from a weather that used clouds [from mods like Classic Moving Clouds or Michiko's Weather Revamp Revised] to an emission weather - the clouds would become bright in an instant before disappearing. It's safe to say the addons themselves were not at fault, but the emission weathers are - they didn't have a defined the path to the clouds texture.

Really fixing these weathers implies doing a small shader modification and editing the weather + sky related color values. Here's a link to a thread Rambito sent [in the Anomaly Discord's modding-general channel].

A mod such as Atmospherics already excels at fixing weathers, and it's based on Enhanced Shaders as well. You'll use my patch only for other weather mods that do not change Emission/Psi Storm weather, such as Michiko's Weather Revamp Revised.

Note: This is based on SSS's Windy Vanilla Emission module, so you'll get some wind action even if not using Weather Dynamic Params. Does not require SSS. If we want fixed weathers independent of ES and Atmos, this should be a weather addon by itself.

The tweaks does two simple things:
- No moving clouds instant brightness when emission
- Wind

----------------------------------------------------------
-Patches:

----------------------------------------------------------
-Known issues:
