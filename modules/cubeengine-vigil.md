# CubeEngine - Vigil
Log everything you want!

## Features:
 - Tracks any world changes
 - Storage in MongoDB database
 - Ingame lookup and restore
 - Restore preview

## Dependencies:
 `cubeengine-bigdata`

## Commands:

| Command | Description | Permission<br>`cubeengine.vigil.command.<perm>` |
| --- | --- | --- |
| [*vigil*](#vigil) | Vigil-Module Commands | `vigil` |
| [**vigil**&nbsp;*admin*](#vigil&nbsp;admin) | Vigil-Admin Commands | `vigil.admin` |
| [**vigil**&nbsp;**admin**&nbsp;*purge*](#vigil&nbsp;admin&nbsp;purge) | purges all logs | `vigil.admin.purge.use` |
| [**vigil**&nbsp;**admin**&nbsp;*setReportActive*](#vigil&nbsp;admin&nbsp;setreportactive) | enables or disables reports in a world | `vigil.admin.setreportactive.use` |
| [**vigil**&nbsp;*block*](#vigil&nbsp;block) | Gives you a block to check logs with. | `vigil.block.use` |
| [**vigil**&nbsp;*tool*](#vigil&nbsp;tool) | Gives you an item to check logs with. | `vigil.tool.use` |

#### vigil  
Vigil-Module Commands  
**Usage:** `vigil <command>`  
**Alias:** `log`  
**Permission:** `cubeengine.vigil.command.vigil`  
**SubCommands:** `admin` `block` `tool`  

#### vigil&nbsp;admin  
Vigil-Admin Commands  
**Usage:** `vigil admin <command>`  
**Permission:** `cubeengine.vigil.command.vigil.admin`  
**SubCommands:** `purge` `setReportActive`  

#### vigil&nbsp;admin&nbsp;purge  
purges all logs  
**Usage:** `vigil admin purge `  
**Permission:** `cubeengine.vigil.command.vigil.admin.purge.use`  
  

#### vigil&nbsp;admin&nbsp;setReportActive  
enables or disables reports in a world  
**Usage:** `vigil admin setReportActive <world> <name> <enable>`  
**Permission:** `cubeengine.vigil.command.vigil.admin.setreportactive.use`  
  

#### vigil&nbsp;block  
Gives you a block to check logs with.  
**Usage:** `vigil block <log-type>`  
**Alias:** `/lb`  
**Permission:** `cubeengine.vigil.command.vigil.block.use`  
  

#### vigil&nbsp;tool  
Gives you an item to check logs with.  
**Usage:** `vigil tool <log-type>`  
**Alias:** `/lt`  
**Permission:** `cubeengine.vigil.command.vigil.tool.use`  
  

## Additional Permissions:

| Permission | Description |
| --- | --- |
| `cubeengine.vigil` | Base Permission for vigil |