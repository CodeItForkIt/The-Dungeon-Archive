---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/erlw
- monster/cr/5
- monster/size/medium
- monster/type/humanoid/any-race
aliases: ["Bone Knight"]
---
# Bone Knight
*Source: Eberron: Rising from the Last War p. 316*  

Bone knights are the champions of the Order of the Emerald Claw. Clad in distinctive bonecraft armor—heavy armor adorned with the bones of fallen enemies—these fearsome warriors command squads of undead soldiers as they pursue the sinister goals of Lady Illmarrow.

## Karrnathi Patriots

Early in the Last War, Karrnath turned to the necromancers of the Blood of Vol to bolster the nation's army with undead forces. The skeletons and zombies created by the necromancers were mindless creatures that required guidance. The first bone knights were appointed to provide this control.

Devoted paladins of the Blood of Vol were fused into suits of bonecraft armor, whose magic focused their divine gifts, allowing them to command units of mindless undead. Bonecraft armor can't be removed without killing the knight who wears it, and when donning it, each bone knight understood that their former life was over.

## The Fall of the Emerald Claw

During the Last War, many bone knights took service with the Order of the Emerald Claw, helping that name strike fear into the enemies of Karrnath. In the last decade, King Kaius III of Karrnath has done much to ensure a peaceful end to the Last War. Under the terms of the Treaty of Thronehold, Kaius sealed most of Karrnath's undead in deep vaults, and the Order of the Emerald Claw was disbanded. A few bone knights remained in service to the crown, but most were cast aside—still bound to their bonecraft armor and still convinced of Karrnathi supremacy. These bone knights felt that Kaius had betrayed both them and their nation, leading their once-proud order to find a new purpose in the service of Lady Illmarrow.

## Statblock

```ad-statblock
title: Bone Knight
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ERLW/Bone%20Knight.webp#token)
*Medium humanoid (any race), Any Non-Good alignment*

- **Armor Class** 20 (bonecraft armor)
- **Hit Points** 84 (`13d8 + 26`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|18 (+4)|13 (+1)|14 (+2)|12 (+1)|14 (+2)|16 (+3)|

- **Proficiency Bonus** +3
- **Saving Throws** Wisdom +5, Charisma +6
- **Skills** Athletics +7, Deception +6, Intimidation +6
- **Senses** passive Perception 12
- **Damage Resistances** necrotic, poison
- **Languages** any one language (usually Common)
- **Challenge** 5

## Traits

***Commander of Bones.*** As a bonus action, the knight can target one skeleton or zombie it can see within 30 feet of it. The target must make a DC 14 Wisdom saving throw. On a failed save, the target must obey the knight's commands until the knight dies or until the knight releases it as a bonus action. The knight can command up to twelve undead at a time this way.

***Master of the Pallid Banner.*** While within 60 feet of the knight, any undead ally of the knight has advantage on saving throws against any effect that turns undead.

***Spellcasting.*** The knight is an 8th-level spellcaster. Its spellcasting ability is Charisma (spell save DC 14, `dice:1d20+6|noform|text(+6)` to hit with spell attacks). It has the following paladin spells prepared:

**1st level (4 slots)**: [command](2-Mechanics/CLI/spells/command.md), [compelled duel](2-Mechanics/CLI/spells/compelled-duel.md), [hellish rebuke](2-Mechanics/CLI/spells/hellish-rebuke.md), [wrathful smite](2-Mechanics/CLI/spells/wrathful-smite.md)

**2nd level (3 slots)**: [branding smite](2-Mechanics/CLI/spells/branding-smite.md), [crown of madness](2-Mechanics/CLI/spells/crown-of-madness.md), [darkness](2-Mechanics/CLI/spells/darkness.md), [find steed](2-Mechanics/CLI/spells/find-steed.md), [magic weapon](2-Mechanics/CLI/spells/magic-weapon.md)

## Actions

***Multiattack.*** The knight attacks twice with one of its weapons.

***Greatsword.*** *Melee Weapon Attack:* `dice:1d20+7|noform|text(+7)` to hit, reach 5 ft., one target. *Hit:* `dice:2d6+4|noform|avg|text(11)` (`2d6 + 4`) slashing damage.

***Longbow.*** *Ranged Weapon Attack:* `dice:1d20+4|noform|text(+4)` to hit, range 150/600 ft., one target. *Hit:* `dice:1d8+1|noform|avg|text(5)` (`1d8 + 1`) piercing damage.
```
^statblock