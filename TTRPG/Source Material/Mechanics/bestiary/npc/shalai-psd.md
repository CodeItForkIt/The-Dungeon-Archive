---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/psd
- monster/cr/21
- monster/size/large
- monster/type/celestial
statblock: inline
aliases: ["Shalai"]
---
# [Shalai](Mechanics\bestiary\npc/shalai-psd.md)
*Source: Plane Shift: Dominaria p. 9*  

The most visible and recognized symbols of the Church of Serra are her angels—both those that were personally created by Serra and those that appeared spontaneously in the Cathedral at Sursi. Some angels live contemplative lives within the cathedrals, but most are active defenders of the faith, protecting Serra's people across the world. Powerful angels often take responsibility for large regions of the world. Lyra, for example, stands as the protector of Benalia, and Shalai plays a similar role in Llanowar. Serra's angels are believed to hear prayers addressed to Serra, and they have an uncanny tendency to arrive exactly when they are needed.

Any of the angels in the "Monster Manual" can serve as [Serra angels](Mechanics/bestiary/celestial/serra-angel-psd.md). The [deva](Mechanics/bestiary/celestial/deva.md) represents the most common angels, while the [planetar](Mechanics/bestiary/celestial/planetar.md) and [solar](Mechanics/bestiary/celestial/solar.md) are appropriate for powerful angels such as [Lyra](Mechanics/bestiary/npc/lyra-psd.md) and [Shalai](Mechanics/bestiary/npc/shalai-psd.md).

```statblock
"name": "Shalai (PSD)"
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
- "desc": "Shalai's spellcasting ability is Charisma (spell save DC 25). It can innately\
    \ cast the following spells, requiring no material components:\n\nAt will:\
    \ [detect evil and good](Mechanics/spells/detect-evil-and-good.md), [invisibility](Mechanics/spells/invisibility.md)\
    \ (self only)\n\n1/day each: [commune](Mechanics/spells/commune.md), [control\
    \ weather](Mechanics/spells/control-weather.md)\n\n3/day each: [blade barrier](Mechanics/spells/blade-barrier.md),\
    \ [dispel evil and good](Mechanics/spells/dispel-evil-and-good.md), [resurrection](Mechanics/spells/resurrection.md)"
  "name": "Innate Spellcasting"
- "desc": "Shalai's weapon attacks are magical. When Shalai hits with any weapon,\
    \ the weapon deals an extra 6d8 radiant damage (included in the attack)."
  "name": "Angelic Weapons"
- "desc": "Shalai knows if it hears a lie."
  "name": "Divine Awareness"
- "desc": "Shalai has advantage on saving throws against spells and other magical\
    \ effects."
  "name": "Magic Resistance"
"actions":
- "desc": "Shalai makes two greatsword attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +15 to hit, reach 5 ft., one target. Hit: 22\
    \ (4d6 + 8) slashing damage plus 27 (6d8) radiant damage."
  "name": "Greatsword"
- "desc": "Ranged Weapon Attack: +13 to hit, range 150/600 ft., one target. Hit:\
    \ 15 (2d8 + 6) piercing damage plus 27 (6d8) radiant damage. If the target\
    \ is a creature that has 100 hit points or fewer, it must succeed on a DC 15 Constitution\
    \ saving throw or die."
  "name": "Slaying Longbow"
- "desc": "Shalai releases its greatsword to hover magically in an unoccupied space\
    \ within 5 feet of it. If Shalai can see the sword, Shalai can mentally command\
    \ it as a bonus action to fly up to 50 feet and either make one attack against\
    \ a target or return to Shalai's hands. If the hovering sword is targeted by any\
    \ effect, Shalai is considered to be holding it. The hovering sword falls if Shalai\
    \ dies."
  "name": "Flying Sword"
- "desc": "Shalai touches another creature. The target magically regains 40 (8d8\
    \ + 4) hit points and is freed from any curse, disease, poison, blindness, or\
    \ deafness."
  "name": "Healing Touch (4/Day)"
"legendary_actions":
- "desc": "Shalai magically teleports, along with any equipment it is wearing or carrying,\
    \ up to 120 feet to an unoccupied space it can see."
  "name": "Teleport"
- "desc": "Shalai emits magical, divine energy. Each creature of its choice in a 10-foot\
    \ radius must make a DC 23 Dexterity saving throw, taking 14 (4d6) fire damage\
    \ plus 14 (4d6) radiant damage on a failed save, or half as much damage on a\
    \ successful one."
  "name": "Searing Burst (Costs 2 Actions)"
- "desc": "Shalai targets one creature it can see within 30 feet of it. If the target\
    \ can see it, the target must succeed on a DC 15 Constitution saving throw or\
    \ be [blinded](Mechanics/Rules/conditions.md#Blinded) until magic such as the\
    \ [lesser restoration](Mechanics/spells/lesser-restoration.md) spell removes the\
    \ blindness."
  "name": "Blinding Gaze (Costs 3 Actions)"
"source":
- "PSD"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/PSD/Shalai.webp"
```
^statblock