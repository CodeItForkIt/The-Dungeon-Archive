---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/coa
- monster/cr/14
- monster/size/medium
- monster/type/humanoid
aliases: ["Ramius"]
---
# Ramius
*Source: Chains of Asmodeus p. 24*  

Ramius Dangremond is the commander of the Hellriders of Elturel. He never wanted the position, but because of the many deaths within the ranks of the order, he had to step up. His friend and fellow Hellrider, Barachiel, was the main reason he was able to grow into a capable commander. The loss of his friend saddens Ramius, and the news of his imprisonment within the Nine Hells gnaws at his soul.

Ramius is a natural horseman and a gifted athlete. The soldiers he leads often say that there isn't anything that Ramius can't mount or ride. He's ridden horses, mammoths, and machines into battle. Loyalty, honor, and duty are virtues that Ramius upholds. He fears nothing other than losing those he cares for.

```ad-statblock
title: Ramius
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/CoA/Ramius.webp#token)
*Medium humanoid, Neutral Good*

- **Armor Class** 22 ([plate](2-Mechanics/CLI/items/plate-armor.md), [+2 shield](2-Mechanics/CLI/items/2-shield.md))
- **Hit Points** 190 (`20d8 + 100`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|23 (+6)|10 (+0)|21 (+5)|11 (+0)|14 (+2)|18 (+4)|

- **Proficiency Bonus** +5
- **Saving Throws** Wisdom +7, Charisma +9
- **Skills** Animal Handling +12, Athletics +11, Insight +7, Religion +10
- **Senses** passive Perception 12
- **Damage Resistances** bludgeoning, piercing, slashing from nonmagical attacks; damage from spells
- **Languages** Abyssal, Celestial, Common, Infernal
- **Challenge** 14

## Traits

***Aura of Protection.*** Ramius and any ally that starts their turn within 30 feet of him have a +4 bonus to all saving throws and resistance to nonmagical damage.

***Spellcasting.*** Ramius casts one of the following spells, using Charisma as the spellcasting ability (spell save DC 17):

**1/day each**: [Aura of Purity](2-Mechanics/CLI/spells/aura-of-purity.md), [Compelled Duel](2-Mechanics/CLI/spells/compelled-duel.md), [Crusader's Mantle](2-Mechanics/CLI/spells/crusaders-mantle.md), [Death Ward](2-Mechanics/CLI/spells/death-ward.md), [Dispel Evil and Good](2-Mechanics/CLI/spells/dispel-evil-and-good.md), [Find Steed](2-Mechanics/CLI/spells/find-steed.md), [Lesser Restoration](2-Mechanics/CLI/spells/lesser-restoration.md), [Remove Curse](2-Mechanics/CLI/spells/remove-curse.md), [Revivify](2-Mechanics/CLI/spells/revivify.md), [Shield of Faith](2-Mechanics/CLI/spells/shield-of-faith.md)

## Actions

***Multiattack.*** Ramius makes two Longsword attacks.

***Longsword.*** *Melee Weapon Attack:* `dice:1d20+11|noform|text(+11)` to hit, reach 5ft., one target. *Hit:* `dice:1d8+6|noform|avg|text(10)` (`1d8 + 6`) slashing damage or `dice:1d10+6|noform|avg|text(11)` (`1d10 + 6`) if wielded in two hands, plus `dice:3d8|noform|avg|text(13)` (`3d8`) radiant damage. If the target is an evil creature, it must succeed on a DC 17 Charisma saving throw or take an additional `dice:3d8|noform|avg|text(13)` (`3d8`) radiant damage.

***Divine Wave (Recharge 6).*** Ramius strikes the ground and causes holy energy to radiate outwards. Each creature of his choice within 30 feet of him must make a DC 17 Constitution saving throw. Targets take `dice:6d6|noform|avg|text(21)` (`6d6`) thunder damage plus `dice:6d6|noform|avg|text(21)` (`6d6`) radiant damage on a failed save, or half as much damage on a successful one. Creatures that fail the save are knocked down (have the [prone](2-Mechanics/CLI/rules/conditions.md#Prone) condition).

## Reactions

***Healing Touch.*** As a reaction to Ramius or an adjacent creature taking 50 points or more of damage, Ramius reaches out and channels divine energy, healing `dice:2d8+4|noform|avg|text(13)` (`2d8 + 4`) hit points.
```
^statblock