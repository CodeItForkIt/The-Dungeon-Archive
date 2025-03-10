---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/pabtso
- monster/cr/5
- monster/size/huge
- monster/type/construct
statblock: inline
aliases: ["Fiendish Auger"]
---
# [Fiendish Auger](Mechanics\bestiary\construct/fiendish-auger-pabtso.md)
*Source: Phandelver and Below: The Shattered Obelisk p. 206*  

A fiendish auger is created when a wicked spirit enters an excavation drill, causing the hulking corkscrew bore to glow brightly with hellfire.

Fueled by the fervent aggression of the evil spirit within, fiendish augers can rapidly churn through solid rock. However, those who employ a fiendish auger must keep a keen eye on the machine. Without careful instruction, a fiendish auger indiscriminately bores through creature and earth alike.

```statblock
"name": "Fiendish Auger (PaBTSO)"
"size": "Huge"
"type": "construct"
"alignment": "typically  Neutral Evil"
"ac": !!int "15"
"ac_class": "natural armor"
"hp": !!int "85"
"hit_dice": "9d12 + 27"
"stats":
- !!int "23"
- !!int "10"
- !!int "17"
- !!int "6"
- !!int "12"
- !!int "5"
"speed": "40 ft., burrow 30 ft."
"damage_immunities": "fire, poison"
"condition_immunities": "[blinded](Mechanics/Rules/conditions.md#Blinded), [charmed](Mechanics/Rules/conditions.md#Charmed),\
  \ [exhaustion](Mechanics/Rules/conditions.md#Exhaustion), [frightened](Mechanics/Rules/conditions.md#Frightened),\
  \ [paralyzed](Mechanics/Rules/conditions.md#Paralyzed), [petrified](Mechanics/Rules/conditions.md#Petrified),\
  \ [poisoned](Mechanics/Rules/conditions.md#Poisoned), [unconscious](Mechanics/Rules/conditions.md#Unconscious)"
"senses": "blindsight 60 ft. (can't see beyond this radius), passive Perception 11"
"languages": ""
"cr": "5"
"traits":
- "desc": "The auger deals double damage to objects and structures."
  "name": "Siege Monster"
- "desc": "The auger can burrow through solid rock at half its burrow speed and leaves\
    \ a 10-foot-diameter tunnel in its wake."
  "name": "Tunneler"
"actions":
- "desc": "Melee Weapon Attack: +9 to hit, reach 5 ft., one target. Hit: 17\
    \ (2d10 + 6) piercing damage plus 7 (2d6) fire damage. If the auger moves\
    \ at least 20 feet in a straight line toward the target immediately before the\
    \ hit, the target takes an additional 11 (2d10) piercing damage, and if the\
    \ target is a creature, it must succeed on a DC 17 Strength saving throw or have\
    \ the [prone](Mechanics/Rules/conditions.md#Prone) condition."
  "name": "Flaming Drill"
"bonus_actions":
- "desc": "The auger releases an intense burst of heat in a 30-foot-radius sphere\
    \ centered on itself. This heat spreads around corners. Each creature in this\
    \ area must make a DC 17 Constitution saving throw, taking 13 (3d8) fire damage\
    \ on a failed save, or half as much damage on a successful one."
  "name": "Burst of Heat (Recharge 5-6)"
"source":
- "PaBTSO"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/PaBTSO/Fiendish%20Auger.webp"
```
^statblock