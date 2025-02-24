---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/mabjov
- monster/cr/24
- monster/size/huge
- monster/type/beast
statblock: inline
aliases: ["Bhaal, Ravager"]
---
# [Bhaal, Ravager](Mechanics\bestiary\beast/bhaal-ravager-mabjov.md)
*Source: Minsc and Boo's Journal of Villainy p. 95*  

> [!quote] A quote from MINSC & BOO!  
> 
> When evil knocks on your door, don't ask who's there. Let your SWORD do the talking! But when you knock on evil's door, give it a good, hard KICK. And when evil asks, Who's there? tell them Boo sent you!

A wholly evil, debased and sadistic god, Bhaal—the God of Murder—is reviled by a majority of Faerûn's pantheon; his divine foes include Chauntea, Helm, Ilmater, Lathander, Lliira and Tyr.

Before his ascension to godhood, Bhaal was a power-hungry adventurer on Toril. Along with his companions Bane and Myrkul, he sought to attain the portfolio of Jergal, God of the Dead. Jergal willingly offered his realm to the Dark Three, though they couldn't decide amongst themselves who would rule. Upon Jergal's suggestion, the three divided his power, deciding how to divide it based on the outcome of a game. The three played a game of knucklebones, and Bane emerged as the victor. He claimed the domains of hatred, strife and tyranny as his own. Myrkul, coming second, chose rule over the dead. Finally, Bhaal chose the divine province of death and murder.

A century ago, Bhaal foresaw that he would die in the Time of Troubles and enacted a plan that would allow him to return to life by creating the Bhaalspawn—mortal children imbued with a fraction of his divine essence. While that plan took more than a century to come to fruition, Bhaal has indeed been reborn. Having been dead for more than a century, he now works to rebuild his following, which will augment his divine power. Some of his most powerful and devout followers include his Bhaalspawn son Sarevok and the famous sky captain Pelyious.

Bhaal has two avatar forms: a corpse-like male humanoid called the Slayer, and a huge beast known as the Ravager. He hunts victims at night in his Slayer form. When he has killed, it gives him the power to transform into the Ravager.

```statblock
"name": "Bhaal, Ravager (MaBJoV)"
"size": "Huge"
"type": "beast"
"alignment": "Lawful Evil"
"ac": !!int "20"
"ac_class": "natural armor"
"hp": !!int "351"
"hit_dice": "26d12 + 182"
"stats":
- !!int "28"
- !!int "24"
- !!int "24"
- !!int "14"
- !!int "16"
- !!int "14"
"speed": "40 ft."
"saves":
  "Charisma": !!int "9"
  "Dexterity": !!int "14"
  "Strength": !!int "16"
"skillsaves":
  "Athletics": !!int "16"
  "Stealth": !!int "14"
  "Perception": !!int "10"
"damage_resistances": "necrotic"
"damage_immunities": "acid; cold; fire; lightning; poison; bludgeoning, piercing,\
  \ slashing from nonmagical attacks"
"condition_immunities": "[charmed](Mechanics/Rules/conditions.md#Charmed), [exhaustion](Mechanics/Rules/conditions.md#Exhaustion),\
  \ [frightened](Mechanics/Rules/conditions.md#Frightened), [incapacitated](Mechanics/Rules/conditions.md#Incapacitated),\
  \ [paralyzed](Mechanics/Rules/conditions.md#Paralyzed), [petrified](Mechanics/Rules/conditions.md#Petrified),\
  \ [poisoned](Mechanics/Rules/conditions.md#Poisoned), [stunned](Mechanics/Rules/conditions.md#Stunned),\
  \ [unconscious](Mechanics/Rules/conditions.md#Unconscious)"
"senses": "darkvision 120 ft., truesight 60 ft., passive Perception 20"
"languages": "Abyssal, Common, Primordial, Undercommon"
"cr": "24"
"traits":
- "desc": "When the ravager drops to 0 hit points, its form fractures. Within the\
    \ next 24 hours, it will reappear in its [slayer form](Mechanics/bestiary/humanoid/bhaal-slayer-mabjov.md)\
    \ within 2d6 miles of where the ravager form fell."
  "name": "Avatar of Bhaal"
- "desc": "When the ravager damages a creature with a melee attack and the target\
    \ is left with 20 or fewer remaining hit points, the creature must succeed on\
    \ a DC 21 Constitution saving throw or be reduced to 0 hit points."
  "name": "Cull the Weak"
- "desc": "The ravager is immune to any spell or effect that would alter its form."
  "name": "Immutable Form"
- "desc": "If the ravager fails a saving throw, it can choose to succeed instead."
  "name": "Legendary Resistance (3/Day)"
- "desc": "The ravager has advantage on saving throws against spells and other magical\
    \ effects."
  "name": "Magic Resistance"
- "desc": "The ravager's Claw, Bite, and Spines attacks are magical."
  "name": "Magic Weapons"
- "desc": "At the start of each of its turns, the ravager deals 16 (3d10) piercing\
    \ damage to any creature grappling it or being [grappled](Mechanics/Rules/conditions.md#Grappled)\
    \ by it."
  "name": "Spiked Hide"
"actions":
- "desc": "The ravager makes one Bite attack and then either two Claw attacks or two\
    \ Spines attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +16 to hit, reach 5 ft., one target. Hit: 22\
    \ (3d8 + 9) slashing damage plus 7 (2d6) necrotic damage. If the target is\
    \ a creature, it must succeed on a DC 21 Constitution saving throw or have its\
    \ hit point maximum reduced by an amount equal to the damage taken. The target\
    \ dies if this attack reduces its hit point maximum to 0. The reduction lasts\
    \ until removed by the [greater restoration](Mechanics/spells/greater-restoration.md)\
    \ spell or other magic."
  "name": "Claw"
- "desc": "Melee Weapon Attack: +16 to hit, reach 5 ft., one target. Hit: 25\
    \ (3d10 + 9) piercing damage plus 7 (2d6) necrotic damage. If the target is\
    \ a creature, it must succeed on a DC 21 Constitution saving throw or have its\
    \ hit point maximum reduced by an amount equal to the damage taken. The target\
    \ dies if this attack reduces its hit point maximum to 0. The reduction lasts\
    \ until removed by the [greater restoration](Mechanics/spells/greater-restoration.md)\
    \ spell or other magic. Large or smaller creatures damaged by this attack are\
    \ [grappled](Mechanics/Rules/conditions.md#Grappled) (escape DC 20) and the ravager\
    \ can't make another Bite attack until this grapple ends."
  "name": "Bite"
- "desc": "Ranged Weapon Attack: +14 to hit, range 60/120 ft., one target. Hit:\
    \ 17 (3d6 + 7) piercing damage. If the target fails a DC 19 Constitution saving\
    \ throw, they are [stunned](Mechanics/Rules/conditions.md#Stunned) until the end\
    \ of their next turn."
  "name": "Spines"
"legendary_actions":
- "desc": "The ravager makes a Wisdom ([Perception](Mechanics/Rules/skills.md#Perception))\
    \ check."
  "name": "Detect"
- "desc": "The ravager flares its numerous spines and they elongate. Any creature\
    \ within 5 feet of the ravager must make a DC 21 Dexterity saving throw, taking\
    \ 27 (5d10) piercing damage on a failed save, or half as much damage on a successful\
    \ one."
  "name": "Spiky Carapace"
- "desc": "The ravager smashes downwards with great force, causing a violent implosion.\
    \ Any creature within 10 feet of the ravager must make a DC 20 Constitution saving\
    \ throw, taking 18 (4d8) thunder damage on a failed save, or half as much damage\
    \ on a successful one. Creatures that fail the saving throw are also pulled 5\
    \ feet towards the ravager. The noise produced by this attack can be heard up\
    \ to 1 mile away."
  "name": "Smash (Costs 2 Actions)"
"source":
- "MaBJoV"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/MaBJoV/Bhaal%2C%20Ravager.webp"
```
^statblock