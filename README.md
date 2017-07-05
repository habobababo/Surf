SURF
===============


**SURF** h*** s*** its the Counter-Strike: Source Surfstyle for Garry's Mod!



----------
# <i class="icon-file"></i> Developer documentation
-------------
<i class="icon-th-list">Serverside hooks:
>**Surf_PlayerLoadOut** Calls the loadout of the returned player || returns ply<br>
**Surf_NewRound** Calls when the new round starts<br>
**Surf_RoundEnd** Calls the roundend || returns winner as int<br>
**Surf_FastestPlayer** Calls with roundend|| returns fastest ply on map


<i class="icon-user">Clientside hooks:
>

<i class="icon-user"><i class="icon-th-list">Shared hooks:

>**Surf_Initialize** Calls when the gamemode is initialized<br>

*Functions:*
SHARED:
>**PLAYER:IsGhost()** Returns true or false (!redie)<br>

SERVER:
>**PLAYER:LoadOut()** Forces the LoadOut on ply
**PLAYER:ResetStats()** Sets Kills and Deaths to 0
**PLAYER:ToggleGhost()** Toggles between Ghost and normal, does not revive!
**PLAYER:RespawnGhost()** Use :Spawn() on Ghost, teleports to spawn
**PLAYER:SendTopSpeed()** Sends topspeed to client


----------
# <i class="icon-pencil"></i> Configuration
----------
### Concommands for clients<br>
<i class="icon-th-list">Admin concommands:
>**surf_debug** <toggle> Shows coordinates onscreen<br>
**surf_items** opens the menu to place permanent weapons<br>
**surf_restartround** restarts the round<br>
**surf_save** saves the permanent weapons after they are placed

<i class="icon-user">User concommands
>**surf_teamchange** Opens F1 menu, the team choose menu.
**Surf_DropWeapon** Drops the current weapon.
**motd** or **surf_motd** Shows message of the day<br>




----------



----------
powered by ![cc](http://37.228.134.43/files/files/logos/Logo/128x128_grey.png) [Core-Community.de](http://core-community.de/)
