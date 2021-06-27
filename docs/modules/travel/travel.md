# CubeEngine - Travel
Travel anywhere!

## Features:
 - Home teleport points (owned by players)
 - Warp teleport points (global)
 - Multiple homes per player
 - Invitations

## Dependencies:
 `cubeengine-zoned` (optional)

## Commands:

| Command | Description | Permission<br>`cubeengine.travel.command.<perm>` |
| --- | --- | --- |
| [*home*](#home) | Teleport to your home |  |
| [**home**&nbsp;*clear*](#homeclear) | Clear all homes [of a player] | `home.clear.use` |
| [**home**&nbsp;*del*](#homedel) | Remove a home | `home.remove.use` |
| [**home**&nbsp;*invite*](#homeinvite) | Invite a user to one of your homes | `home.invite.use` |
| [**home**&nbsp;*invited*](#homeinvited) | List all players invited to your homes | `home.ilist.use` |
| [**home**&nbsp;*listhomes*](#homelisthomes) | Lists homes a player can access | `home.list.use` |
| [**home**&nbsp;*move*](#homemove) | Move a home | `home.move.use` |
| [**home**&nbsp;*purge*](#homepurge) | Removes all homes in a world | `home.purge.use` |
| [**home**&nbsp;*rename*](#homerename) | Rename a home | `home.rename.use` |
| [**home**&nbsp;*set*](#homeset) | Set your home | `home.set.use` |
| [**home**&nbsp;*setwelcome*](#homesetwelcome) | Set the welcome message of homes | `home.greeting.use` |
| [**home**&nbsp;*tp*](#hometp) | Teleport to a home | `home.tp.use` |
| [**home**&nbsp;*uninvite*](#homeuninvite) | Uninvite a player from one of your homes | `home.unInvite.use` |
| [*warp*](#warp) | Teleport to a warp |  |
| [**warp**&nbsp;*clear*](#warpclear) | Clear all warps [of a player] | `warp.clear.use` |
| [**warp**&nbsp;*create*](#warpcreate) | Create a warp | `warp.create.use` |
| [**warp**&nbsp;*delete*](#warpdelete) | Remove a warp | `warp.remove.use` |
| [**warp**&nbsp;*list*](#warplist) | List warps of a player | `warp.list.use` |
| [**warp**&nbsp;*move*](#warpmove) | Move a warp | `warp.move.use` |
| [**warp**&nbsp;*rename*](#warprename) | Rename a warp | `warp.rename.use` |
| [**warp**&nbsp;*setwelcome*](#warpsetwelcome) | Set the welcome message of warps | `warp.greeting.use` |
| [**warp**&nbsp;*tp*](#warptp) | Teleport to a warp | `warp.tp.use` |

#### home  
Teleport to your home  
**Usage:** `home [home]`  
**SubCommands:** `clear` `del` `invite` `invited` `listhomes` `move` `purge` `rename` `set` `setwelcome` `tp` `uninvite`  

#### home&nbsp;clear  
Clear all homes [of a player]  
**Usage:** `home clear [owner][?]`  
**Permission:** `cubeengine.travel.command.home.clear.use`  
  

#### home&nbsp;del  
Remove a home  
**Usage:** `home del [name] [owner]`  
**Alias:** `rem` `delete` `remove`  
**Permission:** `cubeengine.travel.command.home.remove.use`  
  

#### home&nbsp;invite  
Invite a user to one of your homes  
**Usage:** `home invite <player> [home]`  
**Permission:** `cubeengine.travel.command.home.invite.use`  
  

#### home&nbsp;invited  
List all players invited to your homes  
**Usage:** `home invited [owner]`  
**Alias:** `ilist`  
**Permission:** `cubeengine.travel.command.home.ilist.use`  
  

#### home&nbsp;listhomes  
Lists homes a player can access  
**Usage:** `home listhomes [owner][?][?]`  
**Alias:** `list`  
**Permission:** `cubeengine.travel.command.home.list.use`  
  

#### home&nbsp;move  
Move a home  
**Usage:** `home move [name] [owner]`  
**Alias:** `replace`  
**Permission:** `cubeengine.travel.command.home.move.use`  
  

#### home&nbsp;purge  
Removes all homes in a world  
**Usage:** `home purge <world>`  
**Permission:** `cubeengine.travel.command.home.purge.use`  
  

#### home&nbsp;rename  
Rename a home  
**Usage:** `home rename <home> <new name> [owner]`  
**Permission:** `cubeengine.travel.command.home.rename.use`  
  

#### home&nbsp;set  
Set your home  
**Usage:** `home set [name]`  
**Alias:** `sethome` `create` `createhome`  
**Permission:** `cubeengine.travel.command.home.set.use`  
  

#### home&nbsp;setwelcome  
Set the welcome message of homes  
**Usage:** `home setwelcome <home> welcome message[?][?]`  
**Alias:** `setwelcomemsg` `greeting` `setgreeting`  
**Permission:** `cubeengine.travel.command.home.greeting.use`  
  

#### home&nbsp;tp  
Teleport to a home  
**Usage:** `home tp [home] [owner]`  
**Permission:** `cubeengine.travel.command.home.tp.use`  
  

#### home&nbsp;uninvite  
Uninvite a player from one of your homes  
**Usage:** `home uninvite <player> [home]`  
**Permission:** `cubeengine.travel.command.home.unInvite.use`  
  

#### warp  
Teleport to a warp  
**Usage:** `warp <warp>`  
**SubCommands:** `clear` `create` `delete` `list` `move` `rename` `setwelcome` `tp`  

#### warp&nbsp;clear  
Clear all warps [of a player]  
**Usage:** `warp clear [owner]`  
**Permission:** `cubeengine.travel.command.warp.clear.use`  
  

#### warp&nbsp;create  
Create a warp  
**Usage:** `warp create <name>`  
**Alias:** `make`  
**Permission:** `cubeengine.travel.command.warp.create.use`  
  

#### warp&nbsp;delete  
Remove a warp  
**Usage:** `warp delete <warp>`  
**Alias:** `remove`  
**Permission:** `cubeengine.travel.command.warp.remove.use`  
  

#### warp&nbsp;list  
List warps of a player  
**Usage:** `warp list [owner]`  
**Permission:** `cubeengine.travel.command.warp.list.use`  
  

#### warp&nbsp;move  
Move a warp  
**Usage:** `warp move <warp>`  
**Permission:** `cubeengine.travel.command.warp.move.use`  
  

#### warp&nbsp;rename  
Rename a warp  
**Usage:** `warp rename <warp> <new name>`  
**Permission:** `cubeengine.travel.command.warp.rename.use`  
  

#### warp&nbsp;setwelcome  
Set the welcome message of warps  
**Usage:** `warp setwelcome <warp> welcome message[?]`  
**Alias:** `setwelcomemsg` `greeting` `setgreeting`  
**Permission:** `cubeengine.travel.command.warp.greeting.use`  
  

#### warp&nbsp;tp  
Teleport to a warp  
**Usage:** `warp tp <warp>`  
**Permission:** `cubeengine.travel.command.warp.tp.use`  
  

## Permissions:

| Permission | Description |
| --- | --- |
| `cubeengine.travel` | Base Permission for Travel |
| `cubeengine.travel.command.home.list.other` | Lets you list other player homes |
| `cubeengine.travel.command.home.move.other` | Lets you move other player homes |
| `cubeengine.travel.command.home.remove.other` | Lets you remove other player homes |
| `cubeengine.travel.command.home.rename.other` | Lets you rename other player homes |
| `cubeengine.travel.command.home.set.more` | Lets you set more then the configured max. homes |
| `cubeengine.travel.command.home.tp.other` | Lets you tp to other player homes |
| `cubeengine.travel.command.warp.list.other` | Lets you list other player warps |
| `cubeengine.travel.command.warp.move.other` | Lets you move other player warps |
| `cubeengine.travel.command.warp.remove.other` | Lets you remove other player warps |
| `cubeengine.travel.command.warp.rename.other` | Lets you rename other player warps |
| `cubeengine.travel.command.warp.tp.other` | Lets you tp to other player warps |
