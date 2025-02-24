---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/coa
- monster/cr/20
- monster/size/medium
- monster/type/fiend/devil
statblock: inline
aliases: ["Zagum"]
---
# [Zagum](Mechanics\bestiary\npc/zagum-coa.md)
*Source: Chains of Asmodeus p. 210*  

```statblock
"name": "Zagum (CoA)"
"size": "Medium"
"type": "fiend"
"subtype": "devil"
"alignment": "Lawful Evil"
"ac": !!int "19"
"ac_class": "natural armor"
"hp": !!int "255"
"hit_dice": "30d8 + 120"
"stats":
- !!int "17"
- !!int "16"
- !!int "18"
- !!int "22"
- !!int "25"
- !!int "27"
"speed": "30 ft."
"saves":
  "Charisma": !!int "14"
  "Wisdom": !!int "13"
  "Intelligence": !!int "12"
"skillsaves":
  "Intimidation": !!int "14"
  "Deception": !!int "20"
  "Insight": !!int "13"
  "Performance": !!int "14"
  "Arcana": !!int "12"
  "Persuasion": !!int "20"
"damage_resistances": "cold; bludgeoning, piercing, slashing from nonmagical attacks\
  \ that aren't silvered"
"damage_immunities": "fire, poison, psychic"
"condition_immunities": "[charmed](Mechanics/Rules/conditions.md#Charmed), [poisoned](Mechanics/Rules/conditions.md#Poisoned)"
"senses": "darkvision 120 ft., passive Perception 17"
"languages": "Celestial, Common, Draconic, Infernal, telepathy 120 ft."
"cr": "20"
"traits":
- "desc": "Zagum has advantage to hit creatures under an infernal contract and when\
    \ he hits such creatures he delivers an additional 9 (2d8) damage of a type\
    \ the target is most vulnerable to. A creature bound under an infernal contract\
    \ also makes all saving throws against effects originating from Zagum with disadvantage."
  "name": "Contractually Obligated"
- "desc": "Magical darkness doesn't impede Zagum's darkvision."
  "name": "Devil's Sight"
- "desc": "Zagum has advantage on saving throws against spells and other magical effects."
  "name": "Magic Resistance"
"actions":
- "desc": "Zagum makes three attacks with Disarming Tongue or Oration."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +9 to hit, reach 10 ft., one target. Hit: 10\
    \ (3d4 + 3) slashing damage. A target hit by this attack has vulnerability to\
    \ psychic damage until the start of their next turn."
  "name": "Disarming Tongue"
- "desc": "Ranged Spell Attack: +14 to hit, range 60 ft., one target. Hit: 35\
    \ (6d8 + 8) psychic damage."
  "name": "Oration"
- "desc": "Zagum chooses a point he can see within 90 feet of him. All creatures within\
    \ a 20-foot-radius sphere centered on that point must make a DC 22 Wisdom saving\
    \ throw. Creatures that fail the save are confused for up to 1 minute and must\
    \ roll a d10 at the start of each of their turns.\n\nOn a 1, a creature moves\
    \ in a random direction then ends their turn. On a 2-6, a creature can't use actions\
    \ this turn. On a 7-8, a creature must use their action to make a melee attack\
    \ against a randomly determined creature within their reach that is not a Fiend.\
    \ On a 9-10, a creature can move and act normally.\n\nA confused creature may\
    \ repeat the saving throw at the end of its turn, ending the effect on a success."
  "name": "Legal Jargon (Recharge 4-6)"
"source":
- "CoA"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/CoA/Zagum.webp"
```
^statblock