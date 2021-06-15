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
| [*vigil*](#vigil) | Vigil-Module Commands |  |
| [**vigil**&nbsp;*admin*](#vigiladmin) | Vigil-Admin Commands |  |
| [**vigil**&nbsp;**admin**&nbsp;*purge*](#vigiladminpurge) | purges all logs | `vigil.admin.purge.use` |
| [**vigil**&nbsp;**admin**&nbsp;*setreportactive*](#vigiladminsetreportactive) | enables or disables reports in a world | `vigil.admin.setReportActive.use` |
| [**vigil**&nbsp;*block*](#vigilblock) | Gives you a block to check logs with. | `vigil.block.use` |
| [**vigil**&nbsp;*lookup*](#vigillookup) | Performs a lookup. | `vigil.lookup.use` |
| [**vigil**&nbsp;*nearby*](#vigilnearby) | Performs a lookup nearby | `vigil.nearby.use` |
| [**vigil**&nbsp;*tool*](#vigiltool) | Gives you an item to check logs with. | `vigil.tool.use` |

#### vigil  
Vigil-Module Commands  
**Usage:** `vigil`  
**Alias:** `log`  
**SubCommands:** `admin` `block` `lookup` `nearby` `tool`  

#### vigil&nbsp;admin  
Vigil-Admin Commands  
**Usage:** `vigil admin`  
**SubCommands:** `purge` `setreportactive`  

#### vigil&nbsp;admin&nbsp;purge  
purges all logs  
**Usage:** `vigil admin purge`  
**Permission:** `cubeengine.vigil.command.vigil.admin.purge.use`  
  

#### vigil&nbsp;admin&nbsp;setreportactive  
enables or disables reports in a world  
**Usage:** `vigil admin setreportactive <world> <name> [enable]`  
**Permission:** `cubeengine.vigil.command.vigil.admin.setReportActive.use`  
  

#### vigil&nbsp;block  
Gives you a block to check logs with.  
**Usage:** `vigil block log-type`  
**Permission:** `cubeengine.vigil.command.vigil.block.use`  
  

#### vigil&nbsp;lookup  
Performs a lookup.  
**Usage:** `vigil lookup[?][?]`  
**Permission:** `cubeengine.vigil.command.vigil.lookup.use`  
  

#### vigil&nbsp;nearby  
Performs a lookup nearby  
**Usage:** `vigil nearby[?]`  
**Permission:** `cubeengine.vigil.command.vigil.nearby.use`  
  

#### vigil&nbsp;tool  
Gives you an item to check logs with.  
**Usage:** `vigil tool log-type`  
**Permission:** `cubeengine.vigil.command.vigil.tool.use`  
  

## Permissions:

| Permission | Description |
| --- | --- |
| `cubeengine.vigil` | Base Permission for Vigil |
| `cubeengine.vigil.use-logtool` | Allows using log-tools |
