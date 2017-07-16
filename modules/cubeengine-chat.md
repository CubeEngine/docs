# CubeEngine - Chat
This module adds chat formatting functionality.

## Features:
 - Configurable chat line
 - Subject options support
 - Whisper chat commands
 - AFK detection
 - Chat colors

## Commands:

| Command | Description | Permission<br>`cubeengine.chat.command.<perm>` |
| --- | --- | --- |
| [*nick*](#nick) | Changes your display name | `nick.use` |
| [*broadcast*](#broadcast) | Broadcasts a message | `broadcast.use` |
| [*afk*](#afk) | Displays that you are afk | `afk.use` |
| [*me*](#me) | Allows you to emote | `me.use` |
| [*chatcolors*](#chatcolors) | Displays the colors | `chatcolors.use` |
| [*msg*](#msg) | Sends a private message to someone | `msg.use` |
| [*rand*](#rand) | Shows a random number from 0 to 100 | `rand.use` |
| [*reply*](#reply) | Replies to the last person that whispered to you. | `reply.use` |

#### nick  
Changes your display name  
**Usage:** `nick <<name>|-reset> [player]`  
**Permission:** `cubeengine.chat.command.nick.use`  
  

#### broadcast  
Broadcasts a message  
**Usage:** `broadcast <message>`  
**Permission:** `cubeengine.chat.command.broadcast.use`  
  

#### afk  
Displays that you are afk  
**Usage:** `afk <player>`  
**Permission:** `cubeengine.chat.command.afk.use`  
  

#### me  
Allows you to emote  
**Usage:** `me <message>`  
**Permission:** `cubeengine.chat.command.me.use`  
  

#### chatcolors  
Displays the colors  
**Usage:** `chatcolors `  
**Permission:** `cubeengine.chat.command.chatcolors.use`  
  

#### msg  
Sends a private message to someone  
**Usage:** `msg <player> <message>`  
**Alias:** `tell` `message` `pm` `m` `t` `whisper` `w`  
**Permission:** `cubeengine.chat.command.msg.use`  
  

#### rand  
Shows a random number from 0 to 100  
**Usage:** `rand `  
**Alias:** `roll`  
**Permission:** `cubeengine.chat.command.rand.use`  
  

#### reply  
Replies to the last person that whispered to you.  
**Usage:** `reply <message>`  
**Alias:** `r`  
**Permission:** `cubeengine.chat.command.reply.use`  
  

## Additional Permissions:

| Permission | Description |
| --- | --- |
| `cubeengine.chat` | Base Permission for chat |