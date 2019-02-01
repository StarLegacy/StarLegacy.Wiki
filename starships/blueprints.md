# Blueprints

Blueprints are files that store the data of ships, reproduced using ship factories.

## Creating a blueprint

> **Saving blueprints of ships you didn't design \(without permission\) is illegal!!**

You can make a blueprint from a ship by piloting it and using the command.

1. Pilot the ship
2. Run the command: `/blueprint save <name>` \(replace `<name>` with the name of the blueprint\)

## Ship Factory

A ship factory is a machine that automatically builds a ship in front of you.

### Multiblock

Materials: 2 Iron Blocks, 1 Furnace, 1 Sign, 1 Chest

> Sign:
>
> Line 1: `[shipfactory]`
>
> Line 2: `blueprint name`

### Material Types

There are two types of ship factories - **Credit Factory**, and **Material Factory**.

> Both types of factories have the same multi-block and mechanics.

#### Credit Factories

A **Credit Factory** takes credits out of the user's money and uses it to make materials. The cost is based on the cost of the material.

To make a Credit Factory, place a golden ingot/block/nugget in the furnace bottom slot and a focusing lens in its top slot.

#### Material Factories

A **Material Factory**, takes materials from the multiblock's chest and prints the ship, taking blocks from the chest and placing them down.

To make a Material Factory, place a focusing lens in the bottom AND top slot of the furnace.

### Adding a blueprint to a ship factory

First, make sure you have the name of the blueprint. If you forgot it, check `/blueprint list`.

For the ship factory sign, put `[shipfactory]` on line 1 and `<name>` on line 2. \(replace `<name>` with the name of your blueprint\)

> You'll need enough free space to print. Factories print above, to the right, and in front of the furnace.

### Images

![Image](https://raw.githubusercontent.com/StarLegacy/StarLegacy.Wiki/48ecd68cd23ece2a32b53a34e415344d2c441923/Images/Blueprints%26ShipFactories/6a0a724dafa8c7722586d94c824f3cfc.png) ![Image](https://raw.githubusercontent.com/StarLegacy/StarLegacy.Wiki/48ecd68cd23ece2a32b53a34e415344d2c441923/Images/Blueprints%26ShipFactories/8639ade7bbd3765297bbf669e004bbf6.png) ![Image](https://raw.githubusercontent.com/StarLegacy/StarLegacy.Wiki/48ecd68cd23ece2a32b53a34e415344d2c441923/Images/Blueprints%26ShipFactories/96205035a10c7c89006fbf8137a289f7.png) ![Image](https://raw.githubusercontent.com/StarLegacy/StarLegacy.Wiki/48ecd68cd23ece2a32b53a34e415344d2c441923/Images/Blueprints%26ShipFactories/97778221eab0880d71efa870b8c0fa91.png)

