# Spleef-Arena-Summon-Minecraft-

Quick explanation for how this command works:

Basically, by summoning in a falling_block and using the BlockState NBT tag, we can summon a command redstone block. Then by setting the passenger to the falling_block block-entity to an armor stand, then setting the passenger of the armor stand to an activator rail, the activator rail is powered on. We can then summon minecart command blocks that fall onto the activator rail, and are subsequently powered on, summoning different parts of the Spleef Arena, specifically the tnt, sand, stone pressure plates, and glass enclosure of the arena. We have to use minecart command blocks so we can have multiple commands to be run all at once. The final parts of the code remove the activator rail, the armor stand, and the minecart command blocks, and our result is a spleef arena.
