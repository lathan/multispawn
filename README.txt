multispawn mod for minetest

This mod allows to define many named spawns through ingame formspec gui. To be allowed
to manage spawns, you need spawn_admin privs. This mod save its settings into world directory,
to the file spawn.conf.

Spawns can be added/removed/edited without server restart.

This mod needs 0.4.8 or some latest git versions of 0.4.7

Commands:

/spawnset
Create spawn

/spawnremove <spawnid|spawnnum>
Remove spawn

/spawnedit <spawnid|spawnnum>
Edit spawn

/spawndefault <spawnid|spawnnum>
Set this spawn as default (New players and respawned dead players will be spawned here)

/spawnnear (playername)
Write name of (yours or playernames) nearest spawn

/spawn [spawnname|spawnid]
Spawns you to nearest/specified spawn

/spawnlist
list all available spawns

Credits:
Thanks to fairiestoy and Ritchie for suggestions, advices and testing.

Licence: WTFPL

Full licence text:

        DO WHAT THE FUCK YOU WANT TO PUBLIC LICENSE
                    Version 2, December 2004

 Copyright (C) 2004 Sam Hocevar <sam@hocevar.net>

 Everyone is permitted to copy and distribute verbatim or modified
 copies of this license document, and changing it is allowed as long
 as the name is changed.

            DO WHAT THE FUCK YOU WANT TO PUBLIC LICENSE
   TERMS AND CONDITIONS FOR COPYING, DISTRIBUTION AND MODIFICATION

  0. You just DO WHAT THE FUCK YOU WANT TO.