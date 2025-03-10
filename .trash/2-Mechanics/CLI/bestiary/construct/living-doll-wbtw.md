---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/wbtw
- monster/cr/2
- monster/size/tiny
- monster/type/construct
aliases: ["Living Doll"]
---
# Living Doll
*Source: The Wild Beyond the Witchlight p. 238*  

A living doll is easily mistaken for an inanimate doll or a stuffed animal until it moves. Trapped within each living doll is a mean spirit that encourages those around it to behave badly toward others. The doll takes pleasure in tormenting the guilt-ridden and despondent, hastening their descent into depression or paranoia. Because it fears its own destruction, the doll rarely causes direct harm to others. When forced to defend itself, it debilitates opponents with its maniacal cackle and assaults the minds of its enemies by turning their worst fears against them.

```ad-statblock
title: Living Doll
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/WBtW/Living%20Doll.webp#token)
*Tiny construct, typically  Neutral Evil*

- **Armor Class** 11 (natural armor)
- **Hit Points** 28 (`8d4 + 8`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
| 3 (-4)|11 (+0)|13 (+1)|10 (+0)|10 (+0)| 7 (-2)|

- **Proficiency Bonus** +2
- **Saving Throws** Intelligence +2, Wisdom +2, Charisma +0
- **Skills** ⏤
- **Senses** darkvision 30 ft., passive Perception 10
- **Damage Immunities** poison
- **Condition Immunities** [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed), [petrified](2-Mechanics/CLI/rules/conditions.md#Petrified), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** Common
- **Challenge** 2

## Traits

***False Appearance.*** If the doll is motionless at the start of combat, it has advantage on its initiative roll. Moreover, if a creature hasn't observed the doll move or act, that creature must succeed on a DC 18 Intelligence ([Investigation](2-Mechanics/CLI/rules/skills.md#Investigation)) check to discern that the doll is animate.

***Regeneration.*** The doll regains 5 hit points at the start of its turn. If the doll takes fire or psychic damage, this trait doesn't function at the start of the doll's next turn. The doll is destroyed only if it starts its turn with 0 hit points and doesn't regenerate.

***Unusual Nature.*** The doll doesn't require air, food, drink, or sleep.

## Actions

***Grabby Hands.*** *Melee Weapon Attack:* `dice:1d20+2|noform|text(+2)` to hit, reach 5 ft., one creature. *Hit:* The target is [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) (escape DC 6) and takes `dice:2d10|noform|avg|text(11)` (`2d10`) psychic damage at the start of each of its turns until this grapple ends. The doll can grapple only one creature at a time.

## Bonus Actions

***Cackle (Recharge 4-6).*** The doll cackles as it targets one or two creatures it can see within 30 feet of it. Each target that can hear the doll's cackling must make a DC 11 Wisdom saving throw, succeeding automatically if it has an Intelligence of 4 or lower. On a failed saving throw, the creature takes `dice:2d4|noform|avg|text(5)` (`2d4`) psychic damage and is [incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated) for 1 minute as it is overcome by a fit of laughter. At the end of each of its turns, the creature can repeat the saving throw, ending the effect on itself on a success. A creature that succeeds on this saving throw is immune to this doll's Cackle for 24 hours.
```
^statblock