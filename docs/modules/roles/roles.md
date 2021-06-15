# CubeEngine - Roles
This module assigns permissions based on roles.

## Features:
 - Implementation of standard permissions interface
 - Role (multi-)inheritance
 - Player-specific permissions
 - Temporary permissions
 - Multiple roles per player
 - Subject options per context per role or player
 - Permission configuration per context per role or player
 - Live reload
 - No database necessary!

## Commands:

| Command | Description | Permission<br>`cubeengine.roles.command.<perm>` |
| --- | --- | --- |
| [*roles*](#roles) | Manages the roles |  |
| [**roles**&nbsp;*manadmin*](#rolesmanadmin) | Manages the module |  |
| [**roles**&nbsp;**manadmin**&nbsp;*debug*](#rolesmanadmindebug) | Toggles debug mode | `roles.admin.debug.use` |
| [**roles**&nbsp;**manadmin**&nbsp;*findpermission*](#rolesmanadminfindpermission) | Searches for registered Permissions | `roles.admin.findPermission.use` |
| [**roles**&nbsp;**manadmin**&nbsp;*reload*](#rolesmanadminreload) | Reloads all roles from config | `roles.admin.reload.use` |
| [**roles**&nbsp;**manadmin**&nbsp;*save*](#rolesmanadminsave) | Overrides all configs with current settings | `roles.admin.save.use` |
| [**roles**&nbsp;*role*](#rolesrole) | Manage roles |  |
| [**roles**&nbsp;**role**&nbsp;*addparent*](#rolesroleaddparent) | Adds a parent role to given role [in context] | `roles.role.addParent.use` |
| [**roles**&nbsp;**role**&nbsp;*checkpermission*](#rolesrolecheckpermission) | Checks the permission in given role [in context] | `roles.role.checkPermission.use` |
| [**roles**&nbsp;**role**&nbsp;*cleardata*](#rolesrolecleardata) | Clears the options for given role [in context] | `roles.role.clearOption.use` |
| [**roles**&nbsp;**role**&nbsp;*clearparent*](#rolesroleclearparent) | Removes all parent roles from given role [in context] | `roles.role.clearParent.use` |
| [**roles**&nbsp;**role**&nbsp;*create*](#rolesrolecreate) | Creates a new role | `roles.role.create.use` |
| [**roles**&nbsp;**role**&nbsp;*default*](#rolesroledefault) | Lists all default roles | `roles.role.listDefaultRoles.use` |
| [**roles**&nbsp;**role**&nbsp;*delete*](#rolesroledelete) | Deletes a role | `roles.role.delete.use` |
| [**roles**&nbsp;**role**&nbsp;*list*](#rolesrolelist) | Lists all roles | `roles.role.list.use` |
| [**roles**&nbsp;**role**&nbsp;*listoption*](#rolesrolelistoption) | Lists all options of given role [in context] | `roles.role.listOption.use` |
| [**roles**&nbsp;**role**&nbsp;*listparent*](#rolesrolelistparent) | Lists all parents of given role [in context] | `roles.role.listParent.use` |
| [**roles**&nbsp;**role**&nbsp;*listpermission*](#rolesrolelistpermission) | Lists all permissions of given role [in context] | `roles.role.listPermission.use` |
| [**roles**&nbsp;**role**&nbsp;*priority*](#rolesrolepriority) | Show the priority of given role | `roles.role.priority.use` |
| [**roles**&nbsp;**role**&nbsp;*removeparent*](#rolesroleremoveparent) | Removes a parent role from given role [in context] | `roles.role.removeParent.use` |
| [**roles**&nbsp;**role**&nbsp;*rename*](#rolesrolerename) | Renames given role | `roles.role.rename.use` |
| [**roles**&nbsp;**role**&nbsp;*resetoption*](#rolesroleresetoption) | Resets the options for given role [in context] | `roles.role.resetOption.use` |
| [**roles**&nbsp;**role**&nbsp;*setoption*](#rolesrolesetoption) | Sets an option for given role [in context] | `roles.role.setOption.use` |
| [**roles**&nbsp;**role**&nbsp;*setpermission*](#rolesrolesetpermission) | Sets the permission for given role [in context] | `roles.role.setPermission.use` |
| [**roles**&nbsp;**role**&nbsp;*setpriority*](#rolesrolesetpriority) | Sets the priority of given role | `roles.role.setPriority.use` |
| [**roles**&nbsp;**role**&nbsp;*toggledefault*](#rolesroletoggledefault) | Toggles whether given role is a default role | `roles.role.toggleDefaultRole.use` |
| [**roles**&nbsp;*user*](#rolesuser) | Manage users |  |
| [**roles**&nbsp;**user**&nbsp;*add*](#rolesuseradd) | Assign a role to the player [-temp] | `roles.user.assign.use` |
| [**roles**&nbsp;**user**&nbsp;*checkdata*](#rolesusercheckdata) | Checks for options of a user [in context] | `roles.user.checkOption.use` |
| [**roles**&nbsp;**user**&nbsp;*checkpermission*](#rolesusercheckpermission) | Checks for permissions of a user [in context] | `roles.user.checkPermission.use` |
| [**roles**&nbsp;**user**&nbsp;*clear*](#rolesuserclear) | Clears all roles from the player and sets the defaultroles [in context] | `roles.user.clear.use` |
| [**roles**&nbsp;**user**&nbsp;*cleardata*](#rolesusercleardata) | Resets options for this user [in context] | `roles.user.clearOption.use` |
| [**roles**&nbsp;**user**&nbsp;*deletedata*](#rolesuserdeletedata) | Resets options for this user [in context] | `roles.user.resetOption.use` |
| [**roles**&nbsp;**user**&nbsp;*list*](#rolesuserlist) | Lists roles of a user | `roles.user.list.use` |
| [**roles**&nbsp;**user**&nbsp;*listoption*](#rolesuserlistoption) | Lists assigned options from a user [in context] | `roles.user.listOption.use` |
| [**roles**&nbsp;**user**&nbsp;*listpermission*](#rolesuserlistpermission) | List permission assigned to a user [in context] | `roles.user.listPermission.use` |
| [**roles**&nbsp;**user**&nbsp;*remove*](#rolesuserremove) | Removes a role from the player | `roles.user.remove.use` |
| [**roles**&nbsp;**user**&nbsp;*resetpermission*](#rolesuserresetpermission) | Resets a permission for this user [in context] | `roles.user.resetPermission.use` |
| [**roles**&nbsp;**user**&nbsp;*setoption*](#rolesusersetoption) | Sets options for this user [in context] | `roles.user.setOption.use` |
| [**roles**&nbsp;**user**&nbsp;*setpermission*](#rolesusersetpermission) | Sets a permission for this user [in context] | `roles.user.setPermission.use` |

#### roles  
Manages the roles  
**Usage:** `roles`  
**SubCommands:** `manadmin` `role` `user`  

#### roles&nbsp;manadmin  
Manages the module  
**Usage:** `roles manadmin`  
**Alias:** `admin`  
**SubCommands:** `debug` `findpermission` `reload` `save`  

#### roles&nbsp;manadmin&nbsp;debug  
Toggles debug mode  
**Usage:** `roles manadmin debug [seconds]`  
**Permission:** `cubeengine.roles.command.roles.admin.debug.use`  
  

#### roles&nbsp;manadmin&nbsp;findpermission  
Searches for registered Permissions  
**Usage:** `roles manadmin findpermission <permission>`  
**Permission:** `cubeengine.roles.command.roles.admin.findPermission.use`  
  

#### roles&nbsp;manadmin&nbsp;reload  
Reloads all roles from config  
**Usage:** `roles manadmin reload`  
**Permission:** `cubeengine.roles.command.roles.admin.reload.use`  
  

#### roles&nbsp;manadmin&nbsp;save  
Overrides all configs with current settings  
**Usage:** `roles manadmin save`  
**Permission:** `cubeengine.roles.command.roles.admin.save.use`  
  

#### roles&nbsp;role  
Manage roles  
**Usage:** `roles role`  
**SubCommands:** `addparent` `checkpermission` `cleardata` `clearparent` `create` `default` `delete` `list` `listoption` `listparent` `listpermission` `priority` `removeparent` `rename` `resetoption` `setoption` `setpermission` `setpriority` `toggledefault`  

#### roles&nbsp;role&nbsp;addparent  
Adds a parent role to given role [in context]  
**Usage:** `roles role addparent <role> <parentRole>[?]`  
**Permission:** `cubeengine.roles.command.roles.role.addParent.use`  
  

#### roles&nbsp;role&nbsp;checkpermission  
Checks the permission in given role [in context]  
**Usage:** `roles role checkpermission <role> <permission>[?]`  
**Alias:** `checkperm`  
**Permission:** `cubeengine.roles.command.roles.role.checkPermission.use`  
  

#### roles&nbsp;role&nbsp;cleardata  
Clears the options for given role [in context]  
**Usage:** `roles role cleardata <role>[?]`  
**Alias:** `clearoption`  
**Permission:** `cubeengine.roles.command.roles.role.clearOption.use`  
  

#### roles&nbsp;role&nbsp;clearparent  
Removes all parent roles from given role [in context]  
**Usage:** `roles role clearparent <role>[?]`  
**Permission:** `cubeengine.roles.command.roles.role.clearParent.use`  
  

#### roles&nbsp;role&nbsp;create  
Creates a new role  
**Usage:** `roles role create <name>`  
**Permission:** `cubeengine.roles.command.roles.role.create.use`  
  

#### roles&nbsp;role&nbsp;default  
Lists all default roles  
**Usage:** `roles role default`  
**Alias:** `listdefroles` `listdefaultroles` `defaultroles`  
**Permission:** `cubeengine.roles.command.roles.role.listDefaultRoles.use`  
  

#### roles&nbsp;role&nbsp;delete  
Deletes a role  
**Usage:** `roles role delete <role>[?]`  
**Permission:** `cubeengine.roles.command.roles.role.delete.use`  
  

#### roles&nbsp;role&nbsp;list  
Lists all roles  
**Usage:** `roles role list`  
**Permission:** `cubeengine.roles.command.roles.role.list.use`  
  

#### roles&nbsp;role&nbsp;listoption  
Lists all options of given role [in context]  
**Usage:** `roles role listoption <role>[?][?]`  
**Alias:** `listdata`  
**Permission:** `cubeengine.roles.command.roles.role.listOption.use`  
  

#### roles&nbsp;role&nbsp;listparent  
Lists all parents of given role [in context]  
**Usage:** `roles role listparent <role>[?]`  
**Permission:** `cubeengine.roles.command.roles.role.listParent.use`  
  

#### roles&nbsp;role&nbsp;listpermission  
Lists all permissions of given role [in context]  
**Usage:** `roles role listpermission <role>[?][?]`  
**Alias:** `listperm`  
**Permission:** `cubeengine.roles.command.roles.role.listPermission.use`  
  

#### roles&nbsp;role&nbsp;priority  
Show the priority of given role  
**Usage:** `roles role priority <role>`  
**Alias:** `prio`  
**Permission:** `cubeengine.roles.command.roles.role.priority.use`  
  

#### roles&nbsp;role&nbsp;removeparent  
Removes a parent role from given role [in context]  
**Usage:** `roles role removeparent <role> <parentRole>[?]`  
**Permission:** `cubeengine.roles.command.roles.role.removeParent.use`  
  

#### roles&nbsp;role&nbsp;rename  
Renames given role  
**Usage:** `roles role rename <role> <new name>`  
**Permission:** `cubeengine.roles.command.roles.role.rename.use`  
  

#### roles&nbsp;role&nbsp;resetoption  
Resets the options for given role [in context]  
**Usage:** `roles role resetoption <role> <key>[?]`  
**Alias:** `resetdata`  
**Permission:** `cubeengine.roles.command.roles.role.resetOption.use`  
  

#### roles&nbsp;role&nbsp;setoption  
Sets an option for given role [in context]  
**Usage:** `roles role setoption <role> <key> [value][?]`  
**Alias:** `setdata`  
**Permission:** `cubeengine.roles.command.roles.role.setOption.use`  
  

#### roles&nbsp;role&nbsp;setpermission  
Sets the permission for given role [in context]  
**Usage:** `roles role setpermission <role> <permission> [type][?]`  
**Alias:** `setperm`  
**Permission:** `cubeengine.roles.command.roles.role.setPermission.use`  
  

#### roles&nbsp;role&nbsp;setpriority  
Sets the priority of given role  
**Usage:** `roles role setpriority <role> <priority>`  
**Alias:** `setprio`  
**Permission:** `cubeengine.roles.command.roles.role.setPriority.use`  
  

#### roles&nbsp;role&nbsp;toggledefault  
Toggles whether given role is a default role  
**Usage:** `roles role toggledefault <role>`  
**Alias:** `toggledefaultrole` `toggledef`  
**Permission:** `cubeengine.roles.command.roles.role.toggleDefaultRole.use`  
  

#### roles&nbsp;user  
Manage users  
**Usage:** `roles user`  
**SubCommands:** `add` `checkdata` `checkpermission` `clear` `cleardata` `deletedata` `list` `listoption` `listpermission` `remove` `resetpermission` `setoption` `setpermission`  

#### roles&nbsp;user&nbsp;add  
Assign a role to the player [-temp]  
**Usage:** `roles user add <player> <role>[?]`  
**Alias:** `give` `assign`  
**Permission:** `cubeengine.roles.command.roles.user.assign.use`  
  

#### roles&nbsp;user&nbsp;checkdata  
Checks for options of a user [in context]  
**Usage:** `roles user checkdata [player] <key>[?]`  
**Alias:** `checkoption`  
**Permission:** `cubeengine.roles.command.roles.user.checkOption.use`  
  

#### roles&nbsp;user&nbsp;checkpermission  
Checks for permissions of a user [in context]  
**Usage:** `roles user checkpermission [player] <permission>[?]`  
**Alias:** `checkperm`  
**Permission:** `cubeengine.roles.command.roles.user.checkPermission.use`  
  

#### roles&nbsp;user&nbsp;clear  
Clears all roles from the player and sets the defaultroles [in context]  
**Usage:** `roles user clear <player>`  
**Permission:** `cubeengine.roles.command.roles.user.clear.use`  
  

#### roles&nbsp;user&nbsp;cleardata  
Resets options for this user [in context]  
**Usage:** `roles user cleardata <player>[?]`  
**Alias:** `clearoption`  
**Permission:** `cubeengine.roles.command.roles.user.clearOption.use`  
  

#### roles&nbsp;user&nbsp;deletedata  
Resets options for this user [in context]  
**Usage:** `roles user deletedata <player> <key>[?]`  
**Alias:** `deleteoption` `resetoption` `resetdata`  
**Permission:** `cubeengine.roles.command.roles.user.resetOption.use`  
  

#### roles&nbsp;user&nbsp;list  
Lists roles of a user  
**Usage:** `roles user list [player]`  
**Permission:** `cubeengine.roles.command.roles.user.list.use`  
  

#### roles&nbsp;user&nbsp;listoption  
Lists assigned options from a user [in context]  
**Usage:** `roles user listoption [player][?][?]`  
**Alias:** `listdata`  
**Permission:** `cubeengine.roles.command.roles.user.listOption.use`  
  

#### roles&nbsp;user&nbsp;listpermission  
List permission assigned to a user [in context]  
**Usage:** `roles user listpermission [player][?][?]`  
**Alias:** `listperm`  
**Permission:** `cubeengine.roles.command.roles.user.listPermission.use`  
  

#### roles&nbsp;user&nbsp;remove  
Removes a role from the player  
**Usage:** `roles user remove <player> <role>`  
**Permission:** `cubeengine.roles.command.roles.user.remove.use`  
  

#### roles&nbsp;user&nbsp;resetpermission  
Resets a permission for this user [in context]  
**Usage:** `roles user resetpermission [player] <permission>[?]`  
**Alias:** `resetperm`  
**Permission:** `cubeengine.roles.command.roles.user.resetPermission.use`  
  

#### roles&nbsp;user&nbsp;setoption  
Sets options for this user [in context]  
**Usage:** `roles user setoption <player> <key> <value>[?]`  
**Alias:** `setdata`  
**Permission:** `cubeengine.roles.command.roles.user.setOption.use`  
  

#### roles&nbsp;user&nbsp;setpermission  
Sets a permission for this user [in context]  
**Usage:** `roles user setpermission <player> <permission> [type][?]`  
**Alias:** `setperm`  
**Permission:** `cubeengine.roles.command.roles.user.setPermission.use`  
  

## Permissions:

| Permission | Description |
| --- | --- |
| `cubeengine.roles` | Base Permission for Roles |
