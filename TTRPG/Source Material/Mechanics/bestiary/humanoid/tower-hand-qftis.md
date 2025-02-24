---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/qftis
- monster/cr/1-2
- monster/size/medium
- monster/type/humanoid
statblock: inline
aliases: ["Tower Hand"]
---
# [Tower Hand](Mechanics\bestiary\humanoid/tower-hand-qftis.md)
*Source: Quests from the Infinite Staircase p. 217*  

Tower hands belong to the Order of the Night Sky, an ancient society of martial artists who protect the sages of the Tower of the Heavens. They rarely speak and carry few worldly possessions.

## Tower Stewards

For centuries, the Tower of the Heavens has been stewarded by dutiful folk who practice two distinct traditions.

```statblock
"name": "Tower Hand (QftIS)"
"size": "Medium"
"type": "humanoid"
"alignment": "Any alignment"
"ac": !!int "14"
"ac_class": "Unarmored Defense"
"hp": !!int "22"
"hit_dice": "4d8 + 4"
"stats":
- !!int "10"
- !!int "14"
- !!int "12"
- !!int "12"
- !!int "14"
- !!int "9"
"speed": "40 ft."
"skillsaves":
  "Insight": !!int "4"
"senses": "passive Perception 12"
"languages": "Common"
"cr": "1/2"
"traits":
- "desc": "While the tower hand is wearing no armor and wielding no shield, its AC\
    \ includes its Wisdom modifier."
  "name": "Unarmored Defense"
"actions":
- "desc": "The tower hand makes two Unarmed Strike attacks, two Dart attacks, or one\
    \ of each."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 5 (1d6\
    \ + 2) bludgeoning damage."
  "name": "Unarmed Strike"
- "desc": "Ranged Weapon Attack: +4 to hit, range 20/60 ft., one target. Hit:\
    \ 4 (1d4 + 2) piercing damage."
  "name": "Dart"
"reactions":
- "desc": "In response to being hit by a ranged weapon attack, the tower hand deflects\
    \ the missile. The damage it takes from the attack is reduced by 7 (1d10 + 2)."
  "name": "Deflect Missile"
"source":
- "QftIS"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/QftIS/Tower%20Hand.webp"
```
^statblock