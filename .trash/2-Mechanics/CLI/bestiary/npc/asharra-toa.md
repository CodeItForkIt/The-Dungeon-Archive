---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/toa
- monster/cr/2
- monster/size/medium
- monster/type/humanoid/aarakocra
aliases: ["Asharra"]
---
# Asharra
*Source: Tomb of Annihilation p. 69*  

Aarakocra range the Howling Gyre, an endless storm of mighty winds and lashing rains that surrounds the tranquil realm of Aaqa in the Elemental Plane of Air. Making aerial patrols, these birdlike humanoids guard the windy borders of their home against invaders from the Elemental Plane of Earth, such as gargoyles, their sworn enemies.

## Biography

The incredibly old leader of the community at Kir Sabal. The others refer to her as Teacher, and they revere her as a living saint. Asharra is intelligent, ambitious, and somewhat manipulative, but never cruel or insensitive.

## Statblock

```ad-statblock
title: Asharra
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToA/Asharra.webp#token)
*Medium humanoid (aarakocra), Lawful Neutral*

- **Armor Class** 12
- **Hit Points** 31 (`7d8`)
- **Speed** 20 ft., fly 50 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|10 (+0)|14 (+2)|10 (+0)|14 (+2)|17 (+3)|11 (+0)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** History +4, Insight +5, Perception +7
- **Senses** passive Perception 17
- **Languages** Auran, Common
- **Challenge** 2

## Traits

***Dive Attack.*** If the aarakocra is flying and dives at least 30 feet straight toward a target and then hits it with a melee weapon attack, the attack deals an extra `dice:1d6|noform|avg|text(3)` (`1d6`) damage to the target.

***Dance of the Seven Winds.*** Asharra knows a ritual called the Dance of the Seven Winds, which temporarily grants magical flight to as many as ten nonflying creatures. The ritual, which takes 10 minutes to complete, can only be performed by an aarakocra elder and requires a black orchid as a material component.

Asharra must grind the orchid to powder, inhale it, and dance in circles around the ritual's beneficiaries uninterrupted while seven other aarakocra chant prayers to the Wind Dukes of Aaqa. When the dance concludes, Asharra's wings disappear and she loses the ability to fly. The ritual's beneficiaries each gain a magical flying speed of 30 feet (allowing them to fly 4 miles per hour). This benefit lasts for 3 days, after which Asharra's wings reappear and she regains the ability to fly.

***Spellcasting.*** Asharra is a 5th-level spellcaster. Her spellcasting ability is Wisdom (spell save DC 13, `dice:1d20+5|noform|text(+5)` to hit with spell attacks). Asharra has the following druid spells prepared:

**Cantrips (at will)**: [druidcraft](2-Mechanics/CLI/spells/druidcraft.md), [mending](2-Mechanics/CLI/spells/mending.md), [produce flame](2-Mechanics/CLI/spells/produce-flame.md)

**1st level (4 slots)**: [detect magic](2-Mechanics/CLI/spells/detect-magic.md), [faerie fire](2-Mechanics/CLI/spells/faerie-fire.md), [thunderwave](2-Mechanics/CLI/spells/thunderwave.md)

**2nd level (3 slots)**: [gust of wind](2-Mechanics/CLI/spells/gust-of-wind.md), [hold person](2-Mechanics/CLI/spells/hold-person.md), [lesser restoration](2-Mechanics/CLI/spells/lesser-restoration.md)

**3rd level (2 slots)**: [call lightning](2-Mechanics/CLI/spells/call-lightning.md), [wind wall](2-Mechanics/CLI/spells/wind-wall.md)

## Actions

***Talon.*** *Melee Weapon Attack:* `dice:1d20+4|noform|text(+4)` to hit, reach 5 ft., one target. *Hit:* `dice:1d4+2|noform|avg|text(4)` (`1d4 + 2`) slashing damage.

***Javelin.*** *Melee or Ranged Weapon Attack:* `dice:1d20+4|noform|text(+4)` to hit, reach 5 ft. or range 30/120 ft., one target. *Hit:* `dice:1d6+2|noform|avg|text(5)` (`1d6 + 2`) piercing damage.

***Summon Air Elemental.*** Five aarakocra within 30 feet of each other can magically summon an [air elemental](2-Mechanics/CLI/bestiary/elemental/air-elemental.md). Each of the five must use its action and movement on three consecutive turns to perform an aerial dance and must maintain [concentration](2-Mechanics/CLI/rules/conditions.md#Concentration) while doing so (as if concentrating on a spell). When all five have finished their third turn of the dance, the elemental appears in an unoccupied space within 60 feet of them. It is friendly toward them and obeys their spoken commands. It remains for 1 hour, until it or all its summoners die, or until any of its summoners dismisses it as a bonus action. A summoner can't perform the dance again until it finishes a short rest. When the elemental returns to the Elemental Plane of Air, any aarakocra within 5 feet of it can return with it.
```
^statblock