---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tdcsr
- monster/cr/12
- monster/size/huge
- monster/type/construct
statblock: inline
aliases: ["Adranach"]
---
# [Adranach](Mechanics\bestiary\construct/adranach-tdcsr.md)
*Source: Tal'Dorei Campaign Setting Reborn p. 224*  

An adranach is a winged feline construct made of raw arcane energy, fuchsia in hue and flecked with stars. It is an iconic servitor of the "League of Miracles", and the exact method of their creation is a closely guarded secret known only to the "Wonderworker" who guides that organization and the spellwrights who serve them.

## Perfect Obedience

As constructs, adranachs are unfailingly loyal servants to the spellwrights who created them. To the people of Tal'Dorei, they are best known as the creatures that allowed cities razed by the "Chroma Conclave" to be rebuilt in a matter of weeks, rather than years. But adranachs are also mighty combatants that serve their masters as hunters, bodyguards, and even assassins.

## Astral Body

An adranach's body is formed from the energy of the Astral Plane. Their claws and face, as well as a number of rune-inscribed braces on their body, are made of mithral and are necessary to keep their form of pure energy from losing cohesion. The methods for creating these mithral foundations and for binding astral energy to them are known only to the "Wonderworker" (the leader of the "League of Miracles") and the spellwrights who learn from them.

This secret knowledge is granted to worthy spellwrights in the form of an orb of mithral bands, about three feet in diameter, called a dormen. As the bands are removed and forged into the adranach's braces and mask, the dormen speaks aloud the instructions of how to craft an adranach in the magically recorded voice of the "Wonderworker".

## Mithral Mask

Each adranach has a unique mask crafted by its creator as their signature. This mask is crafted from pure mithral, and is the key to summoning and dismissing an adranach to a unique pocket dimension where it can rest and repair itself. When not in use, the mask magically shrinks from its true size to an easily concealable size fit for a humanoid face. Most spellwrights keep this mask in a chest stored on the Ethereal Plane with the [secret chest](Mechanics/spells/leomunds-secret-chest.md) spell, and only produce the mask when it is time to call their adranach forth.

## Master Adranach

The secretive master spellwrights of the "League of Miracles" are taught how to build adranachs of monumental size, with strength to match. These legendary constructs are also inevitably outfitted with unique enhancements of their creators' own devising, from upgraded espionage tools to the ability to sublimate their starry form and travel through the Astral Plane.

## Arcane Nature

An adranach doesn't require air, food, drink, or sleep.

```statblock
"name": "Adranach (TDCSR)"
"size": "Huge"
"type": "construct"
"alignment": "Unaligned"
"ac": !!int "17"
"ac_class": "natural armor"
"hp": !!int "170"
"hit_dice": "20d12 + 40"
"stats":
- !!int "23"
- !!int "16"
- !!int "14"
- !!int "8"
- !!int "14"
- !!int "11"
"speed": "40 ft., fly 60 ft."
"saves":
  "Dexterity": !!int "8"
  "Strength": !!int "11"
"skillsaves":
  "Athletics": !!int "11"
  "Perception": !!int "7"
"damage_resistances": "damage from spells"
"damage_immunities": "poison; bludgeoning, piercing, slashing from non-magical attacks"
"condition_immunities": "[charmed](Mechanics/Rules/conditions.md#Charmed), [exhaustion](Mechanics/Rules/conditions.md#Exhaustion),\
  \ [frightened](Mechanics/Rules/conditions.md#Frightened), [paralyzed](Mechanics/Rules/conditions.md#Paralyzed),\
  \ [petrified](Mechanics/Rules/conditions.md#Petrified), [poisoned](Mechanics/Rules/conditions.md#Poisoned)"
"senses": "darkvision 120 ft., passive Perception 17"
"languages": "understands the languages spoken by its creator but can't speak"
"cr": "12"
"traits":
- "desc": "When the adranach is reduced to half its hit point maximum (85 hit points),\
    \ its mithral mask cracks and its arcane form begins to waver, creating a field\
    \ of unstable magic around it. Any creature that starts its turn within 10 feet\
    \ of the adranach or enters that area for the first time on a turn takes 10 (3d6)\
    \ radiant damage. Additionally, if a creature casts a spell within this area,\
    \ it must make a DC 14 ability check using its spellcasting ability. On a failure,\
    \ the spell backfires, consuming the spell slot and dealing 3 (1d6) force damage\
    \ to the caster for each level of the spell slot that was consumed."
  "name": "Arcane Leak"
- "desc": "The adranach is immune to any spell or effect that would alter its form."
  "name": "Immutable Form"
- "desc": "The adranach has advantage on saving throws against spells and other magical\
    \ effects."
  "name": "Magic Resistance"
- "desc": "The adranach's weapon attacks are magical."
  "name": "Magic Weapons"
- "desc": "The adranach counts as one size larger when determining its carrying capacity\
    \ and the weight it can push, drag, or lift."
  "name": "Powerful Build"
"actions":
- "desc": "The adranach makes two attacks with its claws."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +11 to hit, one target, reach 5 ft. Hit: 32\
    \ (4d12 + 6) slashing damage."
  "name": "Claws"
- "desc": "The adranach targets up to four creatures it can see within 60 feet of\
    \ it. Each target must succeed on a DC 18 Dexterity saving throw or take 28 (8d6)\
    \ force damage."
  "name": "Force Bolts (Recharge 5-6)"
"source":
- "TDCSR"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/TDCSR/Adranach.webp"
```
^statblock