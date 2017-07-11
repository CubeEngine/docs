# CubeEngine - Vigil
Log everything you want!
## Features:
 - Tracks any world changes
 - Storage in MongoDB database
 - Ingame lookup and restore
 - Restore preview
## Dependencies:
 `cubeengine-bigdata`
## Commands
| Command | Description | Permission<br>`cubeengine.vigil.command.<perm>` |
| --- | --- | --- |
| [*vigil*](#vigil) | Vigil-Module Commands | `vigil` |
| [**vigil** *admin*](#vigil-admin) | Vigil-Admin Commands | `vigil.admin` |
| [**vigil** **admin** *purge*](#vigil-admin-purge) | purges all logs | `vigil.admin.purge.use` |
| [**vigil** **admin** *setReportActive*](#vigil-admin-setreportactive) | enables or disables reports in a world | `vigil.admin.setreportactive.use` |
| [**vigil** *block*](#vigil-block) | Gives you a block to check logs with.no log-type: Shows everything
chest: Shows chest-interactions only
player: Shows player-interactions only
kills: Shows kill-interactions only
block: Shows block-changes only | `vigil.block.use` |
| [**vigil** *tool*](#vigil-tool) | Gives you an item to check logs with.
no log-type: Shows everything
chest: Shows chest-interactions only
player: Shows player-interactions only
kills: Shows kill-interactions only
block: Shows block-changes only | `vigil.tool.use` |
#### vigil  
Vigil-Module Commands  
**Usage:** `vigil <command>`  
**Alias:** `log`  
**Permission:** `cubeengine.vigil.command.vigil`  
**SubCommands:** `admin` `block` `tool`  
#### vigil admin  
Vigil-Admin Commands  
**Usage:** `vigil admin <command>`  
**Permission:** `cubeengine.vigil.command.vigil.admin`  
**SubCommands:** `purge` `setReportActive`  
#### vigil admin purge  
purges all logs  
**Usage:** `vigil admin purge `  
**Permission:** `cubeengine.vigil.command.vigil.admin.purge.use`  
  
#### vigil admin setReportActive  
enables or disables reports in a world  
**Usage:** `vigil admin setReportActive <world> <name> <enable>`  
**Permission:** `cubeengine.vigil.command.vigil.admin.setreportactive.use`  
  
#### vigil block  
Gives you a block to check logs with.no log-type: Shows everything
chest: Shows chest-interactions only
player: Shows player-interactions only
kills: Shows kill-interactions only
block: Shows block-changes only  
**Usage:** `vigil block [log-type]`  
**Alias:** `/lb`  
**Permission:** `cubeengine.vigil.command.vigil.block.use`  
  
#### vigil tool  
Gives you an item to check logs with.
no log-type: Shows everything
chest: Shows chest-interactions only
player: Shows player-interactions only
kills: Shows kill-interactions only
block: Shows block-changes only  
**Usage:** `vigil tool [log-type]`  
**Alias:** `/lt`  
**Permission:** `cubeengine.vigil.command.vigil.tool.use`  
  
## Additional Permissions

| Permission | Description |
| --- | --- |
| `cubeengine.vigil` | Base Permission for vigil |