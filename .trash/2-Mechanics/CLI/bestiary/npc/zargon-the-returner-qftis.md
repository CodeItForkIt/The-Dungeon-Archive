---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/qftis
- monster/cr/17
- monster/size/huge
- monster/type/aberration
aliases: ["Zargon the Returner"]
---
# Zargon the Returner
*Source: Quests from the Infinite Staircase p. 223*  

Zargon the Returner is an elder evil—an undying abomination from eons past with an insatiable appetite. A tentacled, slime-covered horror with a cyclopic red eye and an indestructible horn, Zargon corrupts creatures it doesn't devour, transforming its victims into amorphous servants.

No one knows Zargon's true origin. The creature was one of the first inhabitants of the Nine Hells, predating even the arrival of Asmodeus, the plane's foremost ruler. Long-lived devils and occult sages theorize Zargon and its kind were invaders from another plane—or another reality entirely.

When Asmodeus ascended the infernal hierarchy, he and his legions wiped out most of the plane's earlier inhabitants, but Zargon proved beyond even Asmodeus' might. No matter what blistering wrath Asmodeus brought to bear on Zargon, the aberration continually re-formed from its horn. Finally, Asmodeus cast Zargon's horn from the Nine Hells in disgust, banishing the elder evil to the Material Plane. The horn was driven deep into the earth where it fell, entombing Zargon below.

Eventually a civilization arose above Zargon's prison. The elder evil whispered through dreams and nightmares to the people of Cynidicea, the realm's capital, until one day, a crew of Cynidiceans accidentally dug through to the Returner's prison. Zargon emerged, devouring many of the city's inhabitants and drowning many more in its slime. The city soon fell. Those who survived Zargon's rampage turned to it in worship, sacrificing their own to appease their so-called god. Appeased by these living offerings, Zargon returned to the tunnels beneath Cynidicea, where its cult grew.

## Zargon's Lair

Zargon's lair is a slimy cavern beneath the lost city of Cynidicea. The elder evil lurks in the depths, feasting on sacrifices cast down by its worshipers.

## Statblock

```ad-statblock
title: Zargon the Returner
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/QftIS/Zargon%20the%20Returner.webp#token)
*Huge aberration, Lawful Evil*

- **Armor Class** 18 (natural armor)
- **Hit Points** 253 (`22d12 + 110`)
- **Speed** 40 ft., swim 80 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|22 (+6)|10 (+0)|20 (+5)|14 (+2)|18 (+4)|18 (+4)|

- **Proficiency Bonus** +6
- **Saving Throws** Dexterity +6, Charisma +10
- **Skills** History +8, Perception +10
- **Senses** truesight 120 ft., passive Perception 20
- **Damage Resistances** cold; fire; bludgeoning, piercing, slashing from nonmagical attacks
- **Damage Immunities** acid, poison
- **Condition Immunities** [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** all, telepathy 120 ft.
- **Challenge** 17

## Traits

***Legendary Resistance (4/Day).*** If Zargon fails a saving throw, it can choose to succeed instead.

***Regeneration.*** Zargon regains 20 hit points at the start of each of its turns. If Zargon takes cold or fire damage, this trait doesn't function at the start of Zargon's next turn. Zargon dies only if it starts its turn with 0 hit points and doesn't regenerate.

***Shrouded Being.*** Zargon can't be targeted by divination magic or perceived through magical scrying sensors.

***Slimy Demise.*** When Zargon dies, its body dissolves into foul slime, leaving only its horn behind. Zargon re-forms in `dice:1d10|noform|avg` (`1d10`) days, regrowing from the horn. The horn is immune to all damage and can be destroyed only by submerging it in a cleansing waterfall on one of the Upper Planes for 101 days. While the horn is submerged in this way, Zargon doesn't re-form, and the horn slowly dissolves, sending corrupting slime downriver that permanently fouls the water for 10 miles from the place where the horn dissolved. The fouled water is unfit to drink, chokes aquatic wildlife, and withers plants.

## Actions

***Multiattack.*** Zargon makes two Barbed Tentacle attacks, one Bite attack, and one Gore attack.

***Barbed Tentacle.*** *Melee Weapon Attack:* `dice:1d20+12|noform|text(+12)` to hit, reach 20 ft., one target. *Hit:* `dice:2d8+6|noform|avg|text(15)` (`2d8 + 6`) piercing damage. If the target is a Large or smaller creature, it has the [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) condition (escape DC 20), and Zargon can pull the creature up to 20 feet straight toward itself. Zargon has six tentacles, each of which can grapple one creature. Zargon can move at its full speed while dragging creatures it is grappling.

***Bite.*** *Melee Weapon Attack:* `dice:1d20+12|noform|text(+12)` to hit, reach 5 ft., one target. *Hit:* `dice:2d12+6|noform|avg|text(19)` (`2d12 + 6`) piercing damage plus `dice:2d6|noform|avg|text(7)` (`2d6`) acid damage.

***Gore.*** *Melee Weapon Attack:* `dice:1d20+12|noform|text(+12)` to hit, reach 10 ft., one target. *Hit:* `dice:2d8+6|noform|avg|text(15)` (`2d8 + 6`) force damage, and a 10-foot-radius [invisible](2-Mechanics/CLI/rules/conditions.md#Invisible) sphere of antimagic, like that created by an [Antimagic Field](2-Mechanics/CLI/spells/antimagic-field.md) spell, surrounds the target. The sphere is centered on the target, moves with the target, and lasts until the end of Zargon's next turn.

***Slime Wave (Recharge 5-6).*** Zargon spews slime in a 60-foot cone. Each creature in that area that isn't an Aberration or Ooze must make a DC 19 Constitution saving throw. On a failed save, the creature takes `dice:7d10|noform|avg|text(38)` (`7d10`) acid damage and has the [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) condition for 1 minute. On a successful save, the creature takes half as much damage only. A [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

A creature reduced to 0 hit points by the acid damage dies and dissolves into a puddle of slime that rises as a gibbering mouther at the start of Zargon's next turn. The creature obeys Zargon's commands and takes its turn immediately after Zargon's. Only a [Wish](2-Mechanics/CLI/spells/wish.md) spell can reverse this transformation and restore the creature to life.

## Reactions

Zargon can take up to three reactions per round but only one per turn.

***Defiant Essence.*** When a creature casts a spell that targets Zargon or would deal damage to it, Zargon attempts to absorb the magic into its horn. The creature must make a DC 19 Charisma saving throw. On a failed save, the creature takes `dice:1d12|noform|avg|text(6)` (`1d12`) force damage, and the spell it cast fails and is wasted.

***Slime Spray.*** When a creature ends its turn within 30 feet of Zargon, Zargon sprays toxic slime at the creature. The target must make a DC 19 Dexterity saving throw (with disadvantage if it has the [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) condition). On a failed save, the creature takes `dice:2d6|noform|avg|text(7)` (`2d6`) poison damage. On a successful save, it takes half as much damage.

![Zargon the Returner](2-Mechanics/CLI/bestiary/legendary-group/zargon-the-returner-qftis.md)
```
^statblock