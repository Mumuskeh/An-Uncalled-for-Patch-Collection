-Module:
Anomalous Creation [Wang_Laoshi]
https://www.moddb.com/mods/stalker-anomaly/addons/anomalous-creation
By plyaka.egor

----------------------------------------------------------
-Compatibility:
NOTE: You still need the original mod.

----------------------------------------------------------
-Explanation:

Fixes an issue in the code that eventually causes busy hands.

As explained by RavenAscendant:
	"Bad code is bad. They pass 2 game objects into do_spawn via a timed event. Storing gameobjects in the timed event handler is a common way to get busy hands. Should be storing the ids (and maybe sections) in the event and fetching the objects fresh (and maybe validating them by section) in do_spawn once it is called by the event.
	Once this code breaks all other timed events will fail. Like the ones used for fanatics quest and sid's door.
	Mod hasn't been touched in a year, I doubt it will be fixed but you could ask."

And per plyaka.egor:
	"The issue was that there is a "victim" variable. Basically when a mutant dies it makes a time-event which means that it will do the artifact spawn like not at the same time when mutant dies. And that time is enough for game to actually delete the object of the mutant, which means that "victim" variable tries to access an unexisting object and lua shits itself.
	Mostly I just made it save all the things for that mutant so it doesn't need to access the object afterwards, it accesses the saved parameters."

----------------------------------------------------------
-Patches:

----------------------------------------------------------
-Known issues:
