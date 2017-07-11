# CubeEngine - Worlds
Create universes with countless worlds

## Features:
 - Create or delete new worlds
 - Load or unload existing worls

## Commands:
| Command | Description | Permission<br>`cubeengine.worlds.command.<perm>` |
| --- | --- | --- |
| [*worlds*](#worlds) | Worlds commands | `worlds` |
| [**worlds** *autoload*](#worlds-autoload) | Sets the autoload behaviour | `worlds.autoload.use` |
| [**worlds** *create*](#worlds-create) | Creates a new world | `worlds.create.use` |
| [**worlds** *info*](#worlds-info) | Show info about a world | `worlds.info.use` |
| [**worlds** *list*](#worlds-list) | Lists all worlds | `worlds.list.use` |
| [**worlds** *listplayers*](#worlds-listplayers) | Lists the players in a world | `worlds.listplayers.use` |
| [**worlds** *load*](#worlds-load) | Loads a world | `worlds.load.use` |
| [**worlds** *remove*](#worlds-remove) | Remove a world | `worlds.remove.use` |
| [**worlds** *unload*](#worlds-unload) | Unload a loaded world | `worlds.unload.use` |

#### worlds  
Worlds commands  
**Usage:** `worlds <command>`  
**Permission:** `cubeengine.worlds.command.worlds`  
**SubCommands:** `autoload` `create` `info` `list` `listplayers` `load` `remove` `unload`  

#### worlds autoload  
Sets the autoload behaviour  
**Usage:** `worlds autoload <world> [set]`  
**Permission:** `cubeengine.worlds.command.worlds.autoload.use`  
  

#### worlds create  
Creates a new world  
**Usage:** `worlds create <name> [dimension <dimension>] [seed <seed>] [type <type>] [structure <generate>] [gamemode <gamemode>] [difficulty <difficulty>] [generator <name>] [-recreate] [-noload] [-spawnInMemory]`  
**Permission:** `cubeengine.worlds.command.worlds.create.use`  
  

#### worlds info  
Show info about a world  
**Usage:** `worlds info <world> [-showGameRules]`  
**Permission:** `cubeengine.worlds.command.worlds.info.use`  
  

#### worlds list  
Lists all worlds  
**Usage:** `worlds list `  
**Alias:** `/listworlds`  
**Permission:** `cubeengine.worlds.command.worlds.list.use`  
  

#### worlds listplayers  
Lists the players in a world  
**Usage:** `worlds listplayers <world>`  
**Permission:** `cubeengine.worlds.command.worlds.listplayers.use`  
  

#### worlds load  
Loads a world  
**Usage:** `worlds load <world> [-enable]`  
**Permission:** `cubeengine.worlds.command.worlds.load.use`  
  

#### worlds remove  
Remove a world  
**Usage:** `worlds remove <world> [-folder] [-unload]`  
**Alias:** `delete`  
**Permission:** `cubeengine.worlds.command.worlds.remove.use`  
  

#### worlds unload  
Unload a loaded world  
**Usage:** `worlds unload <world> [-force]`  
**Permission:** `cubeengine.worlds.command.worlds.unload.use`  
  

## Additional Permissions:

| Permission | Description |
| --- | --- |
| `cubeengine.worlds` | Base Permission for worlds |