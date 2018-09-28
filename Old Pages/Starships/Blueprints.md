# Ship Factory

A ship factory is a machine that automatically builds a ship in front of you.

There are two types of ship factories -
**Credit Factory**, and **Material Factory**.

> Both types of factories have the same multi-block and mechanics.

A **Credit Factory** takes credits out of the user's money and uses it
to make materials. The cost is based on the cost of the material.
To make a ship factory a Credit Factory,
place a golden ingot/block/nugget in the bottom slot of the furnace
and a focusing lens in top slot.

A **Material Factory**, takes materials from the multiblock's chest and prints the ship, taking blocks from the chest and placing them down. To make a ship factory a Material Factory, place a focusing lens in the bottom AND top slot of the furnace.

## Multiblock
Materials: 2 Iron Blocks, 1 Furnace, 1 Sign, 1 Chest

> Sign:
>
> Line 1: `[shipfactory]`
>
> Line 2: `blueprint name`

### Images
([Contribute!](/wiki/contributing))

# Blueprints
Blueprints are files that store the data of your ship
which you can reproduce using a ship factory.

### Creating a blueprint
> **Saving blueprints of ships you didn't design** 
> **without permission is illegal!!**

You can make a blueprint from a ship by piloting it and using the command.

1. Pilot the ship
2. Run the command: `/blueprint save <name>`
(replace `<name>` with the name of the blueprint)

### Adding a blueprint to a ship factory
First, make sure you have the name of the blueprint.
If you forgot it, check out `/blueprint list`.

For the ship factory sign,
put `[shipfactory]` on line 1 and `<name>` on line 2.
(replace `<name>` with the name of your blueprint)

> You'll need enough free space to print.
> Factories print above, to the right, and in front of the furnace.

#### Images
([Contribute!](/wiki/contributing))