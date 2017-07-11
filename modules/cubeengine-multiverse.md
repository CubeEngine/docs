# CubeEngine - Multiverse
Group your worlds in universes
## Features:
 - Arbitrary world grouping
 - Separate Inventory etc. for each universe
 - Contexts for each universe
## Commands
| Command | Description | Permission<br>`cubeengine.multiverse.command.<perm>` |
| --- | --- | --- |
| [*multiverse*](#multiverse) | Multiverse commands | `multiverse` |
| [**multiverse** *list*](#multiverse-list) | Lists all known universes | `multiverse.list.use` |
| [**multiverse** *move*](#multiverse-move) | Moves a world into another universe | `multiverse.move.use` |
| [**multiverse** *remove*](#multiverse-remove) | Removes a universe | `multiverse.remove.use` |
| [**multiverse** *rename*](#multiverse-rename) | Renames a universe | `multiverse.rename.use` |
#### multiverse  
Multiverse commands  
**Usage:** `multiverse <command>`  
**Alias:** `mv`  
**Permission:** `cubeengine.multiverse.command.multiverse`  
**SubCommands:** `list` `move` `remove` `rename`  
#### multiverse list  
Lists all known universes  
**Usage:** `multiverse list `  
**Permission:** `cubeengine.multiverse.command.multiverse.list.use`  
  
#### multiverse move  
Moves a world into another universe  
**Usage:** `multiverse move <world> <universe>`  
**Permission:** `cubeengine.multiverse.command.multiverse.move.use`  
  
#### multiverse remove  
Removes a universe  
**Usage:** `multiverse remove <universe>`  
**Permission:** `cubeengine.multiverse.command.multiverse.remove.use`  
  
#### multiverse rename  
Renames a universe  
**Usage:** `multiverse rename <universe> <newName>`  
**Permission:** `cubeengine.multiverse.command.multiverse.rename.use`  
  
## Additional Permissions

| Permission | Description |
| --- | --- |
| `cubeengine.multiverse` | Base Permission for multiverse |