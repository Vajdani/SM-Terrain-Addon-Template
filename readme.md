# Terrain Override Addon Template
This mod is an addon template for the [Scrap Mechanic Terrain Override](https://github.com/Vajdani/SM-Terrain-Override) mod.\
It adds, and removes tiles from the creative terrain generation.

# Working with the template
1. The tile modification data is located in `tileList.json`, where you can find two tables, `addedTiles` and `removedTiles`, that list what tiles are added and removed.\
You have to list the paths to the tiles in those tables. If the tile is user made, you have to refer to it using `$CONTENT_uuid`.
2. Add the tiles and their asset pack dependencies to the mod's dependencies list.
3. Go to `Objects\Database\ShapeSets\example.shapeset`, and change the uuid of the shape, so that your addon doesn't conflict with others.
4. Copy `description_template.json` and rename it to `description.json`. Open the file, and give your addon a name, description, and generate it a new uuid. (For example, on [this](https://www.uuidgenerator.net/version4) website)
5. Publish the mod on the workshop, and wait until the **Mod Database** updates.
6. Enjoy your custom tiles in the terrain generation!

If you'd like a more detailed explanation, you can find it [here](https://github.com/Vajdani/SM-Terrain-Override).