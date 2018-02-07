# CubeEngine - Travel
Travel anywhere!

## Features:
 - Home teleport points (owned by players)
 - Warp teleport points (global)
 - Multiple homes per player
 - Invitations

## Commands:

| Command | Description | Permission<br>`cubeengine.travel.command.<perm>` |
| --- | --- | --- |
| [*home*](#home) | Teleport to your home | `home` |
| [**home**&nbsp;*clear*](#homeclear) | Clear all homes [of a player] | `home.clear.use` |
| [**home**&nbsp;*greeting*](#homegreeting) | Set the welcome message of homes | `home.greeting.use` |
| [**home**&nbsp;*ilist*](#homeilist) | List all players invited to your homes | `home.ilist.use` |
| [**home**&nbsp;*invite*](#homeinvite) | Invite a user to one of your homes | `home.invite.use` |
| [**home**&nbsp;*list*](#homelist) | Lists homes a player can access | `home.list.use` |
| [**home**&nbsp;*move*](#homemove) | Move a home | `home.move.use` |
| [**home**&nbsp;*purge*](#homepurge) | Removes all homes in a world | `home.purge.use` |
| [**home**&nbsp;*remove*](#homeremove) | Remove a home | `home.remove.use` |
| [**home**&nbsp;*rename*](#homerename) | Rename a home | `home.rename.use` |
| [**home**&nbsp;*set*](#homeset) | Set your home | `home.set.use` |
| [**home**&nbsp;*tp*](#hometp) | Teleport to a home | `home.tp.use` |
| [**home**&nbsp;*unInvite*](#homeuninvite) | Uninvite a player from one of your homes | `home.uninvite.use` |
| [*warp*](#warp) | Teleport to a warp | `warp` |
| [**warp**&nbsp;*clear*](#warpclear) | Clear all warps [of a player] | `warp.clear.use` |
| [**warp**&nbsp;*create*](#warpcreate) | Create a warp | `warp.create.use` |
| [**warp**&nbsp;*greeting*](#warpgreeting) | Set the welcome message of warps | `warp.greeting.use` |
| [**warp**&nbsp;*list*](#warplist) | List warps of a player | `warp.list.use` |
| [**warp**&nbsp;*move*](#warpmove) | Move a warp | `warp.move.use` |
| [**warp**&nbsp;*remove*](#warpremove) | Remove a warp | `warp.remove.use` |
| [**warp**&nbsp;*rename*](#warprename) | Rename a warp | `warp.rename.use` |
| [**warp**&nbsp;*tp*](#warptp) | Teleport to a warp | `warp.tp.use` |

#### home  
Teleport to your home  
**Usage:** `home <command>`  
**Permission:** `cubeengine.travel.command.home`  
**SubCommands:** `clear` `greeting` `ilist` `invite` `list` `move` `purge` `remove` `rename` `set` `tp` `unInvite`  

#### home&nbsp;clear  
Clear all homes [of a player]  
**Usage:** `home clear [owner] [-selection]`  
**Alias:** `/clearhomes`  
**Permission:** `cubeengine.travel.command.home.clear.use`  
  

#### home&nbsp;greeting  
Set the welcome message of homes  
**Usage:** `home greeting <home> [welcome message] [owner <owner>] [-append]`  
**Alias:** `setgreeting` `setwelcome` `setwelcomemsg`  
**Permission:** `cubeengine.travel.command.home.greeting.use`  
  

#### home&nbsp;ilist  
List all players invited to your homes  
**Usage:** `home ilist <owner>`  
**Alias:** `invited`  
**Permission:** `cubeengine.travel.command.home.ilist.use`  
  

#### home&nbsp;invite  
Invite a user to one of your homes  
**Usage:** `home invite <player> [home]`  
**Permission:** `cubeengine.travel.command.home.invite.use`  
  

#### home&nbsp;list  
Lists homes a player can access  
**Usage:** `home list <owner> [-owned] [-invited]`  
**Alias:** `listhomes` `/listhomes` `/homes`  
**Permission:** `cubeengine.travel.command.home.list.use`  
  

#### home&nbsp;move  
Move a home  
**Usage:** `home move [name] <owner>`  
**Alias:** `replace`  
**Permission:** `cubeengine.travel.command.home.move.use`  
  

#### home&nbsp;purge  
Removes all homes in a world  
**Usage:** `home purge <world>`  
**Alias:** `/purgehomes`  
**Permission:** `cubeengine.travel.command.home.purge.use`  
  

#### home&nbsp;remove  
Remove a home  
**Usage:** `home remove [name] [owner]`  
**Alias:** `delete` `rem` `del` `/remhome` `/removehome` `/delhome` `/deletehome`  
**Permission:** `cubeengine.travel.command.home.remove.use`  
  

#### home&nbsp;rename  
Rename a home  
**Usage:** `home rename <home> <new name> [owner]`  
**Permission:** `cubeengine.travel.command.home.rename.use`  
  

#### home&nbsp;set  
Set your home  
**Usage:** `home set [name]`  
**Alias:** `create` `sethome` `createhome` `/sethome`  
**Permission:** `cubeengine.travel.command.home.set.use`  
  

#### home&nbsp;tp  
Teleport to a home  
**Usage:** `home tp [home] <owner>`  
**Permission:** `cubeengine.travel.command.home.tp.use`  
  

#### home&nbsp;unInvite  
Uninvite a player from one of your homes  
**Usage:** `home unInvite <player> [home]`  
**Permission:** `cubeengine.travel.command.home.uninvite.use`  
  

#### warp  
Teleport to a warp  
**Usage:** `warp <command>`  
**Permission:** `cubeengine.travel.command.warp`  
**SubCommands:** `clear` `create` `greeting` `list` `move` `remove` `rename` `tp`  

#### warp&nbsp;clear  
Clear all warps [of a player]  
**Usage:** `warp clear [owner]`  
**Alias:** `/clearwarps`  
**Permission:** `cubeengine.travel.command.warp.clear.use`  
  

#### warp&nbsp;create  
Create a warp  
**Usage:** `warp create <name>`  
**Alias:** `make` `/createwarp` `/mkwarp` `/makewarp`  
**Permission:** `cubeengine.travel.command.warp.create.use`  
  

#### warp&nbsp;greeting  
Set the welcome message of warps  
**Usage:** `warp greeting <warp> [welcome message] [-append]`  
**Alias:** `setgreeting` `setwelcome` `setwelcomemsg`  
**Permission:** `cubeengine.travel.command.warp.greeting.use`  
  

#### warp&nbsp;list  
List warps of a player  
**Usage:** `warp list [owner]`  
**Permission:** `cubeengine.travel.command.warp.list.use`  
  

#### warp&nbsp;move  
Move a warp  
**Usage:** `warp move <warp>`  
**Permission:** `cubeengine.travel.command.warp.move.use`  
  

#### warp&nbsp;remove  
Remove a warp  
**Usage:** `warp remove <warp>`  
**Alias:** `delete` `/removewarp` `/deletewarp` `/delwarp` `/remwarp`  
**Permission:** `cubeengine.travel.command.warp.remove.use`  
  

#### warp&nbsp;rename  
Rename a warp  
**Usage:** `warp rename <warp> <new name>`  
**Permission:** `cubeengine.travel.command.warp.rename.use`  
  

#### warp&nbsp;tp  
Teleport to a warp  
**Usage:** `warp tp <warp>`  
**Permission:** `cubeengine.travel.command.warp.tp.use`  
  

## Additional Permissions:

| Permission | Description |
| --- | --- |
| `cubeengine.travel` | Base Permission for Travel |
| `cubeengine.travel.command` | Allows using all commands of Travel |
| `cubeengine.travel.command.home.list.other` |  |
| `cubeengine.travel.command.home.move.other` |  |
| `cubeengine.travel.command.home.remove.other` |  |
| `cubeengine.travel.command.home.rename.other` |  |
| `cubeengine.travel.command.home.set.more` |  |
| `cubeengine.travel.command.home.tp.other` |  |
| `cubeengine.travel.command.warp.list.other` |  |
| `cubeengine.travel.command.warp.move.other` |  |
| `cubeengine.travel.command.warp.remove.other` |  |
| `cubeengine.travel.command.warp.rename.other` |  |
| `cubeengine.travel.command.warp.tp.other` |  |
