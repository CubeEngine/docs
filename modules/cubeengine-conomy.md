# CubeEngine - Conomy

Economy API and basic commands

## Commands

#### money

Manage your money

Usage: `money <command>`

Permission: `cubeengine.conomy.command.money`

Child Commands:
`balance`
`pay`
`top`

#### money balance

Shows your balance

Usage: `money balance <account>`

Alias:
`/balance`
`/moneybalance`
`/pmoney`

Permission: `cubeengine.conomy.command.money.balance.use`

#### money pay

Transfer the given amount to another account.

Usage: `money pay <*|<players>> <amount> [as <source>]`

Alias:
`give`
`/pay`

Permission: `cubeengine.conomy.command.money.pay.use`

#### money top

Shows the players with the highest balance.

Usage: `money top [[fromRank-]toRank]`

Alias:
`/toplist`
`/balancetop`
`/topmoney`

Permission: `cubeengine.conomy.command.money.top.use`

#### eco

Administrative commands for Conomy

Usage: `eco <command>`

Permission: `cubeengine.conomy.command.eco`

Child Commands:
`give`
`hide`
`reset`
`set`
`take`
`unhide`

#### eco give

Gives money to one or all players.

Usage: `eco give <*|<players>> <amount>`

Alias:
`grant`

Permission: `cubeengine.conomy.command.eco.give.use`

#### eco hide

Hides the account of a given player

Usage: `eco hide <*|<players>>`

Permission: `cubeengine.conomy.command.eco.hide.use`

#### eco reset

Reset the money from given user

Usage: `eco reset <*|<players>>`

Permission: `cubeengine.conomy.command.eco.reset.use`

#### eco set

Sets the money of a given player

Usage: `eco set <*|<players>> <amount>`

Permission: `cubeengine.conomy.command.eco.set.use`

#### eco take

Takes money from given user

Usage: `eco take <*|<players>> <amount>`

Alias:
`remove`

Permission: `cubeengine.conomy.command.eco.take.use`

#### eco unhide

Unhides the account of a given player

Usage: `eco unhide <*|<players>>`

Permission: `cubeengine.conomy.command.eco.unhide.use`

## Additional Permissions

 - ##### `cubeengine.conomy`
   Base Permission for conomy

