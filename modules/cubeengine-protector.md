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
| [**region** *control*](#region-control) | Manages the region settings | `control` |
| [**region** **control** *blockdamage*](#region-control-blockdamage) | Manages the region block-damage settings | `control.blockdamage` |
| [**region** **control** **blockdamage** *block*](#region-control-blockdamage-block) | Controls blocks breaking blocks | `control.blockdamage.block.use` |
| [**region** **control** **blockdamage** *explosion*](#region-control-blockdamage-explosion) | Controls explosions breaking blocks | `control.blockdamage.explosion.use` |
| [**region** **control** **blockdamage** *fire*](#region-control-blockdamage-fire) | Controls fire breaking blocks | `control.blockdamage.fire.use` |
| [**region** **control** **blockdamage** *monster*](#region-control-blockdamage-monster) | Controls entities breaking blocks | `control.blockdamage.monster.use` |
| [**region** **control** **blockdamage** *playerExplosion*](#region-control-blockdamage-playerexplosion) | Controls explosions caused by players breaking blocks | `control.blockdamage.playerexplosion.use` |
| [**region** **control** *build*](#region-control-build) | Controls player building | `control.build.use` |
| [**region** **control** *command*](#region-control-command) | Controls executing commands | `control.command.use` |
| [**region** **control** *deadCircuit*](#region-control-deadcircuit) | Controls redstone circuits commands | `control.deadcircuit.use` |
| [**region** **control** *entityDamage*](#region-control-entitydamage) | Manages the region entity-damage settings | `control.entitydamage` |
| [**region** **control** **entityDamage** *all*](#region-control-entitydamage-all) | Controls entity damage | `control.entitydamage.all.use` |
| [**region** **control** **entityDamage** *entity*](#region-control-entitydamage-entity) | Controls explosions caused by players breaking blocks | `control.entitydamage.entity.use` |
| [**region** **control** **entityDamage** *living*](#region-control-entitydamage-living) | Controls damage by living entities | `control.entitydamage.living.use` |
| [**region** **control** **entityDamage** *pvp*](#region-control-entitydamage-pvp) | Controls pvp damage | `control.entitydamage.pvp.use` |
| [**region** **control** *move*](#region-control-move) | Controls movement | `control.move.use` |
| [**region** **control** *spawn*](#region-control-spawn) | Controls spawning of entities | `control.spawn.use` |
| [**region** **control** *teleport*](#region-control-teleport) | Controls teleport movement | `control.teleport.use` |
| [**region** **control** *useAll*](#region-control-useall) | Controls players interacting with blocks | `control.useall.use` |
| [**region** **control** *useBlock*](#region-control-useblock) | Controls player interacting with blocks | `control.useblock.use` |
| [**region** **control** *useItem*](#region-control-useitem) | Controls player interactive with items | `control.useitem.use` |
| [**region** *define*](#region-define) | Defines a new Region | `region.define.use` |
| [**region** *info*](#region-info) | Displays Region info | `region.info.use` |
| [**region** *list*](#region-list) | Lists regions | `region.list.use` |
| [**region** *redefine*](#region-redefine) | Redefines an existing Region | `region.redefine.use` |
| [**region** *select*](#region-select) | Selects a Region | `region.select.use` |

#### region  
Manages the regions  
**Usage:** `region <command>`  
**Permission:** `cubeengine.protector.command.region`  
**SubCommands:** `control` `define` `info` `list` `redefine` `select`  

#### region control  
Manages the region settings  
**Usage:** `region control <command>`  
**Permission:** `cubeengine.protector.command.control`  
**SubCommands:** `blockdamage` `build` `command` `deadCircuit` `entityDamage` `move` `spawn` `teleport` `useAll` `useBlock` `useItem`  

#### region control blockdamage  
Manages the region block-damage settings  
**Usage:** `region control blockdamage <command>`  
**Alias:** `block`  
**Permission:** `cubeengine.protector.command.control.blockdamage`  
**SubCommands:** `block` `explosion` `fire` `monster` `playerExplosion`  

#### region control blockdamage block  
Controls blocks breaking blocks  
**Usage:** `region control blockdamage block <by> <set> [in <region>]`  
**Permission:** `cubeengine.protector.command.control.blockdamage.block.use`  
  

#### region control blockdamage explosion  
Controls explosions breaking blocks  
**Usage:** `region control blockdamage explosion <set> [in <region>]`  
**Permission:** `cubeengine.protector.command.control.blockdamage.explosion.use`  
  

#### region control blockdamage fire  
Controls fire breaking blocks  
**Usage:** `region control blockdamage fire <set> [in <region>]`  
**Permission:** `cubeengine.protector.command.control.blockdamage.fire.use`  
  

#### region control blockdamage monster  
Controls entities breaking blocks  
**Usage:** `region control blockdamage monster <set> [in <region>]`  
**Permission:** `cubeengine.protector.command.control.blockdamage.monster.use`  
  

#### region control blockdamage playerExplosion  
Controls explosions caused by players breaking blocks  
**Usage:** `region control blockdamage playerExplosion <set> [in <region>] [bypass <role>]`  
**Permission:** `cubeengine.protector.command.control.blockdamage.playerexplosion.use`  
  

#### region control build  
Controls player building  
**Usage:** `region control build <set> [in <region>] [bypass <role>]`  
**Permission:** `cubeengine.protector.command.control.build.use`  
  

#### region control command  
Controls executing commands  
**Usage:** `region control command <command> <set> [in <region>] [bypass <role>] [-force]`  
**Permission:** `cubeengine.protector.command.control.command.use`  
  

#### region control deadCircuit  
Controls redstone circuits commands  
**Usage:** `region control deadCircuit <set> [in <region>]`  
**Permission:** `cubeengine.protector.command.control.deadcircuit.use`  
  

#### region control entityDamage  
Manages the region entity-damage settings  
**Usage:** `region control entityDamage <command>`  
**Alias:** `entity`  
**Permission:** `cubeengine.protector.command.control.entitydamage`  
**SubCommands:** `all` `entity` `living` `pvp`  

#### region control entityDamage all  
Controls entity damage  
**Usage:** `region control entityDamage all <set> [in <region>] [bypass <role>]`  
**Permission:** `cubeengine.protector.command.control.entitydamage.all.use`  
  

#### region control entityDamage entity  
Controls explosions caused by players breaking blocks  
**Usage:** `region control entityDamage entity <type> <set> [in <region>]`  
**Permission:** `cubeengine.protector.command.control.entitydamage.entity.use`  
  

#### region control entityDamage living  
Controls damage by living entities  
**Usage:** `region control entityDamage living <set> [in <region>] [bypass <role>]`  
**Permission:** `cubeengine.protector.command.control.entitydamage.living.use`  
  

#### region control entityDamage pvp  
Controls pvp damage  
**Usage:** `region control entityDamage pvp <set> [in <region>] [bypass <role>]`  
**Permission:** `cubeengine.protector.command.control.entitydamage.pvp.use`  
  

#### region control move  
Controls movement  
**Usage:** `region control move <type> <set> [in <region>] [bypass <role>]`  
**Permission:** `cubeengine.protector.command.control.move.use`  
  

#### region control spawn  
Controls spawning of entities  
**Usage:** `region control spawn <type> <what> <set> [in <region>] [bypass <role>]`  
**Permission:** `cubeengine.protector.command.control.spawn.use`  
  

#### region control teleport  
Controls teleport movement  
**Usage:** `region control teleport <set> [in <region>] [bypass <role>]`  
**Permission:** `cubeengine.protector.command.control.teleport.use`  
  

#### region control useAll  
Controls players interacting with blocks  
**Usage:** `region control useAll <type> <set> [in <region>] [bypass <role>]`  
**Permission:** `cubeengine.protector.command.control.useall.use`  
  

#### region control useBlock  
Controls player interacting with blocks  
**Usage:** `region control useBlock <type> <set> [in <region>] [bypass <role>]`  
**Permission:** `cubeengine.protector.command.control.useblock.use`  
  

#### region control useItem  
Controls player interactive with items  
**Usage:** `region control useItem <type> <set> [in <region>] [bypass <role>]`  
**Permission:** `cubeengine.protector.command.control.useitem.use`  
  

#### region define  
Defines a new Region  
**Usage:** `region define <name>`  
**Permission:** `cubeengine.protector.command.region.define.use`  
  

#### region info  
Displays Region info  
**Usage:** `region info <region> [-allSettings]`  
**Permission:** `cubeengine.protector.command.region.info.use`  
  

#### region list  
Lists regions  
**Usage:** `region list [match] [in <world>]`  
**Permission:** `cubeengine.protector.command.region.list.use`  
  

#### region redefine  
Redefines an existing Region  
**Usage:** `region redefine <region>`  
**Permission:** `cubeengine.protector.command.region.redefine.use`  
  

#### region select  
Selects a Region  
**Usage:** `region select <region>`  
**Permission:** `cubeengine.protector.command.region.select.use`  
  

## Additional Permissions:

| Permission | Description |
| --- | --- |
| `cubeengine.protector` | Base Permission for protector |