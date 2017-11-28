# CubeEngine - Protector
Protects your worlds

## Features:
 - Define regions in your worlds and protect them
 - Protects from any world changes
 - Can be used for greylisting

## Commands:

| Command | Description | Permission<br>`cubeengine.protector.command.<perm>` |
| --- | --- | --- |
| [*region*](#region) | Manages the regions | `region` |
| [**region**&nbsp;*define*](#regiondefine) | Defines a new Region | `region.define.use` |
| [**region**&nbsp;*info*](#regioninfo) | Displays Region info | `region.info.use` |
| [**region**&nbsp;*list*](#regionlist) | Lists regions | `region.list.use` |
| [**region**&nbsp;*redefine*](#regionredefine) | Redefines an existing Region | `region.redefine.use` |
| [**region**&nbsp;*select*](#regionselect) | Selects a Region | `region.select.use` |

#### region  
Manages the regions  
**Usage:** `region <command>`  
**Permission:** `cubeengine.protector.command.region`  
**SubCommands:** `define` `info` `list` `redefine` `select`  

#### region&nbsp;define  
Defines a new Region  
**Usage:** `region define <name>`  
**Permission:** `cubeengine.protector.command.region.define.use`  
  

#### region&nbsp;info  
Displays Region info  
**Usage:** `region info <region> [-allSettings]`  
**Permission:** `cubeengine.protector.command.region.info.use`  
  

#### region&nbsp;list  
Lists regions  
**Usage:** `region list [match] [in <world>]`  
**Permission:** `cubeengine.protector.command.region.list.use`  
  

#### region&nbsp;redefine  
Redefines an existing Region  
**Usage:** `region redefine <region>`  
**Permission:** `cubeengine.protector.command.region.redefine.use`  
  

#### region&nbsp;select  
Selects a Region  
**Usage:** `region select <region>`  
**Permission:** `cubeengine.protector.command.region.select.use`  
  

## Additional Permissions:

| Permission | Description |
| --- | --- |
| `cubeengine.protector` | Base Permission for Protector |
| `cubeengine.protector.bypass.blockdamage.explode.player` | Region bypass for players causing blockdamage with explosions |
| `cubeengine.protector.bypass.build` | Region bypass for building |
| `cubeengine.protector.bypass.command` | Region bypass for using all commands |
| `cubeengine.protector.bypass.entity-damage.all` |  |
| `cubeengine.protector.bypass.entity-damage.living` |  |
| `cubeengine.protector.bypass.move.enter` | Region bypass for entering a region |
| `cubeengine.protector.bypass.move.exit` | Region bypass for exiting a region |
| `cubeengine.protector.bypass.move.move` | Region bypass for moving in a region |
| `cubeengine.protector.bypass.move.teleport` | Region bypass for teleport in a region |
| `cubeengine.protector.bypass.move.teleport-portal` | Region bypass for teleport using portals in a region |
| `cubeengine.protector.bypass.player-damage.all` |  |
| `cubeengine.protector.bypass.player-damage.living` |  |
| `cubeengine.protector.bypass.player-damage.pvp` |  |
| `cubeengine.protector.bypass.player-targeting` |  |
| `cubeengine.protector.bypass.spawn.player` | Region bypass for players spawning entities |
| `cubeengine.protector.bypass.use` | Region bypass for using anything |
| `cubeengine.protector.bypass.use-all.block` | Region bypass for using blocks |
| `cubeengine.protector.bypass.use-all.container` | Region bypass for using containers |
| `cubeengine.protector.bypass.use-all.item` | Region bypass for using items |
| `cubeengine.protector.bypass.use-all.open` | Region bypass for opening anything |
| `cubeengine.protector.bypass.use-all.redstone` | Region bypass for using redstone |
| `cubeengine.protector.bypass.use-item` | Region bypass for using items |
| `cubeengine.protector.command` | Allows using all commands of Protector |
