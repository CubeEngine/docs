# CubeEngine - Hide [WIP]
This module allows players to hide themselves.

## Features:
 - Hide a player from all or a few other players
 - Supress chat messages

## Commands:

| Command | Description | Permission<br>`cubeengine.hide.command.<perm>` |
| --- | --- | --- |
| [*hidden*](#hidden) | Checks whether a player is hidden. | `hidden.use` |
| [*hide*](#hide) | Hides a player. | `hide.use` |
| [*listhiddens*](#listhiddens) | Lists all hidden players. | `listhiddens.use` |
| [*unhide*](#unhide) | Unhides a player. | `unhide.use` |

#### hidden  
Checks whether a player is hidden.  
**Usage:** `hidden <player>`  
**Permission:** `cubeengine.hide.command.hidden.use`  
  

#### hide  
Hides a player.  
**Usage:** `hide <player>`  
**Permission:** `cubeengine.hide.command.hide.use`  
  

#### listhiddens  
Lists all hidden players.  
**Usage:** `listhiddens `  
**Permission:** `cubeengine.hide.command.listhiddens.use`  
  

#### unhide  
Unhides a player.  
**Usage:** `unhide <player>`  
**Permission:** `cubeengine.hide.command.unhide.use`  
  

## Permissions:

| Permission | Description |
| --- | --- |
| `cubeengine.hide` | Base Permission for Hide |
| `cubeengine.hide.auto` |  |
| `cubeengine.hide.auto.hide` |  |
| `cubeengine.hide.auto.see-hidden` |  |
| `cubeengine.hide.chat` |  |
| `cubeengine.hide.command` | Allows using all commands of Hide |
| `cubeengine.hide.drop` |  |
| `cubeengine.hide.interact` |  |
| `cubeengine.hide.pickup` |  |
