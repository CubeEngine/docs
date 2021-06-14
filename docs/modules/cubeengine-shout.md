# CubeEngine - Shout
Announce things!

## Features:
 - Reoccurring chat announcements
 - Permissions control announcement receivers
 - Timers are per-player

## Commands:

| Command | Description | Permission<br>`cubeengine.shout.command.<perm>` |
| --- | --- | --- |
| [*shout*](#shout) | Announce a message to players on the server | `shout` |
| [**shout**&nbsp;*create*](#shoutcreate) | Creates a new announcement | `shout.create.use` |
| [**shout**&nbsp;*delete*](#shoutdelete) | delete an announcement | `shout.delete.use` |
| [**shout**&nbsp;*list*](#shoutlist) | List all announcements | `shout.list.use` |
| [**shout**&nbsp;*modify*](#shoutmodify) | modifies an announcement | `shout.modify.use` |
| [**shout**&nbsp;*reload*](#shoutreload) | clean all loaded announcements from memory and load from disk | `shout.reload.use` |
| [**shout**&nbsp;*show*](#shoutshow) | Displays an announcement | `shout.show.use` |

#### shout  
Announce a message to players on the server  
**Usage:** `shout <command>`  
**Alias:** `announce`  
**Permission:** `cubeengine.shout.command.shout`  
**SubCommands:** `create` `delete` `list` `modify` `reload` `show`  

#### shout&nbsp;create  
Creates a new announcement  
**Usage:** `shout create <name> <message> [delay <<x> minutes|hours|days>] [permission <permission>] [weight <weight>] [-fixed-cycle] [-asJson]`  
**Permission:** `cubeengine.shout.command.shout.create.use`  
  

#### shout&nbsp;delete  
delete an announcement  
**Usage:** `shout delete <announcement>`  
**Permission:** `cubeengine.shout.command.shout.delete.use`  
  

#### shout&nbsp;list  
List all announcements  
**Usage:** `shout list `  
**Alias:** `announcements` `/announcements`  
**Permission:** `cubeengine.shout.command.shout.list.use`  
  

#### shout&nbsp;modify  
modifies an announcement  
**Usage:** `shout modify <announcement> <message> [locale <locale>] [-append] [-asJson]`  
**Permission:** `cubeengine.shout.command.shout.modify.use`  
  

#### shout&nbsp;reload  
clean all loaded announcements from memory and load from disk  
**Usage:** `shout reload `  
**Permission:** `cubeengine.shout.command.shout.reload.use`  
  

#### shout&nbsp;show  
Displays an announcement  
**Usage:** `shout show <announcement>`  
**Permission:** `cubeengine.shout.command.shout.show.use`  
  

## Permissions:

| Permission | Description |
| --- | --- |
| `cubeengine.shout` | Base Permission for Shout |
| `cubeengine.shout.announcement` |  |
| `cubeengine.shout.command` | Allows using all commands of Shout |
