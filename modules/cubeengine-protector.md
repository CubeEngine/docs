# CubeEngine - Protector
Protects your worlds

## Features:
 - Define regions in your worlds and protect them
 - Protects from any world changes
 - Can be used for greylisting

## Commands:

| Command | Description | Permission<br>`cubeengine.protector.command.<perm>` |
| --- | --- | --- |
| [*region*](#region) | Manages the regions | `region` |
| [**region**&nbsp;*control*](#regioncontrol) | Manages the region settings | `control` |
| [**region**&nbsp;**control**&nbsp;*blockdamage*](#regioncontrolblockdamage) | Manages the region block-damage settings | `control.blockdamage` |
| [**region**&nbsp;**control**&nbsp;**blockdamage**&nbsp;*block*](#regioncontrolblockdamageblock) | Controls blocks breaking blocks | `control.blockdamage.block.use` |
| [**region**&nbsp;**control**&nbsp;**blockdamage**&nbsp;*explosion*](#regioncontrolblockdamageexplosion) | Controls explosions breaking blocks | `control.blockdamage.explosion.use` |
| [**region**&nbsp;**control**&nbsp;**blockdamage**&nbsp;*fire*](#regioncontrolblockdamagefire) | Controls fire breaking blocks | `control.blockdamage.fire.use` |
| [**region**&nbsp;**control**&nbsp;**blockdamage**&nbsp;*lightningFire*](#regioncontrolblockdamagelightningfire) | Controls lightning fire | `control.blockdamage.lightningfire.use` |
| [**region**&nbsp;**control**&nbsp;**blockdamage**&nbsp;*monster*](#regioncontrolblockdamagemonster) | Controls entities breaking blocks | `control.blockdamage.monster.use` |
| [**region**&nbsp;**control**&nbsp;**blockdamage**&nbsp;*playerExplosion*](#regioncontrolblockdamageplayerexplosion) | Controls explosions caused by players breaking blocks | `control.blockdamage.playerexplosion.use` |
| [**region**&nbsp;**control**&nbsp;*build*](#regioncontrolbuild) | Controls player building | `control.build.use` |
| [**region**&nbsp;**control**&nbsp;*command*](#regioncontrolcommand) | Controls executing commands | `control.command.use` |
| [**region**&nbsp;**control**&nbsp;*deadCircuit*](#regioncontroldeadcircuit) | Controls redstone circuits commands | `control.deadcircuit.use` |
| [**region**&nbsp;**control**&nbsp;*entityDamage*](#regioncontrolentitydamage) | Manages the region entity-damage settings | `control.entitydamage` |
| [**region**&nbsp;**control**&nbsp;**entityDamage**&nbsp;*all*](#regioncontrolentitydamageall) | Controls entity damage | `control.entitydamage.all.use` |
| [**region**&nbsp;**control**&nbsp;**entityDamage**&nbsp;*entity*](#regioncontrolentitydamageentity) | Controls damage by entities | `control.entitydamage.entity.use` |
| [**region**&nbsp;**control**&nbsp;**entityDamage**&nbsp;*living*](#regioncontrolentitydamageliving) | Controls damage by living entities | `control.entitydamage.living.use` |
| [**region**&nbsp;**control**&nbsp;*move*](#regioncontrolmove) | Controls movement | `control.move.use` |
| [**region**&nbsp;**control**&nbsp;*playerDamage*](#regioncontrolplayerdamage) | Manages the region player-damage settings | `control.playerdamage` |
| [**region**&nbsp;**control**&nbsp;**playerDamage**&nbsp;*all*](#regioncontrolplayerdamageall) | Controls player damage | `control.playerdamage.all.use` |
| [**region**&nbsp;**control**&nbsp;**playerDamage**&nbsp;*living*](#regioncontrolplayerdamageliving) | Controls player damage by living entities | `control.playerdamage.living.use` |
| [**region**&nbsp;**control**&nbsp;**playerDamage**&nbsp;*pvp*](#regioncontrolplayerdamagepvp) | Controls pvp damage | `control.playerdamage.pvp.use` |
| [**region**&nbsp;**control**&nbsp;**playerDamage**&nbsp;*targeting*](#regioncontrolplayerdamagetargeting) | Controls mobs targeting players | `control.playerdamage.targeting.use` |
| [**region**&nbsp;**control**&nbsp;*spawn*](#regioncontrolspawn) | Controls spawning of entities | `control.spawn.use` |
| [**region**&nbsp;**control**&nbsp;*teleport*](#regioncontrolteleport) | Controls teleport movement | `control.teleport.use` |
| [**region**&nbsp;**control**&nbsp;*useAll*](#regioncontroluseall) | Controls players interacting with blocks | `control.useall.use` |
| [**region**&nbsp;**control**&nbsp;*useBlock*](#regioncontroluseblock) | Controls player interacting with blocks | `control.useblock.use` |
| [**region**&nbsp;**control**&nbsp;*useItem*](#regioncontroluseitem) | Controls player interactive with items | `control.useitem.use` |
| [**region**&nbsp;*define*](#regiondefine) | Defines a new Region | `region.define.use` |
| [**region**&nbsp;*info*](#regioninfo) | Displays Region info | `region.info.use` |
| [**region**&nbsp;*list*](#regionlist) | Lists regions | `region.list.use` |
| [**region**&nbsp;*redefine*](#regionredefine) | Redefines an existing Region | `region.redefine.use` |
| [**region**&nbsp;*select*](#regionselect) | Selects a Region | `region.select.use` |

#### region  
Manages the regions  
**Usage:** `region <command>`  
**Permission:** `cubeengine.protector.command.region`  
**SubCommands:** `control` `define` `info` `list` `redefine` `select`  

#### region&nbsp;control  
Manages the region settings  
**Usage:** `region control <command>`  
**Permission:** `cubeengine.protector.command.control`  
**SubCommands:** `blockdamage` `build` `command` `deadCircuit` `entityDamage` `move` `playerDamage` `spawn` `teleport` `useAll` `useBlock` `useItem`  

#### region&nbsp;control&nbsp;blockdamage  
Manages the region block-damage settings  
**Usage:** `region control blockdamage <command>`  
**Alias:** `block`  
**Permission:** `cubeengine.protector.command.control.blockdamage`  
**SubCommands:** `block` `explosion` `fire` `lightningFire` `monster` `playerExplosion`  

#### region&nbsp;control&nbsp;blockdamage&nbsp;block  
Controls blocks breaking blocks  
**Usage:** `region control blockdamage block <by> <set> [in <region>]`  
**Permission:** `cubeengine.protector.command.control.blockdamage.block.use`  
  

#### region&nbsp;control&nbsp;blockdamage&nbsp;explosion  
Controls explosions breaking blocks  
**Usage:** `region control blockdamage explosion <set> [in <region>]`  
**Permission:** `cubeengine.protector.command.control.blockdamage.explosion.use`  
  

#### region&nbsp;control&nbsp;blockdamage&nbsp;fire  
Controls fire breaking blocks  
**Usage:** `region control blockdamage fire <set> [in <region>]`  
**Permission:** `cubeengine.protector.command.control.blockdamage.fire.use`  
  

#### region&nbsp;control&nbsp;blockdamage&nbsp;lightningFire  
Controls lightning fire  
**Usage:** `region control blockdamage lightningFire <set> [in <region>]`  
**Permission:** `cubeengine.protector.command.control.blockdamage.lightningfire.use`  
  

#### region&nbsp;control&nbsp;blockdamage&nbsp;monster  
Controls entities breaking blocks  
**Usage:** `region control blockdamage monster <set> [in <region>]`  
**Permission:** `cubeengine.protector.command.control.blockdamage.monster.use`  
  

#### region&nbsp;control&nbsp;blockdamage&nbsp;playerExplosion  
Controls explosions caused by players breaking blocks  
**Usage:** `region control blockdamage playerExplosion <set> [in <region>] [bypass <role>]`  
**Permission:** `cubeengine.protector.command.control.blockdamage.playerexplosion.use`  
  

#### region&nbsp;control&nbsp;build  
Controls player building  
**Usage:** `region control build <set> [in <region>] [bypass <role>]`  
**Permission:** `cubeengine.protector.command.control.build.use`  
  

#### region&nbsp;control&nbsp;command  
Controls executing commands  
**Usage:** `region control command <command> <set> [in <region>] [bypass <role>] [-force]`  
**Permission:** `cubeengine.protector.command.control.command.use`  
  

#### region&nbsp;control&nbsp;deadCircuit  
Controls redstone circuits commands  
**Usage:** `region control deadCircuit <set> [in <region>]`  
**Permission:** `cubeengine.protector.command.control.deadcircuit.use`  
  

#### region&nbsp;control&nbsp;entityDamage  
Manages the region entity-damage settings  
**Usage:** `region control entityDamage <command>`  
**Alias:** `entity`  
**Permission:** `cubeengine.protector.command.control.entitydamage`  
**SubCommands:** `all` `entity` `living`  

#### region&nbsp;control&nbsp;entityDamage&nbsp;all  
Controls entity damage  
**Usage:** `region control entityDamage all <set> [in <region>] [bypass <role>]`  
**Permission:** `cubeengine.protector.command.control.entitydamage.all.use`  
  

#### region&nbsp;control&nbsp;entityDamage&nbsp;entity  
Controls damage by entities  
**Usage:** `region control entityDamage entity <type> <set> [in <region>]`  
**Permission:** `cubeengine.protector.command.control.entitydamage.entity.use`  
  

#### region&nbsp;control&nbsp;entityDamage&nbsp;living  
Controls damage by living entities  
**Usage:** `region control entityDamage living <set> [in <region>] [bypass <role>]`  
**Permission:** `cubeengine.protector.command.control.entitydamage.living.use`  
  

#### region&nbsp;control&nbsp;move  
Controls movement  
**Usage:** `region control move <type> <set> [in <region>] [bypass <role>]`  
**Permission:** `cubeengine.protector.command.control.move.use`  
  

#### region&nbsp;control&nbsp;playerDamage  
Manages the region player-damage settings  
**Usage:** `region control playerDamage <command>`  
**Alias:** `player`  
**Permission:** `cubeengine.protector.command.control.playerdamage`  
**SubCommands:** `all` `living` `pvp` `targeting`  

#### region&nbsp;control&nbsp;playerDamage&nbsp;all  
Controls player damage  
**Usage:** `region control playerDamage all <set> [in <region>] [bypass <role>]`  
**Permission:** `cubeengine.protector.command.control.playerdamage.all.use`  
  

#### region&nbsp;control&nbsp;playerDamage&nbsp;living  
Controls player damage by living entities  
**Usage:** `region control playerDamage living <set> [in <region>] [bypass <role>]`  
**Permission:** `cubeengine.protector.command.control.playerdamage.living.use`  
  

#### region&nbsp;control&nbsp;playerDamage&nbsp;pvp  
Controls pvp damage  
**Usage:** `region control playerDamage pvp <set> [in <region>] [bypass <role>]`  
**Permission:** `cubeengine.protector.command.control.playerdamage.pvp.use`  
  

#### region&nbsp;control&nbsp;playerDamage&nbsp;targeting  
Controls mobs targeting players  
**Usage:** `region control playerDamage targeting <set> [in <region>] [bypass <role>]`  
**Permission:** `cubeengine.protector.command.control.playerdamage.targeting.use`  
  

#### region&nbsp;control&nbsp;spawn  
Controls spawning of entities  
**Usage:** `region control spawn <type> <what> <set> [in <region>] [bypass <role>]`  
**Permission:** `cubeengine.protector.command.control.spawn.use`  
  

#### region&nbsp;control&nbsp;teleport  
Controls teleport movement  
**Usage:** `region control teleport <set> [in <region>] [bypass <role>]`  
**Permission:** `cubeengine.protector.command.control.teleport.use`  
  

#### region&nbsp;control&nbsp;useAll  
Controls players interacting with blocks  
**Usage:** `region control useAll <type> <set> [in <region>] [bypass <role>]`  
**Permission:** `cubeengine.protector.command.control.useall.use`  
  

#### region&nbsp;control&nbsp;useBlock  
Controls player interacting with blocks  
**Usage:** `region control useBlock <type> <set> [in <region>] [bypass <role>]`  
**Permission:** `cubeengine.protector.command.control.useblock.use`  
  

#### region&nbsp;control&nbsp;useItem  
Controls player interactive with items  
**Usage:** `region control useItem <type> <set> [in <region>] [bypass <role>]`  
**Permission:** `cubeengine.protector.command.control.useitem.use`  
  

#### region&nbsp;define  
Defines a new Region  
**Usage:** `region define <name>`  
**Permission:** `cubeengine.protector.command.region.define.use`  
  

#### region&nbsp;info  
Displays Region info  
**Usage:** `region info <region> [-allSettings]`  
**Permission:** `cubeengine.protector.command.region.info.use`  
  

#### region&nbsp;list  
Lists regions  
**Usage:** `region list [match] [in <world>]`  
**Permission:** `cubeengine.protector.command.region.list.use`  
  

#### region&nbsp;redefine  
Redefines an existing Region  
**Usage:** `region redefine <region>`  
**Permission:** `cubeengine.protector.command.region.redefine.use`  
  

#### region&nbsp;select  
Selects a Region  
**Usage:** `region select <region>`  
**Permission:** `cubeengine.protector.command.region.select.use`  
  

## Additional Permissions:

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
| `cubeengine.protector.bypass.use-all.item` | Region bypass for using items |
| `cubeengine.protector.bypass.use-all.open` | Region bypass for opening anything |
| `cubeengine.protector.bypass.use-all.redstone` | Region bypass for using redstone |
| `cubeengine.protector.bypass.use-item` | Region bypass for using items |
| `cubeengine.protector.command` | Allows using all commands of Protector |
