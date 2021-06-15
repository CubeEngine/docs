# CubeEngine - Powertools
Empower your tools!

## Features:
 - Bind command executions to any item

## Commands:

| Command | Description | Permission<br>`cubeengine.powertools.command.<perm>` |
| --- | --- | --- |
| [*powertool*](#powertool) | Binding shortcuts to an item. |  |
| [**powertool**&nbsp;*add*](#powertooladd) | Adds a command to your powertool | `powertool.add.use` |
| [**powertool**&nbsp;*clear*](#powertoolclear) | Removes all commands from your powertool | `powertool.clear.use` |
| [**powertool**&nbsp;*del*](#powertooldel) | Removes a command from your powertool | `powertool.remove.use` |
| [**powertool**&nbsp;*list*](#powertoollist) | Lists your powertool-bindings. | `powertool.list.use` |

#### powertool  
Binding shortcuts to an item.  
**Usage:** `powertool`  
**Alias:** `pt`  
**SubCommands:** `add` `clear` `del` `list`  

#### powertool&nbsp;add  
Adds a command to your powertool  
**Usage:** `powertool add <commandString>[?]`  
**Permission:** `cubeengine.powertools.command.powertool.add.use`  
  

#### powertool&nbsp;clear  
Removes all commands from your powertool  
**Usage:** `powertool clear[?]`  
**Permission:** `cubeengine.powertools.command.powertool.clear.use`  
  

#### powertool&nbsp;del  
Removes a command from your powertool  
**Usage:** `powertool del [command]`  
**Alias:** `rm` `delete` `remove`  
**Permission:** `cubeengine.powertools.command.powertool.remove.use`  
  

#### powertool&nbsp;list  
Lists your powertool-bindings.  
**Usage:** `powertool list[?]`  
**Permission:** `cubeengine.powertools.command.powertool.list.use`  
  

## Permissions:

| Permission | Description |
| --- | --- |
| `cubeengine.powertools` | Base Permission for Powertools |
| `cubeengine.powertools.use` | Allows the usage of Powertools |
