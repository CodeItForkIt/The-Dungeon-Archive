---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/cos
- monster/cr/6
- monster/size/medium
- monster/type/undead
aliases: ["Sir Godfrey Gwilym"]
---
# Sir Godfrey Gwilym
*Source: Curse of Strahd p. 139*  

```ad-statblock
title: Sir Godfrey Gwilym
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/CoS/Sir%20Godfrey%20Gwilym.webp#token)
*Medium undead, Lawful Evil*

- **Armor Class** 13 (broken chainmail)
- **Hit Points** 136 (`16d8 + 64`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|18 (+4)|14 (+2)|18 (+4)|13 (+1)|16 (+3)|18 (+4)|

- **Proficiency Bonus** +3
- **Saving Throws** Strength +7, Constitution +7, Wisdom +6, Charisma +7
- **Skills** ⏤
- **Senses** darkvision 60 ft., passive Perception 13
- **Damage Resistances** necrotic, psychic
- **Damage Immunities** poison
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned), [stunned](2-Mechanics/CLI/rules/conditions.md#Stunned)
- **Languages** the languages it knew in life
- **Challenge** 6

## Traits

***Regeneration.*** The knight regains 10 hit points at the start of its turn. If the knight takes fire or radiant damage, this trait doesn't function at the start of the knight's next turn. The knight's body is destroyed only if it starts its turn with 0 hit points and doesn't regenerate.

***Rejuvenation.*** When the knight's body is destroyed, its soul lingers. After 24 hours, the soul inhabits and animates another humanoid corpse on the same plane of existence and regains all its hit points. While the soul is bodiless, a [wish](2-Mechanics/CLI/spells/wish.md) spell can be used to force the soul to go to the afterlife and not return.

***Turn Immunity.*** The knight is immune to effects that turn undead.

***Vengeful Tracker.*** The knight knows the distance to and direction of any creature against which it seeks revenge, even if the creature and the knight are on different planes of existence. If the creature being tracked by the knight dies, the knight knows.

***Spellcasting.*** Sir Godfrey is a 16th-level spellcaster. His spellcasting ability is Wisdom (spell save DC 14, `dice:1d20+6|noform|text(+6)` to hit with spell attacks). He has the following paladin spells prepared:

**1st level (4 slots)**: [command](2-Mechanics/CLI/spells/command.md), [divine favor](2-Mechanics/CLI/spells/divine-favor.md), [thunderous smite](2-Mechanics/CLI/spells/thunderous-smite.md)

**2nd level (3 slots)**: [branding smite](2-Mechanics/CLI/spells/branding-smite.md), [magic weapon](2-Mechanics/CLI/spells/magic-weapon.md)

**3rd level (3 slots)**: [blinding smite](2-Mechanics/CLI/spells/blinding-smite.md), [dispel magic](2-Mechanics/CLI/spells/dispel-magic.md)

**4th level (2 slots)**: [staggering smite](2-Mechanics/CLI/spells/staggering-smite.md)

## Actions

***Multiattack.*** The knight makes two longsword attacks or two fist attacks.

***Longsword.*** *Melee Weapon Attack:* `dice:1d20+7|noform|text(+7)` to hit, reach 5 ft., one target. *Hit:* `dice:2d10+4|noform|avg|text(15)` (`2d10 + 4`) slashing damage. If the target is a creature against which the knight has sworn vengeance, the target takes an extra `dice:4d6|noform|avg|text(14)` (`4d6`) slashing damage.

***Fist.*** *Melee Weapon Attack:* `dice:1d20+7|noform|text(+7)` to hit, reach 5 ft., one target. *Hit:* `dice:2d6+4|noform|avg|text(11)` (`2d6 + 4`) bludgeoning damage. If the target is a creature against which the knight has sworn vengeance, the target takes an extra `dice:4d6|noform|avg|text(14)` (`4d6`) bludgeoning damage. Instead of dealing damage, the knight can grapple the target (escape DC 14) provided the target is Large or smaller.

***Vengeful Glare.*** The knight targets one creature it can see within 30 feet of it and against which it has sworn vengeance. The target must make a DC 15 Wisdom saving throw. On a failure, the target is [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed) until the knight deals damage to it, or until the end of the knight's next turn. When the paralysis ends, the target is [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened) of the knight for 1 minute. The [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened) target can repeat the saving throw at the end of each of its turns, with disadvantage if it can see the knight, ending the [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened) condition on itself on a success.
```
^statblock