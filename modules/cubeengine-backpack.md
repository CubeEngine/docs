# CubeEngine - Backpack
Expand your inventory!

## Features:
 - Additional storage inventories for players

## Commands:

| Command | Description | Permission<br>`cubeengine.backpack.command.<perm>` |
| --- | --- | --- |
| [*backpack*](#backpack) | The Backpack commands | `backpack` |
| [**backpack**&nbsp;*addContext*](#backpack&nbsp;addcontext) | modifies a backpacks context | `backpack.addcontext.use` |
| [**backpack**&nbsp;*blockinput*](#backpack&nbsp;blockinput) | modifies a backpack | `backpack.blockinput.use` |
| [**backpack**&nbsp;*create*](#backpack&nbsp;create) | creates a new backpack | `backpack.create.use` |
| [**backpack**&nbsp;*open*](#backpack&nbsp;open) | opens a backpack | `backpack.open.use` |
| [**backpack**&nbsp;*removeContext*](#backpack&nbsp;removecontext) | modifies a backpacks context | `backpack.removecontext.use` |

#### backpack  
The Backpack commands  
**Usage:** `backpack <command>`  
**Alias:** `bp`  
**Permission:** `cubeengine.backpack.command.backpack`  
**SubCommands:** `addContext` `blockinput` `create` `open` `removeContext`  

#### backpack&nbsp;addContext  
modifies a backpacks context  
**Usage:** `backpack addContext <name> <player> <context>`  
**Permission:** `cubeengine.backpack.command.backpack.addcontext.use`  
  

#### backpack&nbsp;blockinput  
modifies a backpack  
**Usage:** `backpack blockinput <name> <player> <blockinput>`  
**Alias:** `/blockbp`  
**Permission:** `cubeengine.backpack.command.backpack.blockinput.use`  
  

#### backpack&nbsp;create  
creates a new backpack  
**Usage:** `backpack create [player] [name] [in <context>] [-blockinput]`  
**Alias:** `/createbp`  
**Permission:** `cubeengine.backpack.command.backpack.create.use`  
  

#### backpack&nbsp;open  
opens a backpack  
**Usage:** `backpack open [name] <player> [-outOfContext]`  
**Alias:** `/openbp`  
**Permission:** `cubeengine.backpack.command.backpack.open.use`  
  

#### backpack&nbsp;removeContext  
modifies a backpacks context  
**Usage:** `backpack removeContext <name> <player> <context>`  
**Permission:** `cubeengine.backpack.command.backpack.removecontext.use`  
  

## Additional Permissions:

| Permission | Description |
| --- | --- |
| `cubeengine.backpack` | Base Permission for Backpack |