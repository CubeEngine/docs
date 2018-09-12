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
| [*roles*](#roles) | Manages the roles | `roles` |
| [**roles**&nbsp;*admin*](#rolesadmin) | Manages the module | `roles.admin` |
| [**roles**&nbsp;**admin**&nbsp;*debug*](#rolesadmindebug) | Toggles debug mode | `roles.admin.debug.use` |
| [**roles**&nbsp;**admin**&nbsp;*findPermission*](#rolesadminfindpermission) | Searches for registered Permissions | `roles.admin.findpermission.use` |
| [**roles**&nbsp;**admin**&nbsp;*reload*](#rolesadminreload) | Reloads all roles from config | `roles.admin.reload.use` |
| [**roles**&nbsp;**admin**&nbsp;*save*](#rolesadminsave) | Overrides all configs with current settings | `roles.admin.save.use` |
| [**roles**&nbsp;*role*](#rolesrole) | Manage roles | `roles.role` |
| [**roles**&nbsp;**role**&nbsp;*addParent*](#rolesroleaddparent) | Adds a parent role to given role [in context] | `roles.role.addparent.use` |
| [**roles**&nbsp;**role**&nbsp;*checkPermission*](#rolesrolecheckpermission) | Checks the permission in given role [in context] | `roles.role.checkpermission.use` |
| [**roles**&nbsp;**role**&nbsp;*clearOption*](#rolesroleclearoption) | Clears the options for given role [in context] | `roles.role.clearoption.use` |
| [**roles**&nbsp;**role**&nbsp;*clearParent*](#rolesroleclearparent) | Removes all parent roles from given role [in context] | `roles.role.clearparent.use` |
| [**roles**&nbsp;**role**&nbsp;*create*](#rolesrolecreate) | Creates a new role | `roles.role.create.use` |
| [**roles**&nbsp;**role**&nbsp;*delete*](#rolesroledelete) | Deletes a role | `roles.role.delete.use` |
| [**roles**&nbsp;**role**&nbsp;*list*](#rolesrolelist) | Lists all roles | `roles.role.list.use` |
| [**roles**&nbsp;**role**&nbsp;*listDefaultRoles*](#rolesrolelistdefaultroles) | Lists all default roles | `roles.role.listdefaultroles.use` |
| [**roles**&nbsp;**role**&nbsp;*listOption*](#rolesrolelistoption) | Lists all options of given role [in context] | `roles.role.listoption.use` |
| [**roles**&nbsp;**role**&nbsp;*listParent*](#rolesrolelistparent) | Lists all parents of given role [in context] | `roles.role.listparent.use` |
| [**roles**&nbsp;**role**&nbsp;*listPermission*](#rolesrolelistpermission) | Lists all permissions of given role [in context] | `roles.role.listpermission.use` |
| [**roles**&nbsp;**role**&nbsp;*priority*](#rolesrolepriority) | Show the priority of given role | `roles.role.priority.use` |
| [**roles**&nbsp;**role**&nbsp;*removeParent*](#rolesroleremoveparent) | Removes a parent role from given role [in context] | `roles.role.removeparent.use` |
| [**roles**&nbsp;**role**&nbsp;*rename*](#rolesrolerename) | Renames given role | `roles.role.rename.use` |
| [**roles**&nbsp;**role**&nbsp;*resetOption*](#rolesroleresetoption) | Resets the options for given role [in context] | `roles.role.resetoption.use` |
| [**roles**&nbsp;**role**&nbsp;*setOption*](#rolesrolesetoption) | Sets an option for given role [in context] | `roles.role.setoption.use` |
| [**roles**&nbsp;**role**&nbsp;*setPermission*](#rolesrolesetpermission) | Sets the permission for given role [in context] | `roles.role.setpermission.use` |
| [**roles**&nbsp;**role**&nbsp;*setPriority*](#rolesrolesetpriority) | Sets the priority of given role | `roles.role.setpriority.use` |
| [**roles**&nbsp;**role**&nbsp;*toggleDefaultRole*](#rolesroletoggledefaultrole) | Toggles whether given role is a default role | `roles.role.toggledefaultrole.use` |
| [**roles**&nbsp;*user*](#rolesuser) | Manage users | `roles.user` |
| [**roles**&nbsp;**user**&nbsp;*assign*](#rolesuserassign) | Assign a role to the player [-temp] | `roles.user.assign.use` |
| [**roles**&nbsp;**user**&nbsp;*checkOption*](#rolesusercheckoption) | Checks for options of a user [in context] | `roles.user.checkoption.use` |
| [**roles**&nbsp;**user**&nbsp;*checkPermission*](#rolesusercheckpermission) | Checks for permissions of a user [in context] | `roles.user.checkpermission.use` |
| [**roles**&nbsp;**user**&nbsp;*clear*](#rolesuserclear) | Clears all roles from the player and sets the defaultroles [in context] | `roles.user.clear.use` |
| [**roles**&nbsp;**user**&nbsp;*clearOption*](#rolesuserclearoption) | Resets options for this user [in context] | `roles.user.clearoption.use` |
| [**roles**&nbsp;**user**&nbsp;*list*](#rolesuserlist) | Lists roles of a user | `roles.user.list.use` |
| [**roles**&nbsp;**user**&nbsp;*listOption*](#rolesuserlistoption) | Lists assigned options from a user [in context] | `roles.user.listoption.use` |
| [**roles**&nbsp;**user**&nbsp;*listPermission*](#rolesuserlistpermission) | List permission assigned to a user [in context] | `roles.user.listpermission.use` |
| [**roles**&nbsp;**user**&nbsp;*remove*](#rolesuserremove) | Removes a role from the player | `roles.user.remove.use` |
| [**roles**&nbsp;**user**&nbsp;*resetOption*](#rolesuserresetoption) | Resets options for this user [in context] | `roles.user.resetoption.use` |
| [**roles**&nbsp;**user**&nbsp;*resetPermission*](#rolesuserresetpermission) | Resets a permission for this user [in context] | `roles.user.resetpermission.use` |
| [**roles**&nbsp;**user**&nbsp;*setOption*](#rolesusersetoption) | Sets options for this user [in context] | `roles.user.setoption.use` |
| [**roles**&nbsp;**user**&nbsp;*setPermission*](#rolesusersetpermission) | Sets a permission for this user [in context] | `roles.user.setpermission.use` |

#### roles  
Manages the roles  
**Usage:** `roles <command>`  
**Permission:** `cubeengine.roles.command.roles`  
**SubCommands:** `admin` `role` `user`  

#### roles&nbsp;admin  
Manages the module  
**Usage:** `roles admin <command>`  
**Alias:** `manadmin`  
**Permission:** `cubeengine.roles.command.roles.admin`  
**SubCommands:** `debug` `findPermission` `reload` `save`  

#### roles&nbsp;admin&nbsp;debug  
Toggles debug mode  
**Usage:** `roles admin debug [seconds]`  
**Alias:** `/mandebug`  
**Permission:** `cubeengine.roles.command.roles.admin.debug.use`  
  

#### roles&nbsp;admin&nbsp;findPermission  
Searches for registered Permissions  
**Usage:** `roles admin findPermission <permission>`  
**Permission:** `cubeengine.roles.command.roles.admin.findpermission.use`  
  

#### roles&nbsp;admin&nbsp;reload  
Reloads all roles from config  
**Usage:** `roles admin reload `  
**Alias:** `/manload`  
**Permission:** `cubeengine.roles.command.roles.admin.reload.use`  
  

#### roles&nbsp;admin&nbsp;save  
Overrides all configs with current settings  
**Usage:** `roles admin save `  
**Alias:** `/mansave`  
**Permission:** `cubeengine.roles.command.roles.admin.save.use`  
  

#### roles&nbsp;role  
Manage roles  
**Usage:** `roles role <command>`  
**Alias:** `/manrole`  
**Permission:** `cubeengine.roles.command.roles.role`  
**SubCommands:** `addParent` `checkPermission` `clearOption` `clearParent` `create` `delete` `list` `listDefaultRoles` `listOption` `listParent` `listPermission` `priority` `removeParent` `rename` `resetOption` `setOption` `setPermission` `setPriority` `toggleDefaultRole`  

#### roles&nbsp;role&nbsp;addParent  
Adds a parent role to given role [in context]  
**Usage:** `roles role addParent <role> <parentRole> [in <context>]`  
**Alias:** `/addRParent` `/manRAdd`  
**Permission:** `cubeengine.roles.command.roles.role.addparent.use`  
  

#### roles&nbsp;role&nbsp;checkPermission  
Checks the permission in given role [in context]  
**Usage:** `roles role checkPermission <role> <permission> [in <context>]`  
**Alias:** `checkPerm` `/checkRPerm`  
**Permission:** `cubeengine.roles.command.roles.role.checkpermission.use`  
  

#### roles&nbsp;role&nbsp;clearOption  
Clears the options for given role [in context]  
**Usage:** `roles role clearOption <role> [in <context>]`  
**Alias:** `clearData` `/clearROption` `/clearRData`  
**Permission:** `cubeengine.roles.command.roles.role.clearoption.use`  
  

#### roles&nbsp;role&nbsp;clearParent  
Removes all parent roles from given role [in context]  
**Usage:** `roles role clearParent <role> [in <context>]`  
**Alias:** `/clearRParent`  
**Permission:** `cubeengine.roles.command.roles.role.clearparent.use`  
  

#### roles&nbsp;role&nbsp;create  
Creates a new role  
**Usage:** `roles role create <name>`  
**Alias:** `/createRole`  
**Permission:** `cubeengine.roles.command.roles.role.create.use`  
  

#### roles&nbsp;role&nbsp;delete  
Deletes a role  
**Usage:** `roles role delete <role> [-force]`  
**Alias:** `/deleteRole`  
**Permission:** `cubeengine.roles.command.roles.role.delete.use`  
  

#### roles&nbsp;role&nbsp;list  
Lists all roles  
**Usage:** `roles role list `  
**Alias:** `/listRoles`  
**Permission:** `cubeengine.roles.command.roles.role.list.use`  
  

#### roles&nbsp;role&nbsp;listDefaultRoles  
Lists all default roles  
**Usage:** `roles role listDefaultRoles `  
**Alias:** `default` `defaultRoles` `listDefRoles`  
**Permission:** `cubeengine.roles.command.roles.role.listdefaultroles.use`  
  

#### roles&nbsp;role&nbsp;listOption  
Lists all options of given role [in context]  
**Usage:** `roles role listOption <role> [in <context>] [-all]`  
**Alias:** `listData` `/listROption` `/listRData`  
**Permission:** `cubeengine.roles.command.roles.role.listoption.use`  
  

#### roles&nbsp;role&nbsp;listParent  
Lists all parents of given role [in context]  
**Usage:** `roles role listParent <role> [in <context>]`  
**Alias:** `/listRParent`  
**Permission:** `cubeengine.roles.command.roles.role.listparent.use`  
  

#### roles&nbsp;role&nbsp;listPermission  
Lists all permissions of given role [in context]  
**Usage:** `roles role listPermission <role> [in <context>] [-all]`  
**Alias:** `listPerm` `/listRPerm`  
**Permission:** `cubeengine.roles.command.roles.role.listpermission.use`  
  

#### roles&nbsp;role&nbsp;priority  
Show the priority of given role  
**Usage:** `roles role priority <role>`  
**Alias:** `prio`  
**Permission:** `cubeengine.roles.command.roles.role.priority.use`  
  

#### roles&nbsp;role&nbsp;removeParent  
Removes a parent role from given role [in context]  
**Usage:** `roles role removeParent <role> <parentRole> [in <context>]`  
**Alias:** `/remRParent`  
**Permission:** `cubeengine.roles.command.roles.role.removeparent.use`  
  

#### roles&nbsp;role&nbsp;rename  
Renames given role  
**Usage:** `roles role rename <role> <new name>`  
**Alias:** `/renameRole`  
**Permission:** `cubeengine.roles.command.roles.role.rename.use`  
  

#### roles&nbsp;role&nbsp;resetOption  
Resets the options for given role [in context]  
**Usage:** `roles role resetOption <role> <key> [in <context>]`  
**Alias:** `resetData` `/resetROption` `/resetRData`  
**Permission:** `cubeengine.roles.command.roles.role.resetoption.use`  
  

#### roles&nbsp;role&nbsp;setOption  
Sets an option for given role [in context]  
**Usage:** `roles role setOption <role> <key> [value] [in <context>]`  
**Alias:** `setData` `/setROption` `/setRData`  
**Permission:** `cubeengine.roles.command.roles.role.setoption.use`  
  

#### roles&nbsp;role&nbsp;setPermission  
Sets the permission for given role [in context]  
**Usage:** `roles role setPermission <role> <permission> <type> [in <context>]`  
**Alias:** `setPerm` `/setRPerm`  
**Permission:** `cubeengine.roles.command.roles.role.setpermission.use`  
  

#### roles&nbsp;role&nbsp;setPriority  
Sets the priority of given role  
**Usage:** `roles role setPriority <role> <priority>`  
**Alias:** `setPrio` `/setRolePriority`  
**Permission:** `cubeengine.roles.command.roles.role.setpriority.use`  
  

#### roles&nbsp;role&nbsp;toggleDefaultRole  
Toggles whether given role is a default role  
**Usage:** `roles role toggleDefaultRole <role>`  
**Alias:** `toggleDefault` `toggleDef`  
**Permission:** `cubeengine.roles.command.roles.role.toggledefaultrole.use`  
  

#### roles&nbsp;user  
Manage users  
**Usage:** `roles user <command>`  
**Alias:** `/manuser`  
**Permission:** `cubeengine.roles.command.roles.user`  
**SubCommands:** `assign` `checkOption` `checkPermission` `clear` `clearOption` `list` `listOption` `listPermission` `remove` `resetOption` `resetPermission` `setOption` `setPermission`  

#### roles&nbsp;user&nbsp;assign  
Assign a role to the player [-temp]  
**Usage:** `roles user assign <player> <role> [-temp]`  
**Alias:** `add` `give` `/manUAdd` `/assignURole` `/addURole` `/giveURole`  
**Permission:** `cubeengine.roles.command.roles.user.assign.use`  
  

#### roles&nbsp;user&nbsp;checkOption  
Checks for options of a user [in context]  
**Usage:** `roles user checkOption <player> <key> [in <context>]`  
**Alias:** `checkData` `/checkUOption` `/checkUData`  
**Permission:** `cubeengine.roles.command.roles.user.checkoption.use`  
  

#### roles&nbsp;user&nbsp;checkPermission  
Checks for permissions of a user [in context]  
**Usage:** `roles user checkPermission <player> <permission> [in <context>]`  
**Alias:** `checkperm` `/checkuperm`  
**Permission:** `cubeengine.roles.command.roles.user.checkpermission.use`  
  

#### roles&nbsp;user&nbsp;clear  
Clears all roles from the player and sets the defaultroles [in context]  
**Usage:** `roles user clear <player>`  
**Alias:** `/clearURole` `/manUClear`  
**Permission:** `cubeengine.roles.command.roles.user.clear.use`  
  

#### roles&nbsp;user&nbsp;clearOption  
Resets options for this user [in context]  
**Usage:** `roles user clearOption <player> [in <context>]`  
**Alias:** `clearData` `/clearUOption` `/clearUData`  
**Permission:** `cubeengine.roles.command.roles.user.clearoption.use`  
  

#### roles&nbsp;user&nbsp;list  
Lists roles of a user  
**Usage:** `roles user list <player>`  
**Alias:** `/listurole`  
**Permission:** `cubeengine.roles.command.roles.user.list.use`  
  

#### roles&nbsp;user&nbsp;listOption  
Lists assigned options from a user [in context]  
**Usage:** `roles user listOption <player> [in <context>] [-all]`  
**Alias:** `listData` `/listUOption` `/listUData`  
**Permission:** `cubeengine.roles.command.roles.user.listoption.use`  
  

#### roles&nbsp;user&nbsp;listPermission  
List permission assigned to a user [in context]  
**Usage:** `roles user listPermission <player> [in <context>] [-all]`  
**Alias:** `listperm` `/listuperm`  
**Permission:** `cubeengine.roles.command.roles.user.listpermission.use`  
  

#### roles&nbsp;user&nbsp;remove  
Removes a role from the player  
**Usage:** `roles user remove <player> <role>`  
**Alias:** `/remURole` `/manUDel`  
**Permission:** `cubeengine.roles.command.roles.user.remove.use`  
  

#### roles&nbsp;user&nbsp;resetOption  
Resets options for this user [in context]  
**Usage:** `roles user resetOption <player> <key> [in <context>]`  
**Alias:** `resetData` `deleteOption` `deleteData` `/resetUOption` `/resetUData`  
**Permission:** `cubeengine.roles.command.roles.user.resetoption.use`  
  

#### roles&nbsp;user&nbsp;resetPermission  
Resets a permission for this user [in context]  
**Usage:** `roles user resetPermission <player> <permission> [in <context>]`  
**Alias:** `resetPerm` `/resetUPerm`  
**Permission:** `cubeengine.roles.command.roles.user.resetpermission.use`  
  

#### roles&nbsp;user&nbsp;setOption  
Sets options for this user [in context]  
**Usage:** `roles user setOption <player> <key> <value> [in <context>]`  
**Alias:** `setData` `/setUOption` `/setUData`  
**Permission:** `cubeengine.roles.command.roles.user.setoption.use`  
  

#### roles&nbsp;user&nbsp;setPermission  
Sets a permission for this user [in context]  
**Usage:** `roles user setPermission <player> <permission> <type> [in <context>]`  
**Alias:** `setPerm` `/setUPerm`  
**Permission:** `cubeengine.roles.command.roles.user.setpermission.use`  
  

## Permissions:

| Permission | Description |
| --- | --- |
| `cubeengine.roles` | Base Permission for Roles |
| `cubeengine.roles.command` | Allows using all commands of Roles |
