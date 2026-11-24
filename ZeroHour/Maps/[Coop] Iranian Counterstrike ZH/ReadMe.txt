"Iranian Counterstrike" 
A 3 Player/Skirmish Map for Zero Hour (co-op online mission)
2 human player GLA vs USA AIRF 1 Skirmish Comp and an additional scripted comp.
by El Chapo a.k.a. issy
contact: [email redacted]

Goal:
2 Humans starts with a hand full off units and they need to free the city area behind the bridges.
After that worker will be send to us. There we can build and kill all enemies on map for win.

Setup:
2 Humans start as GLA
1 Comp starts as USA AirF

There is a map.ini with the map. It allows to collect Generals Points for kills on CompEnemy.
That forces you to restart Generals after map transfer. Have all player the map in the second run, it works fine.

Features List:
===-Player Civilian-===

Script Folder: 01 Check Setup Faction GLA vs USA AirForceGeneral
- Failsafe = Players can start from each slot in Lobby, but they must have the correct armies and startpositions chosen in Lobby.

Script Folder: 02 Relationships
- Relationships to additionally Civilian Players (CompEnemy and CompFriend)

Script Folder: 03 Map Setup
- Humans have no Sneak-Attack and no Rebell Ambush Level 3
- Superweapons only for Comps available
- Supplies has modiefied values worth of money
- Unshrouded Waypoints on map for all players (for the waterfalls and Enemy Base)
- Removal Scripts for unnecessary units after Start.

Script Folder: 04 Intro Manager
- Timers for the intro
- Removal Script for Intro Units

Script Folder: 05 Audio
- Playing sounds and Speeches

Script Folder: 06 Briefings
- shows text messages during the game

Script Folder: 07 Camera
- Camera movements
- shrouds map with fog of war after intro

Script Folder: 08 Early Defeat
- Ending the game to own conditions
- Shows related Text messages

The Music scripts are default.. but it starts delayed after intro...

===-Player CompEnemy-===
(Player Civilian in blue)

Script Folder: CE Intro Units
- Intro Units of Player CE and its actions

Script Folder:  CE War Manager
- control scripts for activation of action scripts and script folders
- 3 main trigger activating the following actions

Script Folder:  CE Basic Setup
- Money of Player CE
- Full Science availability
- All Upgrades are bought
- Scoring on for CE ( but it is not necessary here actually)

Script Folder: CE Strategy Center
- It chooses randomly a tactic on build event

Script Folder: CE-PowerPlants Manager
- linked scripts for build event of power plants, it upgrades the powerplants

Script Folder: CE-Power Free Energy
- exists a power plant usa a chineese will be spawned too (outside the map), and with killing powerplants they disappear also. Just extra power)

Script Folder: CE Garrison Buildings
- Spawn of units at waypoints and garrision certain buildings then

Use of Special Powers:
- Spydrones
- Paradrops
- A10 Strikes
- Spectre Gunship
- CarpetBomb
- Daisy Cutter
- MOAB
- Particle Canon

War Production Folders:
3x WarBaracks where units will be spawned if they are not exist anymore
3x WarFactories ...
3x Airfields ...
- spawning of untis in sequences of timers at a waypoint in a special direction
- sequences repeating in randomly times and stops while a production build is dead

===-Player CompFriend-===
(Player Civilian in green)

Script Folder: CF Intro Units
- spawns and moves intro units of player

Script Folder: CF Base Setup
- Money setup of player
- Buys several updates

Script Folder: CF Transfer Manager
- Tigger scripts to activate transfers from Player CF to both human players in 3 steps
- 3 times transfering of units to the player based on startpositions

Skirmish Scripts should be default.

