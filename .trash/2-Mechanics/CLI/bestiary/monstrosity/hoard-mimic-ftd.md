---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/ftd
- monster/cr/8
- monster/size/huge
- monster/type/monstrosity
aliases: ["Hoard Mimic"]
---
# Hoard Mimic
*Source: Fizban's Treasury of Dragons p. 204*  

Kin to the common mimic described in the *Monster Manual*, hoard mimics are among the oldest and most cunning of their kind. A hoard mimic's massive, amorphous form and shape-shifting prowess allow it to take on the semblance of a vast trove of treasures, not just a single object. Like smaller mimics, hoard mimics exude adhesive goo to trap prey. They can also vent a fine, caustic mist from their pores that burns and blinds creatures caught in it.

Hoard mimics are so named because many enter into partnerships with dragons, each one serving as a false hoard in a dragon's lair to draw unwitting intruders away from the real riches—and into the mimic's maw. If faced with unexpectedly fierce opposition, though, a hoard mimic might offer information about the true hoard in exchange for its life.

```ad-statblock
title: Hoard Mimic
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/FTD/Hoard%20Mimic.webp#token)
*Huge monstrosity, typically  Neutral*

- **Armor Class** 14 (natural armor)
- **Hit Points** 123 (`13d12 + 39`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|21 (+5)|12 (+1)|17 (+3)|10 (+0)|16 (+3)|10 (+0)|

- **Proficiency Bonus** +3
- **Saving Throws** Constitution +6, Wisdom +6
- **Skills** Persuasion +3, Stealth +6
- **Senses** darkvision 60 ft., passive Perception 13
- **Condition Immunities** [prone](2-Mechanics/CLI/rules/conditions.md#Prone)
- **Languages** Common, Draconic, telepathy 120 ft.
- **Challenge** 8

## Traits

***False Appearance (Hoard Form Only).*** If the mimic is motionless at the start of combat, it has advantage on its initiative roll. Moreover, if a creature hasn't observed the mimic move or act, that creature must succeed on a DC 18 Intelligence ([Investigation](2-Mechanics/CLI/rules/skills.md#Investigation)) check to discern that the mimic is animate.

## Actions

***Multiattack.*** The mimic makes one Bite attack and two Pseudopod attacks.

***Bite.*** *Melee Weapon Attack:* `dice:1d20+8|noform|text(+8)` to hit, reach 5 ft., one creature. *Hit:* `dice:2d10+5|noform|avg|text(16)` (`2d10 + 5`) piercing damage plus `dice:2d6|noform|avg|text(7)` (`2d6`) acid damage.

***Pseudopod.*** *Melee Weapon Attack:* `dice:1d20+8|noform|text(+8)` to hit, reach 10 ft., one target. *Hit:* `dice:2d6+5|noform|avg|text(12)` (`2d6 + 5`) bludgeoning damage, and the mimic adheres to the target. A creature adhered to the mimic is also [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) by it (escape DC 16). Until this grapple ends, the target is [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained). Ability checks made to escape this grapple have disadvantage.

***Caustic Mist (Recharge 5-6).*** The mimic sprays a fine mist of acid in a 30-foot cone. Each creature in that area must make a DC 14 Dexterity saving throw. On a failed save, the creature takes `dice:6d8|noform|avg|text(27)` (`6d8`) acid damage and is [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded) until the end of its next turn. On a successful save, the creature takes half as much damage and isn't [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded).

***Shapechanger.*** The mimic transforms into a hoard or back into its true, amorphous form. Its statistics are the same in each form. Any equipment it is wearing or carrying isn't transformed. It reverts to its true form if it dies.
```
^statblock