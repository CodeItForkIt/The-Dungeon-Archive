---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/skt
- monster/cr/23
- monster/size/gargantuan
- monster/type/elemental
aliases: ["Maegera the Dawn Titan"]
---
# Maegera the Dawn Titan
*Source: Storm King's Thunder p. 241*  

Maegera is powerful elemental that has been trapped in the forges of Gauntlgrym for millennia. About fifty years ago, Maegera briefly escaped and triggered the eruption of Mount Hotenow. Lava from the volcano flowed toward the coast, laying waste to Neverwinter. The city is still rebuilding in the wake of that catastrophe.

The fire giant duke Zalto recently sent a team of drow to infiltrate Gauntlgrym and trap Maegera in an iron flask . Zalto needs the primordial to ignite an adamantine forge beneath the Ice Spires. Returning Maegera to Gauntlgrym is one way to thwart the fire giant's plans.

Maegera looks like a 50-foot-tall, multi-limbed beast made of flame, with smoldering black pits for eyes.

```ad-statblock
title: Maegera the Dawn Titan
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/SKT/Maegera%20the%20Dawn%20Titan.webp#token)
*Gargantuan elemental, Chaotic Evil*

- **Armor Class** 16
- **Hit Points** 341 (`22d20 + 110`)
- **Speed** 50 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|21 (+5)|22 (+6)|20 (+5)|10 (+0)|10 (+0)|19 (+4)|

- **Proficiency Bonus** +7
- **Saving Throws** Constitution +12, Wisdom +7, Charisma +11
- **Skills** ⏤
- **Senses** blindsight 120 ft., passive Perception 10
- **Damage Resistances** bludgeoning, piercing, slashing from nonmagical attacks
- **Damage Immunities** fire, poison
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled), [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed), [petrified](2-Mechanics/CLI/rules/conditions.md#Petrified), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned), [prone](2-Mechanics/CLI/rules/conditions.md#Prone), [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained)
- **Languages** Ignan
- **Challenge** 23

## Traits

***Empowered Attacks.*** Maegera's slam attacks are treated as magical for the purpose of overcoming resistance and immunity to damage from nonmagical attacks.

***Fire Aura.*** At the start of each of Maegera's turns, each creature within 30 feet of it takes `dice:10d6|noform|avg|text(35)` (`10d6`) fire damage, and flammable objects in the aura that aren't being worn or carried ignite. A creature also takes `dice:10d6|noform|avg|text(35)` (`10d6`) fire damage from touching Maegera or from hitting it with a melee attack while within 10 feet of it, and a creature takes that damage the first time on a turn that Maegera moves into its space. Nonmagical weapons that hit Maegera are destroyed by fire immediately after dealing damage to it.

***Fire Form.*** Maegera can enter a hostile creature's space and stop there. It can move through a space as narrow as 1 inch wide without squeezing if fire could pass through that space.

***Illumination.*** Maegera sheds bright light in a 120-foot radius and dim light in an additional 120 ft..

***Magic Resistance.*** Maegera has advantage on saving throws against spells and other magical effects.

***Spellcasting.*** Maegera casts [fireball](2-Mechanics/CLI/spells/fireball.md) (spell save DC 19), requiring no material components and using Charisma as the spellcasting ability.


## Actions

***Multiattack.*** Maegera makes three slam attacks.

***Slam.*** *Melee Weapon Attack:* `dice:1d20+12|noform|text(+12)` to hit, reach 15 ft., one target. *Hit:* `dice:3d6+5|noform|avg|text(15)` (`3d6 + 5`) bludgeoning damage plus `dice:10d6|noform|avg|text(35)` (`10d6`) fire damage

## Legendary Actions

***Quench Magic.*** Maegera targets one creature that it can see within 60 feet of it. Any resistance or immunity to fire damage that the target gains from a spell or magic item is suppressed. The effect lasts until the end of Maegera's next turn.

***Smoke Cloud (Costs 2 Actions).*** Maegera exhales a billowing cloud of hot smoke and embers that fills a 60 feet cube. Each creature in the area takes `dice:2d10|noform|avg|text(11)` (`2d10`) fire damage. The cloud lasts until the end of Maegera's next turn. Creatures completely in the cloud are [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded) and can't be seen.

***Create Fire Elemental (Costs 3 Actions).*** Maegera's hit points are reduced by 50 as part of it separates and becomes a [fire elemental](2-Mechanics/CLI/bestiary/elemental/fire-elemental.md) with 102 hit points. The fire element appears in an unoccupied space within 15 feet of Maegera and acts on Maegera's initiative count. Maegera can't use this action if it has 50 hit points or fewer. The fire element obeys Maegera's commands and fights until destroyed.
```
^statblock