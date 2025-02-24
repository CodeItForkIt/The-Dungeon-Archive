---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/mabjov
- monster/cr/14
- monster/size/large
- monster/type/fiend
statblock: inline
aliases: ["Shator Warden"]
---
# [Shator Warden](Mechanics\bestiary\fiend/shator-warden-mabjov.md)
*Source: Minsc and Boo's Journal of Villainy p. 137*  

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
"name": "Shator Warden (MaBJoV)"
"size": "Large"
"type": "fiend"
"alignment": "Neutral Evil"
"ac": !!int "16"
"ac_class": "natural armor"
"hp": !!int "119"
"hit_dice": "14d10 + 42"
"stats":
- !!int "24"
- !!int "11"
- !!int "17"
- !!int "14"
- !!int "16"
- !!int "20"
"speed": "30 ft., fly 60 ft."
"saves":
  "Charisma": !!int "10"
  "Strength": !!int "12"
  "Constitution": !!int "8"
"skillsaves":
  "Athletics": !!int "12"
  "Insight": !!int "8"
  "Persuasion": !!int "10"
"damage_resistances": "cold; fire; bludgeoning, piercing, slashing from nonmagical\
  \ attacks that aren't silvered"
"damage_immunities": "acid, poison"
"condition_immunities": "[poisoned](Mechanics/Rules/conditions.md#Poisoned)"
"senses": "darkvision 120 ft., passive Perception 13"
"languages": "Abyssal, Common"
"cr": "14"
"traits":
- "desc": "The shator casts one of the following spells, requiring no material components\
    \ and using Charisma as the spellcasting ability (spell save DC 18):\n\nAt will:\
    \ [clairvoyance](Mechanics/spells/clairvoyance.md), [detect magic](Mechanics/spells/detect-magic.md),\
    \ [fear](Mechanics/spells/fear.md), [invisibility](Mechanics/spells/invisibility.md)\
    \ (self only), [spider climb](Mechanics/spells/spider-climb.md), [tongues](Mechanics/spells/tongues.md)\n\
    \n2/day each: [cloudkill](Mechanics/spells/cloudkill.md), [dispel magic](Mechanics/spells/dispel-magic.md),\
    \ [plane shift](Mechanics/spells/plane-shift.md), [Tasha's hideous laughter](Mechanics/spells/tashas-hideous-laughter.md)"
  "name": "Spellcasting"
- "desc": "Magical darkness doesn't impede the shator's darkvision."
  "name": "Devil's Sight"
- "desc": "The shator has advantage on Wisdom ([Perception](Mechanics/Rules/skills.md#Perception))\
    \ checks that rely on smell."
  "name": "Keen Smell"
- "desc": "The shator has advantage on saving throws against spells and other magical\
    \ effects."
  "name": "Magic Resistance"
- "desc": "The shator's weapon attacks are magical."
  "name": "Magic Weapons"
"actions":
- "desc": "The shator makes one Bite attack or one Poisonous Spit attack (if available)\
    \ and then makes two Claws attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +12 to hit, reach 5 ft., one target. Hit: 16\
    \ (2d8 + 7) piercing damage plus 10 (3d6) acid damage."
  "name": "Bite"
- "desc": "Melee Weapon Attack: +12 to hit, reach 5 ft., one target. Hit: 11\
    \ (1d8 + 7) slashing damage plus 7 (2d6) acid damage."
  "name": "Claws"
- "desc": "The shator exhales poisonous spit in a 20-foot line that is 5 feet wide.\
    \ Each creature in that line must make a DC 18 Dexterity saving throw, taking\
    \ 22 (5d8) acid damage on a failed save and having the [paralyzed](Mechanics/Rules/conditions.md#Paralyzed)\
    \ condition for 1 minute. A creature can repeat the saving throw at the end of\
    \ each of its turns, ending the effect on a success."
  "name": "Poisonous Spit (Recharge 5-6)"
"bonus_actions":
- "desc": "The shator rolls a d6. A result of 1-2 summons in two allied [farastu\
    \ stalkers](Mechanics/bestiary/fiend/farastu-stalker-mabjov.md), a result of 3-4\
    \ summons in one allied [shator warden](Mechanics/bestiary/fiend/shator-warden-mabjov.md)."
  "name": "Summon Demodand (1/Day)"
"reactions":
- "desc": "When hit with a melee attack, the shator expels a toxic slime. The attacker\
    \ must succeed on a DC 18 Dexterity saving throw or have the [paralyzed](Mechanics/Rules/conditions.md#Paralyzed)\
    \ condition for 1 minute. A creature can repeat the saving throw at the end of\
    \ each of its turns, ending the effect on a success."
  "name": "Poisonous Slime"
"source":
- "MaBJoV"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/MaBJoV/Shator%20Warden.webp"
```
^statblock