---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/mabjov
- monster/cr/24
- monster/size/huge
- monster/type/beast
aliases: ["Bhaal, Ravager"]
---
# Bhaal, Ravager
*Source: Minsc and Boo's Journal of Villainy p. 95*  

> [!quote] A quote from MINSC & BOO!  
> 
> When evil knocks on your door, don't ask who's there. Let your SWORD do the talking! But when you knock on evil's door, give it a good, hard KICK. And when evil asks, Who's there? tell them Boo sent you!

A wholly evil, debased and sadistic god, Bhaal—the God of Murder—is reviled by a majority of Faerûn's pantheon; his divine foes include Chauntea, Helm, Ilmater, Lathander, Lliira and Tyr.

Before his ascension to godhood, Bhaal was a power-hungry adventurer on Toril. Along with his companions Bane and Myrkul, he sought to attain the portfolio of Jergal, God of the Dead. Jergal willingly offered his realm to the Dark Three, though they couldn't decide amongst themselves who would rule. Upon Jergal's suggestion, the three divided his power, deciding how to divide it based on the outcome of a game. The three played a game of knucklebones, and Bane emerged as the victor. He claimed the domains of hatred, strife and tyranny as his own. Myrkul, coming second, chose rule over the dead. Finally, Bhaal chose the divine province of death and murder.

A century ago, Bhaal foresaw that he would die in the Time of Troubles and enacted a plan that would allow him to return to life by creating the Bhaalspawn—mortal children imbued with a fraction of his divine essence. While that plan took more than a century to come to fruition, Bhaal has indeed been reborn. Having been dead for more than a century, he now works to rebuild his following, which will augment his divine power. Some of his most powerful and devout followers include his Bhaalspawn son Sarevok and the famous sky captain Pelyious.

Bhaal has two avatar forms: a corpse-like male humanoid called the Slayer, and a huge beast known as the Ravager. He hunts victims at night in his Slayer form. When he has killed, it gives him the power to transform into the Ravager.

```ad-statblock
title: Bhaal, Ravager
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/MaBJoV/Bhaal%2C%20Ravager.webp#token)
*Huge beast, Lawful Evil*

- **Armor Class** 20 (natural armor)
- **Hit Points** 351 (`26d12 + 182`)
- **Speed** 40 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|28 (+9)|24 (+7)|24 (+7)|14 (+2)|16 (+3)|14 (+2)|

- **Proficiency Bonus** +7
- **Saving Throws** Strength +16, Dexterity +14, Charisma +9
- **Skills** Athletics +16, Perception +10, Stealth +14
- **Senses** darkvision 120 ft., truesight 60 ft., passive Perception 20
- **Damage Resistances** necrotic
- **Damage Immunities** acid; cold; fire; lightning; poison; bludgeoning, piercing, slashing from nonmagical attacks
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated), [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed), [petrified](2-Mechanics/CLI/rules/conditions.md#Petrified), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned), [stunned](2-Mechanics/CLI/rules/conditions.md#Stunned), [unconscious](2-Mechanics/CLI/rules/conditions.md#Unconscious)
- **Languages** Abyssal, Common, Primordial, Undercommon
- **Challenge** 24

## Traits

***Avatar of Bhaal.*** When the ravager drops to 0 hit points, its form fractures. Within the next 24 hours, it will reappear in its [slayer form](2-Mechanics/CLI/bestiary/humanoid/bhaal-slayer-mabjov.md) within `dice:2d6|noform|avg` (`2d6`) miles of where the ravager form fell.

***Cull the Weak.*** When the ravager damages a creature with a melee attack and the target is left with 20 or fewer remaining hit points, the creature must succeed on a DC 21 Constitution saving throw or be reduced to 0 hit points.

***Immutable Form.*** The ravager is immune to any spell or effect that would alter its form.

***Legendary Resistance (3/Day).*** If the ravager fails a saving throw, it can choose to succeed instead.

***Magic Resistance.*** The ravager has advantage on saving throws against spells and other magical effects.

***Magic Weapons.*** The ravager's Claw, Bite, and Spines attacks are magical.

***Spiked Hide.*** At the start of each of its turns, the ravager deals `dice:3d10|noform|avg|text(16)` (`3d10`) piercing damage to any creature grappling it or being [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) by it.

## Actions

***Multiattack.*** The ravager makes one Bite attack and then either two Claw attacks or two Spines attacks.

***Claw.*** *Melee Weapon Attack:* `dice:1d20+16|noform|text(+16)` to hit, reach 5 ft., one target. *Hit:* `dice:3d8+9|noform|avg|text(22)` (`3d8 + 9`) slashing damage plus `dice:2d6|noform|avg|text(7)` (`2d6`) necrotic damage. If the target is a creature, it must succeed on a DC 21 Constitution saving throw or have its hit point maximum reduced by an amount equal to the damage taken. The target dies if this attack reduces its hit point maximum to 0. The reduction lasts until removed by the [greater restoration](2-Mechanics/CLI/spells/greater-restoration.md) spell or other magic.

***Bite.*** *Melee Weapon Attack:* `dice:1d20+16|noform|text(+16)` to hit, reach 5 ft., one target. *Hit:* `dice:3d10+9|noform|avg|text(25)` (`3d10 + 9`) piercing damage plus `dice:2d6|noform|avg|text(7)` (`2d6`) necrotic damage. If the target is a creature, it must succeed on a DC 21 Constitution saving throw or have its hit point maximum reduced by an amount equal to the damage taken. The target dies if this attack reduces its hit point maximum to 0. The reduction lasts until removed by the [greater restoration](2-Mechanics/CLI/spells/greater-restoration.md) spell or other magic. Large or smaller creatures damaged by this attack are [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) (escape DC 20) and the ravager can't make another Bite attack until this grapple ends.

***Spines.*** *Ranged Weapon Attack:* `dice:1d20+14|noform|text(+14)` to hit, range 60/120 ft., one target. *Hit:* `dice:3d6+7|noform|avg|text(17)` (`3d6 + 7`) piercing damage. If the target fails a DC 19 Constitution saving throw, they are [stunned](2-Mechanics/CLI/rules/conditions.md#Stunned) until the end of their next turn.

## Legendary Actions

***Detect.*** The ravager makes a Wisdom ([Perception](2-Mechanics/CLI/rules/skills.md#Perception)) check.

***Spiky Carapace.*** The ravager flares its numerous spines and they elongate. Any creature within 5 feet of the ravager must make a DC 21 Dexterity saving throw, taking `dice:5d10|noform|avg|text(27)` (`5d10`) piercing damage on a failed save, or half as much damage on a successful one.

***Smash (Costs 2 Actions).*** The ravager smashes downwards with great force, causing a violent implosion. Any creature within 10 feet of the ravager must make a DC 20 Constitution saving throw, taking `dice:4d8|noform|avg|text(18)` (`4d8`) thunder damage on a failed save, or half as much damage on a successful one. Creatures that fail the saving throw are also pulled 5 feet towards the ravager. The noise produced by this attack can be heard up to 1 mile away.
```
^statblock