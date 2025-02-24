---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/mabjov
- monster/cr/20
- monster/size/medium
- monster/type/humanoid
aliases: ["Bhaal, Slayer"]
---
# Bhaal, Slayer
*Source: Minsc and Boo's Journal of Villainy p. 93*  

> [!quote] A quote from MINSC & BOO!  
> 
> When evil knocks on your door, don't ask who's there. Let your SWORD do the talking! But when you knock on evil's door, give it a good, hard KICK. And when evil asks, Who's there? tell them Boo sent you!

A wholly evil, debased and sadistic god, Bhaal—the God of Murder—is reviled by a majority of Faerûn's pantheon; his divine foes include Chauntea, Helm, Ilmater, Lathander, Lliira and Tyr.

Before his ascension to godhood, Bhaal was a power-hungry adventurer on Toril. Along with his companions Bane and Myrkul, he sought to attain the portfolio of Jergal, God of the Dead. Jergal willingly offered his realm to the Dark Three, though they couldn't decide amongst themselves who would rule. Upon Jergal's suggestion, the three divided his power, deciding how to divide it based on the outcome of a game. The three played a game of knucklebones, and Bane emerged as the victor. He claimed the domains of hatred, strife and tyranny as his own. Myrkul, coming second, chose rule over the dead. Finally, Bhaal chose the divine province of death and murder.

A century ago, Bhaal foresaw that he would die in the Time of Troubles and enacted a plan that would allow him to return to life by creating the Bhaalspawn—mortal children imbued with a fraction of his divine essence. While that plan took more than a century to come to fruition, Bhaal has indeed been reborn. Having been dead for more than a century, he now works to rebuild his following, which will augment his divine power. Some of his most powerful and devout followers include his Bhaalspawn son Sarevok and the famous sky captain Pelyious.

Bhaal has two avatar forms: a corpse-like male humanoid called the Slayer, and a huge beast known as the Ravager. He hunts victims at night in his Slayer form. When he has killed, it gives him the power to transform into the Ravager.

```ad-statblock
title: Bhaal, Slayer
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/MaBJoV/Bhaal%2C%20Slayer.webp#token)
*Medium humanoid, Lawful Evil*

- **Armor Class** 19 (natural armor)
- **Hit Points** 266 (`28d8 + 140`)
- **Speed** 40 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|24 (+7)|22 (+6)|20 (+5)|14 (+2)|16 (+3)|14 (+2)|

- **Proficiency Bonus** +6
- **Saving Throws** Strength +13, Dexterity +12
- **Skills** Stealth +18
- **Senses** darkvision 60 ft., passive Perception 13
- **Damage Resistances** bludgeoning, piercing, slashing from nonmagical attacks
- **Damage Immunities** poison
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated), [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed), [petrified](2-Mechanics/CLI/rules/conditions.md#Petrified), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned), [stunned](2-Mechanics/CLI/rules/conditions.md#Stunned), [unconscious](2-Mechanics/CLI/rules/conditions.md#Unconscious)
- **Languages** Abyssal, Common
- **Challenge** 20

## Traits

***Assassinate.*** During its first turn, the slayer has advantage on attack rolls against any creature that hasn't taken a turn. Any hit the slayer scores against a surprised creature is a critical hit.

***Devil's Sight.*** Magical darkness doesn't impede the slayer's darkvision.

***Immutable Form.*** The slayer is immune to any spell or effect that would alter its form, except for its Ravager Form ability.

***Legendary Resistance (2/Day).*** If the slayer fails a saving throw, it can choose to succeed instead.

***Magic Resistance.*** The slayer has advantage on saving throws against spells and other magical effects.

***Magic Weapons.*** The slayer's claw attacks are magical.

## Actions

***Multiattack.*** The slayer makes four Claw attacks.

***Claw.*** *Melee Weapon Attack:* `dice:1d20+13|noform|text(+13)` to hit, reach 5 ft., one target. *Hit:* `dice:2d8+7|noform|avg|text(16)` (`2d8 + 7`) slashing damage plus `dice:1d6|noform|avg|text(3)` (`1d6`) necrotic damage. If the target is a creature, it must succeed on a DC 19 Constitution saving throw or have its hit point maximum reduced by an amount equal to the damage taken. The target dies if this attack reduces its hit point maximum to 0. The reduction lasts until removed by the [greater restoration](2-Mechanics/CLI/spells/greater-restoration.md) spell or other magic.

## Bonus Actions

***Prey.*** The slayer focuses on a single creature it can see within 60 feet. Afterwards, the first time each turn that the slayer hits that creature, the slayer does an additional `dice:2d6|noform|avg|text(7)` (`2d6`) damage.

## Legendary Actions

***Savage Disengage.*** The slayer disengages without provoking opportunity attacks. If it moves within 5 feet of a creature it makes a Claw attack against the creature.

***Finish (Costs 2 Actions).*** The slayer attacks a creature that has been marked by its Prey ability. If this attack hits and the creature has less than 40 hit points remaining after the attack, the creature is reduced to 0 hit points.

***Ravager Form (Costs 3 Actions).*** If the slayer has killed a creature of CR/level 5 or greater that it previously marked with its Prey ability in the last minute, it can transform into its [ravager form](2-Mechanics/CLI/bestiary/beast/bhaal-ravager-mabjov.md). The form lasts until dawn (minimum 1 hour).
```
^statblock