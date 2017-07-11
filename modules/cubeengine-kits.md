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
| [**kit** *create*](#kit-create) | Opens the configured kit if the kit does not exists a new is created | `kit.create.use` |
| [**kit** *delete*](#kit-delete) | Deletes a kit | `kit.delete.use` |
| [**kit** *give*](#kit-give) | Gives a set of items. | `kit.give.use` |
| [**kit** *giveall*](#kit-giveall) | Gives a kit to every online player | `kit.giveall.use` |
| [**kit** *list*](#kit-list) | Lists all currently available kits. | `kit.list.use` |
| [**kit** *setCommand*](#kit-setcommand) | Sets a command to be run when a kit is received | `kit.setcommand.use` |

#### kit  
Manages item-kits  
**Usage:** `kit <command>`  
**Permission:** `cubeengine.kits.command.kit`  
**SubCommands:** `create` `delete` `give` `giveall` `list` `setCommand`  

#### kit create  
Opens the configured kit if the kit does not exists a new is created  
**Usage:** `kit create <kitname>`  
**Alias:** `open`  
**Permission:** `cubeengine.kits.command.kit.create.use`  
  

#### kit delete  
Deletes a kit  
**Usage:** `kit delete <kit>`  
**Alias:** `remove`  
**Permission:** `cubeengine.kits.command.kit.delete.use`  
  

#### kit give  
Gives a set of items.  
**Usage:** `kit give <kit> <player> [-force]`  
**Permission:** `cubeengine.kits.command.kit.give.use`  
  

#### kit giveall  
Gives a kit to every online player  
**Usage:** `kit giveall <kit> [-force]`  
**Permission:** `cubeengine.kits.command.kit.giveall.use`  
  

#### kit list  
Lists all currently available kits.  
**Usage:** `kit list `  
**Alias:** `/kitlist`  
**Permission:** `cubeengine.kits.command.kit.list.use`  
  

#### kit setCommand  
Sets a command to be run when a kit is received  
**Usage:** `kit setCommand <kit> [commands]`  
**Permission:** `cubeengine.kits.command.kit.setcommand.use`  
  

## Additional Permissions:

| Permission | Description |
| --- | --- |
| `cubeengine.kits` | Base Permission for kits |