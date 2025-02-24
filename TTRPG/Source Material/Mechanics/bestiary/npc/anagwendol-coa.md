---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/coa
- monster/cr/16
- monster/size/medium
- monster/type/celestial
statblock: inline
aliases: ["Anagwendol"]
---
# [Anagwendol](Mechanics\bestiary\npc/anagwendol-coa.md)
*Source: Chains of Asmodeus p. 262*  

A fierce warrior of the Heavens, Anagwendol's career is a trail of slain Fiends. She has never turned from a fight against evil, and though she has taken countless wounds in the fray, she has never lost. And now she is in the Nine Hells.

She owes her captivity to an all-too-common fault among angels. Of all sins, they must beware of pride. Knowing that you're the very instrument of the divine and having carved your way through the inferior mettle of a thousand infernal combatants, makes it hard to hold onto humility. This pride led her into a trap and unable to leave the fourth layer—Phlegethos.

The mastermind behind the entrapment of Anagwendol was the archdevil Kordichai, whose chief interest is a grand game preserve of fiery Elemental monsters in Phlegethos. Kordichai, a canny old hunter, was able to lure her into his preserve, and there at its heart she remains, a prisoner within a blazing stone labyrinth. Occasionally Kordichai sends parties of devils (especially underlings who have disappointed him) to hunt her, and enjoys watching their failures.

Anagwendol is no longer the angel she once was. Whilst the inner warrior of the divine remains, her connection to her surroundings is twisted by an infernal curse so that she believes she is forever fighting an endless swarm of enemies. Everything she encounters is perceived as a loathsome devil, fit only for cutting down.

This constant one-angel war on the infernal is gradually taking its toll. Anagwendol is growing to live for it. The ferocity of shedding infernal blood is becoming an end in itself for her, rather than an unfortunate but necessary means to virtue.

```statblock
"name": "Anagwendol (CoA)"
"size": "Medium"
"type": "celestial"
"alignment": "Lawful Good"
"ac": !!int "17"
"ac_class": "natural armor"
"hp": !!int "190"
"hit_dice": "20d8 + 100"
"stats":
- !!int "20"
- !!int "18"
- !!int "20"
- !!int "18"
- !!int "20"
- !!int "22"
"speed": "30 ft., fly 90 ft."
"saves":
  "Charisma": !!int "11"
  "Wisdom": !!int "10"
  "Intelligence": !!int "9"
"skillsaves":
  "Perception": !!int "10"
"damage_resistances": "radiant; bludgeoning, piercing, slashing from nonmagical attacks"
"condition_immunities": "[charmed](Mechanics/Rules/conditions.md#Charmed), [exhaustion](Mechanics/Rules/conditions.md#Exhaustion),\
  \ [frightened](Mechanics/Rules/conditions.md#Frightened)"
"senses": "truesight 120 ft., passive Perception 20"
"languages": "all, telepathy 120 ft."
"cr": "16"
"traits":
- "desc": "Anagwendol has advantage on saving throws against spells and other magical\
    \ effects."
  "name": "Magic Resistance"
"actions":
- "desc": "Anagwendol makes two attacks using her Defending Greatsword, Longbow, or\
    \ a combination of the two."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +10 to hit, reach 5 ft., one target. Hit: 19\
    \ (4d6 + 5) slashing damage plus 22 (5d8) radiant damage."
  "name": "Defending Greatsword"
- "desc": "Ranged Weapon Attack: +9 to hit, range 150/600 ft., one target. Hit:\
    \ 8 (1d8 + 4) piercing damage damage plus 22 (5d8) radiant damage."
  "name": "Longbow"
- "desc": "Anagwendol touches another creature. The target magically regains 30 (6d8\
    \ + 3) hit points and is freed from any curse, disease, poison, blindness, or\
    \ deafness."
  "name": "Healing Touch (2/Day)"
"bonus_actions":
- "desc": "Anagwendol can forgo attacking with her Defending Greatsword on this turn\
    \ and gain a +3 to her armor class. She can still attack with her Longbow."
  "name": "Defensive Swordwork"
"source":
- "CoA"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/CoA/Anagwendol.webp"
```
^statblock