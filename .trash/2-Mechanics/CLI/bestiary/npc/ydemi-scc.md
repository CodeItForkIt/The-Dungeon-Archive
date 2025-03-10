---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/scc
- monster/cr/9
- monster/size/medium
- monster/type/humanoid/human
- monster/type/humanoid/warlock
aliases: ["Y'demi"]
---
# Y'demi
*Source: Strixhaven: A Curriculum of Chaos p. 172*  

The Oriq are a secret society of mages who wield forbidden magic in the service of their leader, Extus Narr. Narr was in consideration for elevation to the role of Oracle of Strixhaven, but when the Founder Dragons passed him over in favor of Jadzi, his bitterness knew no bounds. He now uses the Oriq to gather the spells and magical energy he needs to summon a devastating being, the Blood Avatar, to destroy Strixhaven.

The Oriq work in secret, infiltrating Strixhaven to search for the magic their master covets and watch for impressionable students and embittered faculty they might turn to their cause. The Oriq take pains to hide their true allegiance and wear masks to hide their identities. These masks have magical properties that function only for their intended wearers.

## Oriq Blood Mage

Oriq blood mages create deadly weapons formed of their own blood. They can also sense the life energy within nearby creatures, making the blood mages almost impossible to ambush.

## Statblock

```ad-statblock
title: Y'demi
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/SCC/Y%27demi.webp#token)
*Medium humanoid (human, warlock), Neutral Evil*

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

***Blood Aegis.*** The AC of Y'demi includes her Constitution modifier while she isn't wearing armor or wielding a shield.

***Oriq Mask.*** Y'demi wears an Oriq mask. While wearing the mask, Y'demi can't be targeted by any divination magic or perceived through magical scrying sensors, and she adds double her proficiency bonus to Charisma ([Deception](2-Mechanics/CLI/rules/skills.md#Deception)) checks (included above).

***Sanguine Sense.*** While Y'demi isn't [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded), she can see any creature that isn't an Undead or a Construct within 60 feet of itself, even through total cover, heavily obscured areas, invisibility, or any other phenomena that would prevent sight.

## Actions

***Multiattack.*** Y'demi makes two Blood Lash attacks.

***Blood Lash.*** *Melee Spell Attack:* `dice:1d20+9|noform|text(+9)` to hit, reach 10 ft., one target. *Hit:* `dice:3d10+5|noform|avg|text(21)` (`3d10 + 5`) necrotic damage. If the target is a creature, it can't regain hit points until the start of the Y'demi's next turn.

***Blood Boil (Recharge 4-6).*** Y'demi chooses a point within 150 feet of itself, and a 20-foot radius sphere centered on that point fills with a burst of searing, blood-red mist. Each creature of Y'demi's choice that she can see in that area must make a DC 17 Constitution saving throw. On a failed save, a creature takes `dice:7d10|noform|avg|text(38)` (`7d10`) necrotic damage and is [incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated) until the end of its next turn. On a success, a creature takes half as much damage and isn't [incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated). A creature dies if reduced to 0 hit points by this necrotic damage.

## Bonus Actions

***Sanguine Tentacles (1/Day).*** The blood in the copper basin disappears as tentacles of congealed blood fill a 10-foot cube centered at a point on the ground that Y'demi can see within 15 feet of her. The effect lasts for 1 minute, during which time that area is difficult terrain. Any creature entering that area for the first time on a turn or starting its turn there must succeed on a DC 13 Dexterity saving throw or be [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) by the tentacles. A creature that starts its turn [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) by the tentacles takes `dice:3d6|noform|avg|text(10)` (`3d6`) bludgeoning damage. A creature [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) by the tentacles can use its action to make either a DC 13 Strength ([Athletics](2-Mechanics/CLI/rules/skills.md#Athletics)) check or a DC 13 Dexterity ([Acrobatics](2-Mechanics/CLI/rules/skills.md#Acrobatics)) check, ending the [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) condition on itself on a success.
```
^statblock