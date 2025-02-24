---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/mpp
- monster/cr/11
- monster/size/medium
- monster/type/fiend
statblock: inline
aliases: ["Farastu Demodand"]
---
# [Farastu Demodand](Mechanics\bestiary\fiend/farastu-demodand-mpp.md)
*Source: Morte's Planar Parade p. 26, Sigil and the Outlands, Turn of Fortune's Wheel*  

Farastus, also known as tarry demodands, are the least of the demodands. These violent Fiends ooze thick, sticky tar that sticks to anything it touches. Arrogant and cruel, farastus delight in tormenting those weaker than themselves. Due to their sharp senses and vicious streaks, farastus sometimes work as hunters that track down those who escape Carceri.

## Demodands

Demodands, also called gehreleths, are Fiends from the Tarterian Depths of Carceri. Cast into the prison plane long ago for forgotten transgressions, these bitter, wicked creatures have appointed themselves the jailers of the plane. Demodands viciously defend the few known portals that lead out of Carceri and ruthlessly torment other creatures trapped there.

Demodands that manage to leave Carceri know they're doomed to return; a demodand that dies outside Carceri re-forms there in a torturous process that takes `2d20` days. Even those who survive on other planes find themselves eventually dragged back, pulled by some planar tether.

```statblock
"name": "Farastu Demodand (MPP)"
"size": "Medium"
"type": "fiend"
"alignment": "typically  Neutral Evil"
"ac": !!int "17"
"ac_class": "natural armor"
"hp": !!int "195"
"hit_dice": "26d8 + 78"
"stats":
- !!int "20"
- !!int "13"
- !!int "16"
- !!int "8"
- !!int "12"
- !!int "16"
"speed": "40 ft., climb 40 ft."
"saves":
  "Dexterity": !!int "5"
  "Wisdom": !!int "5"
"skillsaves":
  "Stealth": !!int "5"
  "Perception": !!int "9"
  "Survival": !!int "5"
"damage_resistances": "cold, fire"
"damage_immunities": "acid, poison"
"condition_immunities": "[paralyzed](Mechanics/Rules/conditions.md#Paralyzed), [poisoned](Mechanics/Rules/conditions.md#Poisoned),\
  \ [restrained](Mechanics/Rules/conditions.md#Restrained)"
"senses": "darkvision 120 ft., passive Perception 19"
"languages": "Abyssal, Demodand, telepathy 120 ft."
"cr": "11"
"traits":
- "desc": "The farastu casts one of the following spells, requiring no material components\
    \ and using Charisma as the spellcasting ability:\n\nAt will: [invisibility](Mechanics/spells/invisibility.md)\
    \ (self only)\n\n1/day each: [dispel magic](Mechanics/spells/dispel-magic.md),\
    \ [fog cloud](Mechanics/spells/fog-cloud.md)"
  "name": "Spellcasting"
- "desc": "The farastu ignores difficult terrain, and magical effects can't reduce\
    \ its speed. It can spend 5 feet of movement to automatically remove the [grappled](Mechanics/Rules/conditions.md#Grappled)\
    \ condition from itself."
  "name": "Boundless Movement"
- "desc": "The farastu has advantage on saving throws against spells and other magical\
    \ effects."
  "name": "Magic Resistance"
- "desc": "The farastu can climb difficult surfaces, including upside down on ceilings,\
    \ without an ability check."
  "name": "Spider Climb"
"actions":
- "desc": "The farastu makes two Claw attacks and one Bite attack."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +9 to hit, reach 5 ft., one target. Hit: 16\
    \ (2d10 + 5) slashing damage. If the target is a Large or smaller creature,\
    \ it has the [grappled](Mechanics/Rules/conditions.md#Grappled) condition (escape\
    \ DC 15, with disadvantage). The farastu has two claws, each of which can grapple\
    \ one creature."
  "name": "Claw"
- "desc": "Melee Weapon Attack: +9 to hit (with advantage against a creature the\
    \ farastu is grappling), reach 5 ft., one target. Hit: 12 (2d6 + 5) piercing\
    \ damage plus 24 (7d6) acid damage."
  "name": "Bite"
- "desc": "The farastu has a 40 percent chance of summoning 1 farastu demodand. A\
    \ summoned demodand appears in an unoccupied space within 60 feet of the farastu,\
    \ acts as an ally of the farastu, and can't summon other demodands. It remains\
    \ for 1 minute, until it or the farastu dies, or until the farastu dismisses it\
    \ as an action."
  "name": "Summon Demodand (1/Day)"
"source":
- "MPP"
- "SatO"
- "ToFW"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/MPP/Farastu%20Demodand.webp"
```
^statblock