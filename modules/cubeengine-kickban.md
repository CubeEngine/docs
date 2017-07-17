# CubeEngine - KickBan
Kicks and Bans

## Features:
 - Enforce a kick/ban reasons

## Commands:

| Command | Description | Permission<br>`cubeengine.kickban.command.<perm>` |
| --- | --- | --- |
| [*ban*](#ban) | Bans a player permanently on your server. | `ban.use` |
| [*banlist*](#banlist) | View all players banned from this server | `banlist.use` |
| [*ipban*](#ipban) | Bans the IP from this server. | `ipban.use` |
| [*ipunban*](#ipunban) | Bans the IP from this server. | `ipunban.use` |
| [*kick*](#kick) | Kicks a player from the server | `kick.use` |
| [*tempban*](#tempban) | Bans a player for a given time. | `tempban.use` |
| [*unban*](#unban) | Unbans a previously banned player. | `unban.use` |

#### ban  
Bans a player permanently on your server.  
**Usage:** `ban <player> [reason] [-ipban] [-force]`  
**Alias:** `kickban`  
**Permission:** `cubeengine.kickban.command.ban.use`  
  

#### banlist  
View all players banned from this server  
**Usage:** `banlist <type> [filter]`  
**Permission:** `cubeengine.kickban.command.banlist.use`  
  

#### ipban  
Bans the IP from this server.  
**Usage:** `ipban <IP address> [reason]`  
**Alias:** `banip`  
**Permission:** `cubeengine.kickban.command.ipban.use`  
  

#### ipunban  
Bans the IP from this server.  
**Usage:** `ipunban <IP address>`  
**Alias:** `unbanip` `pardonip`  
**Permission:** `cubeengine.kickban.command.ipunban.use`  
  

#### kick  
Kicks a player from the server  
**Usage:** `kick <players> [reason]`  
**Permission:** `cubeengine.kickban.command.kick.use`  
  

#### tempban  
Bans a player for a given time.  
**Usage:** `tempban <player> <time> [reason] [-force]`  
**Alias:** `tban`  
**Permission:** `cubeengine.kickban.command.tempban.use`  
  

#### unban  
Unbans a previously banned player.  
**Usage:** `unban <player>`  
**Alias:** `pardon`  
**Permission:** `cubeengine.kickban.command.unban.use`  
  

## Additional Permissions:

| Permission | Description |
| --- | --- |
| `cubeengine.kickban` | Base Permission for KickBan |