---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/ghloe
- monster/cr/20
- monster/size/medium
- monster/type/undead
aliases: ["Hourglass Widow"]
---
# Hourglass Widow
*Source: Grim Hollow: Lairs of Etharis p. 81*  

> [!quote]  
> 
> When the clock stops, your time has run out.

## Salvage

When the sand from the widow's hourglass is mixed with wine, it creates an elixir that when consumed prevents the creature from aging for `dice:2d6+10|noform|avg` (`2d6 + 10`) years. There is enough sand in the hourglass to create an elixir for two creatures. A creature cannot benefit from the sand of an hourglass widow more than once. The sand can be sold for 5,000 gp.

## Lore

- **DC 10 Intelligence ([Religion](2-Mechanics/CLI/rules/skills.md#Religion)).** Hourglass widows are undead who can control time to act more than once a round.  
- **DC 15 Intelligence ([Arcana](2-Mechanics/CLI/rules/skills.md#Arcana)).** Hourglass widows are resistant to cold, force, lightning, and necrotic. They are immune to poison and nonmagical attacks.  
- **DC 20 Intelligence ([Arcana](2-Mechanics/CLI/rules/skills.md#Arcana)).** Inexplicably, an hourglass widow can affect those trapped in a time stop, imprisonment, or other stasis effect.  

## Statblock

```ad-statblock
title: Hourglass Widow
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/GHLoE/Hourglass%20Widow.webp#token)
*Medium undead, Neutral Evil*

- **Armor Class** 14 (18 with [mage armor](2-Mechanics/CLI/spells/mage-armor.md))
- **Hit Points** 187 (`22d8 + 88`)
- **Speed** 30 ft., fly 60 ft. (hover)

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|16 (+3)|19 (+4)|18 (+4)|19 (+4)|17 (+3)|22 (+6)|

- **Proficiency Bonus** +6
- **Saving Throws** Strength +9, Constitution +10, Intelligence +10, Wisdom +9, Charisma +12
- **Skills** Arcana +10, Athletics +9, Insight +9, Investigation +10, Perception +15
- **Senses** truesight 120 ft., passive Perception 25
- **Damage Resistances** cold, force, lightning, necrotic
- **Damage Immunities** poison; bludgeoning, piercing, slashing from nonmagical attacks
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** the languages it knew in life
- **Challenge** 20

## Traits

***Accelerate Through Time (2/Day).*** The widow takes one additional action.

***Master of Time.*** The widow can choose to be unaffected by effects that modify time or change its speed. The widow can affect others frozen in a time stop or other stasis-like effects.

***Legendary Resistance (3/Day).*** If the widow fails a saving throw, it can choose to succeed instead.

***Regeneration.*** The widow regains 25 hit points at the start of its turn. If it takes fire or radiant damage, this trait doesn't function at the start of the widow's next turn. The widow's body is destroyed only if it starts its turn with 0 hit points and doesn't regenerate.

***Turn Resistance.*** The widow has advantage on saving throws against any effect that turns undead.

***Innate Spellcasting.*** The widow's spellcasting ability is Charisma (spell save DC 20, `dice:1d20+12|noform|text(+12)` to hit with spell attacks). It can innately cast the following spells, requiring no material components:

**At will**: [eldritch blast](2-Mechanics/CLI/spells/eldritch-blast.md) (four beams), [expeditious retreat](2-Mechanics/CLI/spells/expeditious-retreat.md) *, [mage armor](2-Mechanics/CLI/spells/mage-armor.md) *, [mage hand](2-Mechanics/CLI/spells/mage-hand.md)

**1/day each**: [eyebite](2-Mechanics/CLI/spells/eyebite.md), [foresight](2-Mechanics/CLI/spells/foresight.md) *, [freedom of movement](2-Mechanics/CLI/spells/freedom-of-movement.md), [power word stun](2-Mechanics/CLI/spells/power-word-stun.md), [teleport](2-Mechanics/CLI/spells/teleport.md), [time stop](2-Mechanics/CLI/spells/time-stop.md), [wall of force](2-Mechanics/CLI/spells/wall-of-force.md)

**3/day each**: [blight](2-Mechanics/CLI/spells/blight.md), [disintegrate](2-Mechanics/CLI/spells/disintegrate.md), [haste](2-Mechanics/CLI/spells/haste.md), [misty step](2-Mechanics/CLI/spells/misty-step.md), [shield](2-Mechanics/CLI/spells/shield.md), [slow](2-Mechanics/CLI/spells/slow.md), [see invisibility](2-Mechanics/CLI/spells/see-invisibility.md)

*The widow casts these spells before combat.

## Actions

***Multiattack.*** The widow uses disintegrating touch and withering gaze.

***Disintegrating Touch.*** *Melee Weapon Attack:* `dice:1d20+10|noform|text(+10)` to hit, reach 5 ft., one target. *Hit:* `dice:3d6+6|noform|avg|text(16)` (`3d6 + 6`) force damage and the target must succeed on a DC 20 Constitution saving throw or have their speed decreased by 15 feet for 1 minute. The target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success. The effects are cumulative.

***Withering Gaze.*** A creature within 30 feet that the widow can see suffers `dice:6d6|noform|avg|text(21)` (`6d6`) necrotic damage.

## Legendary Actions

***Eldritch Blast.*** The widow casts [eldritch blast](2-Mechanics/CLI/spells/eldritch-blast.md).

***Sudden Rush (2 Actions).*** The widow teleports to a space it can see within 30 feet and uses disintegrating touch before or after it teleports.

***Frozen in Time (3 Actions).*** All creatures within 20 ft. of the widow must succeed on a DC 20 Constitution saving throw or be [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed) until the end of the creature's next turn.
```
^statblock