---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/ghloe
- monster/cr/12
- monster/size/gargantuan
- monster/type/plant
aliases: ["Ordeal Tree"]
---
# Ordeal Tree
*Source: Grim Hollow: Lairs of Etharis p. 39*  

> [!quote]  
> 
> In the primeval wood rises the ordeal tree. Should you hang from this hoary pillar of begone time for seven moons, you will gain power of the ancients.

## Salvage

The heartwood of an ordeal tree can be turned into an incense that, when inhaled, acts as a cure for removing powerful curses. Obtaining the wood requires a successful DC 15 Dexterity ([Sleight of Hand](2-Mechanics/CLI/rules/skills.md#Sleight%20of%20Hand)) check.

## Lore

- **DC 10 Intelligence ([Nature](2-Mechanics/CLI/rules/skills.md#Nature)).** Lashing yourself to an ordeal tree for 7 days can grant a petitioner power based on their heart's desire.  
- **DC 15 Intelligence ([History](2-Mechanics/CLI/rules/skills.md#History)).** The blessings of the ordeal tree often come with curses.  
- **DC 20 Intelligence ([Arcana](2-Mechanics/CLI/rules/skills.md#Arcana)).** Ordeal trees only grant their blessings to those whose hearts are evil.  

## Statblock

```ad-statblock
title: Ordeal Tree
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/GHLoE/Ordeal%20Tree.webp#token)
*Gargantuan plant, Neutral Evil*

- **Armor Class** 17 (natural armor)
- **Hit Points** 186 (`12d20 + 60`)
- **Speed** 20 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|24 (+7)| 7 (-2)|21 (+5)|12 (+1)|16 (+3)|12 (+1)|

- **Proficiency Bonus** +4
- **Saving Throws** ⏤
- **Skills** ⏤
- **Senses** passive Perception 13
- **Damage Vulnerabilities** fire
- **Damage Resistances** bludgeoning, piercing
- **Languages** Sylvan
- **Challenge** 12

## Traits

***Corrupt Desire.*** A humanoid may bind themselves to the ordeal tree. Each day the petitioner is bound to the tree, they must succeed on a Constitution saving throw with a DC equal to 15 + number of days bound or suffer a level of [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion). If they survive for 7 days, the ordeal tree may choose to grant a blessing. The tree only does this if the humanoid is evil, once per humanoid. If the humanoid is neutral or good, the tree attacks them.

The blessing is tailored to the petitioner's desires (GM discretion) but might include +1 to an ability score, a feat, expertise in a skill, or the ability to innately cast a 3rd-level (or lower) spell once per day using Charisma as the petitioner's spellcasting ability.

The petitioner also contracts the curse of foul blight (Grim Hallow Campaign Guide). If the petitioner commits a profoundly evil act every day, the curse never advances beyond stage 1. If the petitioner fails to commit the act, the curse automatically escalates.

***False Appearance.*** While the ordeal tree remains motionless, it is indistinguishable from a normal tree.

***Heart Sight.*** The ordeal tree knows the alignment and desires of any creature that binds itself to the tree.

## Actions

***Multiattack.*** The ordeal tree makes two slam attacks and one attack with a vine or enervate.

***Slam.*** *Melee Weapon Attack:* `dice:1d20+11|noform|text(+11)` to hit, reach 10 ft., one target. *Hit:* `dice:4d10+7|noform|avg|text(29)` (`4d10 + 7`) bludgeoning damage.

***Vine.*** *Melee Weapon Attack:* `dice:1d20+11|noform|text(+11)` to hit, reach 20 ft., one target. *Hit:* `dice:3d8+7|noform|avg|text(20)` (`3d8 + 7`) slashing damage, and the creature is [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) (escape DC 17).

***Enervate (2/Day).*** A creature bound to the ordeal tree or [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) by it must succeed on a DC 17 Constitution saving throw or suffer `dice:8d10|noform|avg|text(44)` (`8d10`) necrotic damage. The ordeal tree gains temporary hit points equal to half the damage done.
```
^statblock