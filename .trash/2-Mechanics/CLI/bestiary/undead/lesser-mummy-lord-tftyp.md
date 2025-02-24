---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tftyp
- monster/cr/15
- monster/size/medium
- monster/type/undead
aliases: ["Lesser Mummy Lord"]
---
# Lesser Mummy Lord
*Source: Tales from the Yawning Portal p. 224*  

```ad-statblock
title: Lesser Mummy Lord
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/TftYP/Lesser%20Mummy%20Lord.webp#token)
*Medium undead, Lawful Evil*

- **Armor Class** 17 (natural armor)
- **Hit Points** 97 (`13d8 + 39`)
- **Speed** 20 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|18 (+4)|10 (+0)|17 (+3)|11 (+0)|18 (+4)|16 (+3)|

- **Proficiency Bonus** +5
- **Saving Throws** Constitution +8, Intelligence +5, Wisdom +9, Charisma +8
- **Skills** History +5, Religion +5
- **Senses** darkvision 60 ft., passive Perception 14
- **Damage Resistances** fire
- **Damage Immunities** necrotic; poison; bludgeoning, piercing, slashing from nonmagical attacks
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** the languages it knew in life
- **Challenge** 15

## Traits

***Magic Resistance.*** The mummy lord has advantage on saving throws against spells and other magical effects.

***Rejuvenation.*** A destroyed mummy lord gains a new body in 24 hours if its heart is intact, regaining all its hit points and becoming active again. The new body appears within 5 feet of the mummy lord's heart.

***Special Equipment.*** The mummy wears a [ring of fire resistance](2-Mechanics/CLI/items/ring-of-fire-resistance.md).

## Actions

***Multiattack.*** The mummy can use its Dreadful Glare and makes one attack with its rotting fist.

***Rotting Fist.*** *Melee Weapon Attack:* `dice:1d20+9|noform|text(+9)` to hit, reach 5 ft., one target. *Hit:* `dice:3d6+4|noform|avg|text(14)` (`3d6 + 4`) bludgeoning damage plus `dice:6d6|noform|avg|text(21)` (`6d6`) necrotic damage. If the target is a creature, it must succeed on a DC 16 Constitution saving throw or be cursed with mummy rot. The cursed target can't regain hit points, and its hit point maximum decreases by `dice:3d6|noform|avg|text(10)` (`3d6`) for every 24 hours that elapse. If the curse reduces the target's hit point maximum to 0, the target dies, and its body turns to dust. The curse lasts until removed by the [remove curse](2-Mechanics/CLI/spells/remove-curse.md) spell or other magic.

***Dreadful Glare.*** The mummy lord targets one creature it can see within 60 feet of it. If the target can see the mummy lord, it must succeed on a DC 16 Wisdom saving throw against this magic or become [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened) until the end of the mummy's next turn. If the target fails the saving throw by 5 or more, it is also [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed) for the same duration. A target that succeeds on the saving throw is immune to the Dreadful Glare of all mummies and mummy lords for the next 24 hours.
```
^statblock