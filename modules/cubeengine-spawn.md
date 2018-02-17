# CubeEngine - Spawn
Modifies the default spawn behaviour

## Features:
 - Sets the the world spawn
 - Supports subject options

## Commands:

| Command | Description | Permission<br>`cubeengine.spawn.command.<perm>` |
| --- | --- | --- |
| [*roleSpawn*](#rolespawn) | Teleports a player to the configured rolespawn | `rolespawn.use` |
| [*setRoleSpawn*](#setrolespawn) | Changes the respawnpoint | `setrolespawn.use` |

#### roleSpawn  
Teleports a player to the configured rolespawn  
**Usage:** `roleSpawn <player> <context> [role <role>] [-force]`  
**Permission:** `cubeengine.spawn.command.rolespawn.use`  
  

#### setRoleSpawn  
Changes the respawnpoint  
**Usage:** `setRoleSpawn <role> <context>`  
**Permission:** `cubeengine.spawn.command.setrolespawn.use`  
  

## Permissions:

| Permission | Description |
| --- | --- |
| `cubeengine.spawn` | Base Permission for Spawn |
| `cubeengine.spawn.command` | Allows using all commands of Spawn |
