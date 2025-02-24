---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/9
- monster/environment/urban
- monster/size/small
- monster/type/humanoid/gnome
statblock: inline
aliases: ["Devilbound Gnome"]
---
# [Devilbound Gnome](Mechanics\bestiary\humanoid/devilbound-gnome-tob1-2023.md)
*Source: Tome of Beasts 1 (2023 Edition) p. 408*  

The devilbound gnome is a gnome spellcaster that has made a magical agreement with a devil for greater power. To ensure loyalty and to further the gnome's power, the devil binds an imp to the gnome's service. This binding changes the gnome, giving it fiendish protections and minor fiendish features, such as glowing eyes, a sulfurous aroma, a forked tongue, or similar. Beyond fulfilling the occasional demand, the devil cares little for what the gnome does with the power, provided the flow of souls doesn't cease.

```statblock
"name": "Devilbound Gnome (ToB1-2023)"
"size": "Small"
"type": "humanoid"
"subtype": "gnome"
"alignment": "Any Evil alignment"
"ac": !!int "17"
"ac_class": "infernal blessing"
"hp": !!int "104"
"hit_dice": "19d6 + 38"
"stats":
- !!int "10"
- !!int "14"
- !!int "15"
- !!int "16"
- !!int "12"
- !!int "21"
"speed": "25 ft."
"saves":
  "Charisma": !!int "9"
  "Intelligence": !!int "7"
  "Constitution": !!int "6"
"skillsaves":
  "Deception": !!int "9"
  "History": !!int "7"
  "Arcana": !!int "7"
  "Persuasion": !!int "9"
"damage_resistances": "cold; fire; poison; bludgeoning, piercing, slashing from nonmagical\
  \ attacks that aren't silvered"
"condition_immunities": "[poisoned](Mechanics/Rules/conditions.md#Poisoned)"
"senses": "darkvision 60 ft., passive Perception 11"
"languages": "Common, Gnomish, Infernal"
"cr": "9"
"traits":
- "desc": "The devilbound gnome casts one of the following spells, requiring no material\
    \ components and using Charisma as the spellcasting ability (spell save DC 17):\n\
    \nAt will: [detect magic](Mechanics/spells/detect-magic.md), [minor illusion](Mechanics/spells/minor-illusion.md),\
    \ [prestidigitation](Mechanics/spells/prestidigitation.md)\n\n1/day each:\
    \ [fly](Mechanics/spells/fly.md), [haste](Mechanics/spells/haste.md), [wall of\
    \ fire](Mechanics/spells/wall-of-fire.md)\n\n3/day each: [command](Mechanics/spells/command.md),\
    \ [dimension door](Mechanics/spells/dimension-door.md), [invisibility](Mechanics/spells/invisibility.md)"
  "name": "Spellcasting"
- "desc": "While the devilbound gnome is conscious and wearing no armor and wielding\
    \ no shield, it adds its Charisma modifier to its AC (included above) and saving\
    \ throws. In addition, magical darkness doesn't impede the gnome's darkvision."
  "name": "Infernal Blessing"
- "desc": "The devilbound gnome is magically bound to an imp. The imp acts as an ally\
    \ of the gnome's, obeying its spoken commands. The gnome can perceive through\
    \ the imp's senses, speak through its mouth, and communicate with it telepathically\
    \ even if the two aren't on the same plane of existence."
  "name": "Infernal Bond"
- "desc": "The devilbound gnome has advantage on saving throws against spells and\
    \ other magical effects."
  "name": "Magic Resistance"
"actions":
- "desc": "The devilbound gnome makes three Hellish Blast attacks. It can replace\
    \ one attack with a use of Spellcasting."
  "name": "Multiattack"
- "desc": "Melee or Ranged Spell Attack: +9 to hit, reach 5 ft. or range 120 ft.,\
    \ one target. Hit: 12 (2d6 + 5) fire damage plus 9 (2d8) poison damage."
  "name": "Hellish Blast"
- "desc": "The devilbound gnome magically calls 1d4 devils with a challenge rating\
    \ of 4 or lower, or it calls 1 devil with a challenge rating of 6 or lower. The\
    \ called Fiends arrive in 1d4 rounds, acting as allies of the gnome and obeying\
    \ its spoken commands. The Fiends remain for 1 hour, until the gnome dies, or\
    \ until the gnome dismisses them as a bonus action."
  "name": "Hell's Servitors (1/Day)"
- "desc": "The devilbound gnome sends one creature it can see within 60 feet of it\
    \ hurling through Hell. The target must make a DC 17 Wisdom saving throw. On a\
    \ success, the target takes 35 (10d6) fire damage as Hell pulls on the creature.\
    \ On a failure, the target is [incapacitated](Mechanics/Rules/conditions.md#Incapacitated)\
    \ and disappears, as it takes a quick trip through the nightmarish landscapes\
    \ of Hell. At the end of the gnome's next turn, the target reappears in the space\
    \ it previously occupied, or the nearest unoccupied space, and takes 55 (10d10)\
    \ psychic damage."
  "name": "To Hell and Back (1/Day)"
"reactions":
- "desc": "When the devilbound gnome is reduced to 0 hp, it can sacrifice a Fiend\
    \ called with the Hell's Servitor's action or sacrifice its bonded imp, preventing\
    \ the damage and killing the chosen Fiend. If the gnome sacrifices its bonded\
    \ imp, it loses its Infernal Blessing and Infernal Bond traits until it receives\
    \ a new imp from its patron devil."
  "name": "Fiendish Sacrifice"
"source":
- "ToB1-2023"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Devilbound%20Gnome.webp"
```
^statblock

## Environment

urban