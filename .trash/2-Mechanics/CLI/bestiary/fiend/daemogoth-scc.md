---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/scc
- monster/cr/10
- monster/size/huge
- monster/type/fiend
aliases: ["Daemogoth"]
---
# Daemogoth
*Source: Strixhaven: A Curriculum of Chaos p. 189*  

Slipping through the darkest corners of the world, daemogoths are powerful fiendish creatures that feed on misery and other negative emotions. Some sages refer to daemogoths as tear lickers, owing to the fiends' tendency to lurk near battlefields and other sites of great tragedy to consume the anguish saturating the area.

Daemogoths are creatures of forbidden knowledge and magic, all fueled by their consumption of anguish. They trade magical influence over the lives and minds of others to ambitious mortals in exchange for the mortal's agony.

Daemogoths are alien-looking in the extreme. Their eyes are insectile or smooth and bulbous like gleaming jewels, and they have five arms. They typically wear long robes, which drape low over their forms, and they sport a halo of horns, antlers, or floating stones or crystals.

```ad-statblock
title: Daemogoth
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/SCC/Daemogoth.webp#token)
*Huge fiend, typically  Lawful Evil*

- **Armor Class** 16 (natural armor)
- **Hit Points** 157 (`15d12 + 60`)
- **Speed** 40 ft., climb 40 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|19 (+4)|15 (+2)|19 (+4)|21 (+5)|14 (+2)|18 (+4)|

- **Proficiency Bonus** +4
- **Saving Throws** Intelligence +9, Wisdom +6, Charisma +8
- **Skills** Arcana +13, Deception +12, History +9, Perception +6
- **Senses** truesight 120 ft., passive Perception 16
- **Damage Immunities** psychic
- **Condition Immunities** [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened)
- **Languages** Abyssal, Infernal, telepathy 120 ft.
- **Challenge** 10

## Traits

***Pact of Pain.*** Using a 10-minute ritual, the daemogoth can forge a magical bond with a willing creature it touches throughout the ritual. The creature becomes bound by the pact until it dies, the daemogoth dies, or the pact is broken by any effect that can remove a curse.

The daemogoth chooses one spell from the necromancy or enchantment school that is 3rd level or lower. The bound creature can cast that spell using this pact, requiring no material components and using Intelligence as the spellcasting ability. When it casts the spell, the creature takes `dice:2d6|noform|avg|text(7)` (`2d6`) psychic damage, which can't break the creature's [concentration](2-Mechanics/CLI/rules/conditions.md#Concentration) on a spell. Once the bound creature casts the spell in this way, it can't do so again until it finishes a long rest.

## Actions

***Multiattack.*** The daemogoth makes three Agonizing Burst attacks. It can use Terrify, if available, in place of one of the attacks.

***Agonizing Burst.*** *Melee or Ranged Spell Attack:* `dice:1d20+9|noform|text(+9)` to hit, reach 10 ft. or range 120 ft., one target. *Hit:* `dice:2d10|noform|avg|text(11)` (`2d10`) force damage. If the target is a creature, the daemogoth regains 5 hit points.

***Terrify (Recharge 4-6).*** The daemogoth targets one creature it can see within 120 feet of itself. The target must make a DC 17 Wisdom saving throw. On a failed save, the target takes `dice:6d10|noform|avg|text(33)` (`6d10`) psychic damage and is [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened) of the daemogoth until the end of the daemogoth's next turn, and the daemogoth regains 5 hit points. On a successful save, the target takes half as much damage and isn't [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), and the daemogoth doesn't heal.
```
^statblock