# CubeEngine - Locker

Put a lock onto your most precious things

## Commands

#### locker

Locker commands

Usage: `locker <command>`

Alias:
`l`

Permission: `cubeengine.locker.command.locker`

Child Commands:
`admin`
`create`
`flag`
`give`
`info`
`key`
`modify`
`persist`
`remove`
`unlock`

#### locker admin

Administrate the protections

Usage: `locker admin <command>`

Permission: `cubeengine.locker.command.locker.admin`

Child Commands:
`cleanup`
`purge`
`remove`
`tp`
`view`

#### locker admin cleanup

Deletes old locks

Usage: `locker admin cleanup `

Permission: `cubeengine.locker.command.locker.admin.cleanup.use`

#### locker admin purge

Deletes all locks of given player

Usage: `locker admin purge <player>`

Permission: `cubeengine.locker.command.locker.admin.purge.use`

#### locker admin remove

Deletes a protection by its id

Usage: `locker admin remove <id>`

Permission: `cubeengine.locker.command.locker.admin.remove.use`

#### locker admin tp

Teleport to a protection

Usage: `locker admin tp <id>`

Permission: `cubeengine.locker.command.locker.admin.tp.use`

#### locker admin view

Opens a protected chest by protection id

Usage: `locker admin view <id>`

Permission: `cubeengine.locker.command.locker.admin.view.use`

#### locker create

Creates various protections

Usage: `locker create <command>`

Permission: `cubeengine.locker.command.locker.create`

Child Commands:
`donation`
`free`
`guarded`
`password`
`private`
`public`

#### locker create donation

creates a donation protection

Usage: `locker create donation [password] [-keybook]`

Alias:
`/cdonation`

Permission: `cubeengine.locker.command.locker.create.donation.use`

#### locker create free

creates a free protection

Usage: `locker create free [password] [-keybook]`

Alias:
`/cfree`

Permission: `cubeengine.locker.command.locker.create.free.use`

#### locker create guarded

creates a guarded protection

Usage: `locker create guarded [password] [-keybook]`

Alias:
`/cguarded`

Permission: `cubeengine.locker.command.locker.create.guarded.use`

#### locker create password

creates a donation protection

Usage: `locker create password <password> [-keybook]`

Alias:
`/cpassword`

Permission: `cubeengine.locker.command.locker.create.password.use`

#### locker create private

creates a private protection

Usage: `locker create private [password] [-keybook]`

Alias:
`/cprivate`

Permission: `cubeengine.locker.command.locker.create.private.use`

#### locker create public

creates a public protection

Usage: `locker create public `

Alias:
`/cpublic`

Permission: `cubeengine.locker.command.locker.create.public.use`

#### locker flag

Sets or unsets flags

Usage: `locker flag [set <flags...>] [unset <flags...>] [-persist]`

Alias:
`/cflag`

Permission: `cubeengine.locker.command.locker.flag.use`

#### locker give

gives a protection to someone else

Usage: `locker give <player> [-persist]`

Alias:
`/cgive`

Permission: `cubeengine.locker.command.locker.give.use`

#### locker info

Shows information about a protection

Usage: `locker info [-persist]`

Alias:
`/cinfo`

Permission: `cubeengine.locker.command.locker.info.use`

#### locker key

creates a KeyBook or invalidates previous KeyBooks

Usage: `locker key [-invalidate] [-persist]`

Alias:
`/ckey`

Permission: `cubeengine.locker.command.locker.key.use`

#### locker modify

adds or removes player from the accesslist

Usage: `locker modify <players> [-global] [-persist]`

Alias:
`/cmodify`

Permission: `cubeengine.locker.command.locker.modify.use`

#### locker persist

persists your last locker command

Usage: `locker persist `

Alias:
`/cpersist`

Permission: `cubeengine.locker.command.locker.persist.use`

#### locker remove

Shows information about a protection

Usage: `locker remove [-persist]`

Alias:
`/cremove`

Permission: `cubeengine.locker.command.locker.remove.use`

#### locker unlock

Unlocks a password protected chest

Usage: `locker unlock <password> [-persist]`

Alias:
`/cunlock`

Permission: `cubeengine.locker.command.locker.unlock.use`

## Additional Permissions

 - ##### `cubeengine.locker`
   Base Permission for locker

