Contents
1 Particle Shield Subsystem
1.1 Multiblocks
1.1.1 Class 0.8 (8 block radius)
1.1.2 Class 2.0 (12 block radius)
1.1.3 Class 3.0 (20 block radius)
1.1.4 Class 6.5 (30 block radius)
1.1.5 Class 8.5 (35 block radius)
Particle Shield Subsystem
Particle shields are essential subsystems for your starship. They vastly reduce the power of impacts on the starship's hull. They have a very high power capacity and take time to regenerate power.

When they absorb impacts, their power goes down. The lower their power, the less they protect your ship.

It is best to have your shields spread out and strategically placed. The closer to the impact, the more power it uses and the more it absorbs the impact. If the impact is outside of its range, it does not absorb the impact. Overlapping shields merely use up double the power, they do not spread the power usage.

Shield class only affects radius, not strength or anything else. Higher shield classes have higher radii.

The protection radius extends from the sign block, and is spherical. You can use //hsphere 95 <radius> to visualize it with stained glass on the creative server.

It is smart to have no more than 9 shields with different names on any ship - any more than that and it does not display all shields on the shield power indicators, due to limitations of Minecraft. If you want more than 9 shields, give some the same name and it will display aggregated data for its boss bar.

Multiblocks:

The sign for their multiblock can be [shield] or [particleshield]. The second line on the sign must be the shield's label. When you get hit, the damage reports will tell you which shield got hit, identified by the name you put.

Shield Power Usage Equation: (power^1.4 / max(1, max(cbrt(distance), 1)) * powerUsage)

(Power usage is a constant used for balancing shields, at the time of writing 4000)

Multiblocks
Class 0.8 (8 block radius)
Materials needed: 1x glass, 1x glass pane, 1x iron block, 1x sponge a98c52ec5b882c8e1047c79be2c36e1a.png

Class 2.0 (12 block radius)
Materials needed: 1x glass, 2x glass pane, 2x iron block, 1x sponge

Screenshot 24.png

Class 3.0 (20 block radius)
Materials needed: 1x glass, 6x glass pane, 4x iron block, 5x stairs, 1x sponge

6ba154bec3cbafbd6d20c448b31fa40a.png d7405f97c7a48627c0c9652e37b88b19.png

Class 6.5 (30 block radius)
Materials needed: 5x glass, 9x glass pane, 6x iron block, 8x stairs, 2x sponge

b4d7e120424490118f0ff01c23c64dbd.png 4196adcdb58ad6ef27280fe97d24b9cc.png

Class 8.5 (35 block radius)
Materials needed: 11x glass, 14x glass pane, 11x iron block, 18x stairs, 4x sponge

9cf0e84bb37bb3ec4de0b94efdbcc40a.png fbc0c2e91d26ef651381b2d2984148ee.png