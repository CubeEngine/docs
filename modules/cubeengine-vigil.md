# CubeEngine - Vigil

Log everything you want!

## Commands

#### vigil

Vigil-Module Commands

Usage: `vigil <command>`

Alias:
`log`

Permission: `cubeengine.vigil.command.vigil`

Child Commands:
`admin`
`block`
`tool`

#### vigil admin

Vigil-Admin Commands

Usage: `vigil admin <command>`

Permission: `cubeengine.vigil.command.vigil.admin`

Child Commands:
`purge`
`setReportActive`

#### vigil admin purge

purges all logs

Usage: `vigil admin purge `

Permission: `cubeengine.vigil.command.vigil.admin.purge.use`

#### vigil admin setReportActive

enables or disables reports in a world

Usage: `vigil admin setReportActive <world> <name> <enable>`

Permission: `cubeengine.vigil.command.vigil.admin.setreportactive.use`

#### vigil block

Gives you a block to check logs with.no log-type: Shows everything
chest: Shows chest-interactions only
player: Shows player-interactions only
kills: Shows kill-interactions only
block: Shows block-changes only

Usage: `vigil block [log-type]`

Alias:
`/lb`

Permission: `cubeengine.vigil.command.vigil.block.use`

#### vigil tool

Gives you an item to check logs with.
no log-type: Shows everything
chest: Shows chest-interactions only
player: Shows player-interactions only
kills: Shows kill-interactions only
block: Shows block-changes only

Usage: `vigil tool [log-type]`

Alias:
`/lt`

Permission: `cubeengine.vigil.command.vigil.tool.use`

## Additional Permissions

 - ##### `cubeengine.vigil`
   Base Permission for vigil

