---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/wbtw
- monster/cr/3
- monster/size/medium
- monster/type/humanoid/cleric
- monster/type/humanoid/human
aliases: ["Zargash"]
---
# Zargash
*Source: The Wild Beyond the Witchlight p. 223*  

Zargash worships Orcus, the Demon Prince of Undeath, who has promised to transform Zargash into a vampire after a lifetime of faithful service. For a living priest to worship Orcus is utter folly, but Zargash is twisted beyond any hope of redemption. His hobbies include slaying the living and animating the dead.

```ad-statblock
title: Zargash
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/WBtW/Zargash.webp#token)
*Medium humanoid (cleric, human), Chaotic Evil*

- **Armor Class** 13 ([chain shirt](2-Mechanics/CLI/items/chain-shirt.md))
- **Hit Points** 45 (`7d8 + 14`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|14 (+2)|10 (+0)|14 (+2)|12 (+1)|16 (+3)|15 (+2)|

- **Proficiency Bonus** +2
- **Saving Throws** Wisdom +5, Charisma +4
- **Skills** Deception +6, Insight +5
- **Senses** passive Perception 13
- **Languages** Common
- **Challenge** 3

## Traits

***Cling to Life (Recharges after a Long Rest).*** The first time Zargash would drop to 0 hit points as a result of taking damage, he instead drops to 1 hit point.

***Special Equipment.*** Zargash wears a bat-shaped amulet that has the properties of a [ring of feather falling](2-Mechanics/CLI/items/ring-of-feather-falling.md).

***Spellcasting.*** Zargash casts one of the following spells, using Wisdom as the spellcasting ability (spell save DC 13):

**At will**: [light](2-Mechanics/CLI/spells/light.md), [thaumaturgy](2-Mechanics/CLI/spells/thaumaturgy.md)

**1/day each**: [command](2-Mechanics/CLI/spells/command.md), [gaseous form](2-Mechanics/CLI/spells/gaseous-form.md), [hold person](2-Mechanics/CLI/spells/hold-person.md), [silence](2-Mechanics/CLI/spells/silence.md), [speak with dead](2-Mechanics/CLI/spells/speak-with-dead.md)

## Actions

***Warhammer.*** *Melee Weapon Attack:* `dice:1d20+4|noform|text(+4)` to hit, reach 5 ft., one target. *Hit:* `dice:1d8+2|noform|avg|text(6)` (`1d8 + 2`) bludgeoning damage, or `dice:1d10+2|noform|avg|text(7)` (`1d10 + 2`) bludgeoning damage when used with two hands.

***Deathly Ray.*** *Ranged Spell Attack:* `dice:1d20+5|noform|text(+5)` to hit, range 60 ft., one creature. *Hit:* `dice:4d10+3|noform|avg|text(25)` (`4d10 + 3`) necrotic damage.

## Bonus Actions

***Animate Corpse (1/Day).*** Zargash targets the lifeless corpse of one Humanoid he can see within 30 feet of him and commands it to rise, transforming it into a zombie under his control. The zombie takes its turn immediately after Zargash. Animating the zombie requires Zargash's [concentration](2-Mechanics/CLI/rules/conditions.md#Concentration) (as if concentrating on a spell). The zombie reverts to an inanimate corpse after 10 minutes, when it drops to 0 hit points, or when Zargash's [concentration](2-Mechanics/CLI/rules/conditions.md#Concentration) ends.
```
^statblock