---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/egw
- monster/cr/16
- monster/size/gargantuan
- monster/type/fiend
aliases: ["Udaak"]
---
# Udaak
*Source: Explorer's Guide to Wildemount p. 301*  

Known commonly as the brutes of Xhorhas, these enormous creatures resemble an immense, demonic cross between ox and gorilla. Udaaks are solitary wanderers, found most commonly along the edges of settled lands in the barrens of Eastern Wynandir. Though they often scavenge for food, a hungry udaak will attack almost any prey, its four sets of red eyes and its tangle of teeth and tusks striking fear into the heart of any creature.

Living Siege Engine. Originally brought to Exandria from the Abyss, udaaks lost their connection to that realm after the Divergence and have roamed the world freely ever since. In recent years, the warmasters of the Kryn Dynasty have developed arcane collars that can keep an udaak under control, and they have begun using these dread creatures in the war against the Dwendalian Empire.

```ad-statblock
title: Udaak
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/EGW/Udaak.webp#token)
*Gargantuan fiend, Neutral Evil*

- **Armor Class** 18 (natural armor)
- **Hit Points** 165 (`10d20 + 60`)
- **Speed** 50 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|26 (+8)|14 (+2)|22 (+6)| 3 (-4)|11 (+0)|10 (+0)|

- **Proficiency Bonus** +5
- **Saving Throws** Strength +13, Constitution +11
- **Skills** ⏤
- **Senses** darkvision 120 ft., passive Perception 10
- **Damage Vulnerabilities** thunder
- **Damage Immunities** poison; bludgeoning, piercing, slashing from nonmagical attacks
- **Condition Immunities** [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned), [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained)
- **Languages** —
- **Challenge** 16

## Traits

***Charge.*** If the udaak moves at least 20 feet straight toward a target and then hits it with a slam attack on the same turn, the target takes an extra `dice:6d8|noform|avg|text(27)` (`6d8`) bludgeoning damage. If the target is a creature, it must succeed on a DC 21 Strength saving throw or be pushed up to 20 feet away from the udaak and knocked [prone](2-Mechanics/CLI/rules/conditions.md#Prone).

***Siege Monster.*** The udaak deals double damage to objects and structures.

## Actions

***Multiattack.*** The udaak makes three attacks: one with its bite and two with its slam.

***Bite.*** *Melee Weapon Attack:* `dice:1d20+13|noform|text(+13)` to hit, reach 5 ft., one creature. *Hit:* `dice:2d12+8|noform|avg|text(21)` (`2d12 + 8`) piercing damage, and the target is [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) (escape DC 21). Until this grapple ends, the target is [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained), and the udaak can't bite another target.

***Slam.*** *Melee Weapon Attack:* `dice:1d20+13|noform|text(+13)` to hit, reach 10 ft., one target. *Hit:* `dice:3d8+8|noform|avg|text(21)` (`3d8 + 8`) bludgeoning damage.

***Swallow.*** The udaak makes one bite attack against a Large or smaller target it is grappling. If the attack hits, the target is also swallowed, and the grapple ends. A swallowed creature is [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded) and [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained), it has total cover against attacks and other effects outside the udaak, and it takes `dice:6d6|noform|avg|text(21)` (`6d6`) acid damage at the start of each of the udaak's turns.

If the udaak takes 30 damage or more on a single turn from a creature inside it, the udaak must succeed on a DC 21 Constitution saving throw at the end of that turn or regurgitate all swallowed creatures, which fall [prone](2-Mechanics/CLI/rules/conditions.md#Prone) in a space within 10 feet of the udaak. If the udaak dies, a swallowed creature is no longer [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) by it and can escape from the corpse by using 20 feet of movement, exiting [prone](2-Mechanics/CLI/rules/conditions.md#Prone).
```
^statblock