# CubeEngine - Teleport
Basic Teleportation

## Features:
 - Various teleport commands
 - Safe teleporting to prevent teleport related deaths
 - Unsafe teleporting for exact teleport destinations

## Commands:

| Command | Description | Permission<br>`cubeengine.teleport.command.<perm>` |
| --- | --- | --- |
| [*swap*](#swap) | Swaps you and another players position | `swap.use` |
| [*tpaccept*](#tpaccept) | Accepts any pending teleport request. | `tpaccept.use` |
| [*jumpTo*](#jumpto) | Jumps to the position you are looking at. | `jumpto.use` |
| [*tppos*](#tppos) | Direct teleport to a coordinate. | `tppos.use` |
| [*tphere*](#tphere) | Teleport a player directly to you. | `tphere.use` |
| [*ascend*](#ascend) | Teleports you to the next safe spot upwards. | `ascend.use` |
| [*tpall*](#tpall) | Teleports everyone directly to a player. | `tpall.use` |
| [*tp*](#tp) | Teleport directly to a player. | `tp.use` |
| [*spawnAll*](#spawnall) | Teleports all players to spawn | `spawnall.use` |
| [*tphereall*](#tphereall) | Teleport every player directly to you. | `tphereall.use` |
| [*tpworld*](#tpworld) | Teleports you to the spawn of given world | `tpworld.use` |
| [*through*](#through) | Jumps to the position you are looking at. | `through.use` |
| [*tpdeny*](#tpdeny) | Denies any pending teleport request. | `tpdeny.use` |
| [*back*](#back) | Teleports you to your last location | `back.use` |
| [*spawn*](#spawn) | Teleports a player to spawn | `spawn.use` |
| [*descend*](#descend) | Teleports you to the next safe spot downwards. | `descend.use` |
| [*up*](#up) | Teleports you X amount of blocks into the air and puts a glass block beneath you. | `up.use` |
| [*tpahere*](#tpahere) | Requests to teleport a player to you. | `tpahere.use` |
| [*setSpawn*](#setspawn) | Changes the global respawnpoint | `setspawn.use` |
| [*top*](#top) | Teleports to the highest point at your position. | `top.use` |
| [*place*](#place) | Places a player to the position you are looking at. | `place.use` |
| [*tpa*](#tpa) | Requests to teleport to a player. | `tpa.use` |

#### swap  
Swaps you and another players position  
**Usage:** `swap <player> <player>`  
**Permission:** `cubeengine.teleport.command.swap.use`  
  

#### tpaccept  
Accepts any pending teleport request.  
**Usage:** `tpaccept `  
**Alias:** `tpac`  
**Permission:** `cubeengine.teleport.command.tpaccept.use`  
  

#### jumpTo  
Jumps to the position you are looking at.  
**Usage:** `jumpTo `  
**Alias:** `jump` `j`  
**Permission:** `cubeengine.teleport.command.jumpto.use`  
  

#### tppos  
Direct teleport to a coordinate.  
**Usage:** `tppos <x> <y> <z> [world <world>] [player <player>] [-unsafe]`  
**Permission:** `cubeengine.teleport.command.tppos.use`  
  

#### tphere  
Teleport a player directly to you.  
**Usage:** `tphere <player> [-force]`  
**Permission:** `cubeengine.teleport.command.tphere.use`  
  

#### ascend  
Teleports you to the next safe spot upwards.  
**Usage:** `ascend `  
**Permission:** `cubeengine.teleport.command.ascend.use`  
  

#### tpall  
Teleports everyone directly to a player.  
**Usage:** `tpall <player> [-force]`  
**Permission:** `cubeengine.teleport.command.tpall.use`  
  

#### tp  
Teleport directly to a player.  
**Usage:** `tp <player> [target] [-force]`  
**Permission:** `cubeengine.teleport.command.tp.use`  
  

#### spawnAll  
Teleports all players to spawn  
**Usage:** `spawnAll <world> [-force]`  
**Permission:** `cubeengine.teleport.command.spawnall.use`  
  

#### tphereall  
Teleport every player directly to you.  
**Usage:** `tphereall [-force]`  
**Permission:** `cubeengine.teleport.command.tphereall.use`  
  

#### tpworld  
Teleports you to the spawn of given world  
**Usage:** `tpworld <world>`  
**Permission:** `cubeengine.teleport.command.tpworld.use`  
  

#### through  
Jumps to the position you are looking at.  
**Usage:** `through `  
**Alias:** `thru`  
**Permission:** `cubeengine.teleport.command.through.use`  
  

#### tpdeny  
Denies any pending teleport request.  
**Usage:** `tpdeny `  
**Permission:** `cubeengine.teleport.command.tpdeny.use`  
  

#### back  
Teleports you to your last location  
**Usage:** `back [-unsafe]`  
**Permission:** `cubeengine.teleport.command.back.use`  
  

#### spawn  
Teleports a player to spawn  
**Usage:** `spawn <player> [world] [-force]`  
**Permission:** `cubeengine.teleport.command.spawn.use`  
  

#### descend  
Teleports you to the next safe spot downwards.  
**Usage:** `descend `  
**Permission:** `cubeengine.teleport.command.descend.use`  
  

#### up  
Teleports you X amount of blocks into the air and puts a glass block beneath you.  
**Usage:** `up <height>`  
**Permission:** `cubeengine.teleport.command.up.use`  
  

#### tpahere  
Requests to teleport a player to you.  
**Usage:** `tpahere <player>`  
**Permission:** `cubeengine.teleport.command.tpahere.use`  
  

#### setSpawn  
Changes the global respawnpoint  
**Usage:** `setSpawn <world> [x] [y] [z]`  
**Permission:** `cubeengine.teleport.command.setspawn.use`  
  

#### top  
Teleports to the highest point at your position.  
**Usage:** `top `  
**Permission:** `cubeengine.teleport.command.top.use`  
  

#### place  
Places a player to the position you are looking at.  
**Usage:** `place <player>`  
**Alias:** `put`  
**Permission:** `cubeengine.teleport.command.place.use`  
  

#### tpa  
Requests to teleport to a player.  
**Usage:** `tpa <player>`  
**Permission:** `cubeengine.teleport.command.tpa.use`  
  

## Additional Permissions:

| Permission | Description |
| --- | --- |
| `cubeengine.teleport` | Base Permission for teleport |