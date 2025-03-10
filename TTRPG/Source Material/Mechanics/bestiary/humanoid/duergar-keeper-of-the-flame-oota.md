---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/oota
- monster/cr/2
- monster/size/medium
- monster/type/humanoid/dwarf
statblock: inline
aliases: ["Duergar Keeper of the Flame"]
---
# [Duergar Keeper of the Flame](Mechanics\bestiary\humanoid/duergar-keeper-of-the-flame-oota.md)
*Source: Out of the Abyss p. 226*  

The tyrannical duergar, also known as gray dwarves, dwell in fantastic cities deep in the Underdark. Using ancient dwarven knowledge and myriad slaves, they work tirelessly to expand their subterranean kingdoms.

Most duergar (including females) are bald and have ashen gray skin. They wear drab clothing designed to blend in with stone, along with simple jewelry that reflects their severe and utilitarian demeanor.

## Slaves to Slavers

The duergar were once dwarves, before their greed and endless delving beneath the earth brought them into contact with the mind flayers. Held in captivity for generations by the illithids, the dwarves eventually won their independence with the aid of the evil god Laduguer. Slavery had forever changed them, however, darkening their spirits to make the duergar as evil as the tyrants they had escaped. Despite winning their freedom, duergar are dour, pessimistic, untrusting creatures, always toiling and complaining, with no memory of what it means to be happy or proud. Their craftsmanship and accomplishments endure, yet they are bereft of warmth or artistry.Duergar make war against their dwarven kin and all other subterranean races. They forge alliances when it is convenient, then break those alliances when they have nothing more to gain. They take and hold slaves to toil in the Underdark, regarding them as free labor and crude currency.

## Tough as Stone

Like dwarves, duergar have strong constitutions. Adding to their physical stamina is an incredible mental fortitude resulting from their time as slaves of the illithids. A duergar's mind is a fortress, able to shrug off charms, illusions, and other spells.Born of Darkness. The Underdark is saturated with strange magical power, which the duergar absorbed over generations of imprisonment. A duergar can increase its size and strength for a short time, becoming a powerful ogre-sized warrior. If it faces a foe it can't fight, or when spying on creatures approaching its territory, it can just as easily become [invisible](Mechanics/Rules/conditions.md#Invisible) to slip away into the darkness. Eons spent in the Underdark also sharpened their [darkvision](Mechanics/Rules/senses.md#Darkvision), allowing them to see twice as far as other dwarves. This keen eyesight comes at a cost, however, as a duergar's vision is compromised by sunlight.

## Infernal Master

Asmodeus, Lord of the Nine Hells, has been known to impersonate duergar gods in order to cultivate the evil brimming in the hearts of the gray dwarves. He offers them divine guidance and vengeance against their enemies while urging them on toward greater acts of tyranny, all the while concealing his true identity.

## Duergar Keeper of the Flame

The Keepers of the Flame is a well-respected order of psionic clerics that serves the red dragon Themberchaud in Gracklstugh, and whose members are advisors to the Deepking.

The duergar Keeper of the Flame uses the same statistics as the duergar in the Monster Manual, except that its challenge rating is 2 (450 XP) and it has the following additional features.

### Innate Spellcasting (Psionics)

The Keeper of the Flame's innate spellcasting ability is Wisdom (spell save DC 12). It can innately cast the following spells, requiring no components:

At will: friends, message

3/day: command

### Spellcasting

The Keeper of the Flame is a 3rd-level spellcaster. Its spellcasting ability is Wisdom (spell save DC 12, +4 to hit with spell attacks). The Keeper of the Flame has the following cleric spells prepared:

Cantrips (at will): guidance, mending, sacred flame

1st level (4 slots): bane, inflict wounds, shield of faith

2nd level (2 slots): enhance ability, spiritual weapon

```statblock
"name": "Duergar Keeper of the Flame (OotA)"
"size": "Medium"
"type": "humanoid"
"subtype": "dwarf"
"alignment": "Lawful Evil"
"ac": !!int "16"
"ac_class": "[scale mail](Mechanics/items/scale-mail.md), [shield](Mechanics/items/shield.md)"
"hp": !!int "26"
"hit_dice": "4d8 + 4"
"stats":
- !!int "14"
- !!int "11"
- !!int "14"
- !!int "11"
- !!int "10"
- !!int "9"
"speed": "25 ft."
"damage_resistances": "poison"
"senses": "darkvision 120 ft., passive Perception 10"
"languages": "Dwarvish, Undercommon"
"cr": "2"
"traits":
- "desc": "The Keeper of the Flame's innate spellcasting ability is Wisdom (spell\
    \ save DC 12.) It can innately cast the following spells, requiring no components:\n\
    \nAt will: [friends](Mechanics/spells/friends.md), [message](Mechanics/spells/message.md)\n\
    \n1/day each: [command](Mechanics/spells/command.md)"
  "name": "Innate Spellcasting (Psionics)"
- "desc": "The Keeper of the Flame is a 3rd-level spellcaster. Its spellcasting ability\
    \ is Wisdom (spell save DC 12, +4 to hit with spell attacks). The Keeper of\
    \ the Flame has the following cleric spells prepared:\n\nCantrips (at will):\
    \ [guidance](Mechanics/spells/guidance.md), [mending](Mechanics/spells/mending.md),\
    \ [sacred flame](Mechanics/spells/sacred-flame.md)\n\n1st level (4 slots):\
    \ [bane](Mechanics/spells/bane.md), [inflict wounds](Mechanics/spells/inflict-wounds.md),\
    \ [shield of faith](Mechanics/spells/shield-of-faith.md)\n\n2nd level (2 slots):\
    \ [enhance ability](Mechanics/spells/enhance-ability.md), [spiritual weapon](Mechanics/spells/spiritual-weapon.md)"
  "name": "Spellcasting"
- "desc": "The duergar has advantage on saving throws against poison, spells, and\
    \ illusions, as well as to resist being [charmed](Mechanics/Rules/conditions.md#Charmed)\
    \ or [paralyzed](Mechanics/Rules/conditions.md#Paralyzed)."
  "name": "Duergar Resilience"
- "desc": "While in sunlight, the duergar has disadvantage on attack rolls, as well\
    \ as on Wisdom ([Perception](Mechanics/Rules/skills.md#Perception)) checks that\
    \ rely on sight."
  "name": "Sunlight Sensitivity"
"actions":
- "desc": "For 1 minute, the duergar magically increases in size, along with anything\
    \ it is wearing or carrying. While enlarged, the duergar is Large, doubles its\
    \ damage dice on Strength-based weapon attacks (included in the attacks), and\
    \ makes Strength checks and Strength saving throws with advantage. If the duergar\
    \ lacks the room to become Large, it attains the maximum size possible in the\
    \ space available."
  "name": "Enlarge (Recharges after a Short or Long Rest)"
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 6 (1d8\
    \ + 2) piercing damage, or 11 (2d8 + 2) piercing damage while enlarged."
  "name": "War Pick"
- "desc": "Melee or Ranged Weapon Attack: +4 to hit, reach 5 ft. or range 30/120\
    \ ft., one target. Hit: 5 (1d6 + 2) piercing damage, or 9 (2d6 + 2) piercing\
    \ damage while enlarged."
  "name": "Javelin"
- "desc": "The duergar magically turns [invisible](Mechanics/Rules/conditions.md#Invisible)\
    \ until it attacks, casts a spell, or uses its Enlarge, or until its [concentration](Mechanics/Rules/conditions.md#Concentration)\
    \ is broken, up to 1 hour (as if concentrating on a spell). Any equipment the\
    \ duergar wears or carries is [invisible](Mechanics/Rules/conditions.md#Invisible)\
    \ with it."
  "name": "Invisibility (Recharges after a Short or Long Rest)"
"source":
- "OotA"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/OotA/Duergar%20Keeper%20of%20the%20Flame.webp"
```
^statblock