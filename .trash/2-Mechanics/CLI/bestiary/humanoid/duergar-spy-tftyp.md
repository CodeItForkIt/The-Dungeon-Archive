---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tftyp
- monster/cr/2
- monster/size/medium
- monster/type/humanoid/dwarf
aliases: ["Duergar Spy"]
---
# Duergar Spy
*Source: Tales from the Yawning Portal p. 234*  

The tyrannical duergar, also known as gray dwarves, dwell in fantastic cities deep in the Underdark. Using ancient dwarven knowledge and myriad slaves, they work tirelessly to expand their subterranean kingdoms.

Most duergar (including females) are bald and have ashen gray skin. They wear drab clothing designed to blend in with stone, along with simple jewelry that reflects their severe and utilitarian demeanor.

## Slaves to Slavers

The duergar were once dwarves, before their greed and endless delving beneath the earth brought them into contact with the mind flayers. Held in captivity for generations by the illithids, the dwarves eventually won their independence with the aid of the evil god Laduguer. Slavery had forever changed them, however, darkening their spirits to make the duergar as evil as the tyrants they had escaped. Despite winning their freedom, duergar are dour, pessimistic, untrusting creatures, always toiling and complaining, with no memory of what it means to be happy or proud. Their craftsmanship and accomplishments endure, yet they are bereft of warmth or artistry.

Duergar make war against their dwarven kin and all other subterranean races. They forge alliances when it is convenient, then break those alliances when they have nothing more to gain. They take and hold slaves to toil in the Underdark, regarding them as free labor and crude currency.

## Tough as Stone

Like dwarves, duergar have strong constitutions. Adding to their physical stamina is an incredible mental fortitude resulting from their time as slaves of the illithids. A duergar's mind is a fortress, able to shrug off charms, illusions, and other spells.

## Born of Darkness

The Underdark is saturated with strange magical power, which the duergar absorbed over generations of imprisonment. A duergar can increase its size and strength for a short time, becoming a powerful ogre-sized warrior. If it faces a foe it can't fight, or when spying on creatures approaching its territory, it can just as easily become [invisible](2-Mechanics/CLI/rules/conditions.md#Invisible) to slip away into the darkness. Eons spent in the Underdark also sharpened their [darkvision](2-Mechanics/CLI/rules/senses.md#Darkvision), allowing them to see twice as far as other dwarves. This keen eyesight comes at a cost, however, as a duergar's vision is compromised by sunlight.

## Infernal Master

Asmodeus, Lord of the Nine Hells, has been known to impersonate duergar gods in order to cultivate the evil brimming in the hearts of the gray dwarves. He offers them divine guidance and vengeance against their enemies while urging them on toward greater acts of tyranny, all the while concealing his true identity.

## Statblock

```ad-statblock
title: Duergar Spy
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/TftYP/Duergar%20Spy.webp#token)
*Medium humanoid (dwarf), Lawful Evil*

- **Armor Class** 15 ([studded leather](2-Mechanics/CLI/items/studded-leather-armor.md))
- **Hit Points** 33 (`6d8 + 6`)
- **Speed** 25 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|10 (+0)|16 (+3)|12 (+1)|12 (+1)|10 (+0)|13 (+1)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** Deception +5, Insight +2, Investigation +5, Perception +4, Persuasion +3, Sleight of Hand +5, Stealth +7
- **Senses** darkvision 120 ft., passive Perception 14
- **Damage Resistances** poison
- **Languages** Dwarvish, Undercommon
- **Challenge** 2

## Traits

***Cunning Action.*** On each of its turns, the spy can use a bonus action to take the Dash, Disengage, or Hide action.

***Duergar Resilience.*** The spy has advantage on saving throws against poison, spells, and illusions, as well as to resist being [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed) or [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed).

***Sneak Attack.*** Once per turn, the spy can deal an extra `dice:2d6|noform|avg|text(7)` (`2d6`) damage when it hits a target with a weapon attack and has advantage on the attack roll, or when the target is within 5 feet of an ally of the spy that isn't [incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated) and the spy doesn't have disadvantage on the attack roll.

***Sunlight Sensitivity.*** While in sunlight, the spy has disadvantage on attack rolls, as well as on Wisdom ([Perception](2-Mechanics/CLI/rules/skills.md#Perception)) checks that rely on sight.

## Actions

***Multiattack.*** The spy makes two shortsword attacks.

***Enlarge (Recharges after a Short or Long Rest).*** For 1 minute, the spy magically increases in size, along with anything it is wearing or carrying. While enlarged, the spy is Large, doubles her damage dice on Strength-based weapon attacks (included in the attacks), and makes Strength checks and Strength saving throws with advantage. If the spy lacks the room to become Large, it attains the maximum size possible in the space available.

***Shortsword.*** *Melee Weapon Attack:* `dice:1d20+5|noform|text(+5)` to hit, reach 5 ft., one target. *Hit:* `dice:1d6+3|noform|avg|text(6)` (`1d6 + 3`) piercing damage, or `dice:2d6+3|noform|avg|text(10)` (`2d6 + 3`) piercing damage while enlarged.

***Hand Crossbow.*** *Ranged Weapon Attack:* `dice:1d20+5|noform|text(+5)` to hit, range 30/120 ft., one target. *Hit:* `dice:1d6+3|noform|avg|text(6)` (`1d6 + 3`) piercing damage.

***Invisibility (Recharges after a Short or Long Rest).*** The spy magically turns [invisible](2-Mechanics/CLI/rules/conditions.md#Invisible) until it attacks, deals damage, casts a spell, or uses its Enlarge, or until its [concentration](2-Mechanics/CLI/rules/conditions.md#Concentration) is broken, up to 1 hour (as if concentrating on a spell). Any equipment the spy wears or carries is [invisible](2-Mechanics/CLI/rules/conditions.md#Invisible) with it.
```
^statblock