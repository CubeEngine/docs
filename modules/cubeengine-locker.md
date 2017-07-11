# CubeEngine - Locker
Put a lock onto your most precious things
## Commands
| Command | Description | Permission<br>`cubeengine.locker.command.<perm>` |
| --- | --- | --- |
| [*locker*](#locker) | Locker commands | `locker` |
| [**locker** *admin*](#locker-admin) | Administrate the protections | `locker.admin` |
| [**locker** **admin** *cleanup*](#locker-admin-cleanup) | Deletes old locks | `locker.admin.cleanup.use` |
| [**locker** **admin** *purge*](#locker-admin-purge) | Deletes all locks of given player | `locker.admin.purge.use` |
| [**locker** **admin** *remove*](#locker-admin-remove) | Deletes a protection by its id | `locker.admin.remove.use` |
| [**locker** **admin** *tp*](#locker-admin-tp) | Teleport to a protection | `locker.admin.tp.use` |
| [**locker** **admin** *view*](#locker-admin-view) | Opens a protected chest by protection id | `locker.admin.view.use` |
| [**locker** *create*](#locker-create) | Creates various protections | `locker.create` |
| [**locker** **create** *donation*](#locker-create-donation) | creates a donation protection | `locker.create.donation.use` |
| [**locker** **create** *free*](#locker-create-free) | creates a free protection | `locker.create.free.use` |
| [**locker** **create** *guarded*](#locker-create-guarded) | creates a guarded protection | `locker.create.guarded.use` |
| [**locker** **create** *password*](#locker-create-password) | creates a donation protection | `locker.create.password.use` |
| [**locker** **create** *private*](#locker-create-private) | creates a private protection | `locker.create.private.use` |
| [**locker** **create** *public*](#locker-create-public) | creates a public protection | `locker.create.public.use` |
| [**locker** *flag*](#locker-flag) | Sets or unsets flags | `locker.flag.use` |
| [**locker** *give*](#locker-give) | gives a protection to someone else | `locker.give.use` |
| [**locker** *info*](#locker-info) | Shows information about a protection | `locker.info.use` |
| [**locker** *key*](#locker-key) | creates a KeyBook or invalidates previous KeyBooks | `locker.key.use` |
| [**locker** *modify*](#locker-modify) | adds or removes player from the accesslist | `locker.modify.use` |
| [**locker** *persist*](#locker-persist) | persists your last locker command | `locker.persist.use` |
| [**locker** *remove*](#locker-remove) | Shows information about a protection | `locker.remove.use` |
| [**locker** *unlock*](#locker-unlock) | Unlocks a password protected chest | `locker.unlock.use` |
#### locker  
Locker commands  
**Usage:** `locker <command>`  
**Alias:** `l`  
**Permission:** `cubeengine.locker.command.locker`  
**SubCommands:** `admin` `create` `flag` `give` `info` `key` `modify` `persist` `remove` `unlock`  
#### locker admin  
Administrate the protections  
**Usage:** `locker admin <command>`  
**Permission:** `cubeengine.locker.command.locker.admin`  
**SubCommands:** `cleanup` `purge` `remove` `tp` `view`  
#### locker admin cleanup  
Deletes old locks  
**Usage:** `locker admin cleanup `  
**Permission:** `cubeengine.locker.command.locker.admin.cleanup.use`  
  
#### locker admin purge  
Deletes all locks of given player  
**Usage:** `locker admin purge <player>`  
**Permission:** `cubeengine.locker.command.locker.admin.purge.use`  
  
#### locker admin remove  
Deletes a protection by its id  
**Usage:** `locker admin remove <id>`  
**Permission:** `cubeengine.locker.command.locker.admin.remove.use`  
  
#### locker admin tp  
Teleport to a protection  
**Usage:** `locker admin tp <id>`  
**Permission:** `cubeengine.locker.command.locker.admin.tp.use`  
  
#### locker admin view  
Opens a protected chest by protection id  
**Usage:** `locker admin view <id>`  
**Permission:** `cubeengine.locker.command.locker.admin.view.use`  
  
#### locker create  
Creates various protections  
**Usage:** `locker create <command>`  
**Permission:** `cubeengine.locker.command.locker.create`  
**SubCommands:** `donation` `free` `guarded` `password` `private` `public`  
#### locker create donation  
creates a donation protection  
**Usage:** `locker create donation [password] [-keybook]`  
**Alias:** `/cdonation`  
**Permission:** `cubeengine.locker.command.locker.create.donation.use`  
  
#### locker create free  
creates a free protection  
**Usage:** `locker create free [password] [-keybook]`  
**Alias:** `/cfree`  
**Permission:** `cubeengine.locker.command.locker.create.free.use`  
  
#### locker create guarded  
creates a guarded protection  
**Usage:** `locker create guarded [password] [-keybook]`  
**Alias:** `/cguarded`  
**Permission:** `cubeengine.locker.command.locker.create.guarded.use`  
  
#### locker create password  
creates a donation protection  
**Usage:** `locker create password <password> [-keybook]`  
**Alias:** `/cpassword`  
**Permission:** `cubeengine.locker.command.locker.create.password.use`  
  
#### locker create private  
creates a private protection  
**Usage:** `locker create private [password] [-keybook]`  
**Alias:** `/cprivate`  
**Permission:** `cubeengine.locker.command.locker.create.private.use`  
  
#### locker create public  
creates a public protection  
**Usage:** `locker create public `  
**Alias:** `/cpublic`  
**Permission:** `cubeengine.locker.command.locker.create.public.use`  
  
#### locker flag  
Sets or unsets flags  
**Usage:** `locker flag [set <flags...>] [unset <flags...>] [-persist]`  
**Alias:** `/cflag`  
**Permission:** `cubeengine.locker.command.locker.flag.use`  
  
#### locker give  
gives a protection to someone else  
**Usage:** `locker give <player> [-persist]`  
**Alias:** `/cgive`  
**Permission:** `cubeengine.locker.command.locker.give.use`  
  
#### locker info  
Shows information about a protection  
**Usage:** `locker info [-persist]`  
**Alias:** `/cinfo`  
**Permission:** `cubeengine.locker.command.locker.info.use`  
  
#### locker key  
creates a KeyBook or invalidates previous KeyBooks  
**Usage:** `locker key [-invalidate] [-persist]`  
**Alias:** `/ckey`  
**Permission:** `cubeengine.locker.command.locker.key.use`  
  
#### locker modify  
adds or removes player from the accesslist  
**Usage:** `locker modify <players> [-global] [-persist]`  
**Alias:** `/cmodify`  
**Permission:** `cubeengine.locker.command.locker.modify.use`  
  
#### locker persist  
persists your last locker command  
**Usage:** `locker persist `  
**Alias:** `/cpersist`  
**Permission:** `cubeengine.locker.command.locker.persist.use`  
  
#### locker remove  
Shows information about a protection  
**Usage:** `locker remove [-persist]`  
**Alias:** `/cremove`  
**Permission:** `cubeengine.locker.command.locker.remove.use`  
  
#### locker unlock  
Unlocks a password protected chest  
**Usage:** `locker unlock <password> [-persist]`  
**Alias:** `/cunlock`  
**Permission:** `cubeengine.locker.command.locker.unlock.use`  
  
## Additional Permissions

| Permission | Description |
| --- | --- |
| `cubeengine.locker` | Base Permission for locker |