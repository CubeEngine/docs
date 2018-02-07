# CubeEngine - Worlds
Create universes with countless worlds

## Features:
 - Create or delete new worlds
 - Load or unload existing worls

## Commands:

| Command | Description | Permission<br>`cubeengine.worlds.command.<perm>` |
| --- | --- | --- |
| [*worlds*](#worlds) | Worlds commands | `worlds` |
| [**worlds**&nbsp;*create*](#worldscreate) | Creates a new world | `worlds.create.use` |
| [**worlds**&nbsp;*info*](#worldsinfo) | Show info about a world | `worlds.info.use` |
| [**worlds**&nbsp;*list*](#worldslist) | Lists all worlds | `worlds.list.use` |
| [**worlds**&nbsp;*listplayers*](#worldslistplayers) | Lists the players in a world | `worlds.listplayers.use` |
| [**worlds**&nbsp;*load*](#worldsload) | Loads a world | `worlds.load.use` |
| [**worlds**&nbsp;*modify*](#worldsmodify) | Worlds modify commands | `worlds.modify` |
| [**worlds**&nbsp;**modify**&nbsp;*autoload*](#worldsmodifyautoload) | Sets the autoload behaviour | `worlds.modify.autoload.use` |
| [**worlds**&nbsp;**modify**&nbsp;*generateStructure*](#worldsmodifygeneratestructure) | Sets whether structors generate | `worlds.modify.generatestructure.use` |
| [**worlds**&nbsp;*remove*](#worldsremove) | Remove a world | `worlds.remove.use` |
| [**worlds**&nbsp;*rename*](#worldsrename) | Renames a world | `worlds.rename.use` |
| [**worlds**&nbsp;*unload*](#worldsunload) | Unload a loaded world | `worlds.unload.use` |

#### worlds  
Worlds commands  
**Usage:** `worlds <command>`  
**Permission:** `cubeengine.worlds.command.worlds`  
**SubCommands:** `create` `info` `list` `listplayers` `load` `modify` `remove` `rename` `unload`  

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
  

#### worlds&nbsp;modify  
Worlds modify commands  
**Usage:** `worlds modify <command>`  
**Permission:** `cubeengine.worlds.command.worlds.modify`  
**SubCommands:** `autoload` `generateStructure`  

#### worlds&nbsp;modify&nbsp;autoload  
Sets the autoload behaviour  
**Usage:** `worlds modify autoload <world> [set]`  
**Permission:** `cubeengine.worlds.command.worlds.modify.autoload.use`  
  

#### worlds&nbsp;modify&nbsp;generateStructure  
Sets whether structors generate  
**Usage:** `worlds modify generateStructure <world> [set]`  
**Permission:** `cubeengine.worlds.command.worlds.modify.generatestructure.use`  
  

#### worlds&nbsp;remove  
Remove a world  
**Usage:** `worlds remove <world> [-folder] [-unload]`  
**Alias:** `delete`  
**Permission:** `cubeengine.worlds.command.worlds.remove.use`  
  

#### worlds&nbsp;rename  
Renames a world  
**Usage:** `worlds rename <world> <newName>`  
**Permission:** `cubeengine.worlds.command.worlds.rename.use`  
  

#### worlds&nbsp;unload  
Unload a loaded world  
**Usage:** `worlds unload <world> [-force]`  
**Permission:** `cubeengine.worlds.command.worlds.unload.use`  
  

## Additional Permissions:

| Permission | Description |
| --- | --- |
| `cubeengine.worlds` | Base Permission for Worlds |
| `cubeengine.worlds.command` | Allows using all commands of Worlds |
