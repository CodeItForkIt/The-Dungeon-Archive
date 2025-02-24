---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/coa
- monster/cr/21
- monster/size/large
- monster/type/fiend/devil
statblock: inline
aliases: ["Buer"]
---
# [Buer](Mechanics\bestiary\npc/buer-coa.md)
*Source: Chains of Asmodeus p. 211*  

```statblock
"name": "Buer (CoA)"
"size": "Large"
"type": "fiend"
"subtype": "devil"
"alignment": "Lawful Evil"
"ac": !!int "21"
"ac_class": "natural armor"
"hp": !!int "315"
"hit_dice": "30d10 + 150"
"stats":
- !!int "23"
- !!int "22"
- !!int "21"
- !!int "16"
- !!int "18"
- !!int "17"
"speed": "25 ft."
"saves":
  "Dexterity": !!int "13"
  "Strength": !!int "15"
  "Constitution": !!int "14"
"skillsaves":
  "Intimidation": !!int "17"
  "Athletics": !!int "22"
  "Insight": !!int "11"
  "Perception": !!int "11"
  "Arcana": !!int "10"
  "Survival": !!int "11"
"damage_resistances": "cold; bludgeoning, piercing, slashing from nonmagical attacks\
  \ that aren't silvered"
"damage_immunities": "fire, poison"
"condition_immunities": "[charmed](Mechanics/Rules/conditions.md#Charmed), [poisoned](Mechanics/Rules/conditions.md#Poisoned)"
"senses": "darkvision 120 ft., passive Perception 21"
"languages": "Celestial, Common, Draconic, Infernal, telepathy 120 ft."
"cr": "21"
"traits":
- "desc": "Buer has advantage to hit creatures under an infernal contract and when\
    \ she hits such creatures she delivers an additional 9 (2d8) damage of a type\
    \ the target is most vulnerable to. A creature bound under an infernal contract\
    \ also makes all saving throws against effects originating from Buer with disadvantage."
  "name": "Contractually Obligated"
- "desc": "Magical darkness doesn't impede Buer's darkvision."
  "name": "Devil's Sight"
- "desc": "Buer has advantage on saving throws against spells and other magical effects."
  "name": "Magic Resistance"
"actions":
- "desc": "Buer makes three attacks using her Claw. She can replace two of the attacks\
    \ with a Cleansing Bite attack."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +13 to hit, reach 10 ft., one target. Hit: 22\
    \ (3d10 + 6) slashing damage."
  "name": "Claw"
- "desc": "Melee Weapon Attack: +13 to hit, reach 5 ft., one target. Hit: 19\
    \ (2d12 + 6) bludgeoning damage, healing Buer for an amount equal to the damage\
    \ dealt."
  "name": "Cleansing Bite"
- "desc": "Buer focuses her ethereal form, dashing up to 50 feet in a straight line\
    \ through the ethereal plane. Any creatures in the line must make a DC 21 Constitution\
    \ saving throw, taking 42 (12d6) force damage on a failed save, or half as much\
    \ damage on a successful one. Buer may reappear at any unoccupied space along\
    \ the line. For 1 minute after using Spectral Reaping, Buer is empowered by ethereal\
    \ essence. Her Cleansing Bite attack now deals force damage instead of bludgeoning."
  "name": "Spectral Reaping (Recharge 6)"
"bonus_actions":
- "desc": "Buer attempts to slow the actions of a creature she can see within 60 feet\
    \ of her. The target must succeed on a DC 18 Wisdom saving throw or be slowed\
    \ until the end of its next turn. A slowed creature's speed is halved, it takes\
    \ a-2 penalty to AC and Dexterity saving throws, and it can't use its reactions.\
    \ Regardless of the slowed creature's abilities or magic items, it can't make\
    \ more than one melee or ranged attack during its turn."
  "name": "Defensive Trip (Recharge 5-6)"
"reactions":
- "desc": "When Buer is subjected to a spell targeting only her, she can attempt to\
    \ swap places with a creature she damaged on her last turn. The creature must\
    \ make a DC 19 Wisdom saving throw. On a failed save, the creature and Buer swap\
    \ positions, and the spell now targets the creature instead of Buer."
  "name": "Soul Exchange"
"legendary_actions":
- "desc": "Buer or one other devil within 60 feet of Buer makes a melee weapon attack\
    \ against a target of Buer's choosing."
  "name": "Teamwork"
- "desc": "Buer wreathes energy around a creature she can see within 60 feet of her.\
    \ Until the end of Buer's next turn, the target is covered in fire or cold energy,\
    \ Buer's choice. Each time the target is struck with a melee attack, the attacker\
    \ takes 9 (2d8) fire or cold damage."
  "name": "Backdoor Clause"
- "desc": "Buer devours a Soul Coin, instantly refreshing one Recharge ability of\
    \ any devil within 60 feet, including herself."
  "name": "Refresh Souls (Costs 2 Actions)"
"source":
- "CoA"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/CoA/Buer.webp"
```
^statblock