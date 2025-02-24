---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/dsotdq
- monster/cr/4
- monster/size/large
- monster/type/monstrosity
aliases: ["Sivak Draconian"]
---
# Sivak Draconian
*Source: Dragonlance: Shadow of the Dragon Queen p. 199*  

Sivak draconians are fearsome brutes created from the eggs of silver dragons. They fly on mighty wings over battlefields wherever the fighting is the fiercest, making them effective shock troops. Sivaks can magically change their features to mimic the appearance of those they've slain. This allows these cunning soldiers to sow confusion and despair among their enemies. When sivaks are killed, their crumbling bodies mimic the form of their killers and shriek in agony.

## Draconians

Draconians are bipedal monsters born from metallic dragon eggs that have been corrupted by a combination of warped alchemy and the Dragon Queen's foul magic. The Dragon Armies closely guard the secret of the draconians' creation, allowing Krynn's metallic dragons to continue to think their eggs are being held hostage so they don't oppose the Dragon Queen's conquests.

## Statblock

```ad-statblock
title: Sivak Draconian
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/DSotDQ/Sivak%20Draconian.webp#token)
*Large monstrosity, typically  Lawful Evil*

- **Armor Class** 16 (natural armor)
- **Hit Points** 57 (`6d10 + 24`)
- **Speed** 30 ft., fly 60 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|18 (+4)|10 (+0)|18 (+4)|13 (+1)|10 (+0)|10 (+0)|

- **Proficiency Bonus** +2
- **Saving Throws** Strength +6, Wisdom +2
- **Skills** ⏤
- **Senses** darkvision 60 ft., passive Perception 10
- **Languages** Common, Draconic
- **Challenge** 4

## Traits

***Death Throes.*** When the draconian is reduced to 0 hit points by a creature that is Large or smaller, the draconian crumbles into dust that then forms a spectral, shrieking image of the creature that killed it. The image lasts for 1 minute. Each creature hostile to the draconian within 10 feet of the image must succeed on a DC 14 Wisdom saving throw or be [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened) of the spectral image for 1 minute. A [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened) creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

## Actions

***Multiattack.*** The draconian makes two Serrated Sword attacks and one Tail attack.

***Serrated Sword.*** *Melee Weapon Attack:* `dice:1d20+6|noform|text(+6)` to hit, reach 5 ft., one target. *Hit:* `dice:2d8+4|noform|avg|text(13)` (`2d8 + 4`) slashing damage.

***Tail.*** *Melee Weapon Attack:* `dice:1d20+6|noform|text(+6)` to hit, reach 5 ft., one target. *Hit:* `dice:1d8+4|noform|avg|text(8)` (`1d8 + 4`) bludgeoning damage. If the target is a Large or smaller creature, it must succeed on a DC 14 Strength saving throw or be knocked [prone](2-Mechanics/CLI/rules/conditions.md#Prone).

## Reactions

***Shape Theft.*** After the draconian kills a Medium or smaller Humanoid, the draconian magically cloaks itself in an illusion to look and feel like that creature while retaining the draconian's game statistics (other than its size). This transformation lasts until the draconian dies or uses a bonus action to end it.
```
^statblock