---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/4
- monster/environment/mountain
- monster/size/tiny
- monster/type/fey
aliases: ["Bereginyas"]
---
# Bereginyas
*Source: Tome of Beasts 1 (2023 Edition) p. 36*  

*These small, winged faeries appear to be made of gray mist, and they can conceal themselves completely in the fogbanks and clouds enshrouding their mountainous lairs.*

## Mist Dancers

These evil, cunning faeries (whose name means "mist dancers" in Old Elvish) overcome their victims by seeping into the creature's lungs to choke it on the bereginyas's foul essence.

## Mountain Spirits

They are most commonly found in the highest mountain ranges, often above the tree line, but they can be encountered in any foggy or misty mountainous region. Shepherds and goatherds often leave bits of milk or cheese to placate them, particularly during the spring lambing season.

## Statblock

```ad-statblock
title: Bereginyas
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Bereginyas.webp#token)
*Tiny fey, Neutral Evil*

- **Armor Class** 14
- **Hit Points** 81 (`18d4 + 36`)
- **Speed** 20 ft., fly 60 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|14 (+2)|19 (+4)|14 (+2)|13 (+1)|12 (+1)|11 (+0)|

- **Proficiency Bonus** +2
- **Saving Throws** Dexterity +6
- **Skills** Perception +5, Stealth +8
- **Senses** darkvision 60 ft., passive Perception 15
- **Damage Immunities** bludgeoning
- **Languages** Common, Elvish, Sylvan
- **Challenge** 4

## Traits

***Foul Form.*** The bereginyas's semi-solid form emits poisonous gases. Any creature that starts its turn within 5 feet of the bereginyas must succeed on a DC 14 Constitution saving throw or be [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned). A creature that succeeds on this saving throw by 5 or more is immune to the bereginyas's Foul Form for the next 24 hours.

## Actions

***Multiattack.*** The bereginyas makes two Claw attacks. If both attacks hit the same target, the bereginyas attaches to the target. While attached, the bereginyas can use only the Smother action, and it moves with the target whenever the target moves, requiring none of the bereginyas's movement. The bereginyas can detach itself by spending 5 feet of its movement. A creature, including the target, can take its action to detach the bereginyas by succeeding on a DC 14 Strength check.

***Claw.*** *Melee Weapon Attack:* `dice:1d20+6|noform|text(+6)` to hit, reach 5 ft., one target. *Hit:* `dice:1d8+4|noform|avg|text(8)` (`1d8 + 4`) slashing damage plus `dice:1d8|noform|avg|text(4)` (`1d8`) poison damage.

***Smother.*** While attached to a creature that isn't a Construct or Undead, the bereginyas extends a tendril of poisonous gas down the creature's throat. The creature must make a DC 14 Constitution saving throw. On a failure, it takes `dice:5d8|noform|avg|text(22)` (`5d8`) poison damage, immediately runs out of breath, and begins suffocating. On a success, it takes half the damage, doesn't run out of breath, and isn't suffocating. Suffocation ends if the creature dies, if the bereginyas is removed from the creature, or if the bereginyas is killed. A suffocating creature that fails this saving throw reduces its remaining rounds of breath by 1.
```
^statblock

## Environment

mountain