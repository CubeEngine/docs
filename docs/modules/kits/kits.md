# CubeEngine - Kits
Hand kits to your players

## Features:
 - Create sets of arbitrary items
 - Can run a command on kit receival
 - Create kits in game using an inventory

## Commands:

| Command | Description | Permission<br>`cubeengine.kits.command.<perm>` |
| --- | --- | --- |
| [*kit*](#kit) | Manages kits |  |
| [**kit**&nbsp;*create*](#kitcreate) | Opens the configured kit if the kit does not exists a new is created | `kit.create.use` |
| [**kit**&nbsp;*delete*](#kitdelete) | Deletes a kit | `kit.delete.use` |
| [**kit**&nbsp;*edit*](#kitedit) | Edit kits |  |
| [**kit**&nbsp;**edit**&nbsp;*addcommand*](#kiteditaddcommand) | Adds a command to be run when a kit is received | `kit.edit.addCommand.use` |
| [**kit**&nbsp;**edit**&nbsp;*custommessage*](#kiteditcustommessage) | Sets the custom message | `kit.edit.customMessage.use` |
| [**kit**&nbsp;**edit**&nbsp;*giveonfirstjoin*](#kiteditgiveonfirstjoin) | Controls if this kit is given to new players | `kit.edit.giveOnFirstJoin.use` |
| [**kit**&nbsp;**edit**&nbsp;*kitpermission*](#kiteditkitpermission) | Controls permission check for a kit | `kit.edit.kitPermission.use` |
| [**kit**&nbsp;**edit**&nbsp;*limitusage*](#kiteditlimitusage) | Controls the limit for receiving a kit | `kit.edit.limitUsage.use` |
| [**kit**&nbsp;**edit**&nbsp;*removecommand*](#kiteditremovecommand) | Removes commands to be run when a kit is received | `kit.edit.removeCommand.use` |
| [**kit**&nbsp;**edit**&nbsp;*usagedelay*](#kiteditusagedelay) | Controls the minimum delay between receiving a kit in seconds | `kit.edit.usageDelay.use` |
| [**kit**&nbsp;*give*](#kitgive) | Gives a set of items. | `kit.give.use` |
| [**kit**&nbsp;*giveall*](#kitgiveall) | Gives a kit to every online player | `kit.giveall.use` |
| [**kit**&nbsp;*list*](#kitlist) | Lists all currently available kits. | `kit.list.use` |

#### kit  
Manages kits  
**Usage:** `kit <kit> [player][?]`  
**SubCommands:** `create` `delete` `edit` `give` `giveall` `list`  

#### kit&nbsp;create  
Opens the configured kit if the kit does not exists a new is created  
**Usage:** `kit create <kitname>`  
**Alias:** `open`  
**Permission:** `cubeengine.kits.command.kit.create.use`  
  

#### kit&nbsp;delete  
Deletes a kit  
**Usage:** `kit delete <kit>`  
**Alias:** `remove`  
**Permission:** `cubeengine.kits.command.kit.delete.use`  
  

#### kit&nbsp;edit  
Edit kits  
**Usage:** `kit edit`  
**SubCommands:** `addcommand` `custommessage` `giveonfirstjoin` `kitpermission` `limitusage` `removecommand` `usagedelay`  

#### kit&nbsp;edit&nbsp;addcommand  
Adds a command to be run when a kit is received  
**Usage:** `kit edit addcommand <kit> <command>`  
**Permission:** `cubeengine.kits.command.kit.edit.addCommand.use`  
  

#### kit&nbsp;edit&nbsp;custommessage  
Sets the custom message  
**Usage:** `kit edit custommessage <kit> [value]`  
**Permission:** `cubeengine.kits.command.kit.edit.customMessage.use`  
  

#### kit&nbsp;edit&nbsp;giveonfirstjoin  
Controls if this kit is given to new players  
**Usage:** `kit edit giveonfirstjoin <kit> <value>`  
**Permission:** `cubeengine.kits.command.kit.edit.giveOnFirstJoin.use`  
  

#### kit&nbsp;edit&nbsp;kitpermission  
Controls permission check for a kit  
**Usage:** `kit edit kitpermission <kit> <value>`  
**Permission:** `cubeengine.kits.command.kit.edit.kitPermission.use`  
  

#### kit&nbsp;edit&nbsp;limitusage  
Controls the limit for receiving a kit  
**Usage:** `kit edit limitusage <kit> <value>`  
**Permission:** `cubeengine.kits.command.kit.edit.limitUsage.use`  
  

#### kit&nbsp;edit&nbsp;removecommand  
Removes commands to be run when a kit is received  
**Usage:** `kit edit removecommand <kit> [command][?]`  
**Permission:** `cubeengine.kits.command.kit.edit.removeCommand.use`  
  

#### kit&nbsp;edit&nbsp;usagedelay  
Controls the minimum delay between receiving a kit in seconds  
**Usage:** `kit edit usagedelay <kit> <value>`  
**Permission:** `cubeengine.kits.command.kit.edit.usageDelay.use`  
  

#### kit&nbsp;give  
Gives a set of items.  
**Usage:** `kit give <kit> [player][?]`  
**Permission:** `cubeengine.kits.command.kit.give.use`  
  

#### kit&nbsp;giveall  
Gives a kit to every online player  
**Usage:** `kit giveall <kit>[?]`  
**Permission:** `cubeengine.kits.command.kit.giveall.use`  
  

#### kit&nbsp;list  
Lists all currently available kits.  
**Usage:** `kit list`  
**Permission:** `cubeengine.kits.command.kit.list.use`  
  

## Permissions:

| Permission | Description |
| --- | --- |
| `cubeengine.kits` | Base Permission for Kits |
| `cubeengine.kits.command.kit.give.other` | Grants giving out kits to other players |
| `cubeengine.kits.kits` | Grants access to all kits |
