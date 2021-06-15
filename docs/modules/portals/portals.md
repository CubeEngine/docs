# CubeEngine - Portals
Start thinking with portals

## Features:
 - Create portals anywhere
 - Random destinations
 - One-way portals

## Dependencies:
 `cubeengine-zoned`

## Commands:

| Command | Description | Permission<br>`cubeengine.portals.command.<perm>` |
| --- | --- | --- |
| [*portals*](#portals) | The portal commands |  |
| [**portals**&nbsp;*create*](#portalscreate) | Creates a new Portal | `portals.create.use` |
| [**portals**&nbsp;*debug*](#portalsdebug) | Shows debug portal information instead of teleporting | `portals.debug.use` |
| [**portals**&nbsp;*info*](#portalsinfo) | Show info about a portal | `portals.info.use` |
| [**portals**&nbsp;*list*](#portalslist) | Lists the portals | `portals.list.use` |
| [**portals**&nbsp;*modify*](#portalsmodify) | modifies a portal |  |
| [**portals**&nbsp;**modify**&nbsp;*destination*](#portalsmodifydestination) | changes the destination of the selected portal | `portals.modify.destination.use` |
| [**portals**&nbsp;**modify**&nbsp;*entity*](#portalsmodifyentity) | Toggles whether entities can teleport with this portal | `portals.modify.entity.use` |
| [**portals**&nbsp;**modify**&nbsp;*exit*](#portalsmodifyexit) | Modifies the location where a player exits when teleporting a portal | `portals.modify.exit.use` |
| [**portals**&nbsp;**modify**&nbsp;*location*](#portalsmodifylocation) | Changes a portals location | `portals.modify.location.use` |
| [**portals**&nbsp;**modify**&nbsp;*owner*](#portalsmodifyowner) | Changes the owner of a portal | `portals.modify.owner.use` |
| [**portals**&nbsp;**modify**&nbsp;*randdest*](#portalsmodifyranddest) | Changes the destination of the selected portal to a random position each time | `portals.modify.randomDestination.use` |
| [**portals**&nbsp;**modify**&nbsp;*togglesafe*](#portalsmodifytogglesafe) | Toggles safe teleportation for this portal | `portals.modify.togglesafe.use` |
| [**portals**&nbsp;*remove*](#portalsremove) | Removes a portal permanently | `portals.remove.use` |
| [**portals**&nbsp;*select*](#portalsselect) | Selects an existing portal | `portals.select.use` |

#### portals  
The portal commands  
**Usage:** `portals`  
**Alias:** `mvp`  
**SubCommands:** `create` `debug` `info` `list` `modify` `remove` `select`  

#### portals&nbsp;create  
Creates a new Portal  
**Usage:** `portals create <name> [destination]`  
**Permission:** `cubeengine.portals.command.portals.create.use`  
  

#### portals&nbsp;debug  
Shows debug portal information instead of teleporting  
**Usage:** `portals debug [isDebug]`  
**Permission:** `cubeengine.portals.command.portals.debug.use`  
  

#### portals&nbsp;info  
Show info about a portal  
**Usage:** `portals info [portal]`  
**Permission:** `cubeengine.portals.command.portals.info.use`  
  

#### portals&nbsp;list  
Lists the portals  
**Usage:** `portals list [world]`  
**Permission:** `cubeengine.portals.command.portals.list.use`  
  

#### portals&nbsp;modify  
modifies a portal  
**Usage:** `portals modify`  
**SubCommands:** `destination` `entity` `exit` `location` `owner` `randdest` `togglesafe`  

#### portals&nbsp;modify&nbsp;destination  
changes the destination of the selected portal  
**Usage:** `portals modify destination <here|<world>|p:<portal>> [portal]`  
**Alias:** `dest`  
**Permission:** `cubeengine.portals.command.portals.modify.destination.use`  
  

#### portals&nbsp;modify&nbsp;entity  
Toggles whether entities can teleport with this portal  
**Usage:** `portals modify entity [portal]`  
**Permission:** `cubeengine.portals.command.portals.modify.entity.use`  
  

#### portals&nbsp;modify&nbsp;exit  
Modifies the location where a player exits when teleporting a portal  
**Usage:** `portals modify exit [portal]`  
**Permission:** `cubeengine.portals.command.portals.modify.exit.use`  
  

#### portals&nbsp;modify&nbsp;location  
Changes a portals location  
**Usage:** `portals modify location [portal]`  
**Permission:** `cubeengine.portals.command.portals.modify.location.use`  
  

#### portals&nbsp;modify&nbsp;owner  
Changes the owner of a portal  
**Usage:** `portals modify owner <owner> [portal]`  
**Permission:** `cubeengine.portals.command.portals.modify.owner.use`  
  

#### portals&nbsp;modify&nbsp;randdest  
Changes the destination of the selected portal to a random position each time  
**Usage:** `portals modify randdest <world> [portal]`  
**Alias:** `randomdestination`  
**Permission:** `cubeengine.portals.command.portals.modify.randomDestination.use`  
  

#### portals&nbsp;modify&nbsp;togglesafe  
Toggles safe teleportation for this portal  
**Usage:** `portals modify togglesafe [portal]`  
**Permission:** `cubeengine.portals.command.portals.modify.togglesafe.use`  
  

#### portals&nbsp;remove  
Removes a portal permanently  
**Usage:** `portals remove [portal]`  
**Permission:** `cubeengine.portals.command.portals.remove.use`  
  

#### portals&nbsp;select  
Selects an existing portal  
**Usage:** `portals select <portal>`  
**Permission:** `cubeengine.portals.command.portals.select.use`  
  

## Permissions:

| Permission | Description |
| --- | --- |
| `cubeengine.portals` | Base Permission for Portals |
