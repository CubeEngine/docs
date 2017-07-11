# CubeEngine - Authorization
Provides password authorization
## Commands
| Command | Description | Permission<br>`cubeengine.authorization.command.<perm>` |
| --- | --- | --- |
| [*logout*](#logout) | Logs you out! | `logout.use` |
| [*login*](#login) | Logs you in with your password! | `login.use` |
| [*clearPassword*](#clearpassword) | Clears your password. | `clearpassword.use` |
| [*setPassword*](#setpassword) | Sets your password. | `setpassword.use` |
#### logout  
Logs you out!  
**Usage:** `logout `  
**Permission:** `cubeengine.authorization.command.logout.use`  
  
#### login  
Logs you in with your password!  
**Usage:** `login <password>`  
**Permission:** `cubeengine.authorization.command.login.use`  
  
#### clearPassword  
Clears your password.  
**Usage:** `clearPassword [players]`  
**Alias:** `clearpw`  
**Permission:** `cubeengine.authorization.command.clearpassword.use`  
  
#### setPassword  
Sets your password.  
**Usage:** `setPassword <password> <player>`  
**Alias:** `setpw`  
**Permission:** `cubeengine.authorization.command.setpassword.use`  
  
## Additional Permissions

| Permission | Description |
| --- | --- |
| `cubeengine.authorization` | Base Permission for authorization |