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
| [**marketsign**&nbsp;*editMode*](#marketsigneditmode) | Enters the editmode allowing to change market signs easily | `marketsign.editmode.use` |

#### marketsign  
MarketSign-Commands  
**Usage:** `marketsign <command>`  
**Alias:** `signmarket` `market`  
**Permission:** `cubeengine.signmarket.command.marketsign`  
**SubCommands:** `editMode`  

#### marketsign&nbsp;editMode  
Enters the editmode allowing to change market signs easily  
**Usage:** `marketsign editMode `  
**Alias:** `edit` `/medit`  
**Permission:** `cubeengine.signmarket.command.marketsign.editmode.use`  
  

## Additional Permissions:

| Permission | Description |
| --- | --- |
| `cubeengine.signmarket` | Base Permission for SignMarket |
| `cubeengine.signmarket.command` | Allows using all commands of SignMarket |
| `cubeengine.signmarket.edit` | Allows creating and modifying all MarketSigns |
| `cubeengine.signmarket.edit.admin` | Allows creating and modifying Admin MarketSigns |
| `cubeengine.signmarket.edit.player` | Allows creating and modifying all Player MarketSigns |
| `cubeengine.signmarket.edit.player.other` | Allows creating and modifying Player MarketSigns of other players |
| `cubeengine.signmarket.edit.player.self` | Allows creating and modifying your own Player MarketSigns |
| `cubeengine.signmarket.edit.use` | Allows creating and modifying MarketSigns |
| `cubeengine.signmarket.interact` | Allows buy and sell interactions with MarketSigns |
| `cubeengine.signmarket.interact.buy` | Allows buying from MarketSigns |
| `cubeengine.signmarket.interact.inventory` | Allows seeing a MarketSigns Inventory |
| `cubeengine.signmarket.interact.sell` | Allows selling to MarketSigns |
| `cubeengine.signmarket.marketsign` |  |
| `cubeengine.signmarket.marketsign.admin.use` | Allows using the command admin |
| `cubeengine.signmarket.marketsign.amount.use` | Allows using the command amount |
| `cubeengine.signmarket.marketsign.buy.use` | Allows using the command buy |
| `cubeengine.signmarket.marketsign.copy.use` | Allows using the command copy |
| `cubeengine.signmarket.marketsign.demand.use` | Allows using the command demand |
| `cubeengine.signmarket.marketsign.exit.use` | Allows using the command exit |
| `cubeengine.signmarket.marketsign.item.use` | Allows using the command item |
| `cubeengine.signmarket.marketsign.nodemand.use` | Allows using the command nodemand |
| `cubeengine.signmarket.marketsign.owner.use` | Allows using the command owner |
| `cubeengine.signmarket.marketsign.player.use` | Allows using the command player |
| `cubeengine.signmarket.marketsign.price.use` | Allows using the command price |
| `cubeengine.signmarket.marketsign.sell.use` | Allows using the command sell |
| `cubeengine.signmarket.marketsign.setstock.use` | Allows using the command setstock |
| `cubeengine.signmarket.marketsign.size.use` | Allows using the command size |
| `cubeengine.signmarket.marketsign.stock.use` | Allows using the command stock |
