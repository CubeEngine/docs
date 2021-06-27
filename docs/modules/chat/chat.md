# CubeEngine - Chat
This module adds chat formatting functionality.

## Features:
 - Configurable chat line
 - Subject options support
 - Whisper chat commands
 - AFK detection
 - Chat colors

## Pages:
 - [Usage](pages/usage.md)

## Config:
 - [ChatConfig](pages/config-chatconfig.md)

## Commands:

| Command | Description | Permission<br>`cubeengine.chat.command.<perm>` |
| --- | --- | --- |
| [*afk*](#afk) | Displays that you are afk | `afk.use` |
| [*broadcast*](#broadcast) | Broadcasts a message | `broadcast.use` |
| [*chatcolors*](#chatcolors) | Displays the colors | `chatcolors.use` |
| [*me*](#me) | Allows you to emote | `me.use` |
| [*msg*](#msg) | Sends a private message to someone | `msg.use` |
| [*nick*](#nick) | Changes your display name | `nick.use` |
| [*rand*](#rand) | Shows a random number from 0 to 100 | `rand.use` |
| [*reply*](#reply) | Replies to the last person that whispered to you. | `reply.use` |

#### afk  
Displays that you are afk  
**Usage:** `afk [player]`  
**Permission:** `cubeengine.chat.command.afk.use`  
  

#### broadcast  
Broadcasts a message  
**Usage:** `broadcast <message>`  
**Permission:** `cubeengine.chat.command.broadcast.use`  
  

#### chatcolors  
Displays the colors  
**Usage:** `chatcolors`  
**Permission:** `cubeengine.chat.command.chatcolors.use`  
  

#### me  
Allows you to emote  
**Usage:** `me <message>`  
**Permission:** `cubeengine.chat.command.me.use`  
  

#### msg  
Sends a private message to someone  
**Usage:** `msg <player> <message>`  
**Alias:** `t` `tell` `w` `whisper` `message` `pm` `m`  
**Permission:** `cubeengine.chat.command.msg.use`  
  

#### nick  
Changes your display name  
**Usage:** `nick <<name>|-reset> [player]`  
**Permission:** `cubeengine.chat.command.nick.use`  
  

#### rand  
Shows a random number from 0 to 100  
**Usage:** `rand [dice]`  
**Alias:** `roll`  
**Permission:** `cubeengine.chat.command.rand.use`  
  

#### reply  
Replies to the last person that whispered to you.  
**Usage:** `reply <message>`  
**Alias:** `r`  
**Permission:** `cubeengine.chat.command.reply.use`  
  

## Permissions:

| Permission | Description |
| --- | --- |
| `cubeengine.chat` | Base Permission for Chat |
| `cubeengine.chat.color` | Allows using color codes in chat |
| `cubeengine.chat.command.afk.other` | Allows to set or unset the afk status of other players |
| `cubeengine.chat.command.afk.prevent.autoafk` | Prevents from being displayed as afk automatically |
| `cubeengine.chat.command.afk.prevent.autounafk` | Prevents from being displayed as no longer afk automatically unless using chat |
| `cubeengine.chat.command.nick.of-other` | Allows to set the nickname to a players name that plays on this server |
| `cubeengine.chat.command.nick.other` | Allows to set the nickname of another player |
| `cubeengine.chat.longer` | Allows using a + at the end of chat to write longer messages |
| `cubeengine.chat.newline` | Allows using newlines (\n) in chat |
