---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/coa
- monster/cr/21
- monster/size/large
- monster/type/fiend/devil
statblock: inline
aliases: ["Brother Morax"]
---
# [Brother Morax](Mechanics\bestiary\npc/brother-morax-coa.md)
*Source: Chains of Asmodeus p. 186*  

```statblock
"name": "Brother Morax (CoA)"
"size": "Large"
"type": "fiend"
"subtype": "devil"
"alignment": "Lawful Evil"
"ac": !!int "21"
"ac_class": "natural armor"
"hp": !!int "337"
"hit_dice": "25d10 + 200"
"stats":
- !!int "24"
- !!int "22"
- !!int "27"
- !!int "14"
- !!int "16"
- !!int "18"
"speed": "40 ft."
"saves":
  "Dexterity": !!int "13"
  "Strength": !!int "14"
  "Constitution": !!int "15"
"skillsaves":
  "Medicine": !!int "10"
  "Intimidation": !!int "11"
  "Athletics": !!int "21"
  "Stealth": !!int "13"
  "Acrobatics": !!int "20"
  "Survival": !!int "10"
"damage_resistances": "cold; bludgeoning, piercing, slashing from nonmagical attacks\
  \ that aren't silvered"
"damage_immunities": "fire, poison"
"condition_immunities": "[poisoned](Mechanics/Rules/conditions.md#Poisoned)"
"senses": "darkvision 120 ft., passive Perception 13"
"languages": "Celestial, Common, Draconic, Infernal, telepathy 120 ft."
"cr": "21"
"traits":
- "desc": "For each Brittle Spine a creature has, the creature takes 3 (1d6) poison\
    \ damage at the start of each of their turns, and when Morax activates Burrow\
    \ or Deep Burrow. Spines can only be removed by a Regeneration spell or similar,\
    \ or by killing Morax."
  "name": "Brittle Spine"
- "desc": "Magical darkness doesn't impede Morax's darkvision."
  "name": "Devil's Sight"
- "desc": "Morax has advantage on saving throws against spells and other magical effects."
  "name": "Magic Resistance"
- "desc": "Whenever Morax is hit with a melee attack, the attacker takes 7 (2d6)\
    \ piercing damage and gains 1 Brittle Spine."
  "name": "Spined Hide"
- "desc": "If Morax is reduced to 0 hit points while Brother Adramalech still lives,\
    \ Morax regenerates 50 hit points at the start of his next turn. This regeneration\
    \ is interrupted if Brother Adramalech is reduced to 0 hit points before the start\
    \ of Morax's turn."
  "name": "Unbreakable Bond"
"actions":
- "desc": "Morax makes four attacks using his Claw, Spine Fling, or a combination\
    \ of the two."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +14 to hit, reach 10 ft., one target. Hit: 17\
    \ (3d6 + 7) slashing damage, and the target gains 1 Brittle Spine."
  "name": "Claw"
- "desc": "Ranged Weapon Attack: +13 to hit, range 30/60 ft., one target. Hit:\
    \ 12 (1d12 + 6) piercing damage, and the target gains 1 Brittle Spine."
  "name": "Spine Fling"
- "desc": "Morax immediately deals Brittle Spine ongoing damage to all creatures that\
    \ have at least one Brittle Spine that he can see."
  "name": "Deep Burrow"
- "desc": "Morax shoves an arm into the ground, rapidly growing bones that erupt at\
    \ a point he can see within 100 feet of him. Each creature in a 60-foot-radius\
    \ sphere centered on that point must make a DC 21 Dexterity saving throw, taking\
    \ 28 (8d6) piercing damage on a failed save, or half as much damage on a successful\
    \ one. Creatures that fail the save gain 2 Brittle Spines, while creatures that\
    \ succeed only gain 1 Brittle Spine."
  "name": "Bone Spikes (Recharge 6)"
"legendary_actions":
- "desc": "Morax makes a Claw attack."
  "name": "Claw"
- "desc": "Morax gestures at a creature he can see that has at least 1 Brittle Spine.\
    \ That creature must succeed on a DC 21 Constitution saving throw or the number\
    \ of Brittle Spines it has doubles."
  "name": "Bone Splinters (Costs 2 Actions)"
- "desc": "Morax bristles the spines within a creature that he can see. The target\
    \ immediately takes Brittle Spine ongoing damage."
  "name": "Burrow (Costs 2 Actions)"
"source":
- "CoA"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/CoA/Brother%20Morax.webp"
```
^statblock