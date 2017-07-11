# CubeEngine - Travel
Travel anywhere!
## Commands
| Command | Description | Permission<br>`cubeengine.travel.command.<perm>` |
| --- | --- | --- |
| [*warp*](#warp) | Teleport to a warp | `warp` |
| [**warp** *clear*](#warp-clear) | Clear all warps [of a player] | `warp.clear.use` |
| [**warp** *create*](#warp-create) | Create a warp | `warp.create.use` |
| [**warp** *greeting*](#warp-greeting) | Set the welcome message of warps | `warp.greeting.use` |
| [**warp** *list*](#warp-list) | List warps of a player | `warp.list.use` |
| [**warp** *move*](#warp-move) | Move a warp | `warp.move.use` |
| [**warp** *remove*](#warp-remove) | Remove a warp | `warp.remove.use` |
| [**warp** *rename*](#warp-rename) | Rename a warp | `warp.rename.use` |
| [**warp** *tp*](#warp-tp) | Teleport to a warp | `warp.tp.use` |
| [*home*](#home) | Teleport to your home | `home` |
| [**home** *clear*](#home-clear) | Clear all homes [of a player] | `home.clear.use` |
| [**home** *greeting*](#home-greeting) | Set the welcome message of homes | `home.greeting.use` |
| [**home** *ilist*](#home-ilist) | List all players invited to your homes | `home.ilist.use` |
| [**home** *invite*](#home-invite) | Invite a user to one of your homes | `home.invite.use` |
| [**home** *list*](#home-list) | Lists homes a player can access | `home.list.use` |
| [**home** *move*](#home-move) | Move a home | `home.move.use` |
| [**home** *remove*](#home-remove) | Remove a home | `home.remove.use` |
| [**home** *rename*](#home-rename) | Rename a home | `home.rename.use` |
| [**home** *set*](#home-set) | Set your home | `home.set.use` |
| [**home** *tp*](#home-tp) | Teleport to a home | `home.tp.use` |
| [**home** *unInvite*](#home-uninvite) | Uninvite a player from one of your homes | `home.uninvite.use` |
#### warp  
Teleport to a warp  
**Usage:** `warp <command>`  
**Permission:** `cubeengine.travel.command.warp`  
**SubCommands:** `clear` `create` `greeting` `list` `move` `remove` `rename` `tp`  
#### warp clear  
Clear all warps [of a player]  
**Usage:** `warp clear [owner]`  
**Alias:** `/clearwarps`  
**Permission:** `cubeengine.travel.command.warp.clear.use`  
  
#### warp create  
Create a warp  
**Usage:** `warp create <name>`  
**Alias:** `make` `/createwarp` `/mkwarp` `/makewarp`  
**Permission:** `cubeengine.travel.command.warp.create.use`  
  
#### warp greeting  
Set the welcome message of warps  
**Usage:** `warp greeting <warp> [welcome message] [-append]`  
**Alias:** `setgreeting` `setwelcome` `setwelcomemsg`  
**Permission:** `cubeengine.travel.command.warp.greeting.use`  
  
#### warp list  
List warps of a player  
**Usage:** `warp list [owner]`  
**Permission:** `cubeengine.travel.command.warp.list.use`  
  
#### warp move  
Move a warp  
**Usage:** `warp move <warp>`  
**Permission:** `cubeengine.travel.command.warp.move.use`  
  
#### warp remove  
Remove a warp  
**Usage:** `warp remove <warp>`  
**Alias:** `delete` `/removewarp` `/deletewarp` `/delwarp` `/remwarp`  
**Permission:** `cubeengine.travel.command.warp.remove.use`  
  
#### warp rename  
Rename a warp  
**Usage:** `warp rename <warp> <new name>`  
**Permission:** `cubeengine.travel.command.warp.rename.use`  
  
#### warp tp  
Teleport to a warp  
**Usage:** `warp tp <warp>`  
**Permission:** `cubeengine.travel.command.warp.tp.use`  
  
#### home  
Teleport to your home  
**Usage:** `home <command>`  
**Permission:** `cubeengine.travel.command.home`  
**SubCommands:** `clear` `greeting` `ilist` `invite` `list` `move` `remove` `rename` `set` `tp` `unInvite`  
#### home clear  
Clear all homes [of a player]  
**Usage:** `home clear [owner] [-selection]`  
**Alias:** `/clearhomes`  
**Permission:** `cubeengine.travel.command.home.clear.use`  
  
#### home greeting  
Set the welcome message of homes  
**Usage:** `home greeting <home> [welcome message] [owner <owner>] [-append]`  
**Alias:** `setgreeting` `setwelcome` `setwelcomemsg`  
**Permission:** `cubeengine.travel.command.home.greeting.use`  
  
#### home ilist  
List all players invited to your homes  
**Usage:** `home ilist <owner>`  
**Alias:** `invited`  
**Permission:** `cubeengine.travel.command.home.ilist.use`  
  
#### home invite  
Invite a user to one of your homes  
**Usage:** `home invite <player> [home]`  
**Permission:** `cubeengine.travel.command.home.invite.use`  
  
#### home list  
Lists homes a player can access  
**Usage:** `home list <owner> [-owned] [-invited]`  
**Alias:** `listhomes` `/listhomes` `/homes`  
**Permission:** `cubeengine.travel.command.home.list.use`  
  
#### home move  
Move a home  
**Usage:** `home move [name] <owner>`  
**Alias:** `replace`  
**Permission:** `cubeengine.travel.command.home.move.use`  
  
#### home remove  
Remove a home  
**Usage:** `home remove [name] [owner]`  
**Alias:** `delete` `rem` `del` `/remhome` `/removehome` `/delhome` `/deletehome`  
**Permission:** `cubeengine.travel.command.home.remove.use`  
  
#### home rename  
Rename a home  
**Usage:** `home rename <home> <new name> [owner]`  
**Permission:** `cubeengine.travel.command.home.rename.use`  
  
#### home set  
Set your home  
**Usage:** `home set [name]`  
**Alias:** `create` `sethome` `createhome` `/sethome`  
**Permission:** `cubeengine.travel.command.home.set.use`  
  
#### home tp  
Teleport to a home  
**Usage:** `home tp [home] <owner>`  
**Permission:** `cubeengine.travel.command.home.tp.use`  
  
#### home unInvite  
Uninvite a player from one of your homes  
**Usage:** `home unInvite <player> [home]`  
**Permission:** `cubeengine.travel.command.home.uninvite.use`  
  
## Additional Permissions

| Permission | Description |
| --- | --- |
| `cubeengine.travel` | Base Permission for travel |