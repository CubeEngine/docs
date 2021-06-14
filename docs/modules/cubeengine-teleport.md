# CubeEngine - Teleport
Basic Teleportation

## Features:
 - Various teleport commands
 - Safe teleporting to prevent teleport related deaths
 - Unsafe teleporting for exact teleport destinations

## Commands:

| Command | Description | Permission<br>`cubeengine.teleport.command.<perm>` |
| --- | --- | --- |
| [*ascend*](#ascend) | Teleports you to the next safe spot upwards. | `ascend.use` |
| [*back*](#back) | Teleports you to your last location | `back.use` |
| [*descend*](#descend) | Teleports you to the next safe spot downwards. | `descend.use` |
| [*jumpTo*](#jumpto) | Jumps to the position you are looking at. | `jumpto.use` |
| [*place*](#place) | Places a player to the position you are looking at. | `place.use` |
| [*setSpawn*](#setspawn) | Changes the global respawnpoint | `setspawn.use` |
| [*spawn*](#spawn) | Teleports a player to spawn | `spawn.use` |
| [*spawnAll*](#spawnall) | Teleports all players to spawn | `spawnall.use` |
| [*swap*](#swap) | Swaps you and another players position | `swap.use` |
| [*through*](#through) | Jumps to the position you are looking at. | `through.use` |
| [*top*](#top) | Teleports to the highest point at your position. | `top.use` |
| [*tp*](#tp) | Teleport directly to a player. | `tp.use` |
| [*tpa*](#tpa) | Requests to teleport to a player. | `tpa.use` |
| [*tpaccept*](#tpaccept) | Accepts any pending teleport request. | `tpaccept.use` |
| [*tpahere*](#tpahere) | Requests to teleport a player to you. | `tpahere.use` |
| [*tpall*](#tpall) | Teleports everyone directly to a player. | `tpall.use` |
| [*tpdeny*](#tpdeny) | Denies any pending teleport request. | `tpdeny.use` |
| [*tphere*](#tphere) | Teleport a player directly to you. | `tphere.use` |
| [*tphereall*](#tphereall) | Teleport every player directly to you. | `tphereall.use` |
| [*tppos*](#tppos) | Direct teleport to a coordinate. | `tppos.use` |
| [*tpworld*](#tpworld) | Teleports you to the spawn of given world | `tpworld.use` |
| [*up*](#up) | Teleports you X amount of blocks into the air and puts a glass block beneath you. | `up.use` |

#### ascend  
Teleports you to the next safe spot upwards.  
**Usage:** `ascend `  
**Permission:** `cubeengine.teleport.command.ascend.use`  
  

#### back  
Teleports you to your last location  
**Usage:** `back [-unsafe]`  
**Permission:** `cubeengine.teleport.command.back.use`  
  

#### descend  
Teleports you to the next safe spot downwards.  
**Usage:** `descend `  
**Permission:** `cubeengine.teleport.command.descend.use`  
  

#### jumpTo  
Jumps to the position you are looking at.  
**Usage:** `jumpTo `  
**Alias:** `jump` `j`  
**Permission:** `cubeengine.teleport.command.jumpto.use`  
  

#### place  
Places a player to the position you are looking at.  
**Usage:** `place <player>`  
**Alias:** `put`  
**Permission:** `cubeengine.teleport.command.place.use`  
  

#### setSpawn  
Changes the global respawnpoint  
**Usage:** `setSpawn <world> [x] [y] [z]`  
**Permission:** `cubeengine.teleport.command.setspawn.use`  
  

#### spawn  
Teleports a player to spawn  
**Usage:** `spawn <player> [world] [-force]`  
**Permission:** `cubeengine.teleport.command.spawn.use`  
  

#### spawnAll  
Teleports all players to spawn  
**Usage:** `spawnAll <world> [-force]`  
**Permission:** `cubeengine.teleport.command.spawnall.use`  
  

#### swap  
Swaps you and another players position  
**Usage:** `swap <player> <player>`  
**Permission:** `cubeengine.teleport.command.swap.use`  
  

#### through  
Jumps to the position you are looking at.  
**Usage:** `through `  
**Alias:** `thru`  
**Permission:** `cubeengine.teleport.command.through.use`  
  

#### top  
Teleports to the highest point at your position.  
**Usage:** `top `  
**Permission:** `cubeengine.teleport.command.top.use`  
  

#### tp  
Teleport directly to a player.  
**Usage:** `tp <player> [target] [-force]`  
**Permission:** `cubeengine.teleport.command.tp.use`  
  

#### tpa  
Requests to teleport to a player.  
**Usage:** `tpa <player>`  
**Permission:** `cubeengine.teleport.command.tpa.use`  
  

#### tpaccept  
Accepts any pending teleport request.  
**Usage:** `tpaccept `  
**Alias:** `tpac`  
**Permission:** `cubeengine.teleport.command.tpaccept.use`  
  

#### tpahere  
Requests to teleport a player to you.  
**Usage:** `tpahere <player>`  
**Permission:** `cubeengine.teleport.command.tpahere.use`  
  

#### tpall  
Teleports everyone directly to a player.  
**Usage:** `tpall <player> [-force]`  
**Permission:** `cubeengine.teleport.command.tpall.use`  
  

#### tpdeny  
Denies any pending teleport request.  
**Usage:** `tpdeny `  
**Permission:** `cubeengine.teleport.command.tpdeny.use`  
  

#### tphere  
Teleport a player directly to you.  
**Usage:** `tphere <player> [-force]`  
**Permission:** `cubeengine.teleport.command.tphere.use`  
  

#### tphereall  
Teleport every player directly to you.  
**Usage:** `tphereall [-force]`  
**Permission:** `cubeengine.teleport.command.tphereall.use`  
  

#### tppos  
Direct teleport to a coordinate.  
**Usage:** `tppos <x> <y> <z> [world <world>] [player <player>] [-unsafe]`  
**Permission:** `cubeengine.teleport.command.tppos.use`  
  

#### tpworld  
Teleports you to the spawn of given world  
**Usage:** `tpworld <world>`  
**Permission:** `cubeengine.teleport.command.tpworld.use`  
  

#### up  
Teleports you X amount of blocks into the air and puts a glass block beneath you.  
**Usage:** `up <height>`  
**Permission:** `cubeengine.teleport.command.up.use`  
  

## Permissions:

| Permission | Description |
| --- | --- |
| `cubeengine.teleport` | Base Permission for Teleport |
| `cubeengine.teleport.command` | Allows using all commands of Teleport |
| `cubeengine.teleport.command.back.ondeath` | Allows using the back command after dieing (if this is not set you won't be able to tp back to your deathpoint) |
| `cubeengine.teleport.command.spawn.force` | Allows teleporting a player to spawn even if the player has the prevent permission |
| `cubeengine.teleport.command.spawn.prevent` | Prevents from being teleported to spawn by someone else |
| `cubeengine.teleport.command.tp.force` | Ignores all prevent permissions when using the /tp command |
| `cubeengine.teleport.command.tp.other` | Allows teleporting another player |
| `cubeengine.teleport.command.tpall.force` | Ignores all prevent permissions when using the /tpall command |
| `cubeengine.teleport.command.tphere.force` | Ignores all prevent permissions when using the /tphere command |
| `cubeengine.teleport.command.tphereall.force` | Ignores all prevent permissions when using the /tphereall command |
| `cubeengine.teleport.command.tppos.unsafe` |  |
| `cubeengine.teleport.compass.jumpto.left` |  |
| `cubeengine.teleport.compass.jumpto.right` |  |
| `cubeengine.teleport.teleport.prevent.tp` | Prevents from being teleported by someone else |
| `cubeengine.teleport.teleport.prevent.tpto` | Prevents from teleporting to you |
