# CubeEngine - Multiverse
Group your worlds in universes

## Features:
 - Arbitrary world grouping
 - Separate Inventory etc. for each universe
 - Contexts for each universe

## Commands:

| Command | Description | Permission<br>`cubeengine.multiverse.command.<perm>` |
| --- | --- | --- |
| [*multiverse*](#multiverse) | Multiverse commands |  |
| [**multiverse**&nbsp;*autoconfig*](#multiverseautoconfig) | Add a regex to automatically assign worlds to universes | `multiverse.autoconfig.use` |
| [**multiverse**&nbsp;*clearautoconfig*](#multiverseclearautoconfig) | Removes all regex for a universe | `multiverse.clearautoconfig.use` |
| [**multiverse**&nbsp;*list*](#multiverselist) | Lists all known universes | `multiverse.list.use` |
| [**multiverse**&nbsp;*move*](#multiversemove) | Moves a world into another universe | `multiverse.move.use` |
| [**multiverse**&nbsp;*remove*](#multiverseremove) | Removes a universe | `multiverse.remove.use` |
| [**multiverse**&nbsp;*rename*](#multiverserename) | Renames a universe | `multiverse.rename.use` |
| [**multiverse**&nbsp;*testautoconfig*](#multiversetestautoconfig) | Displays all known worlds matching given regex | `multiverse.testautoconfig.use` |

#### multiverse  
Multiverse commands  
**Usage:** `multiverse`  
**Alias:** `mv`  
**SubCommands:** `autoconfig` `clearautoconfig` `list` `move` `remove` `rename` `testautoconfig`  

#### multiverse&nbsp;autoconfig  
Add a regex to automatically assign worlds to universes  
**Usage:** `multiverse autoconfig <universe> <regex>`  
**Permission:** `cubeengine.multiverse.command.multiverse.autoconfig.use`  
  

#### multiverse&nbsp;clearautoconfig  
Removes all regex for a universe  
**Usage:** `multiverse clearautoconfig <universe>`  
**Permission:** `cubeengine.multiverse.command.multiverse.clearautoconfig.use`  
  

#### multiverse&nbsp;list  
Lists all known universes  
**Usage:** `multiverse list`  
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
  

#### multiverse&nbsp;testautoconfig  
Displays all known worlds matching given regex  
**Usage:** `multiverse testautoconfig <regex>`  
**Permission:** `cubeengine.multiverse.command.multiverse.testautoconfig.use`  
  

## Permissions:

| Permission | Description |
| --- | --- |
| `cubeengine.multiverse` | Base Permission for Multiverse |
