---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/11
- monster/environment/planar
- monster/size/large
- monster/type/fiend/devil
aliases: ["Koralk Devil"]
---
# Koralk Devil
*Source: Tome of Beasts 1 (2023 Edition) p. 97*  

*The fiendish hulk bears features taken from a nightmare scorpion, with three stinging tails and four limbs. It wields a massive scythe.*

## Shaped by Arbeyach

These fiends sprang from the dark imagination of Hell's Prince of Swarms, Arbeyach, who twisted them into being from lemures and scorpions. Arbeyach shaped the koralk to be annihilators in battle and to gather souls from the fallen, bypassing typical soul collection methods to feed his war machine more quickly. They are sometimes called "harvester devils."

## Transforming Poison

Poison from the koralk's stingers liquefies the victim's insides in an agonizing transformation. The creature swells as its organs, muscles, and skeleton rapidly break down and reform, transforming the creature into a lemure in a burst of fiendish goo. The new lemure is subject to the will of more powerful devils, and its fate from that moment on is the same as any lemure's. The koralk's poison can work this transformation on demons, giving Arbeyach's armies a unique edge.

## Infernal Mounts

A koralk is strong enough for many devils to ride. They prefer only powerful devils as riders, but they obey their superiors and carry even the lowest of devils into battle if directed. Arbeyach often rides an especially large specimen into battle, called the Grand Annihilator by his devilish troops.

## Statblock

```ad-statblock
title: Koralk Devil
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Koralk%20Devil.webp#token)
*Large fiend (devil), Lawful Evil*

- **Armor Class** 15 (natural armor)
- **Hit Points** 136 (`16d10 + 48`)
- **Speed** 40 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|20 (+5)|13 (+1)|17 (+3)|10 (+0)|11 (+0)|13 (+1)|

- **Proficiency Bonus** +4
- **Saving Throws** Constitution +7, Wisdom +4, Charisma +5
- **Skills** ⏤
- **Senses** darkvision 120 ft., passive Perception 10
- **Damage Resistances** cold; bludgeoning, piercing, slashing from nonmagical attacks that aren't silvered
- **Damage Immunities** fire, poison
- **Condition Immunities** [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** Infernal, telepathy 120 ft.
- **Challenge** 11

## Traits

***Devil's Sight.*** Magical darkness does not impair the koralk's darkvision.

***Harvester Venom.*** The koralk produces a potent poison that liquefies the innards of those affected by it. Every hour that elapses after a creature succumbs to this poison, it must succeed on a DC 17 Constitution saving throw or take `dice:2d6|noform|avg|text(7)` (`2d6`) poison damage, and its hp maximum is reduced by that amount. Creatures with resistance or immunity to poison or the [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) condition can be affected by this poison. Such creatures have advantage on the saving throw. This potent poison remains within the creature's body until removed by the [greater restoration](2-Mechanics/CLI/spells/greater-restoration.md) spell or similar magic. If a creature dies while suffering from this poison, it rises as a lemure 1 hour later under the control of the nearest non-lemure devil within 1 mile.

***Magic Resistance.*** The koralk has advantage on saving throws against spells and other magical effects.

***Steadfast.*** The koralk can't be [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened) while it can see an ally within 30 feet of it.

## Actions

***Multiattack.*** The koralk makes one Bite attack, one Scythe attack, and three Stinger attacks. It can replace its Scythe attack with a Vestigial Arms attack.

***Bite.*** *Melee Weapon Attack:* `dice:1d20+9|noform|text(+9)` to hit, reach 5 ft., one target. *Hit:* `dice:2d8+5|noform|avg|text(14)` (`2d8 + 5`) piercing damage.

***Scythe.*** *Melee Weapon Attack:* `dice:1d20+9|noform|text(+9)` to hit, reach 10 ft., one target. *Hit:* `dice:2d10+5|noform|avg|text(16)` (`2d10 + 5`) slashing damage.

***Stinger.*** *Melee Weapon Attack:* `dice:1d20+9|noform|text(+9)` to hit, reach 5 ft., one target. *Hit:* `dice:1d4+5|noform|avg|text(7)` (`1d4 + 5`) piercing damage plus `dice:2d6|noform|avg|text(7)` (`2d6`) poison damage, and the target must succeed on a DC 17 Constitution saving throw or succumb to the devil's venom (see the Harvester Venom trait).

***Vestigial Arms.*** *Melee Weapon Attack:* `dice:1d20+9|noform|text(+9)` to hit, reach 10 ft., one target. *Hit:* If the target is a Medium or smaller creature, it is [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) (escape DC 17). Until this grapple ends, the creature is [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained), and the devil can't use its Vestigial Arms on another target.
```
^statblock

## Environment

planar