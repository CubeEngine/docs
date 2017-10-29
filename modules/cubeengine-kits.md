# CubeEngine - Kits
Hand kits to your players

## Features:
 - Create sets of arbitrary items
 - Can run a command on kit receival
 - Create kits in game using an inventory

## Commands:

| Command | Description | Permission<br>`cubeengine.kits.command.<perm>` |
| --- | --- | --- |
| [*kit*](#kit) | Manages item-kits | `kit` |
| [**kit**&nbsp;*create*](#kitcreate) | Opens the configured kit if the kit does not exists a new is created | `kit.create.use` |
| [**kit**&nbsp;*delete*](#kitdelete) | Deletes a kit | `kit.delete.use` |
| [**kit**&nbsp;*give*](#kitgive) | Gives a set of items. | `kit.give.use` |
| [**kit**&nbsp;*giveall*](#kitgiveall) | Gives a kit to every online player | `kit.giveall.use` |
| [**kit**&nbsp;*list*](#kitlist) | Lists all currently available kits. | `kit.list.use` |
| [**kit**&nbsp;*setCommand*](#kitsetcommand) | Sets a command to be run when a kit is received | `kit.setcommand.use` |

#### kit  
Manages item-kits  
**Usage:** `kit <command>`  
**Permission:** `cubeengine.kits.command.kit`  
**SubCommands:** `create` `delete` `give` `giveall` `list` `setCommand`  

#### kit&nbsp;create  
Opens the configured kit if the kit does not exists a new is created  
**Usage:** `kit create <kitname>`  
**Alias:** `open`  
**Permission:** `cubeengine.kits.command.kit.create.use`  
  

#### kit&nbsp;delete  
Deletes a kit  
**Usage:** `kit delete <kit>`  
**Alias:** `remove`  
**Permission:** `cubeengine.kits.command.kit.delete.use`  
  

#### kit&nbsp;give  
Gives a set of items.  
**Usage:** `kit give <kit> <player> [-force]`  
**Permission:** `cubeengine.kits.command.kit.give.use`  
  

#### kit&nbsp;giveall  
Gives a kit to every online player  
**Usage:** `kit giveall <kit> [-force]`  
**Permission:** `cubeengine.kits.command.kit.giveall.use`  
  

#### kit&nbsp;list  
Lists all currently available kits.  
**Usage:** `kit list `  
**Alias:** `/kitlist`  
**Permission:** `cubeengine.kits.command.kit.list.use`  
  

#### kit&nbsp;setCommand  
Sets a command to be run when a kit is received  
**Usage:** `kit setCommand <kit> [commands]`  
**Permission:** `cubeengine.kits.command.kit.setcommand.use`  
  

## Additional Permissions:

| Permission | Description |
| --- | --- |
| `cubeengine.kits` | Base Permission for Kits |
| `cubeengine.kits.command` | Allows using all commands of Kits |
| `cubeengine.kits.command.kits.give.other` | Grants giving out kits to other players |
| `cubeengine.kits.kits` | Grants access to all kits |
