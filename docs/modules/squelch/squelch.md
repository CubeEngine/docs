# CubeEngine - Squelch
Mute or Ignore other players

## Features:
 - Players can ignore messages from other players
 - Preventing players from chatting at all

## Commands:

| Command | Description | Permission<br>`cubeengine.squelch.command.<perm>` |
| --- | --- | --- |
| [*ignore*](#ignore) | Ignores all messages from players | `ignore.use` |
| [*mute*](#mute) | Mutes a player | `mute.use` |
| [*unignore*](#unignore) | Stops ignoring all messages from a player | `unignore.use` |
| [*unmute*](#unmute) | Unmutes a player | `unmute.use` |

#### ignore  
Ignores all messages from players  
**Usage:** `ignore <player>`  
**Permission:** `cubeengine.squelch.command.ignore.use`  
  

#### mute  
Mutes a player  
**Usage:** `mute <player> [duration]`  
**Permission:** `cubeengine.squelch.command.mute.use`  
  

#### unignore  
Stops ignoring all messages from a player  
**Usage:** `unignore <player>`  
**Permission:** `cubeengine.squelch.command.unignore.use`  
  

#### unmute  
Unmutes a player  
**Usage:** `unmute <player>`  
**Permission:** `cubeengine.squelch.command.unmute.use`  
  

## Permissions:

| Permission | Description |
| --- | --- |
| `cubeengine.squelch` | Base Permission for Squelch |
| `cubeengine.squelch.command.ignore.prevent` | Prevents adding the player with this permission to an ignore-list |
