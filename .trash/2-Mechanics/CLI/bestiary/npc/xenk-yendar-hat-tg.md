---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/hat-tg
- monster/cr/10
- monster/size/medium
- monster/type/humanoid/paladin
aliases: ["Xenk Yendar"]
---
# Xenk Yendar
*Source: Honor Among Thieves: Thieves' Gallery*  

Raised in the nation of Thay, Xenk Yendar has sworn an oath of devotion to aid the innocent. Every inch the knight in shining armor, he thrives when inspiring goodness in his allies. The words "Neither virtue nor blade shall break" are etched in Celestial on the blade of his daggersword.

Xenk ages more slowly than a normal human, and with this gift comes the burden of perspective. His longevity has something to do with Szass Tam's nightmarish rise to power and Xenk's narrow escape from the lich.

Now based in Mornbryn's Shield, Xenk travels Faerûn in search of evil to thwart. He approaches problems with absolute seriousness of purpose—an outlook that clashes with Edgin's nonchalance.

```ad-statblock
title: Xenk Yendar
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/HAT-TG/Xenk%20Yendar.webp#token)
*Medium humanoid (paladin), Lawful Good*

- **Armor Class** 15 ([half plate](2-Mechanics/CLI/items/half-plate-armor.md))
- **Hit Points** 157 (`21d8 + 63`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|19 (+4)|11 (+0)|16 (+3)|14 (+2)|16 (+3)|17 (+3)|

- **Proficiency Bonus** +4
- **Saving Throws** Strength +8, Charisma +7
- **Skills** Athletics +8, History +6, Insight +7, Survival +7
- **Senses** darkvision 60 ft., passive Perception 13
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** Common, Thayan, Undercommon
- **Challenge** 10

## Traits

***Aura of Protection.*** Xenk and his allies within 10 feet of him have advantage on saving throws.

## Actions

***Multiattack.*** Xenk makes three Daggersword attacks and uses Daggersword Flourish. He can replace Daggersword Flourish with Cleansing Touch if it's available.

***Daggersword.*** Choose the attack that corresponds to the daggersword's current form (see Daggersword Shift below):

***Longsword.*** *Melee Weapon Attack:* `dice:1d20+8|noform|text(+8)` to hit, reach 5 ft., one target. *Hit:* `dice:1d8+4|noform|avg|text(8)` (`1d8 + 4`) slashing damage, or `dice:1d10+4|noform|avg|text(9)` (`1d10 + 4`) slashing damage if used with two hands, plus `dice:1d12|noform|avg|text(6)` (`1d12`) radiant damage.

***Shortsword and Dagger.*** *Melee Weapon Attack:* `dice:1d20+8|noform|text(+8)` to hit, reach 5 ft., one target. *Hit:* `dice:1d6+4|noform|avg|text(7)` (`1d6 + 4`) piercing damage plus `dice:1d12|noform|avg|text(6)` (`1d12`) radiant damage.

***Daggersword Flourish.*** Choose the option that corresponds to the daggersword's current form (see Daggersword Shift below):

***Longsword.*** Xenk magically detaches the longsword's blade from its hilt, launching the blade at a creature he can see within 30 feet of himself. The target must make a DC 16 Dexterity saving throw. On a failed save, the target is impaled by the blade, taking `dice:3d6+4|noform|avg|text(14)` (`3d6 + 4`) piercing damage, and is knocked [prone](2-Mechanics/CLI/rules/conditions.md#Prone). At the end of the current turn, the blade magically reattaches to its hilt.

***Shortsword and Dagger.*** Xenk lashes out with both weapons. Each creature of his choice within 10 feet of him must make a DC 16 Dexterity throw. On a failed save, the creature takes `dice:2d6|noform|avg|text(7)` (`2d6`) piercing damage and has disadvantage on attack rolls until the start of Xenk's next turn. On a successful save, the creature takes half as much damage and suffers no other effect.

***Cleansing Touch (1/Day).*** Xenk touches a creature within 5 feet of himself. The target magically regains `dice:6d8|noform|avg|text(27)` (`6d8`) hit points and gains the benefit of a [lesser restoration](2-Mechanics/CLI/spells/lesser-restoration.md) spell.

## Bonus Actions

***Daggersword Shift.*** Xenk changes the form of his daggersword, choosing one of the following forms: a longsword, or a shortsword in one hand and a dagger in the other.
```
^statblock