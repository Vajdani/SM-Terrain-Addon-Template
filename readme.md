# Terrain Override Addon Template
This mod is an addon template for the [Scrap Mechanic Terrain Override](https://github.com/Vajdani/SM-Terrain-Override) mod.\
It adds, and removes tiles from the creative terrain generation.

# Working with the template
The tile modification data is located in `tileList.json`, where you can find two tables, `addedTiles` and `removedTiles`, that list what tiles are added and removed.\
You have to list the paths to the tiles in those tables. If the tile is user made, you have to refer to it using `$CONTENT_uuid`. After you've added your tiles to `tileList.json`, you will have to add the tiles and their asset pack dependencies to the mod's dependencies list.\
After you've finished all of that, you have to go to `Objects\Database\ShapeSets\example.shapeset`, and change the uuid of the shape, so that your addon doesn't conflict with others.

If you'd like a more detailed explanation, you can find it [here](https://github.com/Vajdani/SM-Terrain-Override).