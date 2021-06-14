# Backpack

## Description

This module adds backpacks the player can open via command.  
If a backpack has multiple pages the next page can be opened by left-click without an item in hand outside of the inventory gui to show the previous page use right-click

## Configuration structure

All backpacks are saved in NBT-Format. You can edit the files using an NBT-Editor, but this is not recommended!

* single/<worldname\>/<username\>/*.dat: 
    Backpacks that will only work in this one world
* grouped/<mainworldname\>/<username\>/*.dat: 
    Backpacks that will only work in a set of worlds either defined by the worlds module OR if not installed all worlds with the same prefix get grouped so: world, world\_nether and world\_the\_end
* global/<username\>/*.dat: 
    Backpacks that will work in every world