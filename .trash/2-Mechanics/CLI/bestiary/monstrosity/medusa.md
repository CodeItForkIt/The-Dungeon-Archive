---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/mm
- monster/cr/6
- monster/environment/desert
- monster/size/medium
- monster/type/monstrosity
aliases: ["Medusa"]
---
# Medusa
*Source: Monster Manual p. 214, Waterdeep: Dungeon of the Mad Mage, Ghosts of Saltmarsh, Baldur's Gate: Descent Into Avernus, Eberron: Rising from the Last War, Infernal Machine Rebuild, Candlekeep Mysteries, Sigil and the Outlands, Dungeons of Drakkenheim. Available in the <span title='Systems Reference Document (5.1)'>SRD</span> and the Basic Rules (2014)*  

As deadly as they are ravishing, the serpent-haired medusas suffer an immortal curse brought on by their vanity. They lurk in quiet exile among the tumbled ruins of their former lives, surrounded by the petrified remains of past admirers and would-be heroes.

## Immortal Splendor

Men and women who desire eternal youth, beauty, and adoration might pray to malicious gods, beg dragons for ancient magic, or seek out powerful archmages to fulfill their wishes. Others make sacrifices to demon lords or archdevils, offering all in exchange for this gift, oblivious to the curse that accompanies it. Those who strike such bargains gain physical beauty, restored youth, immortality, and the adoration of all who behold them, granting them the influence and power they so desire. However, after years of the living like a demigod among mortals, the price for their vanity and hubris is exacted, and they are forever transformed into medusas. A medusa's hair turns into a nest of venomous serpents, and all who gaze upon the medusa are [petrified](2-Mechanics/CLI/rules/conditions.md#Petrified), becoming stone monuments to its corruption.

## Medusa Lairs

Medusas live forever in seclusion, alienated from the world around them by their monstrous form and caprice. Their homes gradually fall into disrepair until they are little more than shadowy ruins covered with thorns and creepers, riddled with obstructions and hiding places. Foolhardy looters and adventurers who enter are often unaware of the medusa's presence until the creature is among them.

A medusa is subject to its own curse. By looking vainly on its reflection, it turns to stone as surely as any living mortal. As a result, a medusa destroys or removes any mirrors or reflective surfaces in its lair.

## Statblock

```ad-statblock
title: Medusa
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/MM/Medusa.webp#token)
*Medium monstrosity, Lawful Evil*

- **Armor Class** 15 (natural armor)
- **Hit Points** 127 (`17d8 + 51`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|10 (+0)|15 (+2)|16 (+3)|12 (+1)|13 (+1)|15 (+2)|

- **Proficiency Bonus** +3
- **Saving Throws** ⏤
- **Skills** Deception +5, Insight +4, Perception +4, Stealth +5
- **Senses** darkvision 60 ft., passive Perception 14
- **Languages** Common
- **Challenge** 6

## Traits

***Petrifying Gaze.*** When a creature that can see the medusa's eyes starts its turn within 30 feet of the medusa, the medusa can force it to make a DC 14 Constitution saving throw if the medusa isn't [incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated) and can see the creature. If the saving throw fails by 5 or more, the creature is instantly [petrified](2-Mechanics/CLI/rules/conditions.md#Petrified). Otherwise, a creature that fails the save begins to turn to stone and is [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained). The [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) creature must repeat the saving throw at the end of its next turn, becoming [petrified](2-Mechanics/CLI/rules/conditions.md#Petrified) on a failure or ending the effect on a success. The petrification lasts until the creature is freed by the  [greater restoration](2-Mechanics/CLI/spells/greater-restoration.md) spell or other magic.

Unless [surprised](2-Mechanics/CLI/rules/conditions.md#Surprised), a creature can avert its eyes to avoid the saving throw at the start of its turn. If the creature does so, it can't see the medusa until the start of its next turn, when it can avert its eyes again. If the creature looks at the medusa in the meantime, it must immediately make the save.

If the medusa sees itself reflected on a polished surface within 30 feet of it and in an area of bright light, the medusa is, due to its curse, affected by its own gaze.

## Actions

***Multiattack.*** The medusa makes either three melee attacks—one with its snake hair and two with its shortsword—or two ranged attacks with its longbow.

***Snake Hair.*** *Melee Weapon Attack:* `dice:1d20+5|noform|text(+5)` to hit, reach 5 ft., one creature. *Hit:* `dice:1d4+2|noform|avg|text(4)` (`1d4 + 2`) piercing damage plus `dice:4d6|noform|avg|text(14)` (`4d6`) poison damage.

***Shortsword.*** *Melee Weapon Attack:* `dice:1d20+5|noform|text(+5)` to hit, reach 5 ft., one target. *Hit:* `dice:1d6+2|noform|avg|text(5)` (`1d6 + 2`) piercing damage.

***Longbow.*** *Ranged Weapon Attack:* `dice:1d20+5|noform|text(+5)` to hit, range 150/600 ft., one target. *Hit:* `dice:1d8+2|noform|avg|text(6)` (`1d8 + 2`) piercing damage plus `dice:2d6|noform|avg|text(7)` (`2d6`) poison damage.
```
^statblock

## Environment

desert