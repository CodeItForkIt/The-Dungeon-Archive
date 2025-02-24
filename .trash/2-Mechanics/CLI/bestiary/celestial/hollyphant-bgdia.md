---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/bgdia
- monster/cr/5
- monster/size/small
- monster/type/celestial
aliases: ["Hollyphant"]
---
# Hollyphant
*Source: Baldur's Gate: Descent Into Avernus p. 237*  

Hollyphants are gentle, stalwart creatures native to the Upper Planes. Good-aligned deities and angels use them as messengers and helpers. Hollyphants treasure friendship and honesty.

A hollyphant looks like a miniature elephant with luminous gold fur and small, rapidly fluttering wings that not only hold it aloft but also propel it at great speed. Although kind, a hollyphant won't bear witness to an evil act without punishing the malefactor. Its pearlescent tusks are far from formidable, but it can unleash trumpet blasts from its trunk that can deafen creatures or engulf evildoers in radiant sparkles of positive energy. A hollyphant is also blessed with powerful innate magic to help it combat evil and protect its friends.

```ad-statblock
title: Hollyphant
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/BGDIA/Hollyphant.webp#token)
*Small celestial, Lawful Good*

- **Armor Class** 18 (natural armor)
- **Hit Points** 36 (`8d6 + 8`)
- **Speed** 20 ft., fly 120 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|10 (+0)|11 (+0)|12 (+1)|16 (+3)|19 (+4)|16 (+3)|

- **Proficiency Bonus** +3
- **Saving Throws** Dexterity +3, Constitution +4, Charisma +6
- **Skills** ⏤
- **Senses** passive Perception 14
- **Damage Resistances** bludgeoning, piercing, slashing from nonmagical attacks
- **Damage Immunities** poison
- **Condition Immunities** [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** Celestial, telepathy 120 ft.
- **Challenge** 5

## Traits

***Aura of Invulnerability.*** An [invisible](2-Mechanics/CLI/rules/conditions.md#Invisible) aura forms a 10-foot-radius sphere around the hollyphant for as long as it lives. Any spell of 5th level or lower cast from outside the barrier can't affect creatures or objects within it, even if the spell is cast using a higher level spell slot. Such a spell can target creatures and objects within the barrier, but the spell has no effect on them. Similarly, the area within the barrier is excluded from the areas affected by such spells. The hollyphant can use an action to suppress this trait until its [concentration](2-Mechanics/CLI/rules/conditions.md#Concentration) ends (as if concentrating on a spell).

***Magic Weapons.*** The hollyphant's weapon attacks are magical.

***Innate Spellcasting.*** The hollyphant's innate spellcasting ability is Wisdom (spell save DC 15). It can innately cast the following spells, requiring no material components:

**At will**: [light](2-Mechanics/CLI/spells/light.md)

**1/day each**: [banishment](2-Mechanics/CLI/spells/banishment.md), [heal](2-Mechanics/CLI/spells/heal.md), [raise dead](2-Mechanics/CLI/spells/raise-dead.md), [shapechange](2-Mechanics/CLI/spells/shapechange.md) (into a golden-furred [mammoth](2-Mechanics/CLI/bestiary/beast/mammoth.md) with feathered wings and a flying speed of 120 ft.), [teleport](2-Mechanics/CLI/spells/teleport.md) (with no chance of error)

**2/day each**: [bless](2-Mechanics/CLI/spells/bless.md), [cure wounds](2-Mechanics/CLI/spells/cure-wounds.md), [protection from evil and good](2-Mechanics/CLI/spells/protection-from-evil-and-good.md)

## Actions

***Tusks.*** *Melee Weapon Attack:* `dice:1d20+3|noform|text(+3)` to hit, reach 5 ft., one target. *Hit:* `dice:1d6|noform|avg|text(3)` (`1d6`) piercing damage.

***Trumpet (3/Day).*** The hollyphant blows air through its trunk, creating a trumpet sound that can be heard out to a range of 600 feet. The trumpet also creates a 30-foot cone of energy that has one of the following effects, chosen by the hollyphant:

***Trumpet of Blasting.*** Each creature in the cone must make a DC 14 Constitution saving throw. On a failed save, a creature takes `dice:5d6|noform|avg|text(17)` (`5d6`) thunder damage and is [deafened](2-Mechanics/CLI/rules/conditions.md#Deafened) for 1 minute. On a successful save, a creature takes half as much damage and isn't [deafened](2-Mechanics/CLI/rules/conditions.md#Deafened). Nonmagical objects in the cone that aren't being held or worn take `dice:10d6|noform|avg|text(35)` (`10d6`) thunder damage.

***Trumpet of Sparkles.*** Creatures in the cone must make a DC 14 Constitution saving throw, taking `dice:4d8+4|noform|avg|text(22)` (`4d8 + 4`) radiant damage on a failed save, or half as much damage on a successful one. Evil creatures have disadvantage on the saving throw. Good creatures in the cone take no damage.
```
^statblock