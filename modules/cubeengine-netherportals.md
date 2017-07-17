# CubeEngine - NetherPortals [WIP]
Modifies Vanilla Portal behaviours

## Features:
 - Change nether and ender portal destinations
 - Change distance scaling between worlds

## Commands:

| Command | Description | Permission<br>`cubeengine.netherportals.command.<perm>` |
| --- | --- | --- |
| [*netherportals*](#netherportals) | Manages Netherportals | `netherportals` |
| [**netherportals**&nbsp;*setEndTarget*](#netherportalssetendtarget) | Sets the EndPortal Target | `netherportals.setendtarget.use` |
| [**netherportals**&nbsp;*setNetherTarget*](#netherportalssetnethertarget) | Sets the NetherPortal Target | `netherportals.setnethertarget.use` |

#### netherportals  
Manages Netherportals  
**Usage:** `netherportals <command>`  
**Alias:** `np`  
**Permission:** `cubeengine.netherportals.command.netherportals`  
**SubCommands:** `setEndTarget` `setNetherTarget`  

#### netherportals&nbsp;setEndTarget  
Sets the EndPortal Target  
**Usage:** `netherportals setEndTarget <world> <target>`  
**Alias:** `end`  
**Permission:** `cubeengine.netherportals.command.netherportals.setendtarget.use`  
  

#### netherportals&nbsp;setNetherTarget  
Sets the NetherPortal Target  
**Usage:** `netherportals setNetherTarget <world> <target>`  
**Alias:** `nether`  
**Permission:** `cubeengine.netherportals.command.netherportals.setnethertarget.use`  
  

## Additional Permissions:

| Permission | Description |
| --- | --- |
| `cubeengine.netherportals` | Base Permission for NetherPortals |
| `cubeengine.netherportals.command` | Allows using all commands of NetherPortals |
