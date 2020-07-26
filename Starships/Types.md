# Starship Types
Every starship has a type.
Starship types have their own stats.
These include block size limits, power output, and container percent.

They are split into freighters and warships.

You unlock these by leveling up. At level 1, you get shuttles.
Every 12 levels, you unlock the next tier warship and freighter.

Container percent is the percent of blocks that can be inventory blocks.
Chests count as three inventory blocks.

### Acceleration
Ships can move faster when shift flying for extended times.
The acceleration distance is the amount of blocks a ship must fly
to make it go 1 block per movement faster, and max acceleration is
the most it can move in 1 movement.

## Warships
Warships can have up to **2.5% containers**.
They have a higher power output than freighters, so they're better as combat ships.
However, they can only carry half as many cargo crates.

| Name           | Min Size | Max Size | Power   | Accel Dist | Max Accel | Level   |
|----------------|----------|----------|---------|------------|-----------|---------|
| Starfighter    | 250      | 500      | 25,000  | 3          | 2         | 1 (١)   |
| Corvette       | 500      | 2,000    | 35,000  | 5          | 3         | 12 (١٢) |
| Frigate        | 2,000    | 4,000    | 50,000  | 6          | 2         | 24 (٢٤) |
| Destroyer      | 4,000    | 8,000    | 60,000  | 6          | 2         | 36 (٣٦) |
| Cruiser        | 8,000    | 12,000   | 80,000  | 2          | 3         | 48 (٤٨) |
| Battlecruiser  | 12,000   | 20,000   | 100,000 | 3          | 3         | 60 (٦٠) |
| Star Destroyer | 20,000   | 32,000   | 125,000 | 2          | 2         | 72 (٧٢) | 
| Dreadnought    | 32,000   | 48,000   | 150,000 | 2          | 2         | 84 (٨٤) |

## Freighters
Freighters can have up to **4.5% containers**.
While they cannot do as well as a warship in combat, freighters can transport large amounts of items easily.
They can also be used to trade cargo missiosn between planets. 

You can figure out the amount of sticky pistons your ship can hold by multiplying your block count by 0.015 or by taking the square root of your block count, whichever result is lower. (Make sure to account for blocks that you will remove to place crates!)

| Name             | Min Size | Max Size | Power   | Accel Dist | Max Accel | Level   | Max Stickies |
|------------------|----------|----------|---------|------------|-----------|---------|--------------|
| Shuttle          | 100      | 500      | 16,000  | 3          | 2         | 1 (١)   | 7            |
| Transport        | 500      | 2,000    | 24,000  | 5          | 3         | 12 (١٢) | 29 (+22)     |
| Light Freighter  | 2,000    | 4,000    | 30,000  | 6          | 2         | 24 (٢٤) | 59 (+30)     |
| Medium Freighter | 4,000    | 8,000    | 40,000  | 6          | 2         | 36 (٣٦) | 88 (+29)     |
| Bulk Freighter   | 8,000    | 12,000   | 55,000  | 2          | 3         | 48 (٤٨) | 109 (+21)    |
| Heavy Freighter  | 12,000   | 20,000   | 75,000  | 3          | 3         | 60 (٦٠) | 140 (+31)    |
| Barge            | 20,000   | 32,000   | 90,000  | 2          | 2         | 72 (٧٢) | 178 (+38)    |
| Tanker           | 32,000   | 48,000   | 110,000 | 2          | 2         | 84 (٨٤) | 218 (+40)    |

## Specialized

Specialized ships have varying statistics. These ships serve one purpose extremely well while also having it's other statistics lowered accordingly.

| Name        | Min Size | Max Size | Power   | Containers | Accel Dist | Max Accel | Level   | Specialization |
|-------------|----------|----------|---------|------------|------------|-----------|---------|----------------|
| Interdictor | 14000    | 22000    | 70,000  | 1.5%       | 5          | 8         | 50 (٥٠) | Mass Shadows   |
| Speeder     | 25       | 100      | 10,000  | 2.5%       | 5          | 5         | 1 (١)   | Speed          |
