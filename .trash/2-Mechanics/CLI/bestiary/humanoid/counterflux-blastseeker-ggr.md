---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/ggr
- monster/cr/2
- monster/size/medium
- monster/type/humanoid/any-race
aliases: ["Counterflux Blastseeker"]
---
# Counterflux Blastseeker
*Source: Guildmasters' Guide to Ravnica p. 242*  

While chemisters focus on inventing new tools, weapons, and other devices for the guild to use, the role of a blastseeker is to put those devices to work. Despite the name, not all such devices produce explosions, but all the most interesting ones (from the Izzet perspective) do.

```ad-statblock
title: Counterflux Blastseeker
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/GGR/Counterflux%20Blastseeker.webp#token)
*Medium humanoid (any race), Chaotic Neutral*

- **Armor Class** 13 (16 with [mage armor](2-Mechanics/CLI/spells/mage-armor.md))
- **Hit Points** 39 (`6d8 + 12`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|13 (+1)|16 (+3)|15 (+2)|18 (+4)|11 (+0)|14 (+2)|

- **Proficiency Bonus** +2
- **Saving Throws** Constitution +4, Wisdom +2
- **Skills** Arcana +6, Perception +2
- **Senses** passive Perception 12
- **Languages** Common plus any one language
- **Challenge** 2

## Traits

***Counterflux Overcast (Recharge 5-6).*** The blastseeker can create an additional effect immediately after casting a spell. Roll a `dice:d6|noform|avg` (`d6`) to determine the effect:

- **1–3..** The blastseeker creates a 15-foot-radius [invisible](2-Mechanics/CLI/rules/conditions.md#Invisible) sphere centered on itself that lasts until the end of its next turn. Creatures in the sphere have disadvantage on saving throws against spells and other magical effects.  
- **4–6..** The blastseeker creates a 15-foot-radius [invisible](2-Mechanics/CLI/rules/conditions.md#Invisible) sphere centered on itself that lasts until the end of its next turn. Creatures in the sphere have advantage on saving throws against spells and other magical effects.  

***Innate Spellcasting.*** The blastseeker's innate spellcasting ability is Intelligence (spell save DC 14, `dice:1d20+6|noform|text(+6)` to hit with spell attacks). The blastseeker can innately cast the following spells, requiring no components other than its Izzet gear, which doesn't function for others:

**1/day each**: [counterspell](2-Mechanics/CLI/spells/counterspell.md), [dispel magic](2-Mechanics/CLI/spells/dispel-magic.md), [protection from energy](2-Mechanics/CLI/spells/protection-from-energy.md)

**3/day each**: [enlarge/reduce](2-Mechanics/CLI/spells/enlarge-reduce.md), [mage armor](2-Mechanics/CLI/spells/mage-armor.md) (self only), [scorching ray](2-Mechanics/CLI/spells/scorching-ray.md)

## Actions

***Rapier.*** *Melee Weapon Attack:* `dice:1d20+5|noform|text(+5)` to hit, reach 5 ft., one target. *Hit:* `dice:1d8+3|noform|avg|text(7)` (`1d8 + 3`) piercing damage.
```
^statblock