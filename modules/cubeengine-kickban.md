# CubeEngine - KickBan

Kicks and Bans

## Commands

#### ipunban

Bans the IP from this server.

Usage: `ipunban <IP address>`

Alias:
`unbanip`
`pardonip`

Permission: `cubeengine.kickban.command.ipunban.use`

#### ipban

Bans the IP from this server.

Usage: `ipban <IP address> [reason]`

Alias:
`banip`

Permission: `cubeengine.kickban.command.ipban.use`

#### unban

Unbans a previously banned player.

Usage: `unban <player>`

Alias:
`pardon`

Permission: `cubeengine.kickban.command.unban.use`

#### banlist

View all players banned from this server

Usage: `banlist <type> [filter]`

Permission: `cubeengine.kickban.command.banlist.use`

#### ban

Bans a player permanently on your server.

Usage: `ban <player> [reason] [-ipban] [-force]`

Alias:
`kickban`

Permission: `cubeengine.kickban.command.ban.use`

#### tempban

Bans a player for a given time.

Usage: `tempban <player> <time> [reason] [-force]`

Alias:
`tban`

Permission: `cubeengine.kickban.command.tempban.use`

#### kick

Kicks a player from the server

Usage: `kick <players> [reason]`

Permission: `cubeengine.kickban.command.kick.use`

## Additional Permissions

 - ##### `cubeengine.kickban`
   Base Permission for kickban

