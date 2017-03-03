Star Genesis 00 overrides:
rpgRestorePlayer
dsShipInterior
dsCargoHold
dsAbandonedShip
intBarricadeUse (so you can spawn multiple barricades)
stBarricade1 (so turrets can have noFriendlyFire with them)
pwSustain so it doesn't show up in the game

CHANGELOG:
-fixed the bug where scuttle ships being destroyed before scuttling means the wreck is marked forever as 'being scuttled'

MODDING NOTES:
default="1" means that if you press escape then that action is automatically taken. I don't know if you can stack actions that way but yeah.

Some gameplay mechanics:

NOTES:
set firerate adj to 10 (so they fire at the real rate of their weapons)
doubled scrap income as a result

Scrap
Scrap is the main currency in the game. It is used to spawn stations and is only earned when a wreck is scuttled by the Starbase. The Starbase's scuttle radius is around 60 light seconds, so the wrecks in the asteroid belt from the last war are unreachable.

Spawning turrets
Press [U] to choose the turret selection. At this point there are three turrets to spawn:
Laser Defender
Laser Defenders cost 150 scrap.
Missile Defender
Laser Defenders cost 250 scrap.
Hangar Bay
Laser Defenders cost 500 scrap.
fighters cost 2 scrap now

The main playership right now is supposed to be a carrier but I can't do carrier mechanics yet. It's got an omni sunflare, and type four stealth missiles. I'll fix up the playership later.

Also right now there are 11 waves, and one game lasts ~12 minutes if you can get through all of them.

Upgrades:
I finally made a decent upgrading system!
Ships upgrade the turrets they spawn.
Right now, here are the trees:
The Durkham can upgrade these turrets:
Laser turret
Missile turret
Hangar Bay
The Opinren can upgrade these turrets:
Laser turret
[mining rig]
[solar collector]
The mining rig and solar collector will have updates, but when I update this at a later time.

Fleet Mechanics
Capital Ships
Right now there are three capital ships in the game, two starter ones and one that has to be constructed in-game.
The Durkham is a starting carrier. It makes most of the offensive turrets in the game and is good at taking down gunships.
The Opinren is a starting ship that makes most of the economy stations.
The Aciman is a capital ship counter, and can take down enemy capital ships with ease. It may have trouble with enemy gunships though.

If you use the [I]nvoke screen you can see all of your available capital ships, and you can invoke the right key to change ships to the right capital ship.
If your capital ship gets destroyed you will be given a second chance and spawn in an escape pod. You can then dock to another capship (or construct one) and pilot that.
If you die in the escape pod it's game over.

Economy 
The Opinren makes mining rigs and solar collectors (but don't make solar collectors! They don't do anything yet!)
The mining rig provides a scuttle radius of 60 light seconds, so anything destroyed within 60 ls of the mining rig will be scuttled.
It also generates scrap every 30 seconds, and gives 10 scrap for every asteroid in a 50 light second radius. You also can't stack mining rigs (but I may change this later.)

Multiverse
If you'd like, you can comment with your multiverse nick and I can add you as a beta tester and this will auto update (and that way you don't have to download through Xelerus.)
Notes:
-if you upgrade everything the upgrade screen goes wonky. I still have to fix that.
-laser turrets are OP at the moment, and I still have to balance things out.
-upgrade costs are also kinda iffy, and I have to change them later.

Refueling:
Refueling is also a hassle. I'll make it cost scrap sometime soon, and allow you to install some kind of solar panel array, but right now just dock with the Starbase and refuel for free.

Barricades don't count as taking up location in terms of station placement.