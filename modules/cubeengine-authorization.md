# CubeEngine - Authorization
Provides password authorization

## Features:
 - User registration with password
 - Hashed password storage
 - Random per-server static salt and per player dynamic salt

## Commands:

| Command | Description | Permission<br>`cubeengine.authorization.command.<perm>` |
| --- | --- | --- |
| [*clearPassword*](#clearpassword) | Clears your password. | `clearpassword.use` |
| [*login*](#login) | Logs you in with your password! | `login.use` |
| [*logout*](#logout) | Logs you out! | `logout.use` |
| [*setPassword*](#setpassword) | Sets your password. | `setpassword.use` |

#### clearPassword  
Clears your password.  
**Usage:** `clearPassword [players]`  
**Alias:** `clearpw`  
**Permission:** `cubeengine.authorization.command.clearpassword.use`  
  

#### login  
Logs you in with your password!  
**Usage:** `login <password>`  
**Permission:** `cubeengine.authorization.command.login.use`  
  

#### logout  
Logs you out!  
**Usage:** `logout `  
**Permission:** `cubeengine.authorization.command.logout.use`  
  

#### setPassword  
Sets your password.  
**Usage:** `setPassword <password> <player>`  
**Alias:** `setpw`  
**Permission:** `cubeengine.authorization.command.setpassword.use`  
  

## Additional Permissions:

| Permission | Description |
| --- | --- |
| `cubeengine.authorization` | Base Permission for Authorization |
| `cubeengine.authorization.command` | Base Commands Permission |
| `cubeengine.authorization.command.clearpassword.all` | Allows clearing all passwords |
| `cubeengine.authorization.command.clearpassword.other` | Allows clearing passwords of other players |
| `cubeengine.authorization.command.setpassword.other` | Allows setting passwords of other players |
