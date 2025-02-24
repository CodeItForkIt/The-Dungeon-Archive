---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/coa
- monster/cr/13
- monster/size/medium
- monster/type/humanoid
statblock: inline
aliases: ["Zythan"]
---
# [Zythan](Mechanics\bestiary\npc/zythan-coa.md)
*Source: Chains of Asmodeus p. 26*  

Zythan, like many other Halruaans, spent his early years studying the arcane arts. His talent in Divination magic made him particularly useful to the Conclave, and they quickly sought him out. Under their tutelage, his skill flourished, and he became a powerful mage. Those that know him personally recount his matter-of-fact personality, his green hair, and his third eye that seems to open when he performs magic. He rarely speaks of himself, however, choosing instead to focus his attention on the future.

When he first received an official position within the Conclave, Zythan wanted to prove himself. He spent countless hours peering into the future and examining potential outcomes. One fateful night, he just barely caught sight of a forbidden ritual being prepared—a ritual that could cost the lives of many Halruaans. Because of his sight, the Conclave was able to intervene in time, and he was quickly promoted and showered with praise.

For the past few months, Zythan has felt like something was off: at first, he suspected another ritual within Halruaa. He requisitioned the help of the other diviners, as well as a powerful Crystal Ball, and together they were able to piece together a vision. The dark lord of the Nine Hells, Asmodeus, will unleash a great evil very soon. Though the Conclave often stays out of non-Halruaan affairs, they had no choice but to act. It is for this reason that the adventurers were called to Halruaa.

Zythan's skill in arcane magic, while particularly focused on Divination, extends to every school. While he lacks proficiency in martial combat, he can wield both offensive and defensive magic effectively. Outside of his magical talent, he is also known to be highly intelligent, though his social skills could use work. Much of his time is spent viewing alternate futures and preparing for potential dangers, leaving little for himself. He often goes without meals until he starts to feel weak, and if he had friends, they might be concerned about how much time he spends working.

```statblock
"name": "Zythan (CoA)"
"size": "Medium"
"type": "humanoid"
"alignment": "Lawful Neutral"
"ac": !!int "12"
"ac_class": "15 with [mage armor](Mechanics/spells/mage-armor.md)"
"hp": !!int "117"
"hit_dice": "18d8 + 36"
"stats":
- !!int "10"
- !!int "14"
- !!int "14"
- !!int "20"
- !!int "15"
- !!int "16"
"speed": "30 ft."
"saves":
  "Wisdom": !!int "7"
  "Intelligence": !!int "10"
"skillsaves":
  "Investigation": !!int "10"
  "Religion": !!int "10"
  "History": !!int "15"
  "Arcana": !!int "15"
"damage_resistances": "bludgeoning, piercing, slashing from nonmagical attacks (from\
  \ Stoneskin); damage from spells"
"senses": "passive Perception 12"
"languages": "Celestial, Common, Draconic, Elvish, Infernal, Primordial"
"cr": "13"
"traits":
- "desc": "Zythan casts one of the following spells, using Intelligence as the spellcasting\
    \ ability (spell save DC 18).\n\nAt will: [Arcane Eye](Mechanics/spells/arcane-eye.md),\
    \ [Detect Magic](Mechanics/spells/detect-magic.md), [Detect Thoughts](Mechanics/spells/detect-thoughts.md),\
    \ [Fly](Mechanics/spells/fly.md), [Light](Mechanics/spells/light.md), [Locate\
    \ Object](Mechanics/spells/locate-object.md), [Mage Armor](Mechanics/spells/mage-armor.md),\
    \ [Mage Hand](Mechanics/spells/mage-hand.md), [Message](Mechanics/spells/message.md),\
    \ [Prestidigitation](Mechanics/spells/prestidigitation.md)\n\n1/day: [Cone\
    \ of Cold](Mechanics/spells/cone-of-cold.md), [Foresight](Mechanics/spells/foresight.md),\
    \ [Stoneskin](Mechanics/spells/stoneskin.md), [Rary's telepathic bond](Mechanics/spells/rarys-telepathic-bond.md),\
    \ [True Seeing](Mechanics/spells/true-seeing.md)"
  "name": "Spellcasting"
- "desc": "Being within 5 feet of a hostile creature doesn't impose disadvantage on\
    \ Zythan's ranged attack rolls."
  "name": "Battlemage"
- "desc": "Zythan has advantage on saving throws against spells and other magical\
    \ effects."
  "name": "Magic Resistance"
"actions":
- "desc": "Zythan makes three Dagger or Arcane Burst attacks."
  "name": "Multiattack"
- "desc": "Melee or Ranged Weapon Attack: +7 to hit, reach 5 ft. or range 20/60\
    \ ft., one target. Hit: 4 (1d4 + 2) piercing damage."
  "name": "Dagger"
- "desc": "Ranged Spell Attack: +10 to hit, range 120 ft., one target. Hit:\
    \ 27 (4d10 + 5) radiant damage."
  "name": "Arcane Burst"
- "desc": "Zythan causes a disruption in arcane energies in a 300-foot line that is\
    \ 5 feet wide. Each creature in the line must make a DC 18 Constitution saving\
    \ throw, taking 65 (10d12) radiant damage on a failed save, or half as much\
    \ damage on a successful one."
  "name": "Spirit Fissure (Recharge 4-6)"
"reactions":
- "desc": "As a reaction to a creature Zythan can see making an attack roll, a saving\
    \ throw, or an ability check, Zythan rolls a d20 and chooses whether to use\
    \ that roll in place of the original roll."
  "name": "Portent (3/Day)"
"source":
- "CoA"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/CoA/Zythan.webp"
```
^statblock