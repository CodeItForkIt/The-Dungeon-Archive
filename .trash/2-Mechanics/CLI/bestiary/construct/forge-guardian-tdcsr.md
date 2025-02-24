---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tdcsr
- monster/cr/27
- monster/size/gargantuan
- monster/type/construct
aliases: ["Forge Guardian"]
---
# Forge Guardian
*Source: Tal'Dorei Campaign Setting Reborn p. 241*  

Ageless and unstoppable guardians, golems are expertly crafted to execute their owners' every command without question. Vaguely humanoid in appearance and unfailingly loyal, these powerful constructs feel no agony or sympathy, require no sustenance or sleep, ignore bribes and bargains, and do as they are told without remorse or hesitation.

## Covetous Origins

During the "Age of Arcanum", magic inspired a deep arrogance in many of the gods' children, who assumed arcane gifts were proof of inevitable divinity. In response, many mortal folk experimented with manufacturing "life" of their own. The "dwarves" succeeded first, marrying divine gifts with technical skill to animate autonomous wardens as protectors of their ancestral halls. The "dwarves'" knowledge was quickly stolen and expanded upon by other folk, and creating golems eventually became less about proving that mortals can shape life as the gods do, and more about protecting life, wealth, and secrets from others.

## Forge Guardian

Just as "dwarves" created the earliest golems, the All-Hammer fashioned forge guardians to guard the divine furnaces and hearths that designed the first "dwarves". Shaped from extravagant marble and fused with adamantine, crafted with impeccable detail and care, these rare and massive constructs exemplify the highest form of artistry that every Exandrian blacksmith, forgemaster, and artisan spends a life-time hoping to achieve.

### Divine Spark

A faceless, tireless being of immense strength, a forge golem is gifted life by a single shard from the All-Hammer's own divine spark, lovingly kept safe inside a ring of arcane flame and ancient sigils. The All-Hammer's divinity is akin to a volcano inside the golem, turning the construct's blood into lava. Fire no longer harms the construct, but instead heals it.

### Sacred purpose

Where it looms over a divine forge, a forge guardian's appendages end in a stretched set of hooked forceps and a rune-adorned blade. The golem can assist a blacksmith in creating new golems, or it can trample, bludgeon, push, and knock down any who threaten this sacred process of creation.

Forge golems also serve as opponents for any wishing to engage in the All-Hammer's trial of worthiness. A golem's attacks blind prospective heroes, who must then earn back their vision by risking a deadly counterattack.

## Statblock

```ad-statblock
title: Forge Guardian
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/TDCSR/Forge%20Guardian.webp#token)
*Gargantuan construct, Unaligned*

- **Armor Class** 24 (natural armor)
- **Hit Points** 420 (`24d20 + 168`)
- **Speed** 50 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|30 (+10)|10 (+0)|24 (+7)| 3 (-4)|11 (+0)| 1 (-5)|

- **Proficiency Bonus** +8
- **Saving Throws** Strength +18, Constitution +15
- **Skills** ⏤
- **Senses** truesight 120 ft., passive Perception 10
- **Damage Immunities** fire; poison; psychic; bludgeoning, piercing, slashing from nonmagical weapons that aren't adamantine
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed), [petrified](2-Mechanics/CLI/rules/conditions.md#Petrified), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** —
- **Challenge** 27

## Traits

***Fire Absorption.*** Whenever the guardian is subjected to fire damage, it takes no damage and instead regains a number of hit points equal to the fire damage dealt.

***Immutable Form.*** The guardian is immune to any spell or effect that would alter its form.

***Magic Resistance.*** The guardian has advantage on saving throws against spells and other magical effects.

***Magic Weapons.*** The guardian's weapon attacks are magical.

## Actions

***Multiattack.*** The guardian makes two melee attacks.

***Runeblade.*** *Melee Weapon Attack:* `dice:1d20+18|noform|text(+18)` to hit, reach 15 ft., one target. *Hit:* `dice:4d12+10|noform|avg|text(36)` (`4d12 + 10`) slashing damage, and the target must succeed on a DC 23 Constitution saving throw or be [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded) until it deals damage to the guardian.

***Kick.*** *Melee Weapon Attack:* `dice:1d20+18|noform|text(+18)` to hit, reach 10 ft., one target. *Hit:* `dice:2d12+10|noform|avg|text(23)` (`2d12 + 10`) bludgeoning damage, and the target is pushed up to 15 feet away from the guardian and knocked [prone](2-Mechanics/CLI/rules/conditions.md#Prone).

***Bladestorm (Recharge 5-6).*** The guardian makes a Runeblade attack against every creature within 15 feet of it. On a hit, a target is also pushed up to 15 feet away from the guardian and knocked [prone](2-Mechanics/CLI/rules/conditions.md#Prone).

## Legendary Actions

***Runeblade.*** The guardian makes one Runeblade attack.

***Kick.*** The guardian makes one Kick attack.

***Trample (Costs 2 Actions).*** The guardian moves up to 50 feet without triggering [opportunity attacks](2-Mechanics/CLI/rules/actions.md#Opportunity%20Attack), and can pass through other creature's spaces. Each creature whose space the guardian passes through must make a DC 23 Dexterity saving throw. On a failure, the creature takes `dice:2d12+10|noform|avg|text(23)` (`2d12 + 10`) bludgeoning damage and is knocked [prone](2-Mechanics/CLI/rules/conditions.md#Prone). On a success, the creature takes half as much damage and isn't knocked [prone](2-Mechanics/CLI/rules/conditions.md#Prone). Any creature that shares the guardian's space when it stops this movement is pushed out of its space into the nearest unoccupied space.
```
^statblock