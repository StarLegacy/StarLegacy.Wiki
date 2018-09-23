Contents
1 Thrusters
1.1 Thruster Types
1.2 Tips
1.3 Under the hood
Thrusters
There are 3 kinds of thrusters - glowstone, plasma, and ion. Glowstone thrusters are pretty bad in general but use less power and less space, so they're the best for super small cheap ships. Plasma thrusters have very fast acceleration and almost as fast speed, the best for most ships in general. Ion thrusters are the best for colossal ships, as they have a high power demand and very low acceleration.

Thruster Types
Glowstone thrusters are built literally with just a glowstone block. (Acceleration 0.2, speed 1.75)

Plasma thrusters are built with a redstone block and a redstone lamp behind it; the lamp should face away from your ship. (Acceleration 0.75, speed 2.0)

Sponge thrusters are built with a sponge block and a sea lantern behind it; the lantern should face away from your ship. (Acceleration 0.05, speed 2.75)

Tips
You cannot have any blocks behind thrusters or they don't work. Having walls of thrusters uses too much of your ship's power.

Under the hood
The actual equation for thruster acceleration is (log(2 + totalAcceleration) / (log(mass) / log(thrusterAmount + 2)))

The actual equation for thruster speed is 150 / (log(mass) / log(sqrt(totalSpeed) + 2))

The speed is limited by the starship's available thruster power divided by the total speed times 2.5 (i.e. power / (totalSpeed * 2.5))