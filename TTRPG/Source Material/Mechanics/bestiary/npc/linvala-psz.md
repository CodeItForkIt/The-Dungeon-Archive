---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/psz
- monster/cr/16
- monster/size/large
- monster/type/celestial
statblock: inline
aliases: ["Linvala"]
---
# [Linvala](Mechanics\bestiary\npc/linvala-psz.md)
*Source: Plane Shift: Zendikar p. 21*  

The angels of Zendikar are living manifestations of white mana, and they embody its inherent tendencies toward morality and order. Peace and harmony are their goals, though they are more concerned with reestablishing the natural order of the plane than with interfering in disputes between the lowly mortal races. Angels appear similar to female humans possessing two, four, or six feathered wings. Their eyes glow with inner light, and glowing golden rings surround their heads—usually positioned to cover their eyes.

Zendikar's people consider the angels to be aloof but benevolent. Their resistance to the Eldrazi broods in the ancient past is vaguely remembered in the myths of the humans, kor, and merfolk. Humans in particular venerate angels as divine protectors because of those myths.

You can represent most angels in Zendikar using the [deva](Mechanics/bestiary/celestial/deva.md) in the Monster Manual. For unique or more powerful angels, you can use the [planetar](Mechanics/bestiary/celestial/planetar.md) or [solar](Mechanics/bestiary/celestial/solar.md) instead. Perhaps [Linvala](Mechanics/bestiary/npc/linvala-psz.md) is a [planetar](Mechanics/bestiary/celestial/planetar.md) and [Iona](Mechanics/bestiary/npc/iona-psz.md) is a [solar](Mechanics/bestiary/celestial/solar.md).

```statblock
"name": "Linvala (PSZ)"
"size": "Large"
"type": "celestial"
"alignment": "Lawful Good"
"ac": !!int "19"
"ac_class": "natural armor"
"hp": !!int "200"
"hit_dice": "16d10 + 112"
"stats":
- !!int "24"
- !!int "20"
- !!int "24"
- !!int "19"
- !!int "22"
- !!int "25"
"speed": "40 ft., fly 120 ft."
"saves":
  "Charisma": !!int "12"
  "Wisdom": !!int "11"
  "Constitution": !!int "12"
"skillsaves":
  "Perception": !!int "11"
"damage_resistances": "radiant; bludgeoning, piercing, slashing from nonmagical attacks"
"condition_immunities": "[charmed](Mechanics/Rules/conditions.md#Charmed), [exhaustion](Mechanics/Rules/conditions.md#Exhaustion),\
  \ [frightened](Mechanics/Rules/conditions.md#Frightened)"
"senses": "truesight 120 ft., passive Perception 21"
"languages": "all, telepathy 120 ft."
"cr": "16"
"traits":
- "desc": "Linvala's spellcasting ability is Charisma (spell save DC 20). Linvala\
    \ can innately cast the following spells, requiring no material components:\n\n\
    At will: [detect evil and good](Mechanics/spells/detect-evil-and-good.md),\
    \ [invisibility](Mechanics/spells/invisibility.md) (self only)\n\n1/day each:\
    \ [commune](Mechanics/spells/commune.md), [control weather](Mechanics/spells/control-weather.md),\
    \ [insect plague](Mechanics/spells/insect-plague.md)\n\n3/day each: [blade\
    \ barrier](Mechanics/spells/blade-barrier.md), [dispel evil and good](Mechanics/spells/dispel-evil-and-good.md),\
    \ [flame strike](Mechanics/spells/flame-strike.md), [raise dead](Mechanics/spells/raise-dead.md)"
  "name": "Innate Spellcasting"
- "desc": "Linvala's weapon attacks are magical. When Linvala hits with any weapon,\
    \ the weapon deals an extra 5d8 radiant damage (included in the attack)."
  "name": "Angelic Weapons"
- "desc": "Linvala knows if it hears a lie."
  "name": "Divine Awareness"
- "desc": "Linvala has advantage on saving throws against spells and other magical\
    \ effects."
  "name": "Magic Resistance"
"actions":
- "desc": "Linvala makes two melee attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +12 to hit, reach 5 ft., one target. Hit: 21\
    \ (4d6 + 7) slashing damage plus 22 (5d8) radiant damage."
  "name": "Greatsword"
- "desc": "Linvala touches another creature. The target magically regains 30 (6d8\
    \ + 3) hit points and is freed from any curse, disease, poison, blindness, or\
    \ deafness."
  "name": "Healing Touch (4/Day)"
"source":
- "PSZ"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/PSZ/Linvala.webp"
```
^statblock