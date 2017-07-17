# CubeEngine - Powertools
Empower your tools!

## Features:
 - Bind command executions to any item

## Commands:

| Command | Description | Permission<br>`cubeengine.powertools.command.<perm>` |
| --- | --- | --- |
| [*powertool*](#powertool) | Binding shortcuts to an item. | `powertool` |
| [**powertool**&nbsp;*add*](#powertooladd) | Adds a command to your powertool | `powertool.add.use` |
| [**powertool**&nbsp;*clear*](#powertoolclear) | Removes all commands from your powertool | `powertool.clear.use` |
| [**powertool**&nbsp;*list*](#powertoollist) | Lists your powertool-bindings. | `powertool.list.use` |
| [**powertool**&nbsp;*remove*](#powertoolremove) | Removes a command from your powertool | `powertool.remove.use` |

#### powertool  
Binding shortcuts to an item.  
**Usage:** `powertool <command>`  
**Alias:** `pt`  
**Permission:** `cubeengine.powertools.command.powertool`  
**SubCommands:** `add` `clear` `list` `remove`  

#### powertool&nbsp;add  
Adds a command to your powertool  
**Usage:** `powertool add <commandString> [-replace]`  
**Alias:** `/pta`  
**Permission:** `cubeengine.powertools.command.powertool.add.use`  
  

#### powertool&nbsp;clear  
Removes all commands from your powertool  
**Usage:** `powertool clear [-all]`  
**Alias:** `/ptc`  
**Permission:** `cubeengine.powertools.command.powertool.clear.use`  
  

#### powertool&nbsp;list  
Lists your powertool-bindings.  
**Usage:** `powertool list [-all]`  
**Alias:** `/ptl`  
**Permission:** `cubeengine.powertools.command.powertool.list.use`  
  

#### powertool&nbsp;remove  
Removes a command from your powertool  
**Usage:** `powertool remove [command]`  
**Alias:** `del` `delete` `rm` `/ptr`  
**Permission:** `cubeengine.powertools.command.powertool.remove.use`  
  

## Additional Permissions:

| Permission | Description |
| --- | --- |
| `cubeengine.powertools` | Base Permission for Powertools |
| `cubeengine.powertools.command` | Allows using all commands of Powertools |
| `cubeengine.powertools.use` | Allows the usage of Powertools |
