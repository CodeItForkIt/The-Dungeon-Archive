---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/ggr
- monster/cr/14
- monster/size/medium
- monster/type/undead
aliases: ["Devkarin Lich"]
---
# Devkarin Lich
*Source: Guildmasters' Guide to Ravnica p. 198*  

Powerful spellcasters of the Devkarin elves, steeped in Golgari magic, can transcend death to become liches. For them, life and death don't merely chase each other in an inevitable cycle; the two can intersect, and at that nexus the liches find immense power, which commands the awe, envy, and fear of other Golgari.

Unlike the shambling zombies they command, liches retain their memories, their personalities, and especially their ambition. They also retain the grace and stature of living elves, but their bodies are in a constant state of slow decay. Various forms of fungus grow in and over the rotting flesh to hold the body together.

## Undead Nature

The lich doesn't require air, food, drink, or sleep.

## Statblock

```ad-statblock
title: Devkarin Lich
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/GGR/Devkarin%20Lich.webp#token)
*Medium undead, Neutral Evil*

- **Armor Class** 14 (natural armor)
- **Hit Points** 97 (`15d8 + 30`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|11 (+0)|16 (+3)|14 (+2)|19 (+4)|16 (+3)|15 (+2)|

- **Proficiency Bonus** +5
- **Saving Throws** Constitution +7, Intelligence +9, Wisdom +8
- **Skills** Arcana +14, Insight +8, Perception +8
- **Senses** truesight 120 ft., passive Perception 18
- **Damage Resistances** necrotic; bludgeoning, piercing, slashing from nonmagical attacks
- **Damage Immunities** poison
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** Common, Elvish, Kraul
- **Challenge** 14

## Traits

***Legendary Resistance (3/Day).*** If the lich fails a saving throw, it can choose to succeed instead.

***Regeneration.*** The lich regains 10 hit points at the start of its turn. If the lich takes fire or radiant damage, this trait doesn't function at the start of the lich's next turn. The lich dies only if it starts its turn with 0 hit points and doesn't regenerate.

***Turn Resistance.*** The lich has advantage on saving throws against any effect that turns undead.

***Undead Fortitude.*** If damage reduces the lich to 0 hit points, it must make a Constitution saving throw with a DC of 5 + the damage taken, unless the damage is radiant or from a critical hit. On a success, the lich drops to 1 hit point instead.

***Spellcasting.*** The lich is a 14th-level Golgari spellcaster. Its spellcasting ability is Intelligence (spell save DC 17, `dice:1d20+9|noform|text(+9)` to hit with spell attacks). The lich has the following wizard spells prepared:

**Cantrips (at will)**: [acid splash](2-Mechanics/CLI/spells/acid-splash.md), [chill touch](2-Mechanics/CLI/spells/chill-touch.md), [mage hand](2-Mechanics/CLI/spells/mage-hand.md), [poison spray](2-Mechanics/CLI/spells/poison-spray.md), [prestidigitation](2-Mechanics/CLI/spells/prestidigitation.md)

**1st level (4 slots)**: [chromatic orb](2-Mechanics/CLI/spells/chromatic-orb.md), [magic missile](2-Mechanics/CLI/spells/magic-missile.md), [ray of sickness](2-Mechanics/CLI/spells/ray-of-sickness.md)

**2nd level (3 slots)**: [Melf's acid arrow](2-Mechanics/CLI/spells/melfs-acid-arrow.md), [ray of enfeeblement](2-Mechanics/CLI/spells/ray-of-enfeeblement.md), [spider climb](2-Mechanics/CLI/spells/spider-climb.md), [web](2-Mechanics/CLI/spells/web.md)

**3rd level (3 slots)**: [animate dead](2-Mechanics/CLI/spells/animate-dead.md), [bestow curse](2-Mechanics/CLI/spells/bestow-curse.md), [fear](2-Mechanics/CLI/spells/fear.md), [vampiric touch](2-Mechanics/CLI/spells/vampiric-touch.md)

**4th level (3 slots)**: [blight](2-Mechanics/CLI/spells/blight.md), [Evard's black tentacles](2-Mechanics/CLI/spells/evards-black-tentacles.md)

**5th level (2 slots)**: [cloudkill](2-Mechanics/CLI/spells/cloudkill.md), [insect plague](2-Mechanics/CLI/spells/insect-plague.md)

**6th level (1 slots)**: [circle of death](2-Mechanics/CLI/spells/circle-of-death.md), [create undead](2-Mechanics/CLI/spells/create-undead.md)

**7th level (1 slots)**: [finger of death](2-Mechanics/CLI/spells/finger-of-death.md)

## Actions

***Noxious Touch.*** *Melee Spell Attack:* `dice:1d20+9|noform|text(+9)` to hit, reach 5 ft., one creature. *Hit:* `dice:4d6|noform|avg|text(14)` (`4d6`) poison damage, and the target must succeed on a DC 17 Constitution saving throw or be [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) for 1 minute. The [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

## Legendary Actions

***Cantrip.*** The lich casts one of its cantrips.

***Noxious Touch (Costs 2 Actions).*** The lich uses Noxious Touch.

***Disrupt Life (Costs 3 Actions).*** Each creature within 30 feet of the lich must make a DC 17 Constitution saving throw, taking `dice:6d6|noform|avg|text(21)` (`6d6`) necrotic damage on a failed save, or half as much damage on a successful one.
```
^statblock