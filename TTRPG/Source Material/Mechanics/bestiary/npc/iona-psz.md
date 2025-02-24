---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/psz
- monster/cr/21
- monster/size/large
- monster/type/celestial
statblock: inline
aliases: ["Iona"]
---
# [Iona](Mechanics\bestiary\npc/iona-psz.md)
*Source: Plane Shift: Zendikar p. 21*  

The angels of Zendikar are living manifestations of white mana, and they embody its inherent tendencies toward morality and order. Peace and harmony are their goals, though they are more concerned with reestablishing the natural order of the plane than with interfering in disputes between the lowly mortal races. Angels appear similar to female humans possessing two, four, or six feathered wings. Their eyes glow with inner light, and glowing golden rings surround their heads—usually positioned to cover their eyes.

Zendikar's people consider the angels to be aloof but benevolent. Their resistance to the Eldrazi broods in the ancient past is vaguely remembered in the myths of the humans, kor, and merfolk. Humans in particular venerate angels as divine protectors because of those myths.

You can represent most angels in Zendikar using the [deva](Mechanics/bestiary/celestial/deva.md) in the Monster Manual. For unique or more powerful angels, you can use the [planetar](Mechanics/bestiary/celestial/planetar.md) or [solar](Mechanics/bestiary/celestial/solar.md) instead. Perhaps [Linvala](Mechanics/bestiary/npc/linvala-psz.md) is a [planetar](Mechanics/bestiary/celestial/planetar.md) and [Iona](Mechanics/bestiary/npc/iona-psz.md) is a [solar](Mechanics/bestiary/celestial/solar.md).

```statblock
"name": "Iona (PSZ)"
"size": "Large"
"type": "celestial"
"alignment": "Lawful Good"
"ac": !!int "21"
"ac_class": "natural armor"
"hp": !!int "243"
"hit_dice": "18d10 + 144"
"stats":
- !!int "26"
- !!int "22"
- !!int "26"
- !!int "25"
- !!int "25"
- !!int "30"
"speed": "50 ft., fly 150 ft."
"saves":
  "Charisma": !!int "17"
  "Wisdom": !!int "14"
  "Intelligence": !!int "14"
"skillsaves":
  "Perception": !!int "14"
"damage_resistances": "radiant; bludgeoning, piercing, slashing from nonmagical attacks"
"damage_immunities": "necrotic, poison"
"condition_immunities": "[charmed](Mechanics/Rules/conditions.md#Charmed), [exhaustion](Mechanics/Rules/conditions.md#Exhaustion),\
  \ [frightened](Mechanics/Rules/conditions.md#Frightened), [poisoned](Mechanics/Rules/conditions.md#Poisoned)"
"senses": "truesight 120 ft., passive Perception 24"
"languages": "all, telepathy 120 ft."
"cr": "21"
"traits":
- "desc": "Iona's spellcasting ability is Charisma (spell save DC 25). It can innately\
    \ cast the following spells, requiring no material components:\n\nAt will:\
    \ [detect evil and good](Mechanics/spells/detect-evil-and-good.md), [invisibility](Mechanics/spells/invisibility.md)\
    \ (self only)\n\n1/day each: [commune](Mechanics/spells/commune.md), [control\
    \ weather](Mechanics/spells/control-weather.md)\n\n3/day each: [blade barrier](Mechanics/spells/blade-barrier.md),\
    \ [dispel evil and good](Mechanics/spells/dispel-evil-and-good.md), [resurrection](Mechanics/spells/resurrection.md)"
  "name": "Innate Spellcasting"
- "desc": "Iona's weapon attacks are magical. When Iona hits with any weapon, the\
    \ weapon deals an extra 6d8 radiant damage (included in the attack)."
  "name": "Angelic Weapons"
- "desc": "Iona knows if it hears a lie."
  "name": "Divine Awareness"
- "desc": "Iona has advantage on saving throws against spells and other magical effects."
  "name": "Magic Resistance"
"actions":
- "desc": "Iona makes two greatsword attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +15 to hit, reach 5 ft., one target. Hit: 22\
    \ (4d6 + 8) slashing damage plus 27 (6d8) radiant damage."
  "name": "Greatsword"
- "desc": "Ranged Weapon Attack: +13 to hit, range 150/600 ft., one target. Hit:\
    \ 15 (2d8 + 6) piercing damage plus 27 (6d8) radiant damage. If the target\
    \ is a creature that has 100 hit points or fewer, it must succeed on a DC 15 Constitution\
    \ saving throw or die."
  "name": "Slaying Longbow"
- "desc": "Iona releases its greatsword to hover magically in an unoccupied space\
    \ within 5 feet of it. If Iona can see the sword, Iona can mentally command it\
    \ as a bonus action to fly up to 50 feet and either make one attack against a\
    \ target or return to Iona's hands. If the hovering sword is targeted by any effect,\
    \ Iona is considered to be holding it. The hovering sword falls if Iona dies."
  "name": "Flying Sword"
- "desc": "Iona touches another creature. The target magically regains 40 (8d8 +\
    \ 4) hit points and is freed from any curse, disease, poison, blindness, or deafness."
  "name": "Healing Touch (4/Day)"
"legendary_actions":
- "desc": "Iona magically teleports, along with any equipment it is wearing or carrying,\
    \ up to 120 feet to an unoccupied space it can see."
  "name": "Teleport"
- "desc": "Iona emits magical, divine energy. Each creature of its choice in a 10-foot\
    \ radius must make a DC 23 Dexterity saving throw, taking 14 (4d6) fire damage\
    \ plus 14 (4d6) radiant damage on a failed save, or half as much damage on a\
    \ successful one."
  "name": "Searing Burst (Costs 2 Actions)"
- "desc": "Iona targets one creature it can see within 30 feet of it. If the target\
    \ can see it, the target must succeed on a DC 15 Constitution saving throw or\
    \ be [blinded](Mechanics/Rules/conditions.md#Blinded) until magic such as the\
    \ [lesser restoration](Mechanics/spells/lesser-restoration.md) spell removes the\
    \ blindness."
  "name": "Blinding Gaze (Costs 3 Actions)"
"source":
- "PSZ"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/PSZ/Iona.webp"
```
^statblock