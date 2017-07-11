# CubeEngine - Portals
Start thinking with portals
## Features:
 - Create portals anywhere
 - Random destinations
 - One-way portals
## Commands
| Command | Description | Permission<br>`cubeengine.portals.command.<perm>` |
| --- | --- | --- |
| [*portals*](#portals) | The portal commands | `portals` |
| [**portals** *create*](#portals-create) | Creates a new Portal | `portals.create.use` |
| [**portals** *debug*](#portals-debug) | Shows debug portal information instead of teleporting | `portals.debug.use` |
| [**portals** *info*](#portals-info) | Show info about a portal | `portals.info.use` |
| [**portals** *list*](#portals-list) | Lists the portals | `portals.list.use` |
| [**portals** *modify*](#portals-modify) | modifies a portal | `portals.modify` |
| [**portals** **modify** *destination*](#portals-modify-destination) | changes the destination of the selected portal | `portals.modify.destination.use` |
| [**portals** **modify** *entity*](#portals-modify-entity) | Toggles whether entities can teleport with this portal | `portals.modify.entity.use` |
| [**portals** **modify** *exit*](#portals-modify-exit) | Modifies the location where a player exits when teleporting a portal | `portals.modify.exit.use` |
| [**portals** **modify** *location*](#portals-modify-location) | Changes a portals location | `portals.modify.location.use` |
| [**portals** **modify** *owner*](#portals-modify-owner) | Changes the owner of a portal | `portals.modify.owner.use` |
| [**portals** **modify** *randomDestination*](#portals-modify-randomdestination) | Changes the destination of the selected portal to a random position each time | `portals.modify.randomdestination.use` |
| [**portals** **modify** *togglesafe*](#portals-modify-togglesafe) | Toggles safe teleportation for this portal | `portals.modify.togglesafe.use` |
| [**portals** *remove*](#portals-remove) | Removes a portal permanently | `portals.remove.use` |
| [**portals** *select*](#portals-select) | Selects an existing portal | `portals.select.use` |
#### portals  
The portal commands  
**Usage:** `portals <command>`  
**Alias:** `mvp`  
**Permission:** `cubeengine.portals.command.portals`  
**SubCommands:** `create` `debug` `info` `list` `modify` `remove` `select`  
#### portals create  
Creates a new Portal  
**Usage:** `portals create <name> [destination]`  
**Alias:** `/mvpc`  
**Permission:** `cubeengine.portals.command.portals.create.use`  
  
#### portals debug  
Shows debug portal information instead of teleporting  
**Usage:** `portals debug [onOff]`  
**Permission:** `cubeengine.portals.command.portals.debug.use`  
  
#### portals info  
Show info about a portal  
**Usage:** `portals info <portal>`  
**Alias:** `/mvpi`  
**Permission:** `cubeengine.portals.command.portals.info.use`  
  
#### portals list  
Lists the portals  
**Usage:** `portals list <world>`  
**Alias:** `/mvpl`  
**Permission:** `cubeengine.portals.command.portals.list.use`  
  
#### portals modify  
modifies a portal  
**Usage:** `portals modify <command>`  
**Alias:** `/mvpm`  
**Permission:** `cubeengine.portals.command.portals.modify`  
**SubCommands:** `destination` `entity` `exit` `location` `owner` `randomDestination` `togglesafe`  
#### portals modify destination  
changes the destination of the selected portal  
**Usage:** `portals modify destination <destination> <portal>`  
**Alias:** `dest` `/mvpd`  
**Permission:** `cubeengine.portals.command.portals.modify.destination.use`  
  
#### portals modify entity  
Toggles whether entities can teleport with this portal  
**Usage:** `portals modify entity <portal>`  
**Permission:** `cubeengine.portals.command.portals.modify.entity.use`  
  
#### portals modify exit  
Modifies the location where a player exits when teleporting a portal  
**Usage:** `portals modify exit <portal>`  
**Permission:** `cubeengine.portals.command.portals.modify.exit.use`  
  
#### portals modify location  
Changes a portals location  
**Usage:** `portals modify location <portal>`  
**Permission:** `cubeengine.portals.command.portals.modify.location.use`  
  
#### portals modify owner  
Changes the owner of a portal  
**Usage:** `portals modify owner <owner> <portal>`  
**Permission:** `cubeengine.portals.command.portals.modify.owner.use`  
  
#### portals modify randomDestination  
Changes the destination of the selected portal to a random position each time  
**Usage:** `portals modify randomDestination <world> <portal>`  
**Alias:** `randdest` `/mvprd`  
**Permission:** `cubeengine.portals.command.portals.modify.randomdestination.use`  
  
#### portals modify togglesafe  
Toggles safe teleportation for this portal  
**Usage:** `portals modify togglesafe <portal>`  
**Permission:** `cubeengine.portals.command.portals.modify.togglesafe.use`  
  
#### portals remove  
Removes a portal permanently  
**Usage:** `portals remove <portal>`  
**Alias:** `/mvpr`  
**Permission:** `cubeengine.portals.command.portals.remove.use`  
  
#### portals select  
Selects an existing portal  
**Usage:** `portals select <portal>`  
**Alias:** `/mvps`  
**Permission:** `cubeengine.portals.command.portals.select.use`  
  
## Additional Permissions

| Permission | Description |
| --- | --- |
| `cubeengine.portals` | Base Permission for portals |