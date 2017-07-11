# CubeEngine - Powertools
Empower your tools!

## Features:
 - Bind command executions to any item

## Commands:

| Command | Description | Permission<br>`cubeengine.powertools.command.<perm>` |
| --- | --- | --- |
| [*powertool*](#powertool) | Binding shortcuts to an item. | `powertool` |
| [**powertool** *add*](#powertool-add) | Adds a command to your powertool | `powertool.add.use` |
| [**powertool** *clear*](#powertool-clear) | Removes all commands from your powertool | `powertool.clear.use` |
| [**powertool** *list*](#powertool-list) | Lists your powertool-bindings. | `powertool.list.use` |
| [**powertool** *remove*](#powertool-remove) | Removes a command from your powertool | `powertool.remove.use` |

#### powertool  
Binding shortcuts to an item.  
**Usage:** `powertool <command>`  
**Alias:** `pt`  
**Permission:** `cubeengine.powertools.command.powertool`  
**SubCommands:** `add` `clear` `list` `remove`  

#### powertool add  
Adds a command to your powertool  
**Usage:** `powertool add <commandString> [-replace]`  
**Alias:** `/pta`  
**Permission:** `cubeengine.powertools.command.powertool.add.use`  
  

#### powertool clear  
Removes all commands from your powertool  
**Usage:** `powertool clear [-all]`  
**Alias:** `/ptc`  
**Permission:** `cubeengine.powertools.command.powertool.clear.use`  
  

#### powertool list  
Lists your powertool-bindings.  
**Usage:** `powertool list [-all]`  
**Alias:** `/ptl`  
**Permission:** `cubeengine.powertools.command.powertool.list.use`  
  

#### powertool remove  
Removes a command from your powertool  
**Usage:** `powertool remove [command]`  
**Alias:** `del` `delete` `rm` `/ptr`  
**Permission:** `cubeengine.powertools.command.powertool.remove.use`  
  

## Additional Permissions:

| Permission | Description |
| --- | --- |
| `cubeengine.powertools` | Base Permission for powertools |