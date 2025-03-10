---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/ftd
- monster/cr/11
- monster/size/large
- monster/type/construct
aliases: ["Dragonbone Golem"]
---
# Dragonbone Golem
*Source: Fizban's Treasury of Dragons p. 183*  

A dragonbone golem is composed of dragon bones linked together with adamantine wire into the form of a dragon, animated by drawing on the bones' inherent magic. Most dragon bone golems are created by powerful dragons from the bones of vanquished rivals. Each bone is etched with intricate glyphs that allow animating power to flow through the golem's form.

Dragonbone golems' resilience and obedience make them excellent lair guardians for their dragon creators, and their supernaturally fearsome presence is a strong deterrent against intrusion.

```ad-statblock
title: Dragonbone Golem
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/FTD/Dragonbone%20Golem.webp#token)
*Large construct, Unaligned*

- **Armor Class** 17 (natural armor)
- **Hit Points** 161 (`19d10 + 57`)
- **Speed** 40 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|20 (+5)|10 (+0)|17 (+3)| 3 (-4)|11 (+0)|10 (+0)|

- **Proficiency Bonus** +4
- **Saving Throws** ⏤
- **Skills** ⏤
- **Senses** darkvision 60 ft., passive Perception 10
- **Damage Immunities** poison
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed), [petrified](2-Mechanics/CLI/rules/conditions.md#Petrified), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** understands Draconic and the languages of its creator but can't speak
- **Challenge** 11

## Traits

***Fear Aura.*** Each creature of the golem's choice that starts its turn within 20 feet of the golem must make a DC 15 Wisdom saving throw unless the golem is [incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated). On a failed save, the creature is [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened) until the start of its next turn. On a successful save, the creature is immune to this golem's Fear Aura for the next 24 hours.

***Magic Resistance.*** The golem has advantage on saving throws against spells and other magical effects.

***Unusual Nature.*** The golem doesn't require air, food, drink, or sleep.

## Actions

***Multiattack.*** The golem makes one Pinion attack and two Rend attacks.

***Pinion.*** *Melee Weapon Attack:* `dice:1d20+9|noform|text(+9)` to hit, reach 5 ft., one target. *Hit:* `dice:2d6+5|noform|avg|text(12)` (`2d6 + 5`) piercing damage. If the target is a Medium or smaller creature, it is pinned beneath the bony pinion and [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained). The golem has two pinions, each of which can restrain one target. If a creature is [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) by one of the pinions, the golem can't attack with it. Any creature [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) by a pinion can free itself at the start of its turn with a successful DC 17 Strength ([Athletics](2-Mechanics/CLI/rules/skills.md#Athletics)) check.

***Rend.*** *Melee Weapon Attack:* `dice:1d20+9|noform|text(+9)` to hit, reach 5 ft., one target. *Hit:* `dice:2d6+5|noform|avg|text(12)` (`2d6 + 5`) piercing damage plus `dice:1d10|noform|avg|text(5)` (`1d10`) necrotic damage.

***Petrifying Breath (Recharge 5-6).*** The golem emits a 60-foot cone of petrifying gas from its mouth. Each creature in that area must succeed on a DC 15 Constitution saving throw or take `dice:10d6|noform|avg|text(35)` (`10d6`) poison damage and be [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) as it begins to turn to stone. The [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) target must repeat the saving throw at the end of its next turn. On a successful save, the effect ends on the target. On a failed save, the target is [petrified](2-Mechanics/CLI/rules/conditions.md#Petrified).
```
^statblock