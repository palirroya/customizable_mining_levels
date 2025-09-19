Hey! This is a mod for fabric solely to customize pickaxes and the blocks they're compatible with.

There are two new tags:
    - 'cml:mining_level_n'
    - 'cml:mining_req_n'
where 'n' is any integer above -1.

This overrides the 'minecraft:needs_iron_tool' and other tags, because
they're annoying and way too rigid.

Here's the new default:
WOOD: 0
STONE/GOLD: 10
IRON: 20
DIAMOND/NETHERITE: 30

All vanilla blocks mineable by pickaxes now require this.