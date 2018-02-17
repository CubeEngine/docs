# CubeEngine - Multiverse
Group your worlds in universes

## Features:
 - Arbitrary world grouping
 - Separate Inventory etc. for each universe
 - Contexts for each universe

## Commands:

| Command | Description | Permission<br>`cubeengine.multiverse.command.<perm>` |
| --- | --- | --- |
| [*multiverse*](#multiverse) | Multiverse commands | `multiverse` |
| [**multiverse**&nbsp;*list*](#multiverselist) | Lists all known universes | `multiverse.list.use` |
| [**multiverse**&nbsp;*move*](#multiversemove) | Moves a world into another universe | `multiverse.move.use` |
| [**multiverse**&nbsp;*remove*](#multiverseremove) | Removes a universe | `multiverse.remove.use` |
| [**multiverse**&nbsp;*rename*](#multiverserename) | Renames a universe | `multiverse.rename.use` |

#### multiverse  
Multiverse commands  
**Usage:** `multiverse <command>`  
**Alias:** `mv`  
**Permission:** `cubeengine.multiverse.command.multiverse`  
**SubCommands:** `list` `move` `remove` `rename`  

#### multiverse&nbsp;list  
Lists all known universes  
**Usage:** `multiverse list `  
**Permission:** `cubeengine.multiverse.command.multiverse.list.use`  
  

#### multiverse&nbsp;move  
Moves a world into another universe  
**Usage:** `multiverse move <world> <universe>`  
**Permission:** `cubeengine.multiverse.command.multiverse.move.use`  
  

#### multiverse&nbsp;remove  
Removes a universe  
**Usage:** `multiverse remove <universe>`  
**Permission:** `cubeengine.multiverse.command.multiverse.remove.use`  
  

#### multiverse&nbsp;rename  
Renames a universe  
**Usage:** `multiverse rename <universe> <newName>`  
**Permission:** `cubeengine.multiverse.command.multiverse.rename.use`  
  

## Permissions:

| Permission | Description |
| --- | --- |
| `cubeengine.multiverse` | Base Permission for Multiverse |
| `cubeengine.multiverse.command` | Allows using all commands of Multiverse |
