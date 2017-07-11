# CubeEngine - Shout

Announce things!

## Commands

#### shout

Announce a message to players on the server

Usage: `shout <command>`

Alias:
`announce`

Permission: `cubeengine.shout.command.shout`

Child Commands:
`create`
`delete`
`list`
`modify`
`reload`
`show`

#### shout create

Creates a new announcement

Usage: `shout create <name> [message <message>] [delay <<x> minutes|hours|days>] [permission <permission>] [weight <weight>] [-fixed-cycle]`

Permission: `cubeengine.shout.command.shout.create.use`

#### shout delete

delete an announcement

Usage: `shout delete <announcement>`

Permission: `cubeengine.shout.command.shout.delete.use`

#### shout list

List all announcements

Usage: `shout list `

Alias:
`announcements`
`/announcements`

Permission: `cubeengine.shout.command.shout.list.use`

#### shout modify

modifies an announcement

Usage: `shout modify <announcement> <message> [locale <locale>] [-append]`

Permission: `cubeengine.shout.command.shout.modify.use`

#### shout reload

clean all loaded announcements from memory and load from disk

Usage: `shout reload `

Permission: `cubeengine.shout.command.shout.reload.use`

#### shout show

Displays an announcement

Usage: `shout show <announcement>`

Permission: `cubeengine.shout.command.shout.show.use`

## Additional Permissions

 - ##### `cubeengine.shout`
   Base Permission for shout

