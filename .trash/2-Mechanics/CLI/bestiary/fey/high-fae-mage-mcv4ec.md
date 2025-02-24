---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/mcv4ec
- monster/cr/12
- monster/size/medium
- monster/type/fey/sorcerer
aliases: ["High Fae Mage"]
---
# High Fae Mage
*Source: Monstrous Compendium Volume 3: 4: Eldraine Creatures*  

High fae mages are some of the mightiest magic users among the faeries of Eldraine. These skilled spellcasters have mastered the arcane art of dealmaking among the fae, magically negotiating themselves advantages in battle.

Like many high fae, these mages draw power from the latent energy found throughout the wilds of Eldraine. However, high fae mages also form strong bonds with the elemental powers of Eldraine, allowing the mages to call on forces like the eastern wind or the fiery hearth.

> [!quote] A quote from Chulane, Teller of Tales  
> 
> The high fae are capable of magic that would make even the great Gadwick himself seem little more than a clumsy apprentice.

## High Fae

Ageless and inhuman, high fae are the oldest creatures in Eldraine, embodying the natural splendor and danger of the wilderness. High fae have no regard for mortal values of honor and law, but they nonetheless operate under inviolable rules of their own: gifts must always be repaid, promises must be honored, and outright lies must never be spoken (though misdirection and riddles are always welcome). To amuse themselves over the long centuries of their lives, high fae frequently engage in deceptions and other complex games of wits against one another.

Most high fae remain secluded deep within the wilds of Eldraine. They draw power from motes of light found throughout the wilds, and they use their innate illusory magic to power and embellish their various weapons.

The high fae are ruled by Talion, the Kindly Lord. Talion is as strange, ancient, and fickle as the wilds of Eldraine, and the Kindly Lord demands fealty and respect from followers. Despite having an austere demeanor, the Kindly Lord is also known for following mysterious whims, journeying to the farthest reaches of Eldraine out of an insatiable curiosity.

## Statblock

```ad-statblock
title: High Fae Mage
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/MCV4EC/High%20Fae%20Mage.webp#token)
*Medium fey (sorcerer), Any alignment*

- **Armor Class** 14 (17 with [mage armor](2-Mechanics/CLI/spells/mage-armor.md))
- **Hit Points** 148 (`27d8 + 27`)
- **Speed** 30 ft., fly 30 ft. (hover)

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|11 (+0)|18 (+4)|12 (+1)|17 (+3)|15 (+2)|24 (+7)|

- **Proficiency Bonus** +4
- **Saving Throws** Intelligence +7, Wisdom +6, Charisma +11
- **Skills** Arcana +11, Investigation +7, Nature +7
- **Senses** darkvision 60 ft., passive Perception 12
- **Damage Resistances** bludgeoning, piercing, slashing from nonmagical attacks
- **Languages** Common, Sylvan
- **Challenge** 12

## Traits

***Magic Resistance.*** The high fae has advantage on saving throws against spells and other magical effects.

***Spellcasting.*** The high fae casts one of the following spells, requiring no material components and using Charisma as the spellcasting ability (spell save DC 19):

**At will**: [dancing lights](2-Mechanics/CLI/spells/dancing-lights.md), [detect magic](2-Mechanics/CLI/spells/detect-magic.md), [druidcraft](2-Mechanics/CLI/spells/druidcraft.md), [mage armor](2-Mechanics/CLI/spells/mage-armor.md) (self only)

**2/day each**: [faerie fire](2-Mechanics/CLI/spells/faerie-fire.md), [gust of wind](2-Mechanics/CLI/spells/gust-of-wind.md), [mirror image](2-Mechanics/CLI/spells/mirror-image.md)

## Actions

***Multiattack.*** The high fae makes two Elemental Strike attacks.

***Elemental Strike.*** *Melee or Ranged Spell Attack:* `dice:1d20+11|noform|text(+11)` to hit, reach 5 ft. or range 60 ft., one target. *Hit:* `dice:2d10+7|noform|avg|text(18)` (`2d10 + 7`) acid, cold, fire, force, lightning, or thunder damage (the high fae's choice).

***Negotiate Life (Recharge 5-6).*** The high fae enacts a magical bargain, siphoning energy from its opponents to heal its wounds. The high fae targets up to three creatures it can see within 60 feet of itself. Each target must make a DC 19 Constitution saving throw, taking `dice:4d12|noform|avg|text(26)` (`4d12`) necrotic damage on a failed save, or half as much damage on a successful one. The high fae then regains 30 hit points.

## Reactions

***Fae Counterspell.*** The high fae interrupts a creature it can see that is casting a spell with verbal, somatic, or material components. The caster takes `dice:3d6|noform|avg|text(10)` (`3d6`) psychic damage and must make a DC 19 Charisma saving throw. On a failed save, the spell fails and has no effect, but the spell slot used to cast it is not expended.
```
^statblock