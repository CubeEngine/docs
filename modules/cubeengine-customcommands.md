# CubeEngine - CustomCommands
module adding custom chat commands

## Features:
 - Create simple chat commands using !<command> syntax

## Commands:

| Command | Description | Permission<br>`cubeengine.customcommands.command.<perm>` |
| --- | --- | --- |
| [*customcommands*](#customcommands) | Commands to modify custom commands. | `customcommands` |
| [**customcommands** *add*](#customcommands-add) | Adds a custom chat command. | `customcommands.add.use` |
| [**customcommands** *delete*](#customcommands-delete) | Deletes a custom chat command. | `customcommands.delete.use` |
| [**customcommands** *help*](#customcommands-help) | Prints out all the custom chat commands. | `customcommands.help.use` |

#### customcommands  
Commands to modify custom commands.  
**Usage:** `customcommands <command>`  
**Permission:** `cubeengine.customcommands.command.customcommands`  
**SubCommands:** `add` `delete` `help`  

#### customcommands add  
Adds a custom chat command.  
**Usage:** `customcommands add <name> <message> [-force] [-global]`  
**Permission:** `cubeengine.customcommands.command.customcommands.add.use`  
  

#### customcommands delete  
Deletes a custom chat command.  
**Usage:** `customcommands delete <name> [-global]`  
**Permission:** `cubeengine.customcommands.command.customcommands.delete.use`  
  

#### customcommands help  
Prints out all the custom chat commands.  
**Usage:** `customcommands help `  
**Permission:** `cubeengine.customcommands.command.customcommands.help.use`  
  

## Additional Permissions:

| Permission | Description |
| --- | --- |
| `cubeengine.customcommands` | Base Permission for customcommands |