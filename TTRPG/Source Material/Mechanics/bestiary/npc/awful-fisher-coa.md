---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/coa
- monster/cr/18
- monster/size/gargantuan
- monster/type/monstrosity
statblock: inline
aliases: ["Awful Fisher"]
---
# [Awful Fisher](Mechanics\bestiary\npc/awful-fisher-coa.md)
*Source: Chains of Asmodeus p. 133*  

```statblock
"name": "Awful Fisher (CoA)"
"size": "Gargantuan"
"type": "monstrosity"
"alignment": "Unaligned"
"ac": !!int "17"
"ac_class": "natural armor"
"hp": !!int "348"
"hit_dice": "24d20 + 96"
"stats":
- !!int "23"
- !!int "16"
- !!int "18"
- !!int "5"
- !!int "10"
- !!int "8"
"speed": "30 ft., climb 30 ft."
"saves":
  "Dexterity": !!int "9"
  "Constitution": !!int "10"
"skillsaves":
  "Stealth": !!int "9"
  "Perception": !!int "6"
  "Survival": !!int "6"
"senses": "blindsight 120 ft., darkvision 60 ft., passive Perception 16"
"languages": ""
"cr": "18"
"traits":
- "desc": "If the fisher drops below 200 hit points, it gains vulnerability to fire\
    \ damage."
  "name": "Flammable Blood"
- "desc": "If the fisher fails a saving throw, it can choose to succeed instead."
  "name": "Legendary Resistance (3/Day)"
- "desc": "The fisher can climb difficult surfaces, including upside down on ceilings,\
    \ without needing to make an ability check."
  "name": "Spider Climb"
"actions":
- "desc": "The fisher makes two Claw attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +12 to hit, reach 15 ft., one target. Hit: 20\
    \ (4d6 + 6) slashing damage."
  "name": "Claw"
- "desc": "One Huge or smaller creature [grappled](Mechanics/Rules/conditions.md#Grappled)\
    \ by the fisher's Adhesive Filament must make a DC 20 Strength saving throw. On\
    \ a failed save, the target is pulled into an unoccupied space within 5 feet of\
    \ the fisher, and the fisher makes one Claw attack against it with advantage.\
    \ Anyone else who was attached to the filament is released. Until the grapple\
    \ ends on the target, the fisher can't use Adhesive Filament."
  "name": "Retract Filament"
"bonus_actions":
- "desc": "The fisher extends a sticky filament up to 90 feet in a straight line,\
    \ which adheres to anything that touches it. A Huge or smaller creature the filament\
    \ adheres to has the [grappled](Mechanics/Rules/conditions.md#Grappled) condition\
    \ (escape DC 20), and ability checks made to escape this grapple have disadvantage.\
    \ The filament can be attacked (AC 16; 25 hit points; immunity to poison and psychic\
    \ damage). A weapon that fails to sever it becomes stuck to it, requiring an action\
    \ and a successful DC 20 Strength check to pull free. Destroying the filament\
    \ deals no damage to the fisher. The filament crumbles away if the fisher takes\
    \ this bonus action again."
  "name": "Adhesive Filament"
"legendary_actions":
- "desc": "The fisher makes a Claw attack."
  "name": "Slash"
- "desc": "The fisher uses Adhesive Filament."
  "name": "Spit"
- "desc": "The fisher uses Retract Filament."
  "name": "Reel In"
"source":
- "CoA"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/CoA/Awful%20Fisher.webp"
```
^statblock