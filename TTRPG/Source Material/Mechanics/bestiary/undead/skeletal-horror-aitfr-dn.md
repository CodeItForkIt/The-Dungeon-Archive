---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/aitfr-dn
- monster/cr/6
- monster/size/large
- monster/type/undead
statblock: inline
aliases: ["Skeletal Horror"]
---
# [Skeletal Horror](Mechanics\bestiary\undead/skeletal-horror-aitfr-dn.md)
*Source: Adventures in the Forgotten Realms: Deepest Night p. 13*  

This horrid mass of bones clambers along on a dozen hands and feet without maintaining any consistent shape. One moment it moves like a centipede, the next it rears back to claw like a bear. The only consistent feature is a weird absence: no matter how many skulls make up its mass, this strange horror always seems to be headless.

The skeletal horrors in Kyrilla's lair are made from the bones of yuan-ti supplicants and cultists who came to learn her powers or, later, to steal them. She spared none of these intruders' lives, and in death their remains do her bidding.

```statblock
"name": "Skeletal Horror (AitFR-DN)"
"size": "Large"
"type": "undead"
"alignment": "Neutral Evil"
"ac": !!int "13"
"hp": !!int "150"
"hit_dice": "20d10 + 40"
"stats":
- !!int "16"
- !!int "14"
- !!int "15"
- !!int "6"
- !!int "10"
- !!int "5"
"speed": "30 ft."
"skillsaves":
  "Perception": !!int "3"
"damage_vulnerabilities": "bludgeoning"
"damage_immunities": "poison"
"condition_immunities": "[exhaustion](Mechanics/Rules/conditions.md#Exhaustion), [poisoned](Mechanics/Rules/conditions.md#Poisoned)"
"senses": "darkvision 60 ft., passive Perception 16"
"languages": ""
"cr": "6"
"actions":
- "desc": "The horror makes two attacks with its claws."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 19\
    \ (3d10 + 3) slashing damage."
  "name": "Claw"
- "desc": "The horror crashes into foes like a wave before quickly reforming. Each\
    \ creature within 10 feet of the horror must make a DC 15 Dexterity saving throw,\
    \ taking 18 (4d8) bludgeoning damage on a failed save, or half as much damage\
    \ on a successful one. A creature that fails this saving throw is also knocked\
    \ [prone](Mechanics/Rules/conditions.md#Prone)."
  "name": "Wave of Bones (Recharge 5-6)"
"source":
- "AitFR-DN"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/AitFR-DN/Skeletal%20Horror.webp"
```
^statblock