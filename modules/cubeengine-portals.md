# CubeEngine - Portals

Start thinking with portals

## Commands

#### portals

The portal commands

Usage: `portals <command>`

Alias:
`mvp`

Permission: `cubeengine.portals.command.portals`

Child Commands:
`create`
`debug`
`info`
`list`
`modify`
`remove`
`select`

#### portals create

Creates a new Portal

Usage: `portals create <name> [destination]`

Alias:
`/mvpc`

Permission: `cubeengine.portals.command.portals.create.use`

#### portals debug

Shows debug portal information instead of teleporting

Usage: `portals debug [onOff]`

Permission: `cubeengine.portals.command.portals.debug.use`

#### portals info

Show info about a portal

Usage: `portals info <portal>`

Alias:
`/mvpi`

Permission: `cubeengine.portals.command.portals.info.use`

#### portals list

Lists the portals

Usage: `portals list <world>`

Alias:
`/mvpl`

Permission: `cubeengine.portals.command.portals.list.use`

#### portals modify

modifies a portal

Usage: `portals modify <command>`

Alias:
`/mvpm`

Permission: `cubeengine.portals.command.portals.modify`

Child Commands:
`destination`
`entity`
`exit`
`location`
`owner`
`randomDestination`
`togglesafe`

#### portals modify destination

changes the destination of the selected portal

Usage: `portals modify destination <destination> <portal>`

Alias:
`dest`
`/mvpd`

Permission: `cubeengine.portals.command.portals.modify.destination.use`

#### portals modify entity

Toggles whether entities can teleport with this portal

Usage: `portals modify entity <portal>`

Permission: `cubeengine.portals.command.portals.modify.entity.use`

#### portals modify exit

Modifies the location where a player exits when teleporting a portal

Usage: `portals modify exit <portal>`

Permission: `cubeengine.portals.command.portals.modify.exit.use`

#### portals modify location

Changes a portals location

Usage: `portals modify location <portal>`

Permission: `cubeengine.portals.command.portals.modify.location.use`

#### portals modify owner

Changes the owner of a portal

Usage: `portals modify owner <owner> <portal>`

Permission: `cubeengine.portals.command.portals.modify.owner.use`

#### portals modify randomDestination

Changes the destination of the selected portal to a random position each time

Usage: `portals modify randomDestination <world> <portal>`

Alias:
`randdest`
`/mvprd`

Permission: `cubeengine.portals.command.portals.modify.randomdestination.use`

#### portals modify togglesafe

Toggles safe teleportation for this portal

Usage: `portals modify togglesafe <portal>`

Permission: `cubeengine.portals.command.portals.modify.togglesafe.use`

#### portals remove

Removes a portal permanently

Usage: `portals remove <portal>`

Alias:
`/mvpr`

Permission: `cubeengine.portals.command.portals.remove.use`

#### portals select

Selects an existing portal

Usage: `portals select <portal>`

Alias:
`/mvps`

Permission: `cubeengine.portals.command.portals.select.use`

## Additional Permissions

 - ##### `cubeengine.portals`
   Base Permission for portals

