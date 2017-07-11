# CubeEngine - Roles

This module assigns permissions based on roles.

## Commands

#### roles

Manages the roles

Usage: `roles <command>`

Permission: `cubeengine.roles.command.roles`

Child Commands:
`admin`
`role`
`user`

#### roles admin

Manages the module

Usage: `roles admin <command>`

Alias:
`manadmin`

Permission: `cubeengine.roles.command.roles.admin`

Child Commands:
`debug`
`findPermission`
`reload`
`save`

#### roles admin debug

Toggles debug mode

Usage: `roles admin debug [seconds]`

Alias:
`/mandebug`

Permission: `cubeengine.roles.command.roles.admin.debug.use`

#### roles admin findPermission

Searches for registered Permissions

Usage: `roles admin findPermission <permission>`

Permission: `cubeengine.roles.command.roles.admin.findpermission.use`

#### roles admin reload

Reloads all roles from config

Usage: `roles admin reload `

Alias:
`/manload`

Permission: `cubeengine.roles.command.roles.admin.reload.use`

#### roles admin save

Overrides all configs with current settings

Usage: `roles admin save `

Alias:
`/mansave`

Permission: `cubeengine.roles.command.roles.admin.save.use`

#### roles role

Manage roles

Usage: `roles role <command>`

Alias:
`/manrole`

Permission: `cubeengine.roles.command.roles.role`

Child Commands:
`addParent`
`checkPermission`
`clearOption`
`clearParent`
`create`
`delete`
`list`
`listDefaultRoles`
`listOption`
`listParent`
`listPermission`
`priority`
`removeParent`
`rename`
`resetOption`
`setOption`
`setPermission`
`setPriority`
`toggleDefaultRole`

#### roles role addParent

Adds a parent role to given role [in context]

Usage: `roles role addParent <role> <parentRole> [in <context>]`

Alias:
`/addRParent`
`/manRAdd`

Permission: `cubeengine.roles.command.roles.role.addparent.use`

#### roles role checkPermission

Checks the permission in given role [in context]

Usage: `roles role checkPermission <role> <permission> [in <context>]`

Alias:
`checkPerm`
`/checkRPerm`

Permission: `cubeengine.roles.command.roles.role.checkpermission.use`

#### roles role clearOption

Clears the options for given role [in context]

Usage: `roles role clearOption <role> [in <context>]`

Alias:
`clearData`
`/clearROption`
`/clearRData`

Permission: `cubeengine.roles.command.roles.role.clearoption.use`

#### roles role clearParent

Removes all parent roles from given role [in context]

Usage: `roles role clearParent <role> [in <context>]`

Alias:
`/clearRParent`

Permission: `cubeengine.roles.command.roles.role.clearparent.use`

#### roles role create

Creates a new role

Usage: `roles role create <name>`

Alias:
`/createRole`

Permission: `cubeengine.roles.command.roles.role.create.use`

#### roles role delete

Deletes a role

Usage: `roles role delete <role> [-force]`

Alias:
`/deleteRole`

Permission: `cubeengine.roles.command.roles.role.delete.use`

#### roles role list

Lists all roles

Usage: `roles role list `

Alias:
`/listRoles`

Permission: `cubeengine.roles.command.roles.role.list.use`

#### roles role listDefaultRoles

Lists all default roles

Usage: `roles role listDefaultRoles `

Alias:
`default`
`defaultRoles`
`listDefRoles`

Permission: `cubeengine.roles.command.roles.role.listdefaultroles.use`

#### roles role listOption

Lists all options of given role [in context]

Usage: `roles role listOption <role> [in <context>] [-all]`

Alias:
`listData`
`/listROption`
`/listRData`

Permission: `cubeengine.roles.command.roles.role.listoption.use`

#### roles role listParent

Lists all parents of given role [in context]

Usage: `roles role listParent <role> [in <context>]`

Alias:
`/listRParent`

Permission: `cubeengine.roles.command.roles.role.listparent.use`

#### roles role listPermission

Lists all permissions of given role [in context]

Usage: `roles role listPermission <role> [in <context>] [-all]`

Alias:
`listPerm`
`/listRPerm`

Permission: `cubeengine.roles.command.roles.role.listpermission.use`

#### roles role priority

Show the priority of given role

Usage: `roles role priority <role>`

Alias:
`prio`

Permission: `cubeengine.roles.command.roles.role.priority.use`

#### roles role removeParent

Removes a parent role from given role [in context]

Usage: `roles role removeParent <role> <parentRole> [in <context>]`

Alias:
`/remRParent`

Permission: `cubeengine.roles.command.roles.role.removeparent.use`

#### roles role rename

Renames given role

Usage: `roles role rename <role> <new name>`

Alias:
`/renameRole`

Permission: `cubeengine.roles.command.roles.role.rename.use`

#### roles role resetOption

Resets the options for given role [in context]

Usage: `roles role resetOption <role> <key> [in <context>]`

Alias:
`resetData`
`/resetROption`
`/resetRData`

Permission: `cubeengine.roles.command.roles.role.resetoption.use`

#### roles role setOption

Sets an option for given role [in context]

Usage: `roles role setOption <role> <key> [value] [in <context>]`

Alias:
`setData`
`/setROption`
`/setRData`

Permission: `cubeengine.roles.command.roles.role.setoption.use`

#### roles role setPermission

Sets the permission for given role [in context]

Usage: `roles role setPermission <role> <permission> <type> [in <context>]`

Alias:
`setPerm`
`/setRPerm`

Permission: `cubeengine.roles.command.roles.role.setpermission.use`

#### roles role setPriority

Sets the priority of given role

Usage: `roles role setPriority <role> <priority>`

Alias:
`setPrio`
`/setRolePriority`

Permission: `cubeengine.roles.command.roles.role.setpriority.use`

#### roles role toggleDefaultRole

Toggles whether given role is a default role

Usage: `roles role toggleDefaultRole <role>`

Alias:
`toggleDefault`
`toggleDef`

Permission: `cubeengine.roles.command.roles.role.toggledefaultrole.use`

#### roles user

Manage users

Usage: `roles user <command>`

Alias:
`/manuser`

Permission: `cubeengine.roles.command.roles.user`

Child Commands:
`assign`
`checkOption`
`checkPermission`
`clear`
`clearOption`
`list`
`listOption`
`listPermission`
`remove`
`resetOption`
`resetPermission`
`setOption`
`setPermission`

#### roles user assign

Assign a role to the player [-temp]

Usage: `roles user assign <player> <role> [-temp]`

Alias:
`add`
`give`
`/manUAdd`
`/assignURole`
`/addURole`
`/giveURole`

Permission: `cubeengine.roles.command.roles.user.assign.use`

#### roles user checkOption

Checks for options of a user [in context]

Usage: `roles user checkOption <player> <key> [in <context>]`

Alias:
`checkData`
`/checkUOption`
`/checkUData`

Permission: `cubeengine.roles.command.roles.user.checkoption.use`

#### roles user checkPermission

Checks for permissions of a user [in context]

Usage: `roles user checkPermission <player> <permission> [in <context>]`

Alias:
`checkperm`
`/checkuperm`

Permission: `cubeengine.roles.command.roles.user.checkpermission.use`

#### roles user clear

Clears all roles from the player and sets the defaultroles [in context]

Usage: `roles user clear <player>`

Alias:
`/clearURole`
`/manUClear`

Permission: `cubeengine.roles.command.roles.user.clear.use`

#### roles user clearOption

Resets options for this user [in context]

Usage: `roles user clearOption <player> [in <context>]`

Alias:
`clearData`
`/clearUOption`
`/clearUData`

Permission: `cubeengine.roles.command.roles.user.clearoption.use`

#### roles user list

Lists roles of a user

Usage: `roles user list <player>`

Alias:
`/listurole`

Permission: `cubeengine.roles.command.roles.user.list.use`

#### roles user listOption

Lists assigned options from a user [in context]

Usage: `roles user listOption <player> [in <context>] [-all]`

Alias:
`listData`
`/listUOption`
`/listUData`

Permission: `cubeengine.roles.command.roles.user.listoption.use`

#### roles user listPermission

List permission assigned to a user [in context]

Usage: `roles user listPermission <player> [in <context>] [-all]`

Alias:
`listperm`
`/listuperm`

Permission: `cubeengine.roles.command.roles.user.listpermission.use`

#### roles user remove

Removes a role from the player

Usage: `roles user remove <player> <role>`

Alias:
`/remURole`
`/manUDel`

Permission: `cubeengine.roles.command.roles.user.remove.use`

#### roles user resetOption

Resets options for this user [in context]

Usage: `roles user resetOption <player> <key> [in <context>]`

Alias:
`resetData`
`deleteOption`
`deleteData`
`/resetUOption`
`/resetUData`

Permission: `cubeengine.roles.command.roles.user.resetoption.use`

#### roles user resetPermission

Resets a permission for this user [in context]

Usage: `roles user resetPermission <player> <permission> [in <context>]`

Alias:
`resetPerm`
`/resetUPerm`

Permission: `cubeengine.roles.command.roles.user.resetpermission.use`

#### roles user setOption

Sets options for this user [in context]

Usage: `roles user setOption <player> <key> <value> [in <context>]`

Alias:
`setData`
`/setUOption`
`/setUData`

Permission: `cubeengine.roles.command.roles.user.setoption.use`

#### roles user setPermission

Sets a permission for this user [in context]

Usage: `roles user setPermission <player> <permission> <type> [in <context>]`

Alias:
`setPerm`
`/setUPerm`

Permission: `cubeengine.roles.command.roles.user.setpermission.use`

## Additional Permissions

 - ##### `cubeengine.roles`
   Base Permission for roles

