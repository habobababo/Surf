SURF
===============


**SURF** h*** s*** its the Counter-Strike: Source Surfstyle for Garry's Mod!



----------
#Developer documentation
-------------
#HOOKS
Serverside hooks:
>**Surf_PlayerLoadOut** Calls the loadout of the returned player || returns ply<br>
**Surf_NewRound** Calls when the new round starts<br>
**Surf_RoundEnd** Calls the roundend || returns winner as int<br>
**Surf_FastestPlayer** Calls with roundend|| returns fastest ply on map


Clientside hooks:
>

Shared hooks:

>**Surf_Initialize** Calls when the gamemode is initialized<br>

#FUNCTIONS:
**SHARED:**
>**PLAYER:IsGhost()** Returns true or false (!redie)<br>

SERVER:
>**PLAYER:LoadOut()** Forces the LoadOut on ply<br>
**PLAYER:ResetStats()** Sets Kills and Deaths to 0<br>
**PLAYER:ToggleGhost()** Toggles between Ghost and normal, does not revive!<br>
**PLAYER:RespawnGhost()** Use :Spawn() on Ghost, teleports to spawn<br>
**PLAYER:SendTopSpeed()** Sends topspeed to client<br>


----------
#Configuration
----------
### Concommands for clients<br>
<i class="icon-th-list">Admin concommands:
>**surf_debug** <toggle> Shows coordinates onscreen<br>
**surf_items** opens the menu to place permanent weapons<br>
**surf_restartround** restarts the round<br>
**surf_save** saves the permanent weapons after they are placed

User concommands
>**surf_teamchange** Opens F1 menu, the team choose menu.<br>
**Surf_DropWeapon** Drops the current weapon.<br>
**motd** or **surf_motd** Shows message of the day




----------



----------
powered by ![cc](http://37.228.134.43/files/files/logos/Logo/128x128_grey.png) [Core-Community.de](http://core-community.de/)
