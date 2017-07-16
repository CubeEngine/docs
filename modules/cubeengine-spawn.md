# CubeEngine - Spawn
Modifies the default spawn behaviour

## Features:
 - Sets the the world spawn
 - Supports subject options

## Commands:

| Command | Description | Permission<br>`cubeengine.spawn.command.<perm>` |
| --- | --- | --- |
| [*setRoleSpawn*](#setrolespawn) | Changes the respawnpoint | `setrolespawn.use` |
| [*roleSpawn*](#rolespawn) | Teleports a player to the configured rolespawn | `rolespawn.use` |

#### setRoleSpawn  
Changes the respawnpoint  
**Usage:** `setRoleSpawn <role> <context>`  
**Permission:** `cubeengine.spawn.command.setrolespawn.use`  
  

#### roleSpawn  
Teleports a player to the configured rolespawn  
**Usage:** `roleSpawn <player> <context> [role <role>] [-force]`  
**Permission:** `cubeengine.spawn.command.rolespawn.use`  
  

## Additional Permissions:

| Permission | Description |
| --- | --- |
| `cubeengine.spawn` | Base Permission for spawn |