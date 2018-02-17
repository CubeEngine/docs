# CubeEngine - Squelch
Mute or Ignore other players

## Features:
 - Players can ignore messages from other players
 - Preventing players from chatting at all

## Commands:

| Command | Description | Permission<br>`cubeengine.squelch.command.<perm>` |
| --- | --- | --- |
| [*mute*](#mute) | Mutes a player | `mute.use` |
| [*unmute*](#unmute) | Unmutes a player | `unmute.use` |

#### mute  
Mutes a player  
**Usage:** `mute <player> [duration]`  
**Permission:** `cubeengine.squelch.command.mute.use`  
  

#### unmute  
Unmutes a player  
**Usage:** `unmute <player>`  
**Permission:** `cubeengine.squelch.command.unmute.use`  
  

## Permissions:

| Permission | Description |
| --- | --- |
| `cubeengine.squelch` | Base Permission for Squelch |
| `cubeengine.squelch.command` | Allows using all commands of Squelch |
| `cubeengine.squelch.command.ignore.prevent` | Prevents adding the player with this permission to an ignore-list |
