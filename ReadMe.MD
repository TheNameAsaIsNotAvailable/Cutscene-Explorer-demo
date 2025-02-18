# 'Cutscene Explorer' demo (2024)
A mod for Mafia: The City of Lost Heaven (2002).

INSTRUCTIONS:
- Select **Scene Selector** from the Main Menu, and inside the phone booth choose a level to load.
- Most levels have 7 configuration buttons that can be found nearby (see below).
- Use the Objectives key (F1 by default) to start a cutscene.
- Use the same key again to freeze and exit a cutscene.
- Use the wall-mounted phone in each level to load a different one.

CONFIG BUTTONS:
1. [Reset Scene] Reloads the level (for cleaning up decals, glitched objects, etc.).
2. [Player Visibility] Toggles player visibility, for both gameplay and cutscenes. Note that this affects your shadow, but not that of any unholstered weapons. On by default.
3. [Traffic] Toggles any vehicle and pedestrian traffic in the level. On by default.
4. [Police] Toggles any police presence in the level. Off by default (and not currently implemented).
5. [Cutscene Car Function] Toggles the functionality of any 'cutscene-only' cars, for use afterwards. Note that the toggle setting applies to the *next* time a cutscene is run. Off by default.
6. [Particles] Toggles the continuation of any particle effects (smoke, gunfire, etc.) after a cutscene is exited. Note that while some particles loop indefinitely, others play once and then disappear. Off by default.
7. [The Palermo Clubbing] Clears the player's inventory, and randomly generates one of two possible weapon sets (melee & explosive, or firearm).

KNOWN ISSUES:
- {General} Deactivated peds are invisible but keep their collisions and interactivity
- {General} Phone panel mission list can display in the wrong order
- {General} Unfinished/non-functional buttons (most levels) and missing buttons (01a)
- {Main Menu} Projector SFX starts at profile selection stage (before model anim can)
- {Main Menu} Projector SFX can drop out when returning from certain menus
- {01a} Starting a cutscene with player in a cutscene car produces a crash
- {08c} Particles deactivate when cutscene is unloaded, regardless of button config (FX button has been temporarily disabled)
- {13b} Starting a cutscene with player in a cutscene car produces a crash
- {13b} The restaurant front door can be walked through
- {15g} Lowrider hydraulics on Tom's car when CS begins
- {15g} Distant scenery pop-in with no cache/occluder changes
- {15g} Obvious seams on human anim changes during CS
- {20b} Particles remain active when cutscene is unloaded, regardless of button config (FX button has been temporarily disabled)

NOTES:
- You can start/stop a cutscene at will, but it will always restart from the beginning (no way around this, sorry).
- Sadly, particle effects cannot be frozen in the same way as the rest of the scene. _:(_
- All button configurations will revert to their defaults after a level change or reload (this is to synchronise their function across levels).
- This was designed to be run in 16:9 without the Widescreen Fix. Running it with the fix applied (or in 4:3) will work, but menu text will extend beyond menu backgrounds.
- Let me know of any undocumented bugs, thanks for testing and back-up your files & savegames!

![Game 2023-02-28 10-48-24-55](https://user-images.githubusercontent.com/111624709/221832453-0e1536d7-d813-4815-8f5c-8da0c04420d0.png)

~ AsaSK (thenameasaisnotavailable)
