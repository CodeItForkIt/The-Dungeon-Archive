---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/scc
- monster/cr/7
- monster/size/small-or-medium
- monster/type/humanoid/druid
aliases: ["Witherbloom Professor of Growth"]
---
# Witherbloom Professor of Growth
*Source: Strixhaven: A Curriculum of Chaos p. 223*  

Professors of growth nurture the essence of nature through their magic. They brew infusions of plants, fungi, and insects or other minuscule creatures that thrum with the essence of life, using these infusions to fuel their magic instead of using traditional material components. In battle, they flood their allies with vital essence, healing wounds and soothing ailments. Their foes face the wrath of nature itself, from grasping plants and conjured poisonous vines to avatars of nature's wrath.

These professors teach their students to focus on the growth side of the natural cycle of life and death and to avoid wasting resources. They espouse the philosophy that a thriving system benefits all.

## Witherbloom Scholars

Witherbloom College studies the magic inherent in the natural cycle of life and death. Witherbloom professors approach the philosophy from different directions, with one methodology focusing on decay and the other dealing with growth.

## Statblock

```ad-statblock
title: Witherbloom Professor of Growth
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/SCC/Witherbloom%20Professor%20of%20Growth.webp#token)
*Small or Medium humanoid (druid), Any alignment*

- **Armor Class** 13 ([hide armor](2-Mechanics/CLI/items/hide-armor.md))
- **Hit Points** 112 (`15d8 + 45`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|11 (+0)|13 (+1)|16 (+3)|16 (+3)|19 (+4)|13 (+1)|

- **Proficiency Bonus** +3
- **Saving Throws** Constitution +6, Intelligence +6, Wisdom +7, Charisma +4
- **Skills** Arcana +6, Medicine +7, Nature +6, Survival +7
- **Senses** passive Perception 14
- **Damage Resistances** poison
- **Condition Immunities** [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** Common plus any four languages
- **Challenge** 7

***Spellcasting.*** The professor casts one of the following spells, requiring no material components and using Wisdom as the spellcasting ability:

**At will**: [druidcraft](2-Mechanics/CLI/spells/druidcraft.md), [spare the dying](2-Mechanics/CLI/spells/spare-the-dying.md)

**1/day each**: [greater restoration](2-Mechanics/CLI/spells/greater-restoration.md), [lesser restoration](2-Mechanics/CLI/spells/lesser-restoration.md), [mass cure wounds](2-Mechanics/CLI/spells/mass-cure-wounds.md), [pass without trace](2-Mechanics/CLI/spells/pass-without-trace.md), [plant growth](2-Mechanics/CLI/spells/plant-growth.md), [revivify](2-Mechanics/CLI/spells/revivify.md)

## Actions

***Multiattack.*** The professor makes two Verdant Lash attacks.

***Verdant Lash.*** *Melee Spell Attack:* `dice:1d20+7|noform|text(+7)` to hit, reach 30 ft., one target. *Hit:* `dice:2d6+4|noform|avg|text(11)` (`2d6 + 4`) piercing damage plus `dice:2d6|noform|avg|text(7)` (`2d6`) poison damage, and the target must succeed on a DC 15 Strength saving throw or be pulled up to 10 feet closer to the professor.

***Summon Nature's Avatar (Recharges after a Short or Long Rest).*** The professor magically summons a Groff. The groff appears in an unoccupied space within 60 feet of the professor, acts as the professor's ally, and takes its turns immediately after the professor's. The professor can communicate telepathically with this groff while it remains. The groff remains for 10 minutes, until it or the professor dies, or until the professor dismisses it as an action.
```
^statblock