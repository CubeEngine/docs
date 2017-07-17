# CubeEngine - Mail
Mails

## Features:
 - Sends mails between players

## Commands:

| Command | Description | Permission<br>`cubeengine.mail.command.<perm>` |
| --- | --- | --- |
| [*mail*](#mail) | Manages your server mail. | `mail` |
| [**mail**&nbsp;*clear*](#mail&nbsp;clear) | Clears your mail. | `mail.clear.use` |
| [**mail**&nbsp;*read*](#mail&nbsp;read) | Reads your mail. | `mail.read.use` |
| [**mail**&nbsp;*remove*](#mail&nbsp;remove) | Removes a single mail | `mail.remove.use` |
| [**mail**&nbsp;*send*](#mail&nbsp;send) | Sends mails to other players. | `mail.send.use` |
| [**mail**&nbsp;*sendAll*](#mail&nbsp;sendall) | Sends mails to all players. | `mail.sendall.use` |
| [**mail**&nbsp;*spy*](#mail&nbsp;spy) | Shows the mail of other players. | `mail.spy.use` |

#### mail  
Manages your server mail.  
**Usage:** `mail <command>`  
**Permission:** `cubeengine.mail.command.mail`  
**SubCommands:** `clear` `read` `remove` `send` `sendAll` `spy`  

#### mail&nbsp;clear  
Clears your mail.  
**Usage:** `mail clear [player]`  
**Permission:** `cubeengine.mail.command.mail.clear.use`  
  

#### mail&nbsp;read  
Reads your mail.  
**Usage:** `mail read [player]`  
**Alias:** `/readmail`  
**Permission:** `cubeengine.mail.command.mail.read.use`  
  

#### mail&nbsp;remove  
Removes a single mail  
**Usage:** `mail remove <mailId>`  
**Permission:** `cubeengine.mail.command.mail.remove.use`  
  

#### mail&nbsp;send  
Sends mails to other players.  
**Usage:** `mail send <player> <message>`  
**Alias:** `/sendmail`  
**Permission:** `cubeengine.mail.command.mail.send.use`  
  

#### mail&nbsp;sendAll  
Sends mails to all players.  
**Usage:** `mail sendAll <message>`  
**Alias:** `/sendallmail`  
**Permission:** `cubeengine.mail.command.mail.sendall.use`  
  

#### mail&nbsp;spy  
Shows the mail of other players.  
**Usage:** `mail spy <player>`  
**Alias:** `/spymail`  
**Permission:** `cubeengine.mail.command.mail.spy.use`  
  

## Additional Permissions:

| Permission | Description |
| --- | --- |
| `cubeengine.mail` | Base Permission for Mail |