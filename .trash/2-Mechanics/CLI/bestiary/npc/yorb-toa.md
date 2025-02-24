---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/toa
- monster/cr/2
- monster/size/small
- monster/type/humanoid/grung
aliases: ["Yorb"]
---
# Yorb
*Source: Tomb of Annihilation p. 108*  

```ad-statblock
title: Yorb
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToA/Yorb.webp#token)
*Small humanoid (grung), Lawful Evil*

- **Armor Class** 13
- **Hit Points** 49 (`9d6 + 18`)
- **Speed** 25 ft., climb 25 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
| 7 (-2)|16 (+3)|15 (+2)|10 (+0)|11 (+0)|12 (+1)|

- **Proficiency Bonus** +2
- **Saving Throws** Dexterity +5
- **Skills** Athletics +2, Perception +2, Stealth +5, Survival +2
- **Senses** passive Perception 12
- **Damage Immunities** poison
- **Condition Immunities** [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** Grung
- **Challenge** 2

## Traits

***Amphibious.*** Yorb can breathe air and water.

***Poisonous Skin.*** Any creature that grapples Yorb or otherwise comes into direct contact with Yorb's skin must succeed on a DC 12 Constitution saving throw or become [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) for 1 minute. A [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) creature no longer in direct contact with Yorb can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

***Standing Leap.*** Yorb's long jump is up to 25 feet and its high jump is up to 15 feet, with or without a running start.

## Actions

***Dagger.*** *Melee or Ranged Weapon Attack:* `dice:1d20+5|noform|text(+5)` to hit, reach 5 ft. or range 20/60 ft., one target. *Hit:* `dice:1d4+3|noform|avg|text(5)` (`1d4 + 3`) piercing damage, and the target must succeed on a DC 12 Constitution saving throw or take `dice:2d4|noform|avg|text(5)` (`2d4`) poison damage.

***Shortbow.*** *Ranged Weapon Attack:* `dice:1d20+5|noform|text(+5)` to hit, range 80/320 ft., one target. *Hit:* `dice:1d6+3|noform|avg|text(6)` (`1d6 + 3`) piercing damage, and the target must succeed on a DC 12 Constitution saving throw or take `dice:2d4|noform|avg|text(5)` (`2d4`) poison damage.

***Mesmerizing Chirr (Recharge 6).*** Yorb makes a chirring noise to which grungs are immune. Each humanoid or beast that is within 15 feet of Yorb and able to hear it must succeed on a DC 12 Wisdom saving throw or be [stunned](2-Mechanics/CLI/rules/conditions.md#Stunned) until the end of Yorb's next turn.
```
^statblock