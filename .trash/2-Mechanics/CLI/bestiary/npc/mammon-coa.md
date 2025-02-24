---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/coa
- monster/cr/26
- monster/size/huge
- monster/type/fiend/devil
aliases: ["Mammon"]
---
# Mammon
*Source: Chains of Asmodeus p. 230*  

Perhaps the richest being in all the realms, there is nothing that Mammon loves more than wealth. Where other devils obsess over souls and power, Mammon is perfectly content to continually increase his material possessions. Interestingly, he is one of the only archdevils willing to make deals with mortals over strictly monetary terms. Whether he maintains his end of the deal, however, is a completely different story. Anyone that interacts with Mammon immediately recognizes his two-faced approach—the devil will say or do anything, if he thinks it will benefit him in the end.

Aside from hunting for coin, Mammon also enjoys hunting for sport. If anger strikes him (and it does so often), he will frequently summon up a steed and hounds to partake in a trophy hunt.

Anything he has designated as prey rarely escapes his fervor, though he quickly grows bored once his quarry is caught.

Scheming and betrayal are like breathing for Mammon, and conversely so is bootlicking. Some argue that his punishment after the Reckoning was severely reduced due to his shameless groveling before Asmodeus. In fact, he was the first of all archdevils to surrender during the coup, even selling out some of his co-conspirators.

Despite all his faults, one thing Mammon has mastered is the soul trade. Even Asmodeus recognizes that no archdevil can manage and distribute souls as well as Mammon. Perhaps his expertise comes from the massive profit that can be made from managing souls, or perhaps he wanted to find somewhere to belong—nobody knows for sure.

## Mammon's Lair

Mammon's lair is in a tomb-like palace, within Minauros, and like most structures in the city is in a perpetual state of sinking into the swamp.

## Statblock

```ad-statblock
title: Mammon
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/CoA/Mammon.webp#token)
*Huge fiend (devil), Lawful Evil*

- **Armor Class** 18 (natural armor)
- **Hit Points** 464 (`32d12 + 256`)
- **Speed** 40 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|28 (+9)|17 (+3)|26 (+8)|22 (+6)|25 (+7)|25 (+7)|

- **Proficiency Bonus** +8
- **Saving Throws** Dexterity +11, Constitution +16, Wisdom +15, Charisma +15
- **Skills** Arcana +14, Deception +15, Insight +15, Intimidation +23, Investigation +14, Persuasion +23
- **Senses** darkvision 120 ft., truesight 120 ft., passive Perception 17
- **Damage Resistances** acid; cold; bludgeoning, piercing, slashing from nonmagical attacks that aren't silvered
- **Damage Immunities** fire, poison
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** Celestial, Common, Draconic, Infernal, telepathy 120 ft.
- **Challenge** 26

## Traits

***Devil's Sight.*** Magical darkness doesn't impede Mammon's darkvision.

***Fiendish Regeneration.*** Mammon regains 20 hit points at the start of his turn. If he takes radiant damage this trait doesn't function at the start of his next turn. Mammon only dies if he starts his turn with 0 hit points and is unable to regenerate.

***Legendary Resistance (3/Day).*** If Mammon fails a saving throw, he can choose to succeed instead

***Magic Resistance.*** Mammon has advantage on saving throws against spells and other magical effects.

## Actions

***Multiattack.*** Mammon uses Fearful Gaze, then makes four attacks using Tail Swipe, Constrict, or a combination of the two.

***Tail Swipe.*** *Melee Weapon Attack:* `dice:1d20+17|noform|text(+17)` to hit, reach 10 ft., one target. *Hit:* `dice:4d10+9|noform|avg|text(31)` (`4d10 + 9`) bludgeoning damage. If the target is a Large or smaller creature, it has the [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) condition (escape DC 21). While [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled), the creature also has the [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) condition, and Mammon can't make Tail Swipe attacks.

***Fearful Gaze.*** Mammon focuses his gaze in a 90-foot cone in front of him. Each creature of his choice within the cone must make a DC 23 Wisdom saving throw, taking `dice:3d12|noform|avg|text(19)` (`3d12`) psychic damage on a failed save, or half as much damage on a successful one. Creatures that fail the save have the [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened) condition until the end of their next turn.

***Constrict.*** Mammon tightens his grip around a creature he has [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled). The target takes `dice:4d12+9|noform|avg|text(35)` (`4d12 + 9`) bludgeoning damage.

***Golden Gaze (Recharge 6).*** Mammon attempts to turn one creature he can see within 60 feet of him into solid gold. The target must make a DC 23 Constitution saving throw. On a failed save, the target's flesh begins to harden, and it has the [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) condition. A [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) creature must repeat the saving throw at the end of each turn. If it successfully saves three times, the effect ends. If it fails three times, it turns to gold and now has the [petrified](2-Mechanics/CLI/rules/conditions.md#Petrified) condition. Successes and failures don't need to be consecutive.

## Reactions

***Pain Tax.*** As a reaction to taking damage, Mammon causes the attacker's valuables to glow red hot. This deals `dice:1d6|noform|avg|text(3)` (`1d6`) fire damage to the attacker for every 100 gold (or equivalent in gems, jewelry, and other coinage) that it currently carries.

## Legendary Actions

***Change Form.*** Mammon changes his form into that of a pit fiend, maintaining his statistics but losing his actions. He gains the actions and mobility of a pit fiend, including its weapon, and maintains his legendary actions and lair actions. Mammon's serpentine abilities can still recharge while he is in pit fiend form. If Mammon is already a pit fiend, this action changes him back into his serpentine form.

***Golden Touch (Costs 2 Actions).*** Mammon recharges Golden Gaze.

***Call Underling (Costs 3 Actions).*** Mammon summons an allied [horned devil](2-Mechanics/CLI/bestiary/fiend/horned-devil.md) in an unoccupied space that he can see.

![Mammon](2-Mechanics/CLI/bestiary/legendary-group/mammon-coa.md)
```
^statblock