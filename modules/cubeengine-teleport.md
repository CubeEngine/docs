# CubeEngine - Teleport
Basic Teleportation

## Features:
 - Various teleport commands
 - Safe teleporting to prevent teleport related deaths
 - Unsafe teleporting for exact teleport destinations

## Commands:

| Command | Description | Permission<br>`cubeengine.teleport.command.<perm>` |
| --- | --- | --- |
| [*tpall*](#tpall) | Teleports everyone directly to a player. | `tpall.use` |
| [*back*](#back) | Teleports you to your last location | `back.use` |
| [*tpdeny*](#tpdeny) | Denies any pending teleport request. | `tpdeny.use` |
| [*tphere*](#tphere) | Teleport a player directly to you. | `tphere.use` |
| [*spawnAll*](#spawnall) | Teleports all players to spawn | `spawnall.use` |
| [*descend*](#descend) | Teleports you to the next safe spot downwards. | `descend.use` |
| [*tp*](#tp) | Teleport directly to a player. | `tp.use` |
| [*swap*](#swap) | Swaps you and another players position | `swap.use` |
| [*tphereall*](#tphereall) | Teleport every player directly to you. | `tphereall.use` |
| [*spawn*](#spawn) | Teleports a player to spawn | `spawn.use` |
| [*tppos*](#tppos) | Direct teleport to a coordinate. | `tppos.use` |
| [*jumpTo*](#jumpto) | Jumps to the position you are looking at. | `jumpto.use` |
| [*tpa*](#tpa) | Requests to teleport to a player. | `tpa.use` |
| [*top*](#top) | Teleports to the highest point at your position. | `top.use` |
| [*tpaccept*](#tpaccept) | Accepts any pending teleport request. | `tpaccept.use` |
| [*up*](#up) | Teleports you X amount of blocks into the air and puts a glass block beneath you. | `up.use` |
| [*place*](#place) | Places a player to the position you are looking at. | `place.use` |
| [*ascend*](#ascend) | Teleports you to the next safe spot upwards. | `ascend.use` |
| [*through*](#through) | Jumps to the position you are looking at. | `through.use` |
| [*tpahere*](#tpahere) | Requests to teleport a player to you. | `tpahere.use` |
| [*tpworld*](#tpworld) | Teleports you to the spawn of given world | `tpworld.use` |
| [*setSpawn*](#setspawn) | Changes the global respawnpoint | `setspawn.use` |

#### tpall  
Teleports everyone directly to a player.  
**Usage:** `tpall <player> [-force]`  
**Permission:** `cubeengine.teleport.command.tpall.use`  
  

#### back  
Teleports you to your last location  
**Usage:** `back [-unsafe]`  
**Permission:** `cubeengine.teleport.command.back.use`  
  

#### tpdeny  
Denies any pending teleport request.  
**Usage:** `tpdeny `  
**Permission:** `cubeengine.teleport.command.tpdeny.use`  
  

#### tphere  
Teleport a player directly to you.  
**Usage:** `tphere <player> [-force]`  
**Permission:** `cubeengine.teleport.command.tphere.use`  
  

#### spawnAll  
Teleports all players to spawn  
**Usage:** `spawnAll <world> [-force]`  
**Permission:** `cubeengine.teleport.command.spawnall.use`  
  

#### descend  
Teleports you to the next safe spot downwards.  
**Usage:** `descend `  
**Permission:** `cubeengine.teleport.command.descend.use`  
  

#### tp  
Teleport directly to a player.  
**Usage:** `tp <player> [target] [-force]`  
**Permission:** `cubeengine.teleport.command.tp.use`  
  

#### swap  
Swaps you and another players position  
**Usage:** `swap <player> <player>`  
**Permission:** `cubeengine.teleport.command.swap.use`  
  

#### tphereall  
Teleport every player directly to you.  
**Usage:** `tphereall [-force]`  
**Permission:** `cubeengine.teleport.command.tphereall.use`  
  

#### spawn  
Teleports a player to spawn  
**Usage:** `spawn <player> [world] [-force]`  
**Permission:** `cubeengine.teleport.command.spawn.use`  
  

#### tppos  
Direct teleport to a coordinate.  
**Usage:** `tppos <x> <y> <z> [world <world>] [player <player>] [-unsafe]`  
**Permission:** `cubeengine.teleport.command.tppos.use`  
  

#### jumpTo  
Jumps to the position you are looking at.  
**Usage:** `jumpTo `  
**Alias:** `jump` `j`  
**Permission:** `cubeengine.teleport.command.jumpto.use`  
  

#### tpa  
Requests to teleport to a player.  
**Usage:** `tpa <player>`  
**Permission:** `cubeengine.teleport.command.tpa.use`  
  

#### top  
Teleports to the highest point at your position.  
**Usage:** `top `  
**Permission:** `cubeengine.teleport.command.top.use`  
  

#### tpaccept  
Accepts any pending teleport request.  
**Usage:** `tpaccept `  
**Alias:** `tpac`  
**Permission:** `cubeengine.teleport.command.tpaccept.use`  
  

#### up  
Teleports you X amount of blocks into the air and puts a glass block beneath you.  
**Usage:** `up <height>`  
**Permission:** `cubeengine.teleport.command.up.use`  
  

#### place  
Places a player to the position you are looking at.  
**Usage:** `place <player>`  
**Alias:** `put`  
**Permission:** `cubeengine.teleport.command.place.use`  
  

#### ascend  
Teleports you to the next safe spot upwards.  
**Usage:** `ascend `  
**Permission:** `cubeengine.teleport.command.ascend.use`  
  

#### through  
Jumps to the position you are looking at.  
**Usage:** `through `  
**Alias:** `thru`  
**Permission:** `cubeengine.teleport.command.through.use`  
  

#### tpahere  
Requests to teleport a player to you.  
**Usage:** `tpahere <player>`  
**Permission:** `cubeengine.teleport.command.tpahere.use`  
  

#### tpworld  
Teleports you to the spawn of given world  
**Usage:** `tpworld <world>`  
**Permission:** `cubeengine.teleport.command.tpworld.use`  
  

#### setSpawn  
Changes the global respawnpoint  
**Usage:** `setSpawn <world> [x] [y] [z]`  
**Permission:** `cubeengine.teleport.command.setspawn.use`  
  

## Additional Permissions:

| Permission | Description |
| --- | --- |
| `cubeengine.teleport` | Base Permission for teleport |