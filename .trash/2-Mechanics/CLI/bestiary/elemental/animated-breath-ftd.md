---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/ftd
- monster/cr/6
- monster/size/large
- monster/type/elemental
aliases: ["Animated Breath"]
---
# Animated Breath
*Source: Fizban's Treasury of Dragons p. 163*  

A chromatic dragon's breath weapon is a manifestation of the energy that suffuses the dragon. With sufficient practice, dragons can learn to draw on magic from the Elemental Planes to shape their breath weapons into bipedal form, creating Elemental creatures called animated breaths. Chromatic dragons often use these creatures as guardians for their hoards or send them out to gather treasure from the territory around their lairs.

An animated breath is a bipedal creature formed from the same energy as the breath weapon of the dragon that created it. A red dragon's creation strongly resembles a fire elemental, while a black dragon's is similar to a water elemental, but viscous and foul-looking. A green dragon's animated poison breath looks like billowing clouds of green gas, while a white dragon's animated cold breath looks like a walking ice sculpture with frigid air whirling around it. A blue dragon's animated lightning breath is a constantly shifting form of crackling lightning, and it can suddenly vanish from one place to reappear in another, striking like a bolt from the blue.

```ad-statblock
title: Animated Breath
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/FTD/Animated%20Breath.webp#token)
*Large elemental, typically  Neutral Evil*

- **Armor Class** 15 (natural armor; 17 cold form only)
- **Hit Points** 95 (`10d10 + 40`)
- **Speed** 30 ft., fly 30 ft. (hover)

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|19 (+4)|11 (+0)|18 (+4)| 6 (-2)|10 (+0)| 5 (-3)|

- **Proficiency Bonus** +3
- **Saving Throws** ⏤
- **Skills** ⏤
- **Senses** darkvision 60 ft., passive Perception 10
- **Damage Resistances** damage of the type matching the animated breath's form (acid, cold, fire, lightning, or poison)
- **Condition Immunities** [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed), [petrified](2-Mechanics/CLI/rules/conditions.md#Petrified), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned), [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained), [unconscious](2-Mechanics/CLI/rules/conditions.md#Unconscious)
- **Languages** understands Draconic but can't speak
- **Challenge** 6

## Traits

***Chromatic Form.*** When created, the animated breath takes one of five forms, matching its creator's breath weapon: Acid, Cold, Fire, Lightning, or Poison. This form determines the creature's AC, damage resistance, traits, and attacks.

***Fire Aura (Fire Form Only).*** At the start of each of the animated breath's turns, each creature within 5 feet of it takes `dice:1d6|noform|avg|text(3)` (`1d6`) fire damage, and flammable objects in the aura that aren't being worn or carried ignite. A creature that touches the animated breath or hits it with a melee attack takes `dice:1d6|noform|avg|text(3)` (`1d6`) fire damage.

***Putrid Aura (Acid and Poison Forms Only).*** A creature that starts its turn within 5 feet of the animated breath must succeed on a DC 15 Constitution saving throw or be [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) until the start of its next turn. A creature that touches the animated breath or hits it with a melee attack takes `dice:1d6|noform|avg|text(3)` (`1d6`) acid damage.

## Actions

***Multiattack.*** The animated breath makes two Slam attacks.

***Slam.*** *Melee Weapon Attack:* `dice:1d20+7|noform|text(+7)` to hit, reach 5 ft., one target. *Hit:* `dice:2d8+4|noform|avg|text(13)` (`2d8 + 4`) bludgeoning damage plus `dice:2d10|noform|avg|text(11)` (`2d10`) damage of a type determined by the animated breath's form: acid, cold, fire, lightning, or poison.

## Bonus Actions

***Lightning Burst (Lightning Form Only).*** The animated breath magically teleports to an unoccupied space it can see within 30 feet of it. Each creature within 5 feet of the animated breath after it teleports takes `dice:1d6|noform|avg|text(3)` (`1d6`) lightning damage.
```
^statblock