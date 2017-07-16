# CubeEngine - Worlds
Create universes with countless worlds

## Features:
 - Create or delete new worlds
 - Load or unload existing worls

## Commands:

| Command | Description | Permission<br>`cubeengine.worlds.command.<perm>` |
| --- | --- | --- |
| [*worlds*](#worlds) | Worlds commands | `worlds` |
| [**worlds**&nbsp;*autoload*](#worlds&nbsp;autoload) | Sets the autoload behaviour | `worlds.autoload.use` |
| [**worlds**&nbsp;*create*](#worlds&nbsp;create) | Creates a new world | `worlds.create.use` |
| [**worlds**&nbsp;*info*](#worlds&nbsp;info) | Show info about a world | `worlds.info.use` |
| [**worlds**&nbsp;*list*](#worlds&nbsp;list) | Lists all worlds | `worlds.list.use` |
| [**worlds**&nbsp;*listplayers*](#worlds&nbsp;listplayers) | Lists the players in a world | `worlds.listplayers.use` |
| [**worlds**&nbsp;*load*](#worlds&nbsp;load) | Loads a world | `worlds.load.use` |
| [**worlds**&nbsp;*remove*](#worlds&nbsp;remove) | Remove a world | `worlds.remove.use` |
| [**worlds**&nbsp;*unload*](#worlds&nbsp;unload) | Unload a loaded world | `worlds.unload.use` |

#### worlds  
Worlds commands  
**Usage:** `worlds <command>`  
**Permission:** `cubeengine.worlds.command.worlds`  
**SubCommands:** `autoload` `create` `info` `list` `listplayers` `load` `remove` `unload`  

#### worlds&nbsp;autoload  
Sets the autoload behaviour  
**Usage:** `worlds autoload <world> [set]`  
**Permission:** `cubeengine.worlds.command.worlds.autoload.use`  
  

#### worlds&nbsp;create  
Creates a new world  
**Usage:** `worlds create <name> [dimension <dimension>] [seed <seed>] [type <type>] [structure <generate>] [gamemode <gamemode>] [difficulty <difficulty>] [generator <name>] [-recreate] [-noload] [-spawnInMemory]`  
**Permission:** `cubeengine.worlds.command.worlds.create.use`  
  

#### worlds&nbsp;info  
Show info about a world  
**Usage:** `worlds info <world> [-showGameRules]`  
**Permission:** `cubeengine.worlds.command.worlds.info.use`  
  

#### worlds&nbsp;list  
Lists all worlds  
**Usage:** `worlds list `  
**Alias:** `/listworlds`  
**Permission:** `cubeengine.worlds.command.worlds.list.use`  
  

#### worlds&nbsp;listplayers  
Lists the players in a world  
**Usage:** `worlds listplayers <world>`  
**Permission:** `cubeengine.worlds.command.worlds.listplayers.use`  
  

#### worlds&nbsp;load  
Loads a world  
**Usage:** `worlds load <world> [-enable]`  
**Permission:** `cubeengine.worlds.command.worlds.load.use`  
  

#### worlds&nbsp;remove  
Remove a world  
**Usage:** `worlds remove <world> [-folder] [-unload]`  
**Alias:** `delete`  
**Permission:** `cubeengine.worlds.command.worlds.remove.use`  
  

#### worlds&nbsp;unload  
Unload a loaded world  
**Usage:** `worlds unload <world> [-force]`  
**Permission:** `cubeengine.worlds.command.worlds.unload.use`  
  

## Additional Permissions:

| Permission | Description |
| --- | --- |
| `cubeengine.worlds` | Base Permission for worlds |