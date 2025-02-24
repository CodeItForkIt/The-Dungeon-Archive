---
obsidianUIMode: preview
cssclasses: json5e-item
tags:
- compendium/src/5e/tdcsr
- item/gear/ammunition
- item/rarity/very-rare
aliases: 
- "Cataclysm Bolts"
---
# Cataclysm Bolts
*Ammunition, very rare*  

- **Weight**: 0.075 lbs.

These steel [crossbow bolts](2-Mechanics/CLI/items/crossbow-bolt.md) were first created by the Jaggenstrike Clan during the "Scattered War", and the secret to crafting them remains well guarded by the "Houses of Kraghammer". Cataclysm bolts are usually kept in sets of ten, though anyone who holds even one can feel it thrumming with magical power. When you hit with an attack using a cataclysm bolt, the attack deals normal damage. Then roll a `dice:d6|noform|avg` (`d6`) on the following table to determine its additional effect.

**Cataclysm Bolt Effects**

`dice: [](cataclysm-bolts-tdcsr.md#^cataclysm-bolt-effects)`

| dice: d6 | Effect |
|----------|--------|
| 1-2 | The bolt explodes in a blast of fire, dealing `dice:3d8\\|noform\\|avg` (`3d8`) fire damage to the target and each creature within 5 feet of it. |
| 3-4 | The bolt freezes the air around the target into jagged ice. The target and each creature within 5 feet of it must succeed on a DC 17 Dexterity saving throw or take `dice:1d10\\|noform\\|avg` (`1d10`) cold damage and be [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) until the end of your next turn. |
| 5 | The bolt releases a pulse of necrotic energy. The target takes `dice:2d6\\|noform\\|avg` (`2d6`) necrotic damage and must succeed on a DC 16 Strength saving throw or be [stunned](2-Mechanics/CLI/rules/conditions.md#Stunned) until the end of your next turn. |
| 6 | The bolt shatters to unleash a burst of shrapnel. Make six additional ranged attacks against the target, each of which has a `dice:1d20+7\\|noform\\|text(+7)` attack bonus and deals `dice:1d6\\|noform\\|avg` (`1d6`) piercing damage on a hit. |
^cataclysm-bolt-effects

Once the bolt hits, the enchantment ends and it becomes a normal piece of ammunition.

*Source: Tal'Dorei Campaign Setting Reborn p. 194*