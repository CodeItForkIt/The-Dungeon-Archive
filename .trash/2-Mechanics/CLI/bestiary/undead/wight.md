---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/mm
- monster/cr/3
- monster/environment/desert
- monster/environment/swamp
- monster/environment/underdark
- monster/environment/urban
- monster/size/medium
- monster/type/undead
aliases: ["Wight"]
---
# Wight
*Source: Monster Manual p. 300, Curse of Strahd, Princes of the Apocalypse, The Rise of Tiamat, Storm King's Thunder, Tales from the Yawning Portal, Tomb of Annihilation, Waterdeep: Dungeon of the Mad Mage, Ghosts of Saltmarsh, Dragon of Icespire Peak, Sleeping Dragon's Wake, Baldur's Gate: Descent Into Avernus, Explorer's Guide to Wildemount, Icewind Dale: Rime of the Frostmaiden, Candlekeep Mysteries, Dragonlance: Shadow of the Dragon Queen, Plane Shift: Innistrad, Phandelver and Below: The Shattered Obelisk, Adventure Atlas: The Mortuary, Sigil and the Outlands, Dungeons of Drakkenheim, Vecna: Eve of Ruin, Quests from the Infinite Staircase. Available in the <span title='Systems Reference Document (5.1)'>SRD</span> and the Basic Rules (2014)*  

The word "wight" meant "person" in days of yore, but the name now refers to evil undead who were once mortals driven by dark desire and great vanity. When death stills such a creature's heart and snuffs its living breath, its spirit cries out to the demon lord Orcus or some vile god of the underworld for a reprieve: undeath in return for eternal war on the living. If a dark power answers the call, the spirit is granted undeath so that it can pursue its own malevolent agenda.

Wights possess the memories and drives of their formerly living selves. They will heed the call of whatever dark entity transformed them into undead, swearing oaths to appease their new lord while retaining their autonomy. Never tiring, a wight can pursue its goals relentlessly and without distraction.

## Life Eaters

Neither dead nor alive, a wight exists in a transitional state between one world and the next. The bright spark it possessed in life is gone, and in its place is a yearning to consume that spark in all living things.

When a wight attacks, this life essence glows like white-hot embers to its dark eyes, and the wight's cold touch can drain the spark through flesh, clothing, and armor.

## Shadow of the Grave

Wights flee from the world by day, away from the light of the sun, which they hate. They retreat to barrow mounds, crypts, and tombs where they dwell. Their lairs are silent, desolate places, surrounded by dead plants, noticeably blackened, and avoided by bird and beast.

Humanoids slain by a wight can rise as zombies under its control. Motivated by hunger for living souls and driven by the same desire for power that awakened them in undeath, some wights serve as shock troops for evil leaders, including wraiths. As soldiers, they are able to plan but seldom do so, relying on their hunger for destruction to overwhelm any creature that stands before them.

## Undead Nature

A wight doesn't require air, food, drink, or sleep.

## Statblock

```ad-statblock
title: Wight
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/MM/Wight.webp#token)
*Medium undead, Neutral Evil*

- **Armor Class** 14 ([studded leather](2-Mechanics/CLI/items/studded-leather-armor.md))
- **Hit Points** 45 (`6d8 + 18`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|15 (+2)|14 (+2)|16 (+3)|10 (+0)|13 (+1)|15 (+2)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** Perception +3, Stealth +4
- **Senses** darkvision 60 ft., passive Perception 13
- **Damage Resistances** necrotic; bludgeoning, piercing, slashing from nonmagical attacks that aren't silvered
- **Damage Immunities** poison
- **Condition Immunities** [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** the languages it knew in life
- **Challenge** 3

## Traits

***Sunlight Sensitivity.*** While in sunlight, the wight has disadvantage on attack rolls, as well as on Wisdom ([Perception](2-Mechanics/CLI/rules/skills.md#Perception)) checks that rely on sight.

## Actions

***Multiattack.*** The wight makes two longsword attacks or two longbow attacks. It can use its Life Drain in place of one longsword attack.

***Life Drain.*** *Melee Weapon Attack:* `dice:1d20+4|noform|text(+4)` to hit, reach 5 ft., one creature. *Hit:* `dice:1d6+2|noform|avg|text(5)` (`1d6 + 2`) necrotic damage. The target must succeed on a DC 13 Constitution saving throw or its hit point maximum is reduced by an amount equal to the damage taken. This reduction lasts until the target finishes a long rest. The target dies if this effect reduces its hit point maximum to 0.

A humanoid slain by this attack rises 24 hours later as a [zombie](2-Mechanics/CLI/bestiary/undead/zombie.md) under the wight's control, unless the humanoid is restored to life or its body is destroyed. The wight can have no more than twelve zombies under its control at one time.

***Longsword.*** *Melee Weapon Attack:* `dice:1d20+4|noform|text(+4)` to hit, reach 5 ft., one target. *Hit:* `dice:1d8+2|noform|avg|text(6)` (`1d8 + 2`) slashing damage, or `dice:1d10+2|noform|avg|text(7)` (`1d10 + 2`) slashing damage if used with two hands.

***Longbow.*** *Ranged Weapon Attack:* `dice:1d20+4|noform|text(+4)` to hit, range 150/600 ft., one target. *Hit:* `dice:1d8+2|noform|avg|text(6)` (`1d8 + 2`) piercing damage.
```
^statblock

## Environment

underdark, swamp, urban, desert