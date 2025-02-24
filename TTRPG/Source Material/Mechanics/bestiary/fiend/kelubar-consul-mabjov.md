---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/mabjov
- monster/cr/11
- monster/size/medium
- monster/type/fiend
statblock: inline
aliases: ["Kelubar Consul"]
---
# [Kelubar Consul](Mechanics\bestiary\fiend/kelubar-consul-mabjov.md)
*Source: Minsc and Boo's Journal of Villainy p. 136*  

> [!quote] A quote from MINSC & BOO!  
> 
> Me and Boo like many sticky things, most especially donuts and Boo's favorite, candied pecans. But some sticky things belong on the pointy end of a sword.

> [!quote] A quote from Volo  
> 
> Demodands are difficult to study since they usually never leave their native plane of Carceri. However, the prison in Ust Natha presents a unique opportunity to view them up close. Not that I enjoyed the experience.

Demodands are primal creations of evil and implacable agents of destruction. Exiled to Carceri for their chaotic taint, they are also known as gehreleths or leths.

## Wardens of the Damned

Though they are trapped in Carceri, the demodands do not consider themselves prisoners. Instead, they are the self-appointed wardens and jailors of the Tarterian Depths. They derive pleasure from tormenting and terrorizing their fellow captives through acts of brutality, cruelly taunting them the entire time. However, they make no distinction between those actually condemned to Carceri, and planar travelers just passing through. As far as the demodand are concerned, all must be prevented from escaping at any cost.

## A Trio of the Grotesque

Demodands have three castes, each with a form so repulsive even other denizens of the Lower Planes view them with disgust. The farastu are forced to do the most menial tasks, under orders from their kelubar and shator superiors. When around weaker creatures they are vicious bullies; around more powerful beings they become whimpering cowards. The kelubars are the bureaucrats of the demodands, acting as intermediaries between the lowly farastu and their shator overlords. The kelubar decide which prisoners are rewarded, and which should be punished with extra torments. The shators make up the ruling caste, effectively serving as prison wardens to the lower-ranked guards.

## The Memory of Eons

Each shator possesses an obsidian triangle. These powerful magical artifacts grant the demodands access to the collective memory of their kind; a shared recollection stretching back to the very dawn of time. The shators primarily use the triangles to track the identity of every being that has ever escaped Carceri, concocting elaborate, generation-spanning strategies to recapture these fugitive souls.

```statblock
"name": "Kelubar Consul (MaBJoV)"
"size": "Medium"
"type": "fiend"
"alignment": "Neutral Evil"
"ac": !!int "17"
"ac_class": "natural armor"
"hp": !!int "97"
"hit_dice": "13d8 + 39"
"stats":
- !!int "20"
- !!int "13"
- !!int "17"
- !!int "14"
- !!int "15"
- !!int "18"
"speed": "30 ft., fly 60 ft."
"saves":
  "Charisma": !!int "8"
  "Strength": !!int "9"
  "Constitution": !!int "7"
"skillsaves":
  "Athletics": !!int "9"
  "Insight": !!int "6"
  "Persuasion": !!int "8"
"damage_resistances": "cold; fire; bludgeoning, piercing, slashing from nonmagical\
  \ attacks that aren't silvered"
"damage_immunities": "acid, poison"
"condition_immunities": "[poisoned](Mechanics/Rules/conditions.md#Poisoned)"
"senses": "darkvision 120 ft., passive Perception 12"
"languages": "Abyssal, Common"
"cr": "11"
"traits":
- "desc": "The kelubar casts one of the following spells, requiring no material components\
    \ and using Charisma as the spellcasting ability (spell save DC 16):\n\nAt will:\
    \ [clairvoyance](Mechanics/spells/clairvoyance.md), [detect magic](Mechanics/spells/detect-magic.md),\
    \ [fear](Mechanics/spells/fear.md), [invisibility](Mechanics/spells/invisibility.md)\
    \ (self only), [spider climb](Mechanics/spells/spider-climb.md), [tongues](Mechanics/spells/tongues.md)\n\
    \n2/day each: [dispel magic](Mechanics/spells/dispel-magic.md), [fog cloud](Mechanics/spells/fog-cloud.md)"
  "name": "Spellcasting"
- "desc": "Magical darkness doesn't impede the kelubar's darkvision."
  "name": "Devil's Sight"
- "desc": "The kelubar is unaffected by difficult terrain, and spells and other magical\
    \ affects don't reduce its speed or cause it to be [paralyzed](Mechanics/Rules/conditions.md#Paralyzed)\
    \ or [restrained](Mechanics/Rules/conditions.md#Restrained). If the kelubar spends\
    \ 5 feet of movement is automatically escapes from nonmagical restraints or a\
    \ creature that has it [grappled](Mechanics/Rules/conditions.md#Grappled). It\
    \ is also able to move underwater with no movement or attack penalties."
  "name": "Freedom of Movement"
- "desc": "The kelubar has advantage on Wisdom ([Perception](Mechanics/Rules/skills.md#Perception))\
    \ checks that rely on smell."
  "name": "Keen Smell"
- "desc": "The kelubar has advantage on saving throws against spells and other magical\
    \ effects."
  "name": "Magic Resistance"
- "desc": "The kelubar's weapon attacks are magical."
  "name": "Magic Weapons"
- "desc": "At the start of its turn, the kelubar can gain advantage on all melee weapon\
    \ attack rolls it makes during that turn, but attack rolls against it have advantage\
    \ until the start of its next turn."
  "name": "Reckless"
- "desc": "The kelubar deals an extra 14 (4d6) damage when it hits a target with\
    \ a weapon attack and has advantage on the attack roll, or when the target is\
    \ within 5 ft. of an ally of the kelubar that isn't incapacitated and the kelubar\
    \ doesn't have disadvantage on the attack roll."
  "name": "Sneak Attack (1/Turn)"
- "desc": "Any creature that is not a demodand and starts its turn within 30 feet\
    \ of the kelubar must succeed on a DC 16 Constitution saving throw or or have\
    \ the [poisoned](Mechanics/Rules/conditions.md#Poisoned) condition for 1 minute.\
    \ On a successful saving throw, the creature is immune to the stench of this kelubar\
    \ for 1 hour."
  "name": "Stench"
"actions":
- "desc": "The kelubar makes one Bite attack and three Claws attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +9 to hit, reach 5 ft., one target. Hit: 14\
    \ (2d8 + 5) piercing damage plus 7 (2d6) acid damage."
  "name": "Bite"
- "desc": "Melee Weapon Attack: +9 to hit, reach 5 ft., one target. Hit: 9 (1d8\
    \ + 5) slashing damage plus 7 (2d6) acid damage."
  "name": "Claws"
"bonus_actions":
- "desc": "The kelubar rolls a d6. A result of 1-2 summons in two allied [farastu\
    \ stalkers](Mechanics/bestiary/fiend/farastu-stalker-mabjov.md), a result of 3-4\
    \ summons in one allied [kelubar consul](Mechanics/bestiary/fiend/kelubar-consul-mabjov.md)."
  "name": "Summon Demodand (1/Day)"
"reactions":
- "desc": "When an attacker that the kelubar can see hits it with an attack, the kelubar\
    \ can use its reaction to halve the attack's damage."
  "name": "Impossible Dodge"
"source":
- "MaBJoV"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/MaBJoV/Kelubar%20Consul.webp"
```
^statblock