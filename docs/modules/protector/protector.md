# CubeEngine - Protector
Protects your worlds

## Features:
 - Define regions in your worlds and protect them
 - Protects from any world changes
 - Can be used for greylisting

## Commands:

| Command | Description | Permission<br>`cubeengine.protector.command.<perm>` |
| --- | --- | --- |
| [*protect*](#protect) | Manages the regions |  |
| [**protect**&nbsp;*clear*](#protectclear) | Clears a zones protection settings | `protect.clear.use` |
| [**protect**&nbsp;*control*](#protectcontrol) | Manages the region settings |  |
| [**protect**&nbsp;**control**&nbsp;*blockdamage*](#protectcontrolblockdamage) | Manages the region block-damage settings |  |
| [**protect**&nbsp;**control**&nbsp;**blockdamage**&nbsp;*block*](#protectcontrolblockdamageblock) | Controls blocks breaking blocks | `protect.control.blockdamage.block.use` |
| [**protect**&nbsp;**control**&nbsp;**blockdamage**&nbsp;*explosion*](#protectcontrolblockdamageexplosion) | Controls explosions breaking blocks | `protect.control.blockdamage.explosion.use` |
| [**protect**&nbsp;**control**&nbsp;**blockdamage**&nbsp;*fire*](#protectcontrolblockdamagefire) | Controls fire breaking blocks | `protect.control.blockdamage.fire.use` |
| [**protect**&nbsp;**control**&nbsp;**blockdamage**&nbsp;*lightningfire*](#protectcontrolblockdamagelightningfire) | Controls lightning fire | `protect.control.blockdamage.lightningFire.use` |
| [**protect**&nbsp;**control**&nbsp;**blockdamage**&nbsp;*monster*](#protectcontrolblockdamagemonster) | Controls entities breaking blocks | `protect.control.blockdamage.monster.use` |
| [**protect**&nbsp;**control**&nbsp;**blockdamage**&nbsp;*playerexplosion*](#protectcontrolblockdamageplayerexplosion) | Controls explosions caused by players breaking blocks | `protect.control.blockdamage.playerExplosion.use` |
| [**protect**&nbsp;**control**&nbsp;*build*](#protectcontrolbuild) | Controls player building | `protect.control.build.use` |
| [**protect**&nbsp;**control**&nbsp;*command*](#protectcontrolcommand) | Controls executing commands | `protect.control.command.use` |
| [**protect**&nbsp;**control**&nbsp;*deadcircuit*](#protectcontroldeadcircuit) | Controls redstone circuits commands | `protect.control.deadCircuit.use` |
| [**protect**&nbsp;**control**&nbsp;*entitydamage*](#protectcontrolentitydamage) | Manages the region entity-damage settings |  |
| [**protect**&nbsp;**control**&nbsp;**entitydamage**&nbsp;*all*](#protectcontrolentitydamageall) | Controls entity damage | `protect.control.entityDamage.all.use` |
| [**protect**&nbsp;**control**&nbsp;**entitydamage**&nbsp;*entity*](#protectcontrolentitydamageentity) | Controls damage by entities | `protect.control.entityDamage.entity.use` |
| [**protect**&nbsp;**control**&nbsp;**entitydamage**&nbsp;*living*](#protectcontrolentitydamageliving) | Controls damage by living entities | `protect.control.entityDamage.living.use` |
| [**protect**&nbsp;**control**&nbsp;*move*](#protectcontrolmove) | Controls movement | `protect.control.move.use` |
| [**protect**&nbsp;**control**&nbsp;*playerdamage*](#protectcontrolplayerdamage) | Manages the region player-damage settings |  |
| [**protect**&nbsp;**control**&nbsp;**playerdamage**&nbsp;*all*](#protectcontrolplayerdamageall) | Controls player damage | `protect.control.playerDamage.all.use` |
| [**protect**&nbsp;**control**&nbsp;**playerdamage**&nbsp;*byliving*](#protectcontrolplayerdamagebyliving) | Controls player damage by living entities | `protect.control.playerDamage.byliving.use` |
| [**protect**&nbsp;**control**&nbsp;**playerdamage**&nbsp;*pvp*](#protectcontrolplayerdamagepvp) | Controls pvp damage | `protect.control.playerDamage.pvp.use` |
| [**protect**&nbsp;**control**&nbsp;**playerdamage**&nbsp;*targeting*](#protectcontrolplayerdamagetargeting) | Controls mobs targeting players | `protect.control.playerDamage.targeting.use` |
| [**protect**&nbsp;**control**&nbsp;*spawn*](#protectcontrolspawn) | Controls spawning of entities | `protect.control.spawn.use` |
| [**protect**&nbsp;**control**&nbsp;*teleport*](#protectcontrolteleport) | Controls teleport movement | `protect.control.teleport.use` |
| [**protect**&nbsp;**control**&nbsp;*useall*](#protectcontroluseall) | Controls players interacting with blocks | `protect.control.useAll.use` |
| [**protect**&nbsp;**control**&nbsp;*useblock*](#protectcontroluseblock) | Controls player interacting with blocks | `protect.control.useBlock.use` |
| [**protect**&nbsp;**control**&nbsp;*useitem*](#protectcontroluseitem) | Controls player interacting with items | `protect.control.useItem.use` |
| [**protect**&nbsp;*info*](#protectinfo) | Displays Region info | `protect.info.use` |
| [**protect**&nbsp;*list*](#protectlist) | Lists protected zones | `protect.list.use` |
| [**protect**&nbsp;*priority*](#protectpriority) | Changes protection zone priority | `protect.priority.use` |

#### protect  
Manages the regions  
**Usage:** `protect`  
**SubCommands:** `clear` `control` `info` `list` `priority`  

#### protect&nbsp;clear  
Clears a zones protection settings  
**Usage:** `protect clear <region>`  
**Permission:** `cubeengine.protector.command.protect.clear.use`  
  

#### protect&nbsp;control  
Manages the region settings  
**Usage:** `protect control`  
**SubCommands:** `blockdamage` `build` `command` `deadcircuit` `entitydamage` `move` `playerdamage` `spawn` `teleport` `useall` `useblock` `useitem`  

#### protect&nbsp;control&nbsp;blockdamage  
Manages the region block-damage settings  
**Usage:** `protect control blockdamage`  
**SubCommands:** `block` `explosion` `fire` `lightningfire` `monster` `playerexplosion`  

#### protect&nbsp;control&nbsp;blockdamage&nbsp;block  
Controls blocks breaking blocks  
**Usage:** `protect control blockdamage block <by> <set>[?]`  
**Permission:** `cubeengine.protector.command.protect.control.blockdamage.block.use`  
  

#### protect&nbsp;control&nbsp;blockdamage&nbsp;explosion  
Controls explosions breaking blocks  
**Usage:** `protect control blockdamage explosion <set>[?]`  
**Permission:** `cubeengine.protector.command.protect.control.blockdamage.explosion.use`  
  

#### protect&nbsp;control&nbsp;blockdamage&nbsp;fire  
Controls fire breaking blocks  
**Usage:** `protect control blockdamage fire <set>[?]`  
**Permission:** `cubeengine.protector.command.protect.control.blockdamage.fire.use`  
  

#### protect&nbsp;control&nbsp;blockdamage&nbsp;lightningfire  
Controls lightning fire  
**Usage:** `protect control blockdamage lightningfire <set>[?]`  
**Permission:** `cubeengine.protector.command.protect.control.blockdamage.lightningFire.use`  
  

#### protect&nbsp;control&nbsp;blockdamage&nbsp;monster  
Controls entities breaking blocks  
**Usage:** `protect control blockdamage monster <set>[?]`  
**Permission:** `cubeengine.protector.command.protect.control.blockdamage.monster.use`  
  

#### protect&nbsp;control&nbsp;blockdamage&nbsp;playerexplosion  
Controls explosions caused by players breaking blocks  
**Usage:** `protect control blockdamage playerexplosion <set>[?]`  
**Permission:** `cubeengine.protector.command.protect.control.blockdamage.playerExplosion.use`  
  

#### protect&nbsp;control&nbsp;build  
Controls player building  
**Usage:** `protect control build <set>[?]`  
**Permission:** `cubeengine.protector.command.protect.control.build.use`  
  

#### protect&nbsp;control&nbsp;command  
Controls executing commands  
**Usage:** `protect control command <command> <set>[?][?]`  
**Permission:** `cubeengine.protector.command.protect.control.command.use`  
  

#### protect&nbsp;control&nbsp;deadcircuit  
Controls redstone circuits commands  
**Usage:** `protect control deadcircuit <set>[?]`  
**Permission:** `cubeengine.protector.command.protect.control.deadCircuit.use`  
  

#### protect&nbsp;control&nbsp;entitydamage  
Manages the region entity-damage settings  
**Usage:** `protect control entitydamage`  
**SubCommands:** `all` `entity` `living`  

#### protect&nbsp;control&nbsp;entitydamage&nbsp;all  
Controls entity damage  
**Usage:** `protect control entitydamage all <set>[?]`  
**Permission:** `cubeengine.protector.command.protect.control.entityDamage.all.use`  
  

#### protect&nbsp;control&nbsp;entitydamage&nbsp;entity  
Controls damage by entities  
**Usage:** `protect control entitydamage entity <type> <set>[?]`  
**Permission:** `cubeengine.protector.command.protect.control.entityDamage.entity.use`  
  

#### protect&nbsp;control&nbsp;entitydamage&nbsp;living  
Controls damage by living entities  
**Usage:** `protect control entitydamage living <set>[?]`  
**Permission:** `cubeengine.protector.command.protect.control.entityDamage.living.use`  
  

#### protect&nbsp;control&nbsp;move  
Controls movement  
**Usage:** `protect control move <type> <set>[?]`  
**Permission:** `cubeengine.protector.command.protect.control.move.use`  
  

#### protect&nbsp;control&nbsp;playerdamage  
Manages the region player-damage settings  
**Usage:** `protect control playerdamage`  
**SubCommands:** `all` `byliving` `pvp` `targeting`  

#### protect&nbsp;control&nbsp;playerdamage&nbsp;all  
Controls player damage  
**Usage:** `protect control playerdamage all <set>[?]`  
**Permission:** `cubeengine.protector.command.protect.control.playerDamage.all.use`  
  

#### protect&nbsp;control&nbsp;playerdamage&nbsp;byliving  
Controls player damage by living entities  
**Usage:** `protect control playerdamage byliving <set>[?]`  
**Permission:** `cubeengine.protector.command.protect.control.playerDamage.byliving.use`  
  

#### protect&nbsp;control&nbsp;playerdamage&nbsp;pvp  
Controls pvp damage  
**Usage:** `protect control playerdamage pvp <set>[?]`  
**Permission:** `cubeengine.protector.command.protect.control.playerDamage.pvp.use`  
  

#### protect&nbsp;control&nbsp;playerdamage&nbsp;targeting  
Controls mobs targeting players  
**Usage:** `protect control playerdamage targeting <set>[?]`  
**Permission:** `cubeengine.protector.command.protect.control.playerDamage.targeting.use`  
  

#### protect&nbsp;control&nbsp;spawn  
Controls spawning of entities  
**Usage:** `protect control spawn <type> <what> <set>[?]`  
**Permission:** `cubeengine.protector.command.protect.control.spawn.use`  
  

#### protect&nbsp;control&nbsp;teleport  
Controls teleport movement  
**Usage:** `protect control teleport <set>[?]`  
**Permission:** `cubeengine.protector.command.protect.control.teleport.use`  
  

#### protect&nbsp;control&nbsp;useall  
Controls players interacting with blocks  
**Usage:** `protect control useall <type> <set>[?]`  
**Permission:** `cubeengine.protector.command.protect.control.useAll.use`  
  

#### protect&nbsp;control&nbsp;useblock  
Controls player interacting with blocks  
**Usage:** `protect control useblock <type> <set>[?]`  
**Permission:** `cubeengine.protector.command.protect.control.useBlock.use`  
  

#### protect&nbsp;control&nbsp;useitem  
Controls player interacting with items  
**Usage:** `protect control useitem <type> <set>[?]`  
**Permission:** `cubeengine.protector.command.protect.control.useItem.use`  
  

#### protect&nbsp;info  
Displays Region info  
**Usage:** `protect info [region][?]`  
**Permission:** `cubeengine.protector.command.protect.info.use`  
  

#### protect&nbsp;list  
Lists protected zones  
**Usage:** `protect list [match][?]`  
**Permission:** `cubeengine.protector.command.protect.list.use`  
  

#### protect&nbsp;priority  
Changes protection zone priority  
**Usage:** `protect priority [priority] [region]`  
**Permission:** `cubeengine.protector.command.protect.priority.use`  
  

## Permissions:

| Permission | Description |
| --- | --- |
| `cubeengine.protector` | Base Permission for Protector |
| `cubeengine.protector.bypass.blockdamage.explode.player` | Region bypass for players causing blockdamage with explosions |
| `cubeengine.protector.bypass.build` | Region bypass for building |
| `cubeengine.protector.bypass.command` | Region bypass for using all commands |
| `cubeengine.protector.bypass.entity-damage.all` |  |
| `cubeengine.protector.bypass.entity-damage.living` |  |
| `cubeengine.protector.bypass.move.enter` | Region bypass for entering a region |
| `cubeengine.protector.bypass.move.exit` | Region bypass for exiting a region |
| `cubeengine.protector.bypass.move.move` | Region bypass for moving in a region |
| `cubeengine.protector.bypass.move.teleport` | Region bypass for teleport in a region |
| `cubeengine.protector.bypass.move.teleport-portal` | Region bypass for teleport using portals in a region |
| `cubeengine.protector.bypass.player-damage.all` |  |
| `cubeengine.protector.bypass.player-damage.living` |  |
| `cubeengine.protector.bypass.player-damage.pvp` |  |
| `cubeengine.protector.bypass.player-targeting` |  |
| `cubeengine.protector.bypass.spawn.player` | Region bypass for players spawning entities |
| `cubeengine.protector.bypass.use` | Region bypass for using anything |
| `cubeengine.protector.bypass.use-all.block` | Region bypass for using blocks |
| `cubeengine.protector.bypass.use-all.container` | Region bypass for using containers |
| `cubeengine.protector.bypass.use-all.entity` | Region bypass for using entities |
| `cubeengine.protector.bypass.use-all.item` | Region bypass for using items |
| `cubeengine.protector.bypass.use-all.open` | Region bypass for opening anything |
| `cubeengine.protector.bypass.use-all.redstone` | Region bypass for using redstone |
| `cubeengine.protector.bypass.use-item` | Region bypass for using items |
