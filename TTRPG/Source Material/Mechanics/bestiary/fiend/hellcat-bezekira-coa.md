---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/coa
- monster/cr/10
- monster/size/large
- monster/type/fiend
statblock: inline
aliases: ["Hellcat (Bezekira)"]
---
# [Hellcat (Bezekira)](Mechanics\bestiary\fiend/hellcat-bezekira-coa.md)
*Source: Chains of Asmodeus p. 244*  

Possessing a unique ability to detect both the alignment and strength of an individual telepathically, bezekiras, otherwise known as hellcats, search for the most powerful master of lawful evil alignment. Once they've found a master, they're extremely loyal and follow all commands, until a stronger master comes along. When not serving a master, hellcats are fiercely independent, secretive, and intelligent.

## Hard to See

When visible, hellcats take on the appearance of larger cats, including lions and tigers. However, they have an innate invisibility when in any source of light, preventing their corporeal form from appearing anywhere outside of total darkness. They appear wraith-like, with the wispy outline of their body composed of ethereal light and devilish fire. Though they rarely hunt creatures of evil alignment, good creatures are slaughtered on sight, sometimes even against their master's orders. Bezekiras propagate through natural means, though petitioners and devils are sometimes given their form.

```statblock
"name": "Hellcat (Bezekira) (CoA)"
"size": "Large"
"type": "fiend"
"alignment": "Neutral Evil"
"ac": !!int "16"
"ac_class": "natural armor"
"hp": !!int "136"
"hit_dice": "16d10 + 48"
"stats":
- !!int "21"
- !!int "19"
- !!int "17"
- !!int "10"
- !!int "14"
- !!int "10"
"speed": "40 ft."
"saves":
  "Dexterity": !!int "8"
  "Constitution": !!int "7"
"skillsaves":
  "Athletics": !!int "9"
  "Stealth": !!int "12"
  "Perception": !!int "6"
  "Acrobatics": !!int "8"
"damage_resistances": "bludgeoning, piercing, slashing from nonmagical attacks that\
  \ aren't silvered; damage from spells"
"damage_immunities": "fire"
"senses": "blindsight 30 ft., darkvision 60 ft., passive Perception 16"
"languages": "understands Infernal, telepathy 120 ft."
"cr": "10"
"traits":
- "desc": "Attacks made against a bezekira in bright or dim light have disadvantage."
  "name": "Darkness Dweller"
- "desc": "Magical darkness doesn't impede the bezekira's darkvision."
  "name": "Devil's Sight"
"actions":
- "desc": "The bezekira makes three Claw attacks. It can replace one of the attacks\
    \ with a Bite attack."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +9 to hit, reach 5 ft., one target. Hit: 15\
    \ (3d6 + 5) slashing damage plus 7 (2d6) fire damage. The bezekira deals an\
    \ extra 28 (8d6) fire damage when it hits a target with an attack and has advantage\
    \ on the attack roll."
  "name": "Claw"
- "desc": "Melee Weapon Attack: +9 to hit, reach 5 ft., one target. Hit: 16\
    \ (2d10 + 5) bludgeoning damage, grasping the target with its mouth. If the\
    \ target is a Medium or smaller creature, it has the [grappled](Mechanics/Rules/conditions.md#Grappled)\
    \ condition (escape DC 17). The bezekira can't make a Bite attack while a creature\
    \ is [grappled](Mechanics/Rules/conditions.md#Grappled) in this way."
  "name": "Bite"
"source":
- "CoA"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/CoA/Hellcat%20%28Bezekira%29.webp"
```
^statblock