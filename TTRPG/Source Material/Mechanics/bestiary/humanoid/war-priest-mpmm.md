---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/mpmm
- monster/cr/9
- monster/environment/desert
- monster/environment/urban
- monster/size/medium
- monster/type/humanoid/cleric
statblock: inline
aliases: ["War Priest"]
---
# [War Priest](Mechanics\bestiary\humanoid/war-priest-mpmm.md)
*Source: Mordenkainen Presents: Monsters of the Multiverse p. 254*  

War priests worship deities of war, protection, and strategy. They plan tactics, lead soldiers into battle, confront enemy spellcasters, and tend to casualties. A war priest might command an army or serve as the right hand of a [warlord](Mechanics/bestiary/humanoid/warlord-mpmm.md) (appears in "this book") on the battlefield.

War priests typically adorn themselves with a symbol of their faith. You can roll on the War Priest Holy Symbols table below, or choose one that fits your campaign.

**War Priest Holy Symbols**

`dice: [](war-priest-mpmm.md#^war-priest-holy-symbols)`

| dice: d8 | Holy Symbol |
|----------|-------------|
| 1 | Vial of iridescent liquid |
| 2 | Hilt of a broken sword |
| 3 | Piece of stained glass from a shrine |
| 4 | Clay figurine of a [ki-rin](Mechanics/bestiary/celestial/ki-rin-mpmm.md) or another Celestial |
| 5 | [Torch](Mechanics/items/torch.md) carved so that a hand appears to be holding the flame |
| 6 | Circlet of woven reeds |
| 7 | Scrimshawed bone |
| 8 | Vessel such as a cup, a [jug](Mechanics/items/jug.md), an urn, or an amphora |
^war-priest-holy-symbols

```statblock
"name": "War Priest (MPMM)"
"size": "Medium"
"type": "humanoid"
"subtype": "cleric"
"alignment": "Any alignment"
"ac": !!int "18"
"ac_class": "[plate](Mechanics/items/plate-armor.md)"
"hp": !!int "117"
"hit_dice": "18d8 + 36"
"stats":
- !!int "16"
- !!int "10"
- !!int "14"
- !!int "11"
- !!int "17"
- !!int "13"
"speed": "30 ft."
"saves":
  "Wisdom": !!int "7"
  "Constitution": !!int "6"
"skillsaves":
  "Intimidation": !!int "5"
  "Religion": !!int "4"
"senses": "passive Perception 13"
"languages": "any two languages"
"cr": "9"
"traits":
- "desc": "The war priest casts one of the following spells, using Wisdom as the spellcasting\
    \ ability (spell save DC 15):\n\nAt will: [light](Mechanics/spells/light.md),\
    \ [spare the dying](Mechanics/spells/spare-the-dying.md), [thaumaturgy](Mechanics/spells/thaumaturgy.md)\n\
    \n1/day each: [banishment](Mechanics/spells/banishment.md), [command](Mechanics/spells/command.md),\
    \ [dispel magic](Mechanics/spells/dispel-magic.md), [flame strike](Mechanics/spells/flame-strike.md),\
    \ [guardian of faith](Mechanics/spells/guardian-of-faith.md), [hold person](Mechanics/spells/hold-person.md),\
    \ [lesser restoration](Mechanics/spells/lesser-restoration.md), [revivify](Mechanics/spells/revivify.md)"
  "name": "Spellcasting"
"actions":
- "desc": "The war priest makes two Maul attacks, and it uses Holy Fire."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +7 to hit, reach 5 ft., one target. Hit: 10\
    \ (2d6 + 3) bludgeoning damage  plus Hit: 10 (3d6) radiant damage."
  "name": "Maul"
- "desc": "The war priest targets one creature it can see within 60 feet of it. The\
    \ target must make a DC 15 Wisdom saving throw. On a failed save, the target takes\
    \ 12 (2d8 + 3) radiant damage, and it is [blinded](Mechanics/Rules/conditions.md#Blinded)\
    \ until the start of the war priest's next turn. On a successful save, the target\
    \ takes half as much damage and isn't [blinded](Mechanics/Rules/conditions.md#Blinded)."
  "name": "Holy Fire"
"bonus_actions":
- "desc": "The war priest or one creature of its choice within 60 feet of it regains\
    \ 12 (2d8 + 3) hit points."
  "name": "Healing Light (Recharge 4-6)"
"source":
- "MPMM"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/MPMM/War%20Priest.webp"
```
^statblock

## Environment

desert, urban