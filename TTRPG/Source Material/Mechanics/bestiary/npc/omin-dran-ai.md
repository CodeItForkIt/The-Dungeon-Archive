---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/ai
- monster/cr/5
- monster/size/medium
- monster/type/humanoid/half-elf
statblock: inline
aliases: ["Omin Dran"]
---
# [Omin Dran](Mechanics\bestiary\npc/omin-dran-ai.md)
*Source: Acquisitions Incorporated p. 196*  

> [!quote]  
> 
> My duty, first and foremost, is to my shareholders. And I am the only shareholder.

Ominifis Hereward Dran spent his formative years in the small waystop of Red Larch, where his mother, Prophetess, ran a popular inn and restaurant. In the brief periods of respite afforded by working the family business, Omin and his sisters, Auspicia and Portentia, were wont to wander the hills and trails around town, dreaming of adventure. But adventure of the wrong kind came calling for the trio one day, when an underground ruin they had often explored-actually a creature called the Wandering Crypt-took Auspicia from the world.

Omin Dran built the organization called Acquisitions Incorporated to facilitate and expand his quest to find his true sister, at least in part. For despite his unprecedented success in establishing the market for franchised adventuring across the Sword Coast and beyond, Omin's full measure eludes most people. He is known to be a worshiper of Tymora, ruthless in matters of business, feckless in matters of love, and hopeless in games of chance. Omin is also often accused of being one of the Masked Lords of Waterdeep, though this bit of fancy earns little more than a chuckle in response. And even if the rumor were true, Omin would never leverage such a position for greater financial gain and power. Because that would be wrong...

```statblock
"name": "Omin Dran (AI)"
"size": "Medium"
"type": "humanoid"
"subtype": "half-elf"
"alignment": "Lawful Neutral"
"ac": !!int "18"
"ac_class": "[plate armor](Mechanics/items/plate-armor.md)"
"hp": !!int "65"
"hit_dice": "10d8 + 20"
"stats":
- !!int "16"
- !!int "8"
- !!int "14"
- !!int "11"
- !!int "18"
- !!int "12"
"speed": "30 ft."
"saves":
  "Charisma": !!int "4"
  "Wisdom": !!int "7"
"skillsaves":
  "Medicine": !!int "7"
  "Intimidation": !!int "4"
  "Deception": !!int "4"
  "Insight": !!int "7"
  "Perception": !!int "7"
  "Persuasion": !!int "4"
"senses": "darkvision 60 ft., passive Perception 17"
"languages": "Common, Dwarvish, Elvish, Goblin"
"cr": "5"
"traits":
- "desc": "Omin is a 9th-level spellcaster. His spellcasting ability is Wisdom (spell\
    \ save DC 15, +7 to hit with spell attacks). He has the following cleric spells\
    \ prepared:\n\nCantrips (at will): [guidance](Mechanics/spells/guidance.md),\
    \ [sacred flame](Mechanics/spells/sacred-flame.md), [spare the dying](Mechanics/spells/spare-the-dying.md),\
    \ [thaumaturgy](Mechanics/spells/thaumaturgy.md)\n\n1st level (4 slots): [bless](Mechanics/spells/bless.md),\
    \ [command](Mechanics/spells/command.md), [divine favor](Mechanics/spells/divine-favor.md),\
    \ [shield of faith](Mechanics/spells/shield-of-faith.md)\n\n2nd level (3 slots):\
    \ [enhance ability](Mechanics/spells/enhance-ability.md), [hold person](Mechanics/spells/hold-person.md),\
    \ [magic weapon](Mechanics/spells/magic-weapon.md), [silence](Mechanics/spells/silence.md),\
    \ [spiritual weapon](Mechanics/spells/spiritual-weapon.md)\n\n3rd level (3 slots):\
    \ [beacon of hope](Mechanics/spells/beacon-of-hope.md), [crusader's mantle](Mechanics/spells/crusaders-mantle.md),\
    \ [dispel magic](Mechanics/spells/dispel-magic.md), [mass healing word](Mechanics/spells/mass-healing-word.md),\
    \ [spirit guardians](Mechanics/spells/spirit-guardians.md)\n\n4th level (3 slots):\
    \ [death ward](Mechanics/spells/death-ward.md), [freedom of movement](Mechanics/spells/freedom-of-movement.md),\
    \ [locate creature](Mechanics/spells/locate-creature.md), [stoneskin](Mechanics/spells/stoneskin.md)\n\
    \n5th level (1 slots): [dispel evil and good](Mechanics/spells/dispel-evil-and-good.md),\
    \ [flame strike](Mechanics/spells/flame-strike.md), [hold monster](Mechanics/spells/hold-monster.md),\
    \ [greater restoration](Mechanics/spells/greater-restoration.md), [legend lore](Mechanics/spells/legend-lore.md)"
  "name": "Spellcasting"
- "desc": "Once on each of his turns when he hits a creature with a weapon attack,\
    \ Omin can cause the attack to deal an extra 4 (1d8) damage of the same type\
    \ dealt by the weapon."
  "name": "Divine Strike"
- "desc": "Omin has advantage on saving throws against being [charmed](Mechanics/Rules/conditions.md#Charmed),\
    \ and magic can't put him to sleep."
  "name": "Fey Ancestry"
"actions":
- "desc": "Omin makes two attacks with his maul."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 10\
    \ (2d6 + 3) bludgeoning damage."
  "name": "Maul"
"reactions":
- "desc": "When a creature within 30 feet of Omin makes an attack roll, but before\
    \ learning whether it hits or misses, Omin can grant the creature a +10 bonus\
    \ to that roll."
  "name": "War God's Blessing (Recharges after a Short or Long Rest)"
"source":
- "AI"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/AI/Omin%20Dran.webp"
```
^statblock