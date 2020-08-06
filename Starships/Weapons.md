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

<a href="https://imgur.com/ODat29Z"><img src="https://i.imgur.com/ODat29Z.png" title="Laser cannon" /></a>

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

<a href="https://imgur.com/huvn8QC"><img src="https://i.imgur.com/huvn8QC.png" title="Pulse Cannon" /></a>

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

<a href="https://imgur.com/oYtmk7g"><img src="https://i.imgur.com/oYtmk7g.png" title="Plasma Cannon" /></a>

#### Plasma Cannon Details

> **Power Usage** *1000 per cannon per shot*
>
> **Range** *140 Blocks*
>
> **Type** *Light Weapon*
>
> **Impact** *1x explosion, power 4.0, equivalent to TNT*

### Ion Cannons

Ion cannons are very powerful cannons that can disable nodes and are manually fired.
They can only be used on fighters and corvettes. Click the sponge to fire.

#### Ion Cannon Multiblock

> * `1x Sponge`
> * `1x Lapis Block`
> * `1x Dispenser`
> * `1x Stained Glass`

<a href="https://imgur.com/YPnDeTm"><img src="https://i.imgur.com/YPnDeTm.png" title="Ion Cannon" /></a>

#### Ion Cannon Details

> **Cooldown** *30 Seconds*
>
> **Range** *> 180 Blocks*
>
> **Type** *Speciality Weapon*
>
> **Impact** *1x explosion, massive shield damage; does not affect blocks, 6.5 block radius cube*

### Proton Torpedoes

Proton torpedoes are heavy weapons useful for smaller ships.
You can only have a few on any ship, even ones with high power output.
You fire them by holding or double clicking right click.

#### Proton Torpedo Multiblock

> * `2x Sponge`
> * `1x Dispenser`

<a href="https://imgur.com/IXwJPfc"><img src="https://i.imgur.com/IXwJPfc.png" title="Proton Torpedo" /></a>

#### Proton Torpedo Details

> **Power Usage** *500 per torpedo*
>
> **Range** *300 Blocks*
>
> **Type** *Heavy Weapon*
>
> **Impact** *1x explosion, power 8.0*

### Heavy Lasers

Heavy lasers are powerful weapons useful for larger ships.
They are primarily useful on larger ships
when fighting against other large ships.

#### Heavy Laser Multiblock

> * `7x Redstone Block`
> * `28x Stained Glass`
> * `1x Furnace`

<a href="https://imgur.com/loadd7q"><img src="https://i.imgur.com/loadd7q.png" title="Heavy Laser" /></a>
<a href="https://imgur.com/pq81HXb"><img src="https://i.imgur.com/pq81HXb.png" title="Heavy Laser Cross Section" /></a>

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

<a href="https://imgur.com/cIHPUXf"><img src="https://i.imgur.com/cIHPUXf.png" title="Auto Turret" /></a>
<a href="https://imgur.com/RGmqHkn"><img src="https://i.imgur.com/RGmqHkn.png" title="Auto Turret Cross Section" /></a>

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
