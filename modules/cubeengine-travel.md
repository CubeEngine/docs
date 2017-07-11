# CubeEngine - Travel

Travel anywhere!

## Commands

#### warp

Teleport to a warp

Usage: `warp <command>`

Permission: `cubeengine.travel.command.warp`

Child Commands:
`clear`
`create`
`greeting`
`list`
`move`
`remove`
`rename`
`tp`

#### warp clear

Clear all warps [of a player]

Usage: `warp clear [owner]`

Alias:
`/clearwarps`

Permission: `cubeengine.travel.command.warp.clear.use`

#### warp create

Create a warp

Usage: `warp create <name>`

Alias:
`make`
`/createwarp`
`/mkwarp`
`/makewarp`

Permission: `cubeengine.travel.command.warp.create.use`

#### warp greeting

Set the welcome message of warps

Usage: `warp greeting <warp> [welcome message] [-append]`

Alias:
`setgreeting`
`setwelcome`
`setwelcomemsg`

Permission: `cubeengine.travel.command.warp.greeting.use`

#### warp list

List warps of a player

Usage: `warp list [owner]`

Permission: `cubeengine.travel.command.warp.list.use`

#### warp move

Move a warp

Usage: `warp move <warp>`

Permission: `cubeengine.travel.command.warp.move.use`

#### warp remove

Remove a warp

Usage: `warp remove <warp>`

Alias:
`delete`
`/removewarp`
`/deletewarp`
`/delwarp`
`/remwarp`

Permission: `cubeengine.travel.command.warp.remove.use`

#### warp rename

Rename a warp

Usage: `warp rename <warp> <new name>`

Permission: `cubeengine.travel.command.warp.rename.use`

#### warp tp

Teleport to a warp

Usage: `warp tp <warp>`

Permission: `cubeengine.travel.command.warp.tp.use`

#### home

Teleport to your home

Usage: `home <command>`

Permission: `cubeengine.travel.command.home`

Child Commands:
`clear`
`greeting`
`ilist`
`invite`
`list`
`move`
`remove`
`rename`
`set`
`tp`
`unInvite`

#### home clear

Clear all homes [of a player]

Usage: `home clear [owner] [-selection]`

Alias:
`/clearhomes`

Permission: `cubeengine.travel.command.home.clear.use`

#### home greeting

Set the welcome message of homes

Usage: `home greeting <home> [welcome message] [owner <owner>] [-append]`

Alias:
`setgreeting`
`setwelcome`
`setwelcomemsg`

Permission: `cubeengine.travel.command.home.greeting.use`

#### home ilist

List all players invited to your homes

Usage: `home ilist <owner>`

Alias:
`invited`

Permission: `cubeengine.travel.command.home.ilist.use`

#### home invite

Invite a user to one of your homes

Usage: `home invite <player> [home]`

Permission: `cubeengine.travel.command.home.invite.use`

#### home list

Lists homes a player can access

Usage: `home list <owner> [-owned] [-invited]`

Alias:
`listhomes`
`/listhomes`
`/homes`

Permission: `cubeengine.travel.command.home.list.use`

#### home move

Move a home

Usage: `home move [name] <owner>`

Alias:
`replace`

Permission: `cubeengine.travel.command.home.move.use`

#### home remove

Remove a home

Usage: `home remove [name] [owner]`

Alias:
`delete`
`rem`
`del`
`/remhome`
`/removehome`
`/delhome`
`/deletehome`

Permission: `cubeengine.travel.command.home.remove.use`

#### home rename

Rename a home

Usage: `home rename <home> <new name> [owner]`

Permission: `cubeengine.travel.command.home.rename.use`

#### home set

Set your home

Usage: `home set [name]`

Alias:
`create`
`sethome`
`createhome`
`/sethome`

Permission: `cubeengine.travel.command.home.set.use`

#### home tp

Teleport to a home

Usage: `home tp [home] <owner>`

Permission: `cubeengine.travel.command.home.tp.use`

#### home unInvite

Uninvite a player from one of your homes

Usage: `home unInvite <player> [home]`

Permission: `cubeengine.travel.command.home.uninvite.use`

## Additional Permissions

 - ##### `cubeengine.travel`
   Base Permission for travel

