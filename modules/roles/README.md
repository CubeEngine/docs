# Roles

## Description

This module is an advanced permission manager.
Permissions, as well as meta data, can be grouped in Roles.
Roles support multi-inheritance for their permissions.
Players can have multiple roles and they can get permissions
and meta data directly assigned to them.

## Configuration structure

### Main configuration

The main configuration contains settings to disable permissions in offlinemode, set default roles and mirror roles, assigned roles and/or directly assigned metadata and permissions

### Role Configurations

It is possible to declare global roles and roles for each world. Global roles can be assigned in every world, but normal roles are restricted to the world they were declared for and to worlds that mirror the roles.
Every role configuration contains the rolename, a priority value, a permissions list, a list of parents and a metadata map.

When inheriting from multiple roles or assigning them to a player, priority is used to determine which role has higher priority.
The inheriting role will always override values from its parents

#### Permission list

The permissions can be specified as a list just like you know it from
other permission managers. In addition to the usual list Roles supports
a tree structure which greatly increases readability and maintainability.
Roles will automatilcy optimize the permission list to a compact tree.

#### Metadata Map

The metadata maps strings onto strings.
Other modules like [Chat](http://engine.cubeisland.de/documentation/modules/chat "The Chat Module") access the metadata to set prefix or suffix.
Again when multiple metadata values for the same key collide priority & inheritance is used to determine the final value.
