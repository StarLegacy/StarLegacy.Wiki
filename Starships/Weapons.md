# Starship Weapons

Starships can (and should!) have weapons to defend themselves.
There is a variety of types of starship weapons.
This page walks you through them.

## Firing Weapons

Weapons can be either light or heavy weapons.
**Light weapons** are fired by left clicking with a starship controller.
**Heavy weapons** are fired by right clicking with a starship controller.

## Weapon Types

### Laser Cannons

The simplest starship weapon is the laser cannon.
Laser cannons fire towards the targetted block,
with a firing cone of 15 degrees, a single explosion on impact,
and linear power usage.
They fire yellow projectiles.

#### Laser Cannon Multiblock

> **Requirements**
> * `1x Sponge`
> * `1x Piston`

![lasercannontop]       <!-- Top view image -->
![lasercannonside]      <!-- Side View Image -->

#### Laser Cannon Details

> **Power Usage** *500 power per cannon per shot*
>
> **Range** *190 blocks*
>
> **Type** *Light Weapon*
>
> **Impact** *1x explosion, power 2.0*

### Pulse Cannons

The most aimable light weapon is the pulse cannon.
Pulse cannons fire at the targetted block with no angle limit.
Their color is based on the color of their multiblock's stained glass.

#### Pulse Cannon Multiblock

> **Requirements**
> * `1x Sponge`
> * `1x Stained Glass`

![pulsecannontop]       <!-- Top view image -->
![pulsecannonside]      <!-- Side view image -->

#### Pulse Cannon Details

> **Power Usage** *400 per cannon for ships at least 5000 blocks, 400 more for every 1000 blocks smaller*
>
> **Range** *165 Blocks*
>
> **Type** *Light Weapon*
>
> **Impact** *1x explosion, power 1.75*

### Plasma Cannons

Plasma cannons are like laser cannons but much more powerful.
You can only have a few of them on ships.

#### Plasma Cannon Multiblock

> * `1x Sponge`
> * `1x Iron Block`
> * `1x Furnace`

![Image](https://i.gyazo.com/e020d835f5d726d7b429c6c137c02033.png)

#### Plasma Cannon Details

> **Power Usage** *1000 per cannon per shot*
>
> **Range** *Unknown* | Contribute! (/wiki/contributing)
>
> **Type** *Light Weapon*
>
> **Impact** *1x explosion, power 4.0, equivalent to TNT*

#### Proton Torpedoes

Proton torpedoes are heavy weapons useful for smaller ships.
You can only have a few on any ship, even ones with high power output.
You fire them by holding or double clicking right click.

#### Proton Torpedo Multiblock

> * `2x Sponge`
> * `1x Dispenser`

![Image](https://i.gyazo.com/1ab7937c14d9477845dd3d3fb280a7ec.png)

#### Proton Torpedo Details

> **Power Usage** *500 per torpedo*
>
> **Range** *300 Blocks*
>
> **Type** *Heavy Weapon*
>
> **Impact** *1x explosion, power 8.0*

#### Heavy Lasers

Heavy lasers are powerful weapons useful for larger ships.
They are primarily useful on larger ships
when fighting against other large ships.

#### Heavy Laser Multiblock

> * `7x Redstone Block`
> * `28x Stained Glass`
> * `1x Furnace`

![Image](https://i.gyazo.com/5107adc39d05af0a1a2ee0c48767b12b.png)

#### Heavy Laser Details

> **Power Usage** *5000 per shot; less on bigger ships*
>
> **Range** *500 Blocks*
>
> **Type** *Heavy Weapon*
>
> **Impact** *10x explosions, power 3.0*

> Note: Furnace is the FRONT of the weapon

#### Auto Turrets

Auto turrets can target players and shoot at them automatically.
They are very effective on a cruiser firing
against starfighters and corvettes.
They are also primarily defensive weapons -
if you move around or fire other weapons, they can't fire as much,
and they have difficulty hitting moving targets.

#### Auto Turret Multiblock

> * `1x Redstone Lamp`
> * `1x Iron Block`
> * `1x Dispenser`

![Image](https://i.gyazo.com/b8764272cdb7d391f7b1ac5cbd1a064d.png)

#### Auto Turret Details

> **Power Usage** *100 per shot per cannon*
>
> **Range** *200 Blocks*
>
> **Type** *Neither; Auto Weapon*
>
> **Impact** *1x explosion, power 2.0*

The redstone lamp is where the auto turret fires from.
To set up auto turrets you need [node] signs.
Place a sign on the dispenser that says, for example:
> Line 1: [node]
>
> Line 2: defense

Then, you can do `/settarget defense <player>`

> Alternatively, you can use `/st` instead of `/settarget`

You can also turn heavy turrets into auto turrets.
To do that, place a node sign on the turret sign, like this:

![Image](https://image.prntscr.com/image/oyKvb_ecSYSumhBepC-80A.png)

[lasercannontop]: https://forum.starlegacy.net/uploads/default/original/1X/503c55842997e104ccac75cbdc1577360372ae86.png
[lasercannonside]: https://forum.starlegacy.net/uploads/default/original/1X/4c45592b2fd12e6717010b11d2afd8085f394162.png

[pulsecannontop]: https://forum.starlegacy.net/uploads/default/original/1X/ee68dfd7f357af7edb67a02fdcb1c7748cb060d4.png
[pulsecannonside]: https://forum.starlegacy.net/uploads/default/original/1X/2387f4c223aa8b351e533e1c18e7537c8cfbe7a2.png
