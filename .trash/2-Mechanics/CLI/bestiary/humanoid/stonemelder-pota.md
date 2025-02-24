---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/pota
- monster/cr/4
- monster/size/medium
- monster/type/humanoid/human
aliases: ["Stonemelder"]
---
# Stonemelder
*Source: Princes of the Apocalypse p. 197*  

Stonemelders are spellcasters who gain their power from Ogrémoch, using elemental earth magic to sheathe their bodies in carapaces of rock. They are elite champions of the cult and answer only to the cult leaders. Not even the Black Earth priests tell stonemelders what to do.

Each stonemelder carries a weapon known as a Black Earth rod. Such a rod is like an ordinary mace, but in the hands of a stonemelder, it serves as a conduit for Ogrémoch's wrath.

```ad-statblock
title: Stonemelder
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/PotA/Stonemelder.webp#token)
*Medium humanoid (human), Neutral Evil*

- **Armor Class** 17 ([splint armor](2-Mechanics/CLI/items/splint-armor.md))
- **Hit Points** 75 (`10d8 + 30`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|15 (+2)|10 (+0)|16 (+3)|12 (+1)|11 (+0)|17 (+3)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** Intimidation +5, Perception +2
- **Senses** tremorsense 30 ft., passive Perception 12
- **Languages** Common, Terran
- **Challenge** 4

## Traits

***Death Burst.*** When the Stonemelder dies, it turns to stone and explodes in a burst of rock shards, becoming a smoking pile of rubble. Each creature within 10 feet of the exploding Stonemelder must make a DC 14 Dexterity saving throw, taking `dice:2d10|noform|avg|text(11)` (`2d10`) bludgeoning damage on a failed save, or half as much damage on a successful one.

***Spellcasting.*** The Stonemelder is a 7th-level spellcaster. Its spellcasting ability is Charisma (spell save DC 13, `dice:1d20+5|noform|text(+5)` to hit with spell attacks). It knows the following sorcerer spells:

**Cantrips (at will)**: [acid splash](2-Mechanics/CLI/spells/acid-splash.md), [blade ward](2-Mechanics/CLI/spells/blade-ward.md), [light](2-Mechanics/CLI/spells/light.md), [mending](2-Mechanics/CLI/spells/mending.md), [mold earth](2-Mechanics/CLI/spells/mold-earth-xge.md)

**1st level (4 slots)**: [expeditious retreat](2-Mechanics/CLI/spells/expeditious-retreat.md), [false life](2-Mechanics/CLI/spells/false-life.md), [shield](2-Mechanics/CLI/spells/shield.md)

**2nd level (3 slots)**: [Maximilian's earthen grasp](2-Mechanics/CLI/spells/maximilians-earthen-grasp-xge.md), [shatter](2-Mechanics/CLI/spells/shatter.md)

**3rd level (3 slots)**: [erupting earth](2-Mechanics/CLI/spells/erupting-earth-xge.md), [meld into stone](2-Mechanics/CLI/spells/meld-into-stone.md)

**4th level (1 slots)**: [stoneskin](2-Mechanics/CLI/spells/stoneskin.md)

## Actions

***Black Earth Rod.*** *Melee Weapon Attack:* `dice:1d20+5|noform|text(+5)` to hit, reach 5 ft., one target. *Hit:* `dice:1d6+2|noform|avg|text(5)` (`1d6 + 2`) bludgeoning damage. The Stonemelder can also expend a spell slot to deal extra damage, dealing `dice:2d8|noform|avg` (`2d8`) bludgeoning damage for a 1st level slot, plus an additional `dice:1d8|noform|avg` (`1d8`) for each level of the slot above 1st.
```
^statblock