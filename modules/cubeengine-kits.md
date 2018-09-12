# CubeEngine - Kits
Hand kits to your players

## Features:
 - Create sets of arbitrary items
 - Can run a command on kit receival
 - Create kits in game using an inventory

## Commands:

| Command | Description | Permission<br>`cubeengine.kits.command.<perm>` |
| --- | --- | --- |
| [*kit*](#kit) | Manages kits | `kit` |
| [**kit**&nbsp;*create*](#kitcreate) | Opens the configured kit if the kit does not exists a new is created | `kit.create.use` |
| [**kit**&nbsp;*delete*](#kitdelete) | Deletes a kit | `kit.delete.use` |
| [**kit**&nbsp;*edit*](#kitedit) | Edit kits | `kit.edit` |
| [**kit**&nbsp;**edit**&nbsp;*customMessage*](#kiteditcustommessage) | Sets the custom message | `kit.edit.custommessage.use` |
| [**kit**&nbsp;**edit**&nbsp;*giveOnFirstJoin*](#kiteditgiveonfirstjoin) | Controls if this kit is given to new players | `kit.edit.giveonfirstjoin.use` |
| [**kit**&nbsp;**edit**&nbsp;*kitPermission*](#kiteditkitpermission) | Controls permission check for a kit | `kit.edit.kitpermission.use` |
| [**kit**&nbsp;**edit**&nbsp;*limitUsage*](#kiteditlimitusage) | Controls the limit for receiving a kit | `kit.edit.limitusage.use` |
| [**kit**&nbsp;**edit**&nbsp;*setCommand*](#kiteditsetcommand) | Sets commands to be run when a kit is received | `kit.edit.setcommand.use` |
| [**kit**&nbsp;**edit**&nbsp;*usageDelay*](#kiteditusagedelay) | Controls the minimum delay between receiving a kit in seconds | `kit.edit.usagedelay.use` |
| [**kit**&nbsp;*give*](#kitgive) | Gives a set of items. | `kit.give.use` |
| [**kit**&nbsp;*giveall*](#kitgiveall) | Gives a kit to every online player | `kit.giveall.use` |
| [**kit**&nbsp;*list*](#kitlist) | Lists all currently available kits. | `kit.list.use` |

#### kit  
Manages kits  
**Usage:** `kit <command>`  
**Permission:** `cubeengine.kits.command.kit`  
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
**Usage:** `kit edit <command>`  
**Permission:** `cubeengine.kits.command.kit.edit`  
**SubCommands:** `customMessage` `giveOnFirstJoin` `kitPermission` `limitUsage` `setCommand` `usageDelay`  

#### kit&nbsp;edit&nbsp;customMessage  
Sets the custom message  
**Usage:** `kit edit customMessage <kit> [value]`  
**Permission:** `cubeengine.kits.command.kit.edit.custommessage.use`  
  

#### kit&nbsp;edit&nbsp;giveOnFirstJoin  
Controls if this kit is given to new players  
**Usage:** `kit edit giveOnFirstJoin <kit> <value>`  
**Permission:** `cubeengine.kits.command.kit.edit.giveonfirstjoin.use`  
  

#### kit&nbsp;edit&nbsp;kitPermission  
Controls permission check for a kit  
**Usage:** `kit edit kitPermission <kit> <value>`  
**Permission:** `cubeengine.kits.command.kit.edit.kitpermission.use`  
  

#### kit&nbsp;edit&nbsp;limitUsage  
Controls the limit for receiving a kit  
**Usage:** `kit edit limitUsage <kit> <value>`  
**Permission:** `cubeengine.kits.command.kit.edit.limitusage.use`  
  

#### kit&nbsp;edit&nbsp;setCommand  
Sets commands to be run when a kit is received  
**Usage:** `kit edit setCommand <kit> [commands]`  
**Permission:** `cubeengine.kits.command.kit.edit.setcommand.use`  
  

#### kit&nbsp;edit&nbsp;usageDelay  
Controls the minimum delay between receiving a kit in seconds  
**Usage:** `kit edit usageDelay <kit> <value>`  
**Permission:** `cubeengine.kits.command.kit.edit.usagedelay.use`  
  

#### kit&nbsp;give  
Gives a set of items.  
**Usage:** `kit give <kit> <player> [-force]`  
**Permission:** `cubeengine.kits.command.kit.give.use`  
  

#### kit&nbsp;giveall  
Gives a kit to every online player  
**Usage:** `kit giveall <kit> [-force]`  
**Permission:** `cubeengine.kits.command.kit.giveall.use`  
  

#### kit&nbsp;list  
Lists all currently available kits.  
**Usage:** `kit list `  
**Alias:** `/kitlist`  
**Permission:** `cubeengine.kits.command.kit.list.use`  
  

## Permissions:

| Permission | Description |
| --- | --- |
| `cubeengine.kits` | Base Permission for Kits |
| `cubeengine.kits.command` | Allows using all commands of Kits |
| `cubeengine.kits.command.kit.give.other` | Grants giving out kits to other players |
| `cubeengine.kits.kits` | Grants access to all kits |
