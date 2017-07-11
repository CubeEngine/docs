# CubeEngine - SignMarket
Adds a sign-based market.

## Features:
 - Create signs for trading
 - Signs support either selling or buying
 - Admin signs with unlimited capacity

## Commands:
| Command | Description | Permission<br>`cubeengine.signmarket.command.<perm>` |
| --- | --- | --- |
| [*marketsign*](#marketsign) | MarketSign-Commands | `marketsign` |
| [**marketsign** *editMode*](#marketsign-editmode) | Enters the editmode allowing to change market signs easily | `marketsign.editmode.use` |

#### marketsign  
MarketSign-Commands  
**Usage:** `marketsign <command>`  
**Alias:** `signmarket` `market`  
**Permission:** `cubeengine.signmarket.command.marketsign`  
**SubCommands:** `editMode`  

#### marketsign editMode  
Enters the editmode allowing to change market signs easily  
**Usage:** `marketsign editMode `  
**Alias:** `edit` `/medit`  
**Permission:** `cubeengine.signmarket.command.marketsign.editmode.use`  
  

## Additional Permissions:

| Permission | Description |
| --- | --- |
| `cubeengine.signmarket` | Base Permission for signmarket |