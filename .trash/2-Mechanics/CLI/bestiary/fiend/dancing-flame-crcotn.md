---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/crcotn
- monster/cr/4
- monster/size/medium
- monster/type/fiend
aliases: ["Dancing Flame"]
---
# Dancing Flame
*Source: Critical Role: Call of the Netherdeep p. 68*  

```ad-statblock
title: Dancing Flame
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/CRCotN/Dancing%20Flame.webp#token)
*Medium fiend, Neutral Evil*

- **Armor Class** 15 (natural armor)
- **Hit Points** 66 (`12d8 + 12`)
- **Speed** 30 ft., fly 60 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
| 8 (-1)|17 (+3)|13 (+1)|15 (+2)|12 (+1)|20 (+5)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** Deception +9, Insight +5, Perception +5, Persuasion +9, Stealth +7
- **Senses** darkvision 60 ft., passive Perception 15
- **Damage Resistances** cold; fire; lightning; poison; bludgeoning, piercing, slashing from nonmagical attacks
- **Languages** Abyssal, Common, Infernal, telepathy 60 ft.
- **Challenge** 4

## Traits

***Telepathic Bond.*** The flame ignores the range restriction on its telepathy when communicating with a creature it has [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed). The two don't even need to be on the same plane of existence.

***Flame.*** The flame sheds bright light in a 20-foot radius and dim light for an additional 20 feet. If it leaves the hall or is reduced to 0 hit points, it is destroyed and can't re-form for 24 hours.

## Actions

***Claw.*** *Melee Weapon Attack:* `dice:1d20+5|noform|text(+5)` to hit, reach 5 ft., one target. *Hit:* `dice:1d6+3|noform|avg|text(6)` (`1d6 + 3`) fire damage.

***Charm.*** One humanoid the flame can see within 30 feet of it must succeed on a DC 15 Wisdom saving throw or be magically [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed) for 1 day. The [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed) target obeys the flame's verbal or telepathic commands. If the target suffers any harm or receives a suicidal command, it can repeat the saving throw, ending the effect on a success. If the target successfully saves against the effect, or if the effect on it ends, the target is immune to this flame's Charm for the next 24 hours.

The flame can have only one target [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed) at a time. If it charms another, the effect on the previous target ends.

***Draining Kiss.*** The flame kisses a creature [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed) by it or a willing creature. The target must make a DC 15 Constitution saving throw against this magic, taking `dice:5d10+5|noform|avg|text(32)` (`5d10 + 5`) psychic damage on a failed save, or half as much damage on a successful one. The target's hit point maximum is reduced by an amount equal to the damage taken. This reduction lasts until the target finishes a long rest. The target dies if this effect reduces its hit point maximum to 0.
```
^statblock