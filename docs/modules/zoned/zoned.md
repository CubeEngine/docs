# CubeEngine - Zoned
Select, Create and Manage Zones

## Features:
 - zone creation

## Commands:

| Command | Description | Permission<br>`cubeengine.zoned.command.<perm>` |
| --- | --- | --- |
| [*selectiontool*](#selectiontool) | Provides you with a wand to select a cuboid | `selectiontool.use` |
| [*zone*](#zone) | Manages zones |  |
| [**zone**&nbsp;*circuitselect*](#zonecircuitselect) | Creates a zone by following connected redstone | `zone.circuitSelect.use` |
| [**zone**&nbsp;*define*](#zonedefine) | Defines a new zone | `zone.define.use` |
| [**zone**&nbsp;*delete*](#zonedelete) | Deletes a zone | `zone.delete.use` |
| [**zone**&nbsp;*info*](#zoneinfo) | Displays zone info | `zone.info.use` |
| [**zone**&nbsp;*list*](#zonelist) | Lists zones | `zone.list.use` |
| [**zone**&nbsp;*redefine*](#zoneredefine) | Redefines an existing zone | `zone.redefine.use` |
| [**zone**&nbsp;*select*](#zoneselect) | Selects a zone | `zone.select.use` |
| [**zone**&nbsp;*show*](#zoneshow) | Toggles particles for the currently selected zone | `zone.show.use` |
| [**zone**&nbsp;*teleport*](#zoneteleport) | Teleports to a zone | `zone.teleport.use` |

#### selectiontool  
Provides you with a wand to select a cuboid  
**Usage:** `selectiontool`  
**Permission:** `cubeengine.zoned.command.selectiontool.use`  
  

#### zone  
Manages zones  
**Usage:** `zone`  
**SubCommands:** `circuitselect` `define` `delete` `info` `list` `redefine` `select` `show` `teleport`  

#### zone&nbsp;circuitselect  
Creates a zone by following connected redstone  
**Usage:** `zone circuitselect`  
**Permission:** `cubeengine.zoned.command.zone.circuitSelect.use`  
  

#### zone&nbsp;define  
Defines a new zone  
**Usage:** `zone define <name>`  
**Permission:** `cubeengine.zoned.command.zone.define.use`  
  

#### zone&nbsp;delete  
Deletes a zone  
**Usage:** `zone delete <zone>`  
**Alias:** `remove`  
**Permission:** `cubeengine.zoned.command.zone.delete.use`  
  

#### zone&nbsp;info  
Displays zone info  
**Usage:** `zone info [zone]`  
**Permission:** `cubeengine.zoned.command.zone.info.use`  
  

#### zone&nbsp;list  
Lists zones  
**Usage:** `zone list [match][?]`  
**Permission:** `cubeengine.zoned.command.zone.list.use`  
  

#### zone&nbsp;redefine  
Redefines an existing zone  
**Usage:** `zone redefine [zone]`  
**Permission:** `cubeengine.zoned.command.zone.redefine.use`  
  

#### zone&nbsp;select  
Selects a zone  
**Usage:** `zone select <zone>`  
**Permission:** `cubeengine.zoned.command.zone.select.use`  
  

#### zone&nbsp;show  
Toggles particles for the currently selected zone  
**Usage:** `zone show [zone]`  
**Permission:** `cubeengine.zoned.command.zone.show.use`  
  

#### zone&nbsp;teleport  
Teleports to a zone  
**Usage:** `zone teleport <zone>[?]`  
**Alias:** `tp`  
**Permission:** `cubeengine.zoned.command.zone.teleport.use`  
  

## Permissions:

| Permission | Description |
| --- | --- |
| `cubeengine.zoned` | Base Permission for Zoned |
| `cubeengine.zoned.use-tool` | Allows using the selector tool |
