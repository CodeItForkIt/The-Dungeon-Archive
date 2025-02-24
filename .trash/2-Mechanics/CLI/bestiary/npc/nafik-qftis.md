---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/qftis
- monster/cr/6
- monster/size/medium
- monster/type/undead
aliases: ["Nafik"]
---
# Nafik
*Source: Quests from the Infinite Staircase p. 212*  

In life, Nafik was the high priest of Amun Sa, the last pharaoh of the land of Bakar. Nafik was a loyal subject and was respected in turn by Amun Sa and the lesser priests in the pharaoh's retinue. When Amun Sa died, Nafik and a cadre of priests locked themselves in Amun Sa's tomb according to tradition. There, they performed holy rites and accepted food and offerings from the outside.

As time went on, Nafik grew envious of Amun Sa. "Why should the pharaoh get to enjoy eternal bliss in the afterlife while his priests are condemned to live out the rest of their lives imprisoned in his pyramid?" he thought. In his anger, Nafik turned to unholy grimoires, seeking forbidden rituals he hoped could teach him the secrets of everlasting life.

When the lands of Bakar dried up, the faithful stopped bringing offerings to Amun Sa's tomb. The threat of starvation loomed over Nafik and his priests. In a desperate measure, Nafik wrought a haphazard ritual on himself and his fellow priests, transforming them and himself into Undead. Heartless and corrupted by evil, Nafik now rules over the upper halls of Amun Sa's pyramid and the priests he sentenced to an exanimate eternity.

```ad-statblock
title: Nafik
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/QftIS/Nafik.webp#token)
*Medium undead, Lawful Evil*

- **Armor Class** 13 (natural armor)
- **Hit Points** 82 (`11d8 + 33`)
- **Speed** 20 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|18 (+4)|10 (+0)|16 (+3)|10 (+0)|16 (+3)|14 (+2)|

- **Proficiency Bonus** +3
- **Saving Throws** Intelligence +3, Wisdom +6
- **Skills** History +3, Religion +3
- **Senses** darkvision 60 ft., passive Perception 13
- **Damage Vulnerabilities** fire
- **Damage Resistances** bludgeoning, piercing, slashing from nonmagical attacks
- **Damage Immunities** necrotic, poison
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** Common
- **Challenge** 6

## Traits

***Legendary Resistance (2/Day).*** If Nafik fails a saving throw, he can choose to succeed instead.

***Magic Resistance.*** Nafik has advantage on saving throws against spells and other magical effects.

***Rejuvenation.*** When he is destroyed, Nafik gains a new body in 24 hours if his heart is intact, regaining all his hit points. The new body appears in an unoccupied space within 5 feet of Nafik's heart.

***Spellcasting.*** Nafik casts one of the following spells, using Wisdom as the spellcasting ability (spell save DC 14):

**At will**: [Thaumaturgy](2-Mechanics/CLI/spells/thaumaturgy.md)

**1/day**: [Insect Plague](2-Mechanics/CLI/spells/insect-plague.md)

**2/day each**: [Command](2-Mechanics/CLI/spells/command.md), [Silence](2-Mechanics/CLI/spells/silence.md)

## Actions

***Multiattack.*** Nafik can use his Dreadful Glare and makes one Rotting Fist or Unholy Beam attack.

***Rotting Fist.*** *Melee Weapon Attack:* `dice:1d20+7|noform|text(+7)` to hit, reach 5 ft., one target. *Hit:* `dice:2d6+4|noform|avg|text(11)` (`2d6 + 4`) bludgeoning damage plus `dice:6d6|noform|avg|text(21)` (`6d6`) necrotic damage. If the target is a creature, it must succeed on a DC 14 Constitution saving throw or be cursed with mummy rot. The cursed target can't regain hit points, and its hit point maximum decreases by `dice:3d6|noform|avg|text(10)` (`3d6`) for every 24 hours that elapse. If the curse reduces the target's hit point maximum to 0, the target dies and its body turns to dust. The curse lasts until removed by the [Remove Curse](2-Mechanics/CLI/spells/remove-curse.md) spell or other magic.

***Unholy Beam.*** *Ranged Spell Attack:* `dice:1d20+6|noform|text(+6)` to hit, range 120 ft., one target. *Hit:* `dice:8d6|noform|avg|text(28)` (`8d6`) necrotic damage, and the next attack roll made against this target before the end of Nafik's next turn has advantage.

***Dreadful Glare.*** Nafik targets one creature he can see within 60 feet of himself. The target must succeed on a DC 14 Wisdom saving throw or have the [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened) condition until the end of Nafik's next turn. A target that succeeds on the saving throw is immune to Nafik's Dreadful Glare for the next 24 hours.
```
^statblock