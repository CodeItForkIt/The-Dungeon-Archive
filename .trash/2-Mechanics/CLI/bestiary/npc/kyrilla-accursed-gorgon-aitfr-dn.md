---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/aitfr-dn
- monster/cr/10
- monster/size/large
- monster/type/monstrosity
aliases: ["Kyrilla, Accursed Gorgon"]
---
# Kyrilla, Accursed Gorgon
*Source: Adventures in the Forgotten Realms: Deepest Night p. 12*  

Some small part of Kyrilla hopes she might be pardoned from her immortal curse one day, but her ire and spite have overtaken her heart, and the only way she can imagine escaping eternity is by impressing the gods with her tenacity. She doesn't want pity nor compassion. She wants to be feared and loathed and to press on with existence despite it all. And now that Kathikon is dead and she is alone, she cannot remember mercy.

## Personality Trait

"I am quick to judge others and find them wanting."

## Ideal

"Spite. I survive despite a curse from the gods—I'm not about to go out into the world where fools will try to kill me."

## Bond

"Kathikon was the love of my life. No one else matters to me."

## Flaw

"I never admit when I am wrong."

## Horrific Appearance

Once, Kyrilla looked much like other gorgons of her world. Now, with her curse upon her, Kyrilla's healthy greenish skin has grown sickly pale, and the segmented cables she wore like hair have gone from shiny black to matte gray and green. Her legs became a long, segmented tail. Her eyes now glow green, bright enough to create dim light in front of her. She has grown four needle-like fangs in her mouth, and her hands have become slicing claws.

She reverts to her original appearance when she dies.

## Bestowed Power

The malevolent powers bestowed to Kyrilla by her curse, as well as those given to her by the yuan-ti cult, are hardly of interest to her. She doesn't relish power but instead has taken to wallowing in misery and dwelling in her hatred for the beings that cursed her so long ago that she can hardly remember them.

## Magic Ring

Kyrilla wears a ring of water walking that she was given by an emissary from the Serpent Kingdoms long ago. It is made of a bluish jade and does not reflect light.

## Immortal Curse

Kyrilla does not require food or drink but does breathe and sleep.

## Statblock

```ad-statblock
title: Kyrilla, Accursed Gorgon
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/AitFR-DN/Kyrilla%2C%20Accursed%20Gorgon.webp#token)
*Large monstrosity, Lawful Evil*

- **Armor Class** 15 (natural armor)
- **Hit Points** 127 (`15d10 + 45`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|11 (+0)|16 (+3)|16 (+3)|14 (+2)|14 (+2)|15 (+2)|

- **Proficiency Bonus** +4
- **Saving Throws** Wisdom +6, Charisma +6
- **Skills** Deception +6, Insight +6, Perception +6, Stealth +7
- **Senses** darkvision 60 ft., passive Perception 16
- **Damage Resistances** bludgeoning, piercing, slashing from nonmagical attacks
- **Damage Immunities** poison
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed)
- **Languages** Common, Draconic, Primordial
- **Challenge** 10

## Traits

***Feed on Pain (2/Day).*** The first time she hits with a weapon attack on her turn, Kyrilla can deal an extra `dice:3d10|noform|avg|text(16)` (`3d10`) poison damage to the target and regains a number of hit points equal to half the damage dealt.

***Legendary Resistance (2/Day).*** If she fails a saving throw, Kyrilla can choose to succeed instead.

***Petrifying Gaze.*** When a creature that can see Kyrilla's eyes starts its turn within 30 feet of her, Kyrilla can force it to make a DC 14 Constitution saving throw if Kyrilla isn't [incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated) and can see the creature. If the saving throw fails by 5 or more, the creature is instantly [petrified](2-Mechanics/CLI/rules/conditions.md#Petrified). Otherwise, a creature that fails the save begins to turn to stone and is [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained). The [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) creature must repeat the saving throw at the end of its next turn, becoming [petrified](2-Mechanics/CLI/rules/conditions.md#Petrified) on a failure or ending the effect on a success. The petrification lasts until the creature is freed by the [greater restoration](2-Mechanics/CLI/spells/greater-restoration.md) spell or other magic.

Unless [surprised](2-Mechanics/CLI/rules/conditions.md#Surprised), a creature can avert its eyes to avoid the saving throw at the start of its turn. If the creature does so, it can't see Kyrilla until the start of its next turn, when it can avert its eyes again. If the creature looks at Kyrilla in the meantime, it must immediately make the save.

Kyrilla's accursed gaze does not affect undead or constructs. If Kyrilla sees herself reflected on a polished surface within 30 feet of her and in an area of bright light, she is, due to her curse, affected by her own gaze.

***Sunlight Sensitivity.*** While in sunlight, Kyrilla has disadvantage on attack rolls and on Wisdom ([Perception](2-Mechanics/CLI/rules/skills.md#Perception)) checks that rely on sight.

## Actions

***Multiattack.*** Kyrilla makes one attack to constrict and two attacks with her claws, or she makes three attacks with her longbow.

***Claw.*** *Melee Weapon Attack:* `dice:1d20+7|noform|text(+7)` to hit, reach 5 ft., one target. *Hit:* `dice:3d6+3|noform|avg|text(13)` (`3d6 + 3`) slashing damage.

***Constrict.*** *Melee Weapon Attack:* `dice:1d20+4|noform|text(+4)` to hit, reach 10 ft., one target. *Hit:* `dice:3d6|noform|avg|text(10)` (`3d6`) bludgeoning damage, and the target is [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) (escape DC 13) if it is a Large or smaller creature. Until this grapple ends, the target is [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained), and Kyrilla can't constrict another target.

***Longbow.*** *Ranged Weapon Attack:* `dice:1d20+7|noform|text(+7)` to hit, range 150/600 ft., one target. *Hit:* `dice:3d8+3|noform|avg|text(16)` (`3d8 + 3`) piercing damage.

***Summon Swarm of Poisonous Snakes (Recharge 5-6).*** Kyrilla conjures a swarm of poisonous snakes into an empty space within 10 feet of her. The swarm is under Kyrilla's control and acts on her turn, immediately after her in the initiative order.

It remains in existence for up to 1 hour. She can summon no more than three swarms per day. Kyrilla can banish any or all of her summoned swarms with a bonus action.

## Legendary Actions

***Claw.*** Kyrilla or a swarm of poisonous snakes makes a weapon attack.

***Detect.*** Kyrilla makes a Wisdom ([Perception](2-Mechanics/CLI/rules/skills.md#Perception)) check.

***Slither.*** Kyrilla moves up to her speed without provoking opportunity attacks.

![Kyrilla, Accursed Gorgon](2-Mechanics/CLI/bestiary/legendary-group/kyrilla-accursed-gorgon-aitfr-dn.md)
```
^statblock