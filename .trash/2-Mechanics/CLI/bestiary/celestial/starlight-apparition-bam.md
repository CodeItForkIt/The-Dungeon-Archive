---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/bam
- monster/cr/5
- monster/size/medium
- monster/type/celestial
aliases: ["Starlight Apparition"]
---
# Starlight Apparition
*Source: Boo's Astral Menagerie p. 59, Light of Xaryxis*  

The transparent projections of unfortunate souls who perished in Wildspace or in the Astral Sea are known as starlight apparitions. Each one has a luminous, incorporeal appearance that resembles its former self, but with eyes that glow.

A starlight apparition is different from a ghost. While a ghost is doomed to haunt the place where it died until some promise or goal it couldn't achieve in life is fulfilled, the goal of a starlight apparition is to help someone else avoid or overcome a perilous obstacle or accomplish a difficult task. A starlight apparition comes into being when the soul of a deceased individual, from its resting place in the afterlife, projects a spectral copy of itself across a vast distance with the help of a deity or another powerful celestial entity. The apparition lasts only as long as its services are needed to complete the task at hand; then it fades away, never to return.

```ad-statblock
title: Starlight Apparition
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/BAM/Starlight%20Apparition.webp#token)
*Medium celestial, typically  Neutral Good*

- **Armor Class** 10
- **Hit Points** 72 (`16d8`)
- **Speed** 0 ft., fly 30 ft. (hover)

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
| 1 (-5)|11 (+0)|10 (+0)|18 (+4)|16 (+3)|16 (+3)|

- **Proficiency Bonus** +3
- **Saving Throws** ⏤
- **Skills** ⏤
- **Senses** darkvision 120 ft., passive Perception 13
- **Damage Resistances** acid; cold; fire; bludgeoning, piercing, slashing from nonmagical attacks
- **Damage Immunities** poison, radiant
- **Condition Immunities** [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded), [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled), [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed), [petrified](2-Mechanics/CLI/rules/conditions.md#Petrified), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned), [prone](2-Mechanics/CLI/rules/conditions.md#Prone), [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained)
- **Languages** the languages it knew in life
- **Challenge** 5

## Traits

***Astral Existence.*** The apparition can exist only on the Astral Plane. If it is sent to a location not on the Astral Plane, the apparition is destroyed.

***Illumination.*** While it has at least 1 hit point, the apparition sheds bright light in a 20-foot radius and dim light for an additional 20 feet.

***Incorporeal Movement.*** The apparition can move through other creatures and objects as if they were difficult terrain. It takes `dice:1d10|noform|avg|text(5)` (`1d10`) force damage if it ends its turn inside an object.

***Unusual Nature.*** The apparition doesn't require air, drink, food, or sleep.

## Actions

***Radiant Eruption.*** *Melee or Ranged Spell Attack:* `dice:1d20+6|noform|text(+6)` to hit, reach 5 ft. or range 120 ft., one target. *Hit:* `dice:5d6+3|noform|avg|text(20)` (`5d6 + 3`) radiant damage, and if the target is a creature, it must succeed on a DC 14 Wisdom saving throw or be [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded) for 1 minute. The target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

***Possession (Recharge 6).*** One Humanoid that the apparition can see within 5 feet of itself must succeed on a DC 14 Charisma saving throw or be possessed by the apparition; the apparition then disappears, and the target is [incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated) and loses control of its body. The apparition now controls the body but doesn't deprive the target of awareness. The apparition can't be targeted by any attack, spell, or other effect, and it retains its alignment, Intelligence, Wisdom, Charisma, and immunity to being [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed) and [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened). It otherwise uses the possessed target's statistics, but doesn't gain access to the target's knowledge, class features, or proficiencies.

The possession lasts until the body drops to 0 hit points, the apparition ends it as a bonus action, the body leaves the Astral Plane, or the apparition is forced out by an effect like the [dispel evil and good](2-Mechanics/CLI/spells/dispel-evil-and-good.md) spell. When the possession ends, the apparition reappears in an unoccupied space within 5 feet of the body. If it reappears in a location not on the Astral Plane, the apparition is destroyed. The target is immune to this apparition's Possession for 24 hours after succeeding on the saving throw or after the possession ends.
```
^statblock