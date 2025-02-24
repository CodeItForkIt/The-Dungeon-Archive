---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/scc
- monster/cr/7
- monster/size/small-or-medium
- monster/type/humanoid/druid
aliases: ["Witherbloom Professor of Decay"]
---
# Witherbloom Professor of Decay
*Source: Strixhaven: A Curriculum of Chaos p. 223*  

Professors of decay wield magic that drains and twists the essence of the professors' subjects. The professors use the gathered essence to feed their magic, snuffing the life and decaying the bodies of the living, entreating and commanding the dead and Undead, and twisting curses around their foes. In battle, they steal the essence of their enemies to heal their own wounds and create spears of sickly green life-draining energy.

Witherbloom teachers who espouse the decaying side of the natural cycle instruct their students to exploit the essence of life for their own needs. Professors of decay unravel the mysteries of death and the transition of decay, and they teach that any life's end is an asset waiting to be tapped.

## Witherbloom Scholars

Witherbloom College studies the magic inherent in the natural cycle of life and death. Witherbloom professors approach the philosophy from different directions, with one methodology focusing on decay and the other dealing with growth.

## Statblock

```ad-statblock
title: Witherbloom Professor of Decay
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/SCC/Witherbloom%20Professor%20of%20Decay.webp#token)
*Small or Medium humanoid (druid), Any alignment*

- **Armor Class** 14 ([hide armor](2-Mechanics/CLI/items/hide-armor.md))
- **Hit Points** 105 (`14d8 + 42`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|11 (+0)|14 (+2)|16 (+3)|16 (+3)|19 (+4)|13 (+1)|

- **Proficiency Bonus** +3
- **Saving Throws** Constitution +6, Intelligence +6, Wisdom +7, Charisma +4
- **Skills** Arcana +6, Medicine +7, Nature +6, Survival +7
- **Senses** passive Perception 14
- **Damage Resistances** necrotic
- **Languages** Common plus any four languages
- **Challenge** 7

## Traits

***Essence Transfer (1/Day).*** The professor can cast the [animate dead](2-Mechanics/CLI/spells/animate-dead.md) spell, using Wisdom as the spellcasting ability.

***Spellcasting.*** The professor casts one of the following spells, requiring no material components and using Wisdom as the spellcasting ability (spell save DC 15):

**At will**: [druidcraft](2-Mechanics/CLI/spells/druidcraft.md), [spare the dying](2-Mechanics/CLI/spells/spare-the-dying.md)

**1/day each**: [antilife shell](2-Mechanics/CLI/spells/antilife-shell.md), [bane](2-Mechanics/CLI/spells/bane.md), [feign death](2-Mechanics/CLI/spells/feign-death.md), [speak with dead](2-Mechanics/CLI/spells/speak-with-dead.md)

## Actions

***Multiattack.*** The professor makes two Mortality Spear attacks. It can replace one of the attacks with a use of Spellcasting.

***Mortality Spear.*** *Melee or Ranged Spell Attack:* `dice:1d20+7|noform|text(+7)` to hit, reach 5 ft. or range 120 ft., one target. *Hit:* `dice:3d8+4|noform|avg|text(17)` (`3d8 + 4`) necrotic damage, and the target can't regain hit points until the start of the professor's next turn.

***Essence Pulse (Recharge 5-6).*** The professor creates a life-draining vortex in a 30-foot-radius sphere centered on itself. Each creature of the professor's choice that it can see within that area must make a DC 15 Constitution saving throw, taking `dice:5d8|noform|avg|text(23)` (`5d8`) necrotic damage on a failed save, or half as much damage on a successful one. The professor then regains 10 hit points. An affected creature's hit point maximum is reduced by an amount equal to the necrotic damage taken. This reduction lasts until the creature finishes a long rest. The creature dies if its hit point maximum is reduced to 0.
```
^statblock