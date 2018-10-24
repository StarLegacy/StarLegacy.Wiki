
# Thrusters
There are 3 kinds of thrusters - glowstone, plasma, and ion.

## Thruster Types
### Glowstone
- Built literally with just a glowstone block.
- Worst thruster ovrerall, but use less power and space.
- Best for super small/cheap ships.
- Acceleration 0.2, speed 1.75
![Glowstone]

### Plasma
- Built with a redstone block and a redstone lamp behind it.
- The lamp should face away from your ship.
- Best for most ships.
- Very fast acceleration and almost as fast speed. 
- Acceleration 0.75, speed 2.0
![Plasma]

### Ion 
- Built with a sponge block and a sea lantern behind it.
- The lantern should face away from your ship.
- Best for largest ships
- High power demand, very low acceleration.
- Acceleration 0.05, speed 2.75
![Ion]

## Tips
- You cannot have any blocks behind thrusters or they don't work.
- Having walls of thrusters uses too much of your ship's power.

## Under the hood
The actual equation for thruster acceleration is:
- (log(2 + totalAcceleration) / (log(mass) / log(thrusterAmount + 2)))

The actual equation for thruster speed is: 
- 150 / (log(mass) / log(sqrt(totalSpeed) + 2))

The equation for speed is: 
- availablepower / (totalSpeed * 2.5)

[Glowstone]: https://i.imgur.com/QtsjFnN.png
[Plasma]: https://i.imgur.com/da4g1Pr.png
[Ion]: https://i.imgur.com/zSYwLRE.png