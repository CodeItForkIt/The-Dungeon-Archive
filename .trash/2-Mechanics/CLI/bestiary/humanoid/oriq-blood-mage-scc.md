---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/scc
- monster/cr/9
- monster/size/medium
- monster/type/humanoid/warlock
aliases: ["Oriq Blood Mage"]
---
# Oriq Blood Mage
*Source: Strixhaven: A Curriculum of Chaos p. 201*  

Oriq blood mages create deadly weapons formed of their own blood. They can also sense the life energy within nearby creatures, making the blood mages almost impossible to ambush.

## Oriq

The Oriq are a secret society of mages who wield forbidden magic in the service of their leader, Extus Narr. Narr was in consideration for elevation to the role of Oracle of Strixhaven, but when the Founder Dragons passed him over in favor of Jadzi, his bitterness knew no bounds. He now uses the Oriq to gather the spells and magical energy he needs to summon a devastating being, the Blood Avatar, to destroy Strixhaven.

The Oriq work in secret, infiltrating Strixhaven to search for the magic their master covets and watch for impressionable students and embittered faculty they might turn to their cause. The Oriq take pains to hide their true allegiance and wear masks to hide their identities. These masks have magical properties that function only for their intended wearers.

## Statblock

```ad-statblock
title: Oriq Blood Mage
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/SCC/Oriq%20Blood%20Mage.webp#token)
*Medium humanoid (warlock), typically  Neutral Evil*

- **Armor Class** 16 (blood aegis)
- **Hit Points** 127 (`15d8 + 60`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|11 (+0)|14 (+2)|18 (+4)|20 (+5)|12 (+1)|12 (+1)|

- **Proficiency Bonus** +4
- **Saving Throws** Constitution +8, Intelligence +9, Wisdom +5, Charisma +5
- **Skills** Deception +9, Medicine +5, Survival +5
- **Senses** passive Perception 11
- **Damage Resistances** necrotic
- **Condition Immunities** [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion)
- **Languages** Common plus any four languages
- **Challenge** 9

## Traits

***Blood Aegis.*** The AC of the blood mage includes its Constitution modifier while it isn't wearing armor or wielding a shield.

***Oriq Mask.*** The blood mage wears an Oriq mask. While wearing the mask, the blood mage can't be targeted by any divination magic or perceived through magical scrying sensors, and it adds double its proficiency bonus to Charisma ([Deception](2-Mechanics/CLI/rules/skills.md#Deception)) checks (included above).

***Sanguine Sense.*** While the blood mage isn't [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded), it can see any creature that isn't an Undead or a Construct within 60 feet of itself, even through total cover, heavily obscured areas, invisibility, or any other phenomena that would prevent sight.

## Actions

***Multiattack.*** The blood mage makes two Blood Lash attacks.

***Blood Lash.*** *Melee Spell Attack:* `dice:1d20+9|noform|text(+9)` to hit, reach 10 ft., one target. *Hit:* `dice:3d10+5|noform|avg|text(21)` (`3d10 + 5`) necrotic damage. If the target is a creature, it can't regain hit points until the start of the blood mage's next turn.

***Blood Boil (Recharge 4-6).*** The blood mage chooses a point within 150 feet of itself, and a 20-foot radius sphere centered on that point fills with a burst of searing, blood-red mist. Each creature of the blood mage's choice that it can see in that area must make a DC 17 Constitution saving throw. On a failed save, a creature takes `dice:7d10|noform|avg|text(38)` (`7d10`) necrotic damage and is [incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated) until the end of its next turn. On a success, a creature takes half as much damage and isn't [incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated). A creature dies if reduced to 0 hit points by this necrotic damage.
```
^statblock