---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/ghloe
- monster/cr/6
- monster/size/medium
- monster/type/humanoid/any-race
- monster/type/humanoid/fiend
aliases: ["Infernal Tormentor"]
---
# Infernal Tormentor
*Source: Grim Hollow: Lairs of Etharis p. 50*  

> [!quote]  
> 
> I knew when she pulled out a gold pen reeking of brimstone that I was making a mistake.

## Salvage

Aspiring fiends often possess special materials used in the drafting of infernal contracts. These include special inks and parchment worth up to 200 gp. These materials can also be used for scribing new spells into a spell book or crafting magic scrolls. Any existing contracts on the fiend's person burst into flames upon its death, which might damage other items.

## Lore

- **DC 10 Intelligence ([History](2-Mechanics/CLI/rules/skills.md#History)).** Fiends, or mortals taking on fiendish traits, can be found in every corner of Etharis, working their wiles on those foolish enough to sign one of their contracts. They are clever, deceitful, and evil to the core.  
- **DC 15 Intelligence ([Religion](2-Mechanics/CLI/rules/skills.md#Religion)).** A fiend's power and status are directly tied to the number and quality of mortal souls bound to it by contracts. Sometimes, the terms of such an agreement involve the mortal becoming a fiend itself, so a powerful fiend might have any number of lesser devils serving under it via contract.  
- **DC 20 Intelligence ([Arcana](2-Mechanics/CLI/rules/skills.md#Arcana)).** Fiends are natives of the Netherworld, and any fiend slain returns to that plane to reconstitute itself. Only powerful divine magic can banish a fiend permanently. Uttering a devil's true name, however, grants the speaker power over it.  

## Statblock

```ad-statblock
title: Infernal Tormentor
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/GHLoE/Infernal%20Tormentor.webp#token)
*Medium humanoid (any race, fiend), Any Evil alignment*

- **Armor Class** 16 ([half plate](2-Mechanics/CLI/items/half-plate-armor.md))
- **Hit Points** 97 (`13d8 + 39`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|18 (+4)|12 (+1)|16 (+3)|12 (+1)|13 (+1)|15 (+2)|

- **Proficiency Bonus** +3
- **Saving Throws** ⏤
- **Skills** Intimidation +5, Perception +4
- **Senses** darkvision 60 ft., passive Perception 14
- **Damage Resistances** fire
- **Languages** Infernal and one other language
- **Challenge** 6

## Actions

***Multiattack.*** The infernal tormentor makes two greatsword attacks. It can use infernal leash in place of one attack.

***Greatsword.*** *Melee Weapon Attack:* `dice:1d20+7|noform|text(+7)` to hit, reach 5 ft., one target. *Hit:* `dice:2d6+4|noform|avg|text(11)` (`2d6 + 4`) slashing damage and `dice:2d6|noform|avg|text(7)` (`2d6`) fire damage.

***Infernal Leash (Recharge 6).*** A flaming whip appears in the infernal tormentor's hand or from its greatsword and lashes at a creature the tormentor can see within 30 feet of it. The target must succeed on a DC 13 Charisma saving throw. A creature that has signed a fiendish contract has disadvantage on this save. On a failure, the creature takes `dice:4d6|noform|avg|text(14)` (`4d6`) fire damage, is pulled 10 feet closer to the tormentor, and is cursed for 1 minute or until the tormentor uses this action again. This curse also ends if the target enters hallowed ground.

While cursed, the target can't move more than 30 feet from the tormentor. Also while the curse lasts, the target takes `dice:2d6|noform|avg|text(7)` (`2d6`) extra fire damage from the tormentor's greatsword attacks. The tormentor can use a bonus action to move the target 10 feet to an unoccupied space within 30 feet of the tormentor. If this space is dangerous, the target receives a new saving throw before moving, ending the effect on itself on a success.
```
^statblock