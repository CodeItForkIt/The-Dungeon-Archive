---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/qftis
- monster/cr/2
- monster/size/medium
- monster/type/humanoid
aliases: ["Champion of Usamigaras"]
---
# Champion of Usamigaras
*Source: Quests from the Infinite Staircase p. 206*  

Champions are blessed by Usamigaras to advance the faction by any means necessary. They boast a greater repertoire of spells than their fellows and can radiate an aura of illusions to confuse their foes.

## Mages of Usamigaras

The Mages of Usamigaras are Cynidicean spellcasters who worship Usamigaras, a god of magic, messengers, and lies. They hide their identities and intentions behind silver masks depicting the face of their god. Secrecy is key among the Mages of Usamigaras. Members whisper in the presence of outsiders and pepper their speech with lies, even obvious ones. Such behavior isn't rude among members, who view deceit as worthy of celebration, not chastisement.

## Statblock

```ad-statblock
title: Champion of Usamigaras
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/QftIS/Champion%20of%20Usamigaras.webp#token)
*Medium humanoid, typically  Chaotic Neutral*

- **Armor Class** 12 (15 with [mage armor](2-Mechanics/CLI/spells/mage-armor.md))
- **Hit Points** 33 (`6d8 + 6`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|10 (+0)|14 (+2)|12 (+1)|17 (+3)|14 (+2)|15 (+2)|

- **Proficiency Bonus** +2
- **Saving Throws** Intelligence +5, Charisma +4
- **Skills** Arcana +5, Deception +6, Sleight of Hand +4
- **Senses** passive Perception 12
- **Languages** Common
- **Challenge** 2

***Spellcasting.*** The champion casts one of the following spells, using Intelligence as the spellcasting ability (spell save DC 13):

**At will**: [Light](2-Mechanics/CLI/spells/light.md), [Mage Armor](2-Mechanics/CLI/spells/mage-armor.md) (self only), [Mage Hand](2-Mechanics/CLI/spells/mage-hand.md), [Minor Illusion](2-Mechanics/CLI/spells/minor-illusion.md)

**1/day each**: [Crown of Madness](2-Mechanics/CLI/spells/crown-of-madness.md), [Shatter](2-Mechanics/CLI/spells/shatter.md)

**2/day each**: [Charm Person](2-Mechanics/CLI/spells/charm-person.md), [Disguise Self](2-Mechanics/CLI/spells/disguise-self.md), [Silent Image](2-Mechanics/CLI/spells/silent-image.md)

## Actions

***Multiattack.*** The champion makes two Arcane Burst attacks or makes one Arcane Burst attack and uses Spellcasting.

***Arcane Burst.*** *Melee or Ranged Spell Attack:* `dice:1d20+5|noform|text(+5)` to hit, reach 5 ft. or range 120 ft., one target. *Hit:* `dice:1d10+3|noform|avg|text(8)` (`1d10 + 3`) force damage.

## Bonus Actions

***Aura of Deception (1/Day).*** The champion emits an aura of ghostly illusions that fills a 10-foot-radius sphere centered on itself. While this aura is active, creatures have disadvantage on attack rolls against the champion and any of the champion's allies that are in the aura. The aura moves with the champion and lasts for 1 minute, until the champion has the [incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated) condition, or until the champion uses another bonus action to end the aura.
```
^statblock