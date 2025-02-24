---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/erlw
- monster/cr/6
- monster/size/medium
- monster/type/fey
aliases: ["Dusk Hag"]
---
# Dusk Hag
*Source: Eberron: Rising from the Last War p. 292*  

Dusk hags resemble gnarled crones with shriveled orange skin, tangled gray hair, and eyes that burn like hot coals. They see visions of the future in their dreams, and their dark magic allows them to influence the dreams of others, sending messages or inflicting nightmares with a touch. Tales talk of ambitious wizards, frantic monarchs, and desperate heroes undertaking quests or making bargains with a dusk hag in exchange for its prophecies and visions of the future. But the information gained from a dusk hag often has a way of causing more pain than joy. Like all hags, dusk hags enjoy causing strife to those who bargain with them, and find ways to twist and turn promises to their own advantage. The Dusk Hag Prophecies table provides examples of the sort of dreams dusk hags might share with unsuspecting sleepers.

**Dusk Hag Prophecies**

`dice: [](dusk-hag-erlw.md#^dusk-hag-prophecies)`

| dice: d10 | Prophecy |
|-----------|----------|
| 1 | "A red hat approaches with ill intent. Be wary." |
| 2 | "A ship comes on a sea of bones, but treasure waits behind a silver skull." |
| 3 | "Three days, three deaths, three eyes, three breaths." |
| 4 | "Doom falls on the peacock and the sparrow alike. Best be a raven." |
| 5 | "A white hand on a black field holds the golden key." |
| 6 | "Beware the black horse." |
| 7 | "The fish is your friend." |
| 8 | "The stairs downward lead to that which you seek." |
| 9 | "Look for two crossed swords. There your goal lies." |
| 10 | "If you see two crows, turn back. Beyond is death." |
^dusk-hag-prophecies

```ad-statblock
title: Dusk Hag
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ERLW/Dusk%20Hag.webp#token)
*Medium fey, Neutral Evil*

- **Armor Class** 17 (natural armor)
- **Hit Points** 82 (`15d8 + 15`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|11 (+0)|14 (+2)|12 (+1)|17 (+3)|16 (+3)|18 (+4)|

- **Proficiency Bonus** +3
- **Saving Throws** Intelligence +6, Wisdom +6
- **Skills** Deception +7, Insight +6, Perception +6
- **Senses** blindsight 60 ft., passive Perception 16
- **Condition Immunities** [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded), [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened)
- **Languages** Common, Giant, Infernal
- **Challenge** 6

## Traits

***Magic Resistance.*** The hag has advantage on saving throws against spells and other magical effects.

***Innate Spellcasting.*** The hag's spellcasting ability is Charisma (spell save DC 15). She can innately cast the following spells, requiring no material components:

**At will**: [detect magic](2-Mechanics/CLI/spells/detect-magic.md), [disguise self](2-Mechanics/CLI/spells/disguise-self.md)

**1/day each**: [legend lore](2-Mechanics/CLI/spells/legend-lore.md), [scrying](2-Mechanics/CLI/spells/scrying.md)

**3/day each**: [dream](2-Mechanics/CLI/spells/dream.md), [hypnotic pattern](2-Mechanics/CLI/spells/hypnotic-pattern.md), [sleep](2-Mechanics/CLI/spells/sleep.md) (`dice:9d8|noform|avg` (`9d8`))

## Actions

***Multiattack.*** The hag makes two Nightmare Touch attacks.

***Claws.*** *Melee Weapon Attack:* `dice:1d20+5|noform|text(+5)` to hit, reach 5 ft., one target. *Hit:* `dice:1d6+2|noform|avg|text(5)` (`1d6 + 2`) slashing damage.

***Nightmare Touch.*** *Melee Spell Attack:* `dice:1d20+7|noform|text(+7)` to hit, reach 5 ft., one creature. *Hit:* `dice:4d6+4|noform|avg|text(18)` (`4d6 + 4`) psychic damage. If the target is [unconscious](2-Mechanics/CLI/rules/conditions.md#Unconscious), it takes an extra `dice:3d6|noform|avg|text(10)` (`3d6`) psychic damage and is cursed until the hag dies or the curse is removed. The cursed creature's hit point maximum decreases by `dice:1d10|noform|avg|text(5)` (`1d10`) whenever it finishes a long rest.

## Reactions

***Dream Eater.*** When an [unconscious](2-Mechanics/CLI/rules/conditions.md#Unconscious) creature the hag can see within 30 feet of her regains consciousness, the hag can force the creature to make a DC 15 Wisdom saving throw. Unless the save succeeds, the creature takes `dice:2d10|noform|avg|text(11)` (`2d10`) psychic damage, and the hag regains hit points equal to the amount of damage taken.
```
^statblock