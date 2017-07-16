# CubeEngine - Locker
Put a lock onto your most precious things

## Features:
 - Chest, animal and door locks
 - Additional lockable objects configurable
 - Keys to open locks
 - Automatic protection when taming animals or building chests
 - Protect chests from hopper inputs
 - Synchronized double doors
 - Automatically close doors
 - Everything configurable

## Commands:

| Command | Description | Permission<br>`cubeengine.locker.command.<perm>` |
| --- | --- | --- |
| [*locker*](#locker) | Locker commands | `locker` |
| [**locker**&nbsp;*admin*](#locker&nbsp;admin) | Administrate the protections | `locker.admin` |
| [**locker**&nbsp;**admin**&nbsp;*cleanup*](#locker&nbsp;admin&nbsp;cleanup) | Deletes old locks | `locker.admin.cleanup.use` |
| [**locker**&nbsp;**admin**&nbsp;*purge*](#locker&nbsp;admin&nbsp;purge) | Deletes all locks of given player | `locker.admin.purge.use` |
| [**locker**&nbsp;**admin**&nbsp;*remove*](#locker&nbsp;admin&nbsp;remove) | Deletes a protection by its id | `locker.admin.remove.use` |
| [**locker**&nbsp;**admin**&nbsp;*tp*](#locker&nbsp;admin&nbsp;tp) | Teleport to a protection | `locker.admin.tp.use` |
| [**locker**&nbsp;**admin**&nbsp;*view*](#locker&nbsp;admin&nbsp;view) | Opens a protected chest by protection id | `locker.admin.view.use` |
| [**locker**&nbsp;*create*](#locker&nbsp;create) | Creates various protections | `locker.create` |
| [**locker**&nbsp;**create**&nbsp;*donation*](#locker&nbsp;create&nbsp;donation) | creates a donation protection | `locker.create.donation.use` |
| [**locker**&nbsp;**create**&nbsp;*free*](#locker&nbsp;create&nbsp;free) | creates a free protection | `locker.create.free.use` |
| [**locker**&nbsp;**create**&nbsp;*guarded*](#locker&nbsp;create&nbsp;guarded) | creates a guarded protection | `locker.create.guarded.use` |
| [**locker**&nbsp;**create**&nbsp;*password*](#locker&nbsp;create&nbsp;password) | creates a donation protection | `locker.create.password.use` |
| [**locker**&nbsp;**create**&nbsp;*private*](#locker&nbsp;create&nbsp;private) | creates a private protection | `locker.create.private.use` |
| [**locker**&nbsp;**create**&nbsp;*public*](#locker&nbsp;create&nbsp;public) | creates a public protection | `locker.create.public.use` |
| [**locker**&nbsp;*flag*](#locker&nbsp;flag) | Sets or unsets flags | `locker.flag.use` |
| [**locker**&nbsp;*give*](#locker&nbsp;give) | gives a protection to someone else | `locker.give.use` |
| [**locker**&nbsp;*info*](#locker&nbsp;info) | Shows information about a protection | `locker.info.use` |
| [**locker**&nbsp;*key*](#locker&nbsp;key) | creates a KeyBook or invalidates previous KeyBooks | `locker.key.use` |
| [**locker**&nbsp;*modify*](#locker&nbsp;modify) | adds or removes player from the accesslist | `locker.modify.use` |
| [**locker**&nbsp;*persist*](#locker&nbsp;persist) | persists your last locker command | `locker.persist.use` |
| [**locker**&nbsp;*remove*](#locker&nbsp;remove) | Shows information about a protection | `locker.remove.use` |
| [**locker**&nbsp;*unlock*](#locker&nbsp;unlock) | Unlocks a password protected chest | `locker.unlock.use` |

#### locker  
Locker commands  
**Usage:** `locker <command>`  
**Alias:** `l`  
**Permission:** `cubeengine.locker.command.locker`  
**SubCommands:** `admin` `create` `flag` `give` `info` `key` `modify` `persist` `remove` `unlock`  

#### locker&nbsp;admin  
Administrate the protections  
**Usage:** `locker admin <command>`  
**Permission:** `cubeengine.locker.command.locker.admin`  
**SubCommands:** `cleanup` `purge` `remove` `tp` `view`  

#### locker&nbsp;admin&nbsp;cleanup  
Deletes old locks  
**Usage:** `locker admin cleanup `  
**Permission:** `cubeengine.locker.command.locker.admin.cleanup.use`  
  

#### locker&nbsp;admin&nbsp;purge  
Deletes all locks of given player  
**Usage:** `locker admin purge <player>`  
**Permission:** `cubeengine.locker.command.locker.admin.purge.use`  
  

#### locker&nbsp;admin&nbsp;remove  
Deletes a protection by its id  
**Usage:** `locker admin remove <id>`  
**Permission:** `cubeengine.locker.command.locker.admin.remove.use`  
  

#### locker&nbsp;admin&nbsp;tp  
Teleport to a protection  
**Usage:** `locker admin tp <id>`  
**Permission:** `cubeengine.locker.command.locker.admin.tp.use`  
  

#### locker&nbsp;admin&nbsp;view  
Opens a protected chest by protection id  
**Usage:** `locker admin view <id>`  
**Permission:** `cubeengine.locker.command.locker.admin.view.use`  
  

#### locker&nbsp;create  
Creates various protections  
**Usage:** `locker create <command>`  
**Permission:** `cubeengine.locker.command.locker.create`  
**SubCommands:** `donation` `free` `guarded` `password` `private` `public`  

#### locker&nbsp;create&nbsp;donation  
creates a donation protection  
**Usage:** `locker create donation [password] [-keybook]`  
**Alias:** `/cdonation`  
**Permission:** `cubeengine.locker.command.locker.create.donation.use`  
  

#### locker&nbsp;create&nbsp;free  
creates a free protection  
**Usage:** `locker create free [password] [-keybook]`  
**Alias:** `/cfree`  
**Permission:** `cubeengine.locker.command.locker.create.free.use`  
  

#### locker&nbsp;create&nbsp;guarded  
creates a guarded protection  
**Usage:** `locker create guarded [password] [-keybook]`  
**Alias:** `/cguarded`  
**Permission:** `cubeengine.locker.command.locker.create.guarded.use`  
  

#### locker&nbsp;create&nbsp;password  
creates a donation protection  
**Usage:** `locker create password <password> [-keybook]`  
**Alias:** `/cpassword`  
**Permission:** `cubeengine.locker.command.locker.create.password.use`  
  

#### locker&nbsp;create&nbsp;private  
creates a private protection  
**Usage:** `locker create private [password] [-keybook]`  
**Alias:** `/cprivate`  
**Permission:** `cubeengine.locker.command.locker.create.private.use`  
  

#### locker&nbsp;create&nbsp;public  
creates a public protection  
**Usage:** `locker create public `  
**Alias:** `/cpublic`  
**Permission:** `cubeengine.locker.command.locker.create.public.use`  
  

#### locker&nbsp;flag  
Sets or unsets flags  
**Usage:** `locker flag [set <flags...>] [unset <flags...>] [-persist]`  
**Alias:** `/cflag`  
**Permission:** `cubeengine.locker.command.locker.flag.use`  
  

#### locker&nbsp;give  
gives a protection to someone else  
**Usage:** `locker give <player> [-persist]`  
**Alias:** `/cgive`  
**Permission:** `cubeengine.locker.command.locker.give.use`  
  

#### locker&nbsp;info  
Shows information about a protection  
**Usage:** `locker info [-persist]`  
**Alias:** `/cinfo`  
**Permission:** `cubeengine.locker.command.locker.info.use`  
  

#### locker&nbsp;key  
creates a KeyBook or invalidates previous KeyBooks  
**Usage:** `locker key [-invalidate] [-persist]`  
**Alias:** `/ckey`  
**Permission:** `cubeengine.locker.command.locker.key.use`  
  

#### locker&nbsp;modify  
adds or removes player from the accesslist  
**Usage:** `locker modify <players> [-global] [-persist]`  
**Alias:** `/cmodify`  
**Permission:** `cubeengine.locker.command.locker.modify.use`  
  

#### locker&nbsp;persist  
persists your last locker command  
**Usage:** `locker persist `  
**Alias:** `/cpersist`  
**Permission:** `cubeengine.locker.command.locker.persist.use`  
  

#### locker&nbsp;remove  
Shows information about a protection  
**Usage:** `locker remove [-persist]`  
**Alias:** `/cremove`  
**Permission:** `cubeengine.locker.command.locker.remove.use`  
  

#### locker&nbsp;unlock  
Unlocks a password protected chest  
**Usage:** `locker unlock <password> [-persist]`  
**Alias:** `/cunlock`  
**Permission:** `cubeengine.locker.command.locker.unlock.use`  
  

## Additional Permissions:

| Permission | Description |
| --- | --- |
| `cubeengine.locker` | Base Permission for locker |