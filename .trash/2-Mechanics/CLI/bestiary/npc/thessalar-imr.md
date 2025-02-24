---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/imr
- monster/cr/12
- monster/size/medium
- monster/type/humanoid/human
aliases: ["Thessalar"]
---
# Thessalar
*Source: Infernal Machine Rebuild p. 57*  

Thessalar was a master alchemist and creator of monsters, whose own blood was said to possess dire magical properties.

He is vainglorious, egotistical, and utterly ruthless in furthering his research. His career began as a priest in the service of Moloch, where he rose through the ranks before eventually taking over the temple as a working laboratory. Most of his experiments have involved the pursuit of new forms of life, resulting in such creatures as the thessalhydra and the owlbear. In recent years, he has also researched the prolonging of life—namely his own. Thessalar hopes that by becoming a lich, his research and experiments can continue indefinitely.

Over time, Thessalar has subjected himself to so many of his own experiments that his blood has taken on alchemical and magical properties. He regularly uses it as the basis for many of the reagents used throughout his labs.

```ad-statblock
title: Thessalar
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/IMR/Thessalar.webp#token)
*Medium humanoid (human), Neutral Evil*

- **Armor Class** 14 ([breastplate](2-Mechanics/CLI/items/breastplate.md))
- **Hit Points** 104 (`19d8 + 19`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|10 (+0)|12 (+1)|13 (+1)|19 (+4)|16 (+3)|16 (+3)|

- **Proficiency Bonus** +4
- **Saving Throws** Constitution +5, Intelligence +8, Wisdom +7
- **Skills** Animal Handling +7, Arcana +8, Insight +7, Medicine +7
- **Senses** passive Perception 13
- **Damage Immunities** acid, poison
- **Condition Immunities** [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** Common, Draconic, Elvish, Primordial
- **Challenge** 12

## Traits

***Special Equipment.*** Thessalar wields a [+1 dagger](2-Mechanics/CLI/items/1-weapon.md) coated with [thessaltoxin poison](2-Mechanics/CLI/items/thessaltoxin-imr.md) (see appendix C).

***Alchemical Homunculus.*** Thessalar is accompanied by his [Thessalar's homunculus](2-Mechanics/CLI/bestiary/npc/thessalars-homunculus-imr.md). If the [mending](2-Mechanics/CLI/spells/mending.md) spell is cast on it, the homunculus regains `dice:2d6|noform|avg` (`2d6`) hit points.

***Healing Toxicity.*** Any magic item that restores hit points and can be applied to a piercing or slashing weapon (a potion, an ointment, and so forth) causes a hit with that weapon to deal extra damage to Thessalar equal to the amount the item would normally heal.

***Greater Restoration (1/Day).*** Thessalar can cast [greater restoration](2-Mechanics/CLI/spells/greater-restoration.md) if he has access to [alchemical supplies](2-Mechanics/CLI/items/alchemists-supplies.md).

***Spellcasting.*** Thessalar is an 18th-level spellcaster. His spellcasting ability is Intelligence (spell save DC 16, `dice:1d20+8|noform|text(+8)` to hit with spell attacks). He has the following artificer spells prepared:

**Cantrips (at will)**: [light](2-Mechanics/CLI/spells/light.md), [mending](2-Mechanics/CLI/spells/mending.md), [message](2-Mechanics/CLI/spells/message.md), [shocking grasp](2-Mechanics/CLI/spells/shocking-grasp.md)

**1st level (4 slots)**: [alarm](2-Mechanics/CLI/spells/alarm.md), [cure wounds](2-Mechanics/CLI/spells/cure-wounds.md), [identify](2-Mechanics/CLI/spells/identify.md), [ray of sickness](2-Mechanics/CLI/spells/ray-of-sickness.md)

**2nd level (3 slots)**: [invisibility](2-Mechanics/CLI/spells/invisibility.md), [Melf's acid arrow](2-Mechanics/CLI/spells/melfs-acid-arrow.md), [web](2-Mechanics/CLI/spells/web.md)

**3rd level (3 slots)**: [dispel magic](2-Mechanics/CLI/spells/dispel-magic.md), [haste](2-Mechanics/CLI/spells/haste.md), [stinking cloud](2-Mechanics/CLI/spells/stinking-cloud.md)

**4th level (3 slots)**: [blight](2-Mechanics/CLI/spells/blight.md), [Mordenkainen's faithful hound](2-Mechanics/CLI/spells/mordenkainens-faithful-hound.md), [Otiluke's resilient sphere](2-Mechanics/CLI/spells/otilukes-resilient-sphere.md)

**5th level (1 slots)**: [cloudkill](2-Mechanics/CLI/spells/cloudkill.md)

## Actions

***Dagger.*** *Melee or Ranged Weapon Attack:* `dice:1d20+5|noform|text(+5)` to hit, reach 5 ft. or range 20/60 ft., one target. *Hit:* `dice:1d4+1|noform|avg|text(3)` (`1d4 + 1`) piercing damage, and the target must succeed on a DC 15 Constitution saving throw. On a failed save, the target is affected as if by the [polymorph](2-Mechanics/CLI/spells/polymorph.md) spell, transforming into a random beast or a creature it has seen within the last 24 hours (as chosen by the DM). This effect lasts until the target finishes a long rest.
```
^statblock