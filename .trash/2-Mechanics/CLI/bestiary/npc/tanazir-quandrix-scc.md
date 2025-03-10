---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/scc
- monster/cr/24
- monster/size/gargantuan
- monster/type/dragon/wizard
aliases: ["Tanazir Quandrix"]
---
# Tanazir Quandrix
*Source: Strixhaven: A Curriculum of Chaos p. 218*  

The dragon Tanazir Quandrix is one of the most potent masters of the magic that governs physical reality and theoretical abstraction. Through this knowledge, she can alter the physical properties of existence, gain fundamental understanding, and manipulate the flow of thought.

Tanazir founded Quandrix College to nurture the spark of curiosity in those who would pursue knowledge. The goal is to train mages who seek knowledge for its own sake, guided by the mathematical principles that describe and govern the nature of reality.

Tanazir's spells, legendary actions, and breath weapon manifest luminous patterns of geometric light. These take various forms, such as an interlocking cage around the target of a spell or a wave of infinitely replicating fractal swirls in the area of her breath.

```ad-statblock
title: Tanazir Quandrix
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/SCC/Tanazir%20Quandrix.webp#token)
*Gargantuan dragon (wizard), Lawful Neutral*

- **Armor Class** 21 (natural armor)
- **Hit Points** 444 (`24d20 + 192`)
- **Speed** 40 ft., fly 80 ft. (hover)

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|28 (+9)|14 (+2)|27 (+8)|28 (+9)|18 (+4)|17 (+3)|

- **Proficiency Bonus** +7
- **Saving Throws** Dexterity +9, Constitution +15, Wisdom +11, Charisma +10
- **Skills** Arcana +23, Investigation +23, Nature +16, Perception +18
- **Senses** blindsight 120 ft., passive Perception 28
- **Damage Immunities** force, psychic
- **Languages** Common, Draconic, telepathy 120 ft.
- **Challenge** 24

## Traits

***Legendary Resistance (3/Day).*** If Tanazir fails a saving throw, she can choose to succeed instead.

***Spellcasting.*** Tanazir casts one of the following spells, requiring no material components and using Intelligence as the spellcasting ability (spell save DC 24):

**1/day each**: [divination](2-Mechanics/CLI/spells/divination.md), [enlarge/reduce](2-Mechanics/CLI/spells/enlarge-reduce.md), [mirage arcane](2-Mechanics/CLI/spells/mirage-arcane.md) (as an action), [polymorph](2-Mechanics/CLI/spells/polymorph.md), [scrying](2-Mechanics/CLI/spells/scrying.md) (as an action), [seeming](2-Mechanics/CLI/spells/seeming.md)

## Actions

***Multiattack.*** Tanazir makes one Bite attack and two Claw attacks.

***Bite.*** *Melee Weapon Attack:* `dice:1d20+16|noform|text(+16)` to hit, reach 15 ft., one target. *Hit:* `dice:1d10+9|noform|avg|text(14)` (`1d10 + 9`) piercing damage plus `dice:2d6|noform|avg|text(7)` (`2d6`) force damage.

***Claw.*** *Melee Weapon Attack:* `dice:1d20+16|noform|text(+16)` to hit, reach 10 ft., one target. *Hit:* `dice:2d6+9|noform|avg|text(16)` (`2d6 + 9`) slashing damage. If the target is a creature, it is addled by recursive thoughts, reducing its speed to 0 until the start of Tanazir's next turn.

***Diminution Breath (Recharge 5-6).*** Tanazir exhales a weakening equation in a 90-foot cone. Each creature in that area must make a DC 23 Constitution saving throw. On a failed save, a creature takes `dice:13d6|noform|avg|text(45)` (`13d6`) force damage and `dice:13d6|noform|avg|text(45)` (`13d6`) psychic damage and is weakened until the start of Tanazir's next turn. While weakened, it has disadvantage on the following rolls that rely on Strength: attack rolls, ability checks, and saving throws. On a successful save, a creature takes half as much damage and isn't weakened.

***Teleport.*** Tanazir teleports to an unoccupied space she can see within 100 feet of herself.

## Legendary Actions

***Claw.*** Tanazir makes one Claw attack.

***Fold Space (Costs 2 Actions).*** Tanazir uses Teleport, and each other creature within 20 feet of the space she left must succeed on a DC 24 Strength saving throw or be pulled up to 30 feet closer to the center of that space and take `dice:3d10|noform|avg|text(16)` (`3d10`) force damage.

***Fractal Refraction (Costs 3 Actions).*** Tanazir magically summons `dice:1d4|noform|avg` (`1d4`) [fractal mascots](2-Mechanics/CLI/bestiary/construct/fractal-mascot-scc.md) in unoccupied spaces she can see within 120 feet of herself. The fractals obey her commands and take their turns immediately after hers. While any of these fractals remain, attack rolls made against Tanazir have disadvantage. A summoned fractal disappears after 1 minute, when it or Tanazir dies, or when she uses this action again.
```
^statblock