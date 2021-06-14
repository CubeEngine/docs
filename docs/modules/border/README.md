# Border

## Description

This module allows you to define borders on your worlds to prevent
players from going to far.

The border can be either a circle or a quare and is defined by its
center. The radius is specified in chunks instead of blocks for
multiple reasons:

* performance: The distance only needs to be checked when players
go to a different chunk.
* stable blocking: Minecraft is not round and doesn't nativly support
borders. Running into invisible simulated corners causes clients to
to glicht around. Reducing the number of corners also reduces the
the chance of the problem to occur.
* no difference on rendered maps

The border module is not only able to block players, but can also
simulate [torus](http://de.wikipedia.org/wiki/Torus) behavior.

In addition to the movement blocking the module can pre-generate the
world inside your defined border.

## Configuration structure

Just one configuration with selfexplainatory options and the per-world
border configurations which can be configured ingame via commands.
