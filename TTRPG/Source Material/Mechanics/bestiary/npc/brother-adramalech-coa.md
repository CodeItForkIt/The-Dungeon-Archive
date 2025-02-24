---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/coa
- monster/cr/21
- monster/size/medium
- monster/type/fiend/devil
statblock: inline
aliases: ["Brother Adramalech"]
---
# [Brother Adramalech](Mechanics\bestiary\npc/brother-adramalech-coa.md)
*Source: Chains of Asmodeus p. 185*  

```statblock
"name": "Brother Adramalech (CoA)"
"size": "Medium"
"type": "fiend"
"subtype": "devil"
"alignment": "Lawful Evil"
"ac": !!int "19"
"ac_class": "natural armor"
"hp": !!int "212"
"hit_dice": "25d8 + 100"
"stats":
- !!int "14"
- !!int "16"
- !!int "18"
- !!int "25"
- !!int "25"
- !!int "25"
"speed": "30 ft."
"saves":
  "Charisma": !!int "14"
  "Wisdom": !!int "14"
  "Intelligence": !!int "14"
"skillsaves":
  "Intimidation": !!int "14"
  "Deception": !!int "21"
  "Religion": !!int "14"
  "Insight": !!int "14"
  "Arcana": !!int "14"
  "Persuasion": !!int "21"
"damage_resistances": "cold; bludgeoning, piercing, slashing from nonmagical attacks\
  \ that aren't silvered"
"damage_immunities": "fire, poison"
"condition_immunities": "[charmed](Mechanics/Rules/conditions.md#Charmed), [poisoned](Mechanics/Rules/conditions.md#Poisoned)"
"senses": "darkvision 120 ft., passive Perception 17"
"languages": "Celestial, Common, Draconic, Infernal, telepathy 120 ft."
"cr": "21"
"traits":
- "desc": "Magical darkness doesn't impede Adramalech's darkvision."
  "name": "Devil's Sight"
- "desc": "Adramalech has advantage on saving throws against spells and other magical\
    \ effects."
  "name": "Magic Resistance"
- "desc": "If Adramalech is reduced to 0 hit points while Brother Morax still lives,\
    \ Adramalech regenerates 50 hit points at the start of his next turn. This regeneration\
    \ is interrupted if Brother Morax is reduced to 0 hit points before the start\
    \ of Adramalech's turn."
  "name": "Unbreakable Bond"
"actions":
- "desc": "Adramalech makes four attacks using Mental"
  "name": "Multiattack"
- "desc": "He can replace one of the attacks with Brain Freeze or Cone of Madness\
    \ (if available)."
  "name": "Barrage"
- "desc": "Melee or Ranged Weapon Attack: +14 to hit, reach 5 ft. or range 60/120\
    \ ft., one target. Hit: 25 (4d8 + 7) psychic damage."
  "name": "Mental Barrage"
- "desc": "Adramalech attempts to overload the brain of a creature he can see within\
    \ 60 feet of him. The target must make a DC 22 Intelligence saving throw, taking\
    \ 22 (4d10) psychic damage on a failed save, or half as much on a successful\
    \ one. Creatures that fail the saving throw have the [stunned](Mechanics/Rules/conditions.md#Stunned)\
    \ condition for up to 1 minute. A [stunned](Mechanics/Rules/conditions.md#Stunned)\
    \ creature may repeat the saving throw at the end of each of their turns, ending\
    \ the effect on a success."
  "name": "Brain Freeze"
- "desc": "Adramalech unleashes visions in a 30-foot cone in front of him. All creatures\
    \ in the cone must make a DC 22 Wisdom saving throw, taking 17 (5d6) psychic\
    \ damage on a failed save, or half as much on a successful one. For up to 1 minute,\
    \ creatures that failed the save can't take reactions and each turn must use their\
    \ action to make a melee attack against the nearest creature. Creatures may repeat\
    \ the saving throw at the end of each of their turns, ending the effect on a success."
  "name": "Cone of Madness (Recharge 4-6)"
"bonus_actions":
- "desc": "Adramalech targets a creature, reading its thoughts and creating an effigy\
    \ of a loved one in an unoccupied space that he can see within 60 feet of Adramalech.\
    \ The effigy has 55 (10d10) hit points, an AC of 10, and ability scores of 10.\
    \ It occasionally shouts for help, but otherwise takes no actions. While the effigy\
    \ is alive, the target creature has disadvantage on attacks targeting Adramalech\
    \ and any time the effigy takes damage, the target creature also takes an equal\
    \ amount as psychic damage. If the effigy is killed, the target creature gains\
    \ a level of [exhaustion](Mechanics/Rules/conditions.md#Exhaustion). If Adramalech\
    \ is killed while effigies exist, they harmlessly melt into a warm sludge."
  "name": "Conjure Effigy (Recharge 6)"
"legendary_actions":
- "desc": "Adramalech makes a Mental Barrage attack."
  "name": "Barrage"
- "desc": "Adramalech fortifies the mind of a creature he can see within 60 feet of\
    \ him, or himself. The target benefits as if the [Greater Restoration](Mechanics/spells/greater-restoration.md)\
    \ spell has been cast on them and is granted resistance to psychic damage until\
    \ the end of Adramalech's next turn."
  "name": "Mental Blocker"
"source":
- "CoA"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/CoA/Brother%20Adramalech.webp"
```
^statblock