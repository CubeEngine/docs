# Roles

## Description

This module is an advanced permission manager.
Permissions, as well as meta data, can be grouped in Roles.
Roles support multi-inheritance for their permissions.
Players can have multiple roles and they can get permissions
and meta data directly assigned to them.

## COnfiguration structure

[@Faithcaio]

### Permission list

The permissions can be specified as a list just like you know it from
other permission managers. In addition to the usual list Roles supports
a tree structure which greatly increases readability and maintainability.
Roles will automatilcy optimize the permission list to a compact tree.
