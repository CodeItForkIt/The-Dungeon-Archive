---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/coa
- monster/cr/27
- monster/size/large
- monster/type/fiend/devil
aliases: ["Dispater"]
---
# Dispater
*Source: Chains of Asmodeus p. 222*  

Despite frequent shifts in leadership among other archdevils, Dispater has maintained his position as the ruler of Dis since its creation. Known for his vigilance and caution, he rarely leaves his tower, and even less frequently leaves the Iron City. Those who know his plans, including Asmodeus, know that he hopes to one day rule each layer of the Nine Hells.

Dispater remains one of the foremost suppliers of weapons across all the planes, which helps keep his position in Dis secure. As well, his advisors are carefully chosen and he maintains very few friendships.

Those that attempt battle with the Iron Lord find victory nigh impossible. In addition to his stratagem and defense, Dispater maintains extremely powerful abilities and a legion of minions. Outwitting him can't be done, and anyone unfortunate enough to catch him off guard is quickly disposed of.

Dispater remains calm and controlled in conversation. He prefers wherever possible to engage in gentlemanly debates rather than aggressive arguments. Unlike other archdevils, he almost never forces an individual into doing something, preferring to persuade or deceive instead. Fittingly, his skin is an iron-black color and his signature staff, wrought from the same iron as the tower he lives in, is always in hand.

## Dispater's Lair

The ruler of Dis makes his lair inside the Iron Tower. Within these confines he is vastly more protected.

## Statblock

```ad-statblock
title: Dispater
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/CoA/Dispater.webp#token)
*Large fiend (devil), Lawful Evil*

- **Armor Class** 21 (natural armor, [wrought-iron tower](2-Mechanics/CLI/items/wrought-iron-tower-coa.md))
- **Hit Points** 412 (`33d10 + 231`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|28 (+9)|17 (+3)|25 (+7)|25 (+7)|22 (+6)|24 (+7)|

- **Proficiency Bonus** +8
- **Saving Throws** Strength +17, Dexterity +11, Constitution +15, Intelligence +15
- **Skills** Arcana +23, Insight +22, Intimidation +15, Perception +14, Persuasion +15, Stealth +11
- **Senses** darkvision 120 ft., passive Perception 24
- **Damage Resistances** cold; bludgeoning, piercing, slashing from nonmagical attacks that aren't silvered
- **Damage Immunities** fire, poison
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** Celestial, Common, Draconic, Infernal, telepathy 120 ft.
- **Challenge** 27

## Traits

***Devil's Sight.*** Magical darkness doesn't impede Dispater's darkvision.

***Fear Aura.*** When a creature starts their turn within 120 feet of Dispater, they must succeed on a DC 22 Wisdom saving throw or have the [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened) condition until they leave the aura. A creature that succeeds on the saving throw is immune to this effect for 1 hour.

***Fiendish Regeneration.*** Dispater regains 20 hit points at the start of his turn. If he takes radiant damage this trait doesn't function at the start of his next turn. Dispater dies only if he starts his turn with 0 hit points and is unable to regenerate.

***Legendary Resistance (3/Day).*** If Dispater fails a saving throw, he can choose to succeed instead.

***Magic Resistance.*** Dispater has advantage on saving throws against spells and other magical effects.

***Rust Metal.*** Any nonmagical weapon or ammunition made of metal that hits Dispater corrodes. After its hit, the weapon or ammunition is destroyed.

## Actions

***Multiattack.*** Dispater makes four attacks using his Wrought- Iron Tower, Iron Column, or a combination of the two. He can replace one of the attacks with Superheat Metal (if available).

***Wrought-Iron Tower.*** *Melee Weapon Attack:* `dice:1d20+20|noform|text(+20)` to hit, reach 10 ft., one target. *Hit:* `dice:2d8+12|noform|avg|text(21)` (`2d8 + 12`) bludgeoning damage plus `dice:2d6|noform|avg|text(7)` (`2d6`) fire damage. Dispater may replace the bludgeoning damage with damage of a type that the target is vulnerable to instead.

***Iron Column.*** *Ranged Spell Attack:* `dice:1d20+15|noform|text(+15)` to hit, range 60 ft., one target. *Hit:* `dice:2d8+12|noform|avg|text(21)` (`2d8 + 12`) bludgeoning damage plus `dice:2d6|noform|avg|text(7)` (`2d6`) fire damage. Dispater may replace the bludgeoning damage with damage of a type that the target is vulnerable to instead.

***Superheat Metal (Recharge 4-6).*** Dispater targets a metal object he can see within 90 feet of him. The metal glows white-hot, burning all that touches it. If the object was held by a creature, the creature must succeed on a DC 23 Dexterity saving throw to drop the object or take `dice:10d8|noform|avg|text(45)` (`10d8`) fire damage. If the object is attached to a creature, or they couldn't feasibly drop it, they automatically fail the save. The object returns to room temperature at the end of Dispater's turn.

***Nail Spray (2/Day).*** Dispater conjures a storm of iron nails and launches them forward in a 90-foot-long, 5-foot-wide line. All creatures within the line must make a DC 23 Dexterity saving throw, taking `dice:16d4|noform|avg|text(40)` (`16d4`) piercing damage on a failed save, or half as much damage on a successful one. Nails launched from this ability stick into soft surfaces or fall to the ground after the attack finishes.

## Legendary Actions

***Staff.*** Dispater makes a Wrought-Iron Tower attack.

***Flesh to Iron (Costs 2 Actions).*** *Melee Spell Attack:* `dice:1d20+15|noform|text(+15)` to hit, reach 5 ft., one target. *Hit:* `dice:6d10+7|noform|avg|text(40)` (`6d10 + 7`) force damage, and the target must make a DC 23 Constitution saving throw. On a failed save, the target's flesh begins to harden, and the creature's movement speed is halved for 1 minute. If the creature is harmed by Flesh to Iron again, while still partly iron, the rest of the creature also turns to iron, killing them.

***Call Underling (Costs 3 Actions).*** Dispater summons an allied [erinyes](2-Mechanics/CLI/bestiary/fiend/erinyes.md) in an unoccupied space that he can see.

![Dispater](2-Mechanics/CLI/bestiary/legendary-group/dispater-coa.md)
```
^statblock