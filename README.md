# O2C
A Minecraft Plugin which transform High-Tier ores in Lower-Tier ores when mined

This plugin is for Minecraft-Survival Server. It transforms High-Tier ores like DIAMOND_ORE in Lower-Tier ores like REDSTONE_ORE when mined.
With this you can mine f.e. diamonds and also getting all the lower tier ore, which makes mining faster.
I try to implement a way to customize this plugin, so you can choose, which ore will transform in a other ore when mined.
You also will be aible to f.e. set COBBLE_STONE to BEDROCK, so on a server with multiple worlds you can create a Mining world where only ores can get mined and if you mine COBBLE_STONE you won't able to dig deeper.

# Currently its working like this:
- if EMERALD_ORE  -> transforms to -> DIAMOND_ORE
- if DIAMOND_ORE  -> transforms to -> REDSTONE_ORE
- if REDSTONE_ORE -> transforms to -> LAPIS_ORE
- if LAPIS_ORE -> transforms to -> GOLD_ORE
- if GOLD_ORE -> transforms to -> IRON_ORE
- if IRON_ORE -> transforms to -> COAL_ORE
- if COAL_ORE -> transforms to -> STONE

*All other Blocks are still vanilla!*
