# Succubus Dungeon #

Succubus Dungeon is a mod for vanilla and Masterwork Dwarf Fortress featuring a new evil civ.

# Features #
* A new race
* Fast and fire immune citizens
* The reintroduction of classic lore into Dwarf Fortress such as 40d demons
* Generating slade blocks to build an authentic demonic spire.

# Installation #
* Install DF 42.03+
* Extract the archive in your DF folder, preserving the folder structure.
* Generate a new world and select a succubus civ to play.

# Selecting your race at the embark screen #
* Press tab before embarking until seeing a list of civilization names.
* Press + and - to chose a civ that uses the 'cabinet' tile to display its colonies on the map.
* Pressing tab again until seeing the list of neighbors will confirm your choice, your selected race is the first one.

## Modified vanilla files ##

###entity_default###
The dwarven entities lack the tags needed to interact with you in fortress mode. A modified entity file is included with the needed changes but if this conflict with another mod, you can add the tags manually.

Add the following to the MOUNTAIN entity, in entity_default.txt:
* [PROGRESS_TRIGGER_POPULATION:2]
* [PROGRESS_TRIGGER_PRODUCTION:2]
* [PROGRESS_TRIGGER_TRADE:2]
* [PROGRESS_TRIGGER_POP_SIEGE:4]
* [PROGRESS_TRIGGER_PROD_SIEGE:3]
* [PROGRESS_TRIGGER_TRADE_SIEGE:3]

# Magma #
Magma is important for this race. Succubi are immune to heat and many of their workshops are powered by magma.

Buildings marked with a star '*' must be powered by magma. There is currently no way to easily generate magma but this will be added in the near future.

Unfortunatly the game prevent your citizens from walking in magma. This is why you must be careful manipulating magma to avoid isolating someone in a corner. Succubi inside magma will evacuate without burning clothing or weapons but hauled items will be likely destroyed.

If a succubus is stuck, you can wait for the magma to evaporate or dig around.

# Getting slade and construction materials #
Slade can be generated at no cost in an underworld drill (requires magma) to help you build your spires. However, its extreme cost implies that slade projects will take more time and builders to complete. A smart usage of stockpiles and wheelbarrows is strongly recommended.

To get slade blocks, build the underworld drill from the furnaces menu. Like magma forges, it must have one of its tiles overlapping a pit with at least 4 levels of magma. A miner can then conjure slade blocks (for contruction) or boulders (for craft or masonry jobs).

As an alternative, glass blocks can easily be made using a floating glass furnace, using magma and a tin bar. This workshop is ten times more efficient than a regular glass furnace.

# Adventuring as a succubi #

Civilizations living in dark fortresses are not as well developped than dwarven or human ones. As a result, a succubus starts at an empty pit without the ability to fast travel. It is recommended that you play a succubus assimilated into another civilization, preferably human (# tiles on the world map) or dwarven (omega tiles on the world map).

If you start in a pit, you can open the regional map (shift+Q) to spot the nearest dark fortress, then travel by foot towards it to find people to talk to.

Wandering around, you may also find dungeons with equipment and towers with population on its roof. If you are unable to reach the roof, try pressing alt+direction to open the hatch.

# Known issues #
* Embarking as dwarves? See "Selecting your race at the embark screen" above.
* Upon reaching your site's edge, traders will "kidnap" their own pets, this has no consequenses to your fort.
* Changing graphics in the Lazy Newb Pack deletes the mod, you'll have to reinstall it afterwards.

# Contact #
If you have trouble using this mod, please post a message on the mod thread in the Bay 12 forum :
http://www.bay12forums.com/smf/index.php?topic=124135.0
