---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/imr
- monster/cr/12
- monster/size/medium
- monster/type/humanoid/human
statblock: inline
aliases: ["Thessalar"]
---
# [Thessalar](Mechanics\bestiary\npc/thessalar-imr.md)
*Source: Infernal Machine Rebuild p. 57*  

Thessalar was a master alchemist and creator of monsters, whose own blood was said to possess dire magical properties.

He is vainglorious, egotistical, and utterly ruthless in furthering his research. His career began as a priest in the service of Moloch, where he rose through the ranks before eventually taking over the temple as a working laboratory. Most of his experiments have involved the pursuit of new forms of life, resulting in such creatures as the thessalhydra and the owlbear. In recent years, he has also researched the prolonging of life—namely his own. Thessalar hopes that by becoming a lich, his research and experiments can continue indefinitely.

Over time, Thessalar has subjected himself to so many of his own experiments that his blood has taken on alchemical and magical properties. He regularly uses it as the basis for many of the reagents used throughout his labs.

```statblock
"name": "Thessalar (IMR)"
"size": "Medium"
"type": "humanoid"
"subtype": "human"
"alignment": "Neutral Evil"
"ac": !!int "14"
"ac_class": "[breastplate](Mechanics/items/breastplate.md)"
"hp": !!int "104"
"hit_dice": "19d8 + 19"
"stats":
- !!int "10"
- !!int "12"
- !!int "13"
- !!int "19"
- !!int "16"
- !!int "16"
"speed": "30 ft."
"saves":
  "Wisdom": !!int "7"
  "Intelligence": !!int "8"
  "Constitution": !!int "5"
"skillsaves":
  "Medicine": !!int "7"
  "Animal Handling": !!int "7"
  "Insight": !!int "7"
  "Arcana": !!int "8"
"damage_immunities": "acid, poison"
"condition_immunities": "[poisoned](Mechanics/Rules/conditions.md#Poisoned)"
"senses": "passive Perception 13"
"languages": "Common, Draconic, Elvish, Primordial"
"cr": "12"
"traits":
- "desc": "Thessalar is an 18th-level spellcaster. His spellcasting ability is Intelligence\
    \ (spell save DC 16, +8 to hit with spell attacks). He has the following artificer\
    \ spells prepared:\n\nCantrips (at will): [light](Mechanics/spells/light.md),\
    \ [mending](Mechanics/spells/mending.md), [message](Mechanics/spells/message.md),\
    \ [shocking grasp](Mechanics/spells/shocking-grasp.md)\n\n1st level (4 slots):\
    \ [alarm](Mechanics/spells/alarm.md), [cure wounds](Mechanics/spells/cure-wounds.md),\
    \ [identify](Mechanics/spells/identify.md), [ray of sickness](Mechanics/spells/ray-of-sickness.md)\n\
    \n2nd level (3 slots): [invisibility](Mechanics/spells/invisibility.md), [Melf's\
    \ acid arrow](Mechanics/spells/melfs-acid-arrow.md), [web](Mechanics/spells/web.md)\n\
    \n3rd level (3 slots): [dispel magic](Mechanics/spells/dispel-magic.md), [haste](Mechanics/spells/haste.md),\
    \ [stinking cloud](Mechanics/spells/stinking-cloud.md)\n\n4th level (3 slots):\
    \ [blight](Mechanics/spells/blight.md), [Mordenkainen's faithful hound](Mechanics/spells/mordenkainens-faithful-hound.md),\
    \ [Otiluke's resilient sphere](Mechanics/spells/otilukes-resilient-sphere.md)\n\
    \n5th level (1 slots): [cloudkill](Mechanics/spells/cloudkill.md)"
  "name": "Spellcasting"
- "desc": "Thessalar wields a [+1 dagger](Mechanics/items/1-weapon.md) coated with\
    \ [thessaltoxin poison](Mechanics/items/thessaltoxin-imr.md) (see appendix C)."
  "name": "Special Equipment"
- "desc": "Thessalar is accompanied by his [Thessalar's homunculus](Mechanics/bestiary/npc/thessalars-homunculus-imr.md).\
    \ If the [mending](Mechanics/spells/mending.md) spell is cast on it, the homunculus\
    \ regains 2d6 hit points."
  "name": "Alchemical Homunculus"
- "desc": "Any magic item that restores hit points and can be applied to a piercing\
    \ or slashing weapon (a potion, an ointment, and so forth) causes a hit with that\
    \ weapon to deal extra damage to Thessalar equal to the amount the item would\
    \ normally heal."
  "name": "Healing Toxicity"
- "desc": "Thessalar can cast [greater restoration](Mechanics/spells/greater-restoration.md)\
    \ if he has access to [alchemical supplies](Mechanics/items/alchemists-supplies.md)."
  "name": "Greater Restoration (1/Day)"
"actions":
- "desc": "Melee or Ranged Weapon Attack: +5 to hit, reach 5 ft. or range 20/60\
    \ ft., one target. Hit: 3 (1d4 + 1) piercing damage, and the target must succeed\
    \ on a DC 15 Constitution saving throw. On a failed save, the target is affected\
    \ as if by the [polymorph](Mechanics/spells/polymorph.md) spell, transforming\
    \ into a random beast or a creature it has seen within the last 24 hours (as chosen\
    \ by the DM). This effect lasts until the target finishes a long rest."
  "name": "Dagger"
"source":
- "IMR"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/IMR/Thessalar.webp"
```
^statblock