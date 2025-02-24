---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/coa
- monster/cr/14
- monster/size/medium
- monster/type/humanoid
statblock: inline
aliases: ["Ramius"]
---
# [Ramius](Mechanics\bestiary\npc/ramius-coa.md)
*Source: Chains of Asmodeus p. 24*  

Ramius Dangremond is the commander of the Hellriders of Elturel. He never wanted the position, but because of the many deaths within the ranks of the order, he had to step up. His friend and fellow Hellrider, Barachiel, was the main reason he was able to grow into a capable commander. The loss of his friend saddens Ramius, and the news of his imprisonment within the Nine Hells gnaws at his soul.

Ramius is a natural horseman and a gifted athlete. The soldiers he leads often say that there isn't anything that Ramius can't mount or ride. He's ridden horses, mammoths, and machines into battle. Loyalty, honor, and duty are virtues that Ramius upholds. He fears nothing other than losing those he cares for.

```statblock
"name": "Ramius (CoA)"
"size": "Medium"
"type": "humanoid"
"alignment": "Neutral Good"
"ac": !!int "22"
"ac_class": "[plate](Mechanics/items/plate-armor.md), [+2 shield](Mechanics/items/2-shield.md)"
"hp": !!int "190"
"hit_dice": "20d8 + 100"
"stats":
- !!int "23"
- !!int "10"
- !!int "21"
- !!int "11"
- !!int "14"
- !!int "18"
"speed": "30 ft."
"saves":
  "Charisma": !!int "9"
  "Wisdom": !!int "7"
"skillsaves":
  "Athletics": !!int "11"
  "Animal Handling": !!int "12"
  "Religion": !!int "10"
  "Insight": !!int "7"
"damage_resistances": "bludgeoning, piercing, slashing from nonmagical attacks; damage\
  \ from spells"
"senses": "passive Perception 12"
"languages": "Abyssal, Celestial, Common, Infernal"
"cr": "14"
"traits":
- "desc": "Ramius casts one of the following spells, using Charisma as the spellcasting\
    \ ability (spell save DC 17):\n\n1/day each: [Aura of Purity](Mechanics/spells/aura-of-purity.md),\
    \ [Compelled Duel](Mechanics/spells/compelled-duel.md), [Crusader's Mantle](Mechanics/spells/crusaders-mantle.md),\
    \ [Death Ward](Mechanics/spells/death-ward.md), [Dispel Evil and Good](Mechanics/spells/dispel-evil-and-good.md),\
    \ [Find Steed](Mechanics/spells/find-steed.md), [Lesser Restoration](Mechanics/spells/lesser-restoration.md),\
    \ [Remove Curse](Mechanics/spells/remove-curse.md), [Revivify](Mechanics/spells/revivify.md),\
    \ [Shield of Faith](Mechanics/spells/shield-of-faith.md)"
  "name": "Spellcasting"
- "desc": "Ramius and any ally that starts their turn within 30 feet of him have a\
    \ +4 bonus to all saving throws and resistance to nonmagical damage."
  "name": "Aura of Protection"
"actions":
- "desc": "Ramius makes two Longsword attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +11 to hit, reach 5ft., one target. Hit: 10\
    \ (1d8 + 6) slashing damage or 11 (1d10 + 6) if wielded in two hands, plus\
    \ 13 (3d8) radiant damage. If the target is an evil creature, it must succeed\
    \ on a DC 17 Charisma saving throw or take an additional 13 (3d8) radiant damage."
  "name": "Longsword"
- "desc": "Ramius strikes the ground and causes holy energy to radiate outwards. Each\
    \ creature of his choice within 30 feet of him must make a DC 17 Constitution\
    \ saving throw. Targets take 21 (6d6) thunder damage plus 21 (6d6) radiant\
    \ damage on a failed save, or half as much damage on a successful one. Creatures\
    \ that fail the save are knocked down (have the [prone](Mechanics/Rules/conditions.md#Prone)\
    \ condition)."
  "name": "Divine Wave (Recharge 6)"
"reactions":
- "desc": "As a reaction to Ramius or an adjacent creature taking 50 points or more\
    \ of damage, Ramius reaches out and channels divine energy, healing 13 (2d8 +\
    \ 4) hit points."
  "name": "Healing Touch"
"source":
- "CoA"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/CoA/Ramius.webp"
```
^statblock