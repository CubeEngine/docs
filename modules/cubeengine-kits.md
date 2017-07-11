# CubeEngine - Kits

Hand kits to your players

## Commands

#### kit

Manages item-kits

Usage: `kit <command>`

Permission: `cubeengine.kits.command.kit`

Child Commands:
`create`
`delete`
`give`
`giveall`
`list`
`setCommand`

#### kit create

Opens the configured kit if the kit does not exists a new is created

Usage: `kit create <kitname>`

Alias:
`open`

Permission: `cubeengine.kits.command.kit.create.use`

#### kit delete

Deletes a kit

Usage: `kit delete <kit>`

Alias:
`remove`

Permission: `cubeengine.kits.command.kit.delete.use`

#### kit give

Gives a set of items.

Usage: `kit give <kit> <player> [-force]`

Permission: `cubeengine.kits.command.kit.give.use`

#### kit giveall

Gives a kit to every online player

Usage: `kit giveall <kit> [-force]`

Permission: `cubeengine.kits.command.kit.giveall.use`

#### kit list

Lists all currently available kits.

Usage: `kit list `

Alias:
`/kitlist`

Permission: `cubeengine.kits.command.kit.list.use`

#### kit setCommand

Sets a command to be run when a kit is received

Usage: `kit setCommand <kit> [commands]`

Permission: `cubeengine.kits.command.kit.setcommand.use`

## Additional Permissions

 - ##### `cubeengine.kits`
   Base Permission for kits

