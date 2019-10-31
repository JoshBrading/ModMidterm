# ModMidterm
Quake 4 Arcade is a mod for Quake 4 that introduces increased enemy spawns, more powerful weapons, a shop, and auto turrets.

## Weapon Modifications
All hitscan weapons now have a chance of spawning explosive barrels.

Weapon  						| Modifications
------------------- | -------------------
Blaster  						| Shoots projectiles with single clicks, charged clicks now shoot 5 projectiles with larger spread
Dark Matter Gun  		| Shoots 5 projectiles with massive spread (Not recommended for indoor use)
Grenade Launcher 		| Shoots 2 projectiles with a slight increase in spread
Hyper Blaster  			| Increased fire rate and reduced ammo clip
Lightning Gun  			| Slowed the fire rate slightly
Machinegun  				| Has a chance of firing an insta kill round in exchange of 10 bullets or the remainder of the clip
Nail Gun  					| Now acts as a slow firing auto shotgun
Railgun  						| 3 shot burst
Rocket Launcher  		| Shoots 3 projectiles and has a larger spread
Shotgun  						| Acts a double barrel shotgun

## Auto Turrets
Converted these enemies to friendly auto turrets.
- monster_sentry
- monster_turret
- monster_turret_flying
- monster_convoy_ground (Rolls around a lot but does actually open up to an auto turret on larger maps)
- monster_strogg_hover
## Shop Menu
Players earn $250 per kill.  

| Bind 					| Cost 						| Item 					 | Description	 										|
| :---:         | ---:    		  	| :---					 | :---														 	|
| F1  					| $1,000     			| Random Weapon  | Gives the player a random weapon |
| F2  					| $3,000     			| Random Turret  | Gives the player a random turret |
| F3  					| $1,000     			| Max Health	   | Gives the player max health			|
| F5  					| $10,000     		| Max Ammo	  	 | Gives the player max ammo 				|

## Commands
Command  						| Description
:------------------ | :---
RandomTurret help  	| Prints to the command line how to spawn friendly turrets with a command
RandomTurret name  	| Spawns "name" auto turret, name can be replaced with  "monster_sentry", "monster_turret_flying", "monster_convoy_ground", "monster_strogg_hover", or "monster_turret"
GiveMoney						| Adds $999,999 to the players bank

## Deliverables
- Shoot enemies to earn points
- Add 5 different auto turrets
- Improve each weapon
- Increase number of enemies

## Testing Features
Shop menu will not work without the proper binds set in Quake4Config.cfg, the binds can be found in the file above.  
Weapon modifications will also not work without using the provided pak999.pk4.

- Increased enemy spawns can be tested by loading the first map, "airdefence1.map"
- Weapon mods can be tested with the "give all" command
- Auto turrets can be tested with the "RandomTurret <name>" command
- Points for killing enemies can be tested by killing enmies and obvserving the objective menu
- Buying items can be tested with the GiveMoney command and clicking the binds
