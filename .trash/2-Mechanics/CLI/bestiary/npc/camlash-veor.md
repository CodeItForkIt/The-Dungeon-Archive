---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/veor
- monster/cr/19
- monster/size/huge
- monster/type/fiend/demon
aliases: ["Camlash"]
---
# Camlash
*Source: Vecna: Eve of Ruin p. 181*  

Camlash is a monstrous demon covered in countless tiny, crawling spiders that appear and disappear at random.

Lolth isn't present in Pandesmos; she has given command of her legions to Camlash. The balor general specializes in leading campaigns with troops of loyal driders and mutated arachnids. Adherents of Lolth have joined Camlash's forces, despite the usual animosity between driders and people. All fight together in Lolth's name.

```ad-statblock
title: Camlash
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/VEoR/Camlash.webp#token)
*Huge fiend (demon), Chaotic Evil*

- **Armor Class** 19 (natural armor)
- **Hit Points** 325 (`26d12 + 156`)
- **Speed** 40 ft., fly 80 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|26 (+8)|15 (+2)|22 (+6)|20 (+5)|16 (+3)|22 (+6)|

- **Proficiency Bonus** +6
- **Saving Throws** Strength +14, Constitution +12, Wisdom +9, Charisma +12
- **Skills** ⏤
- **Senses** truesight 120 ft., passive Perception 13
- **Damage Resistances** cold; lightning; bludgeoning, piercing, slashing from nonmagical attacks
- **Damage Immunities** fire, poison
- **Condition Immunities** [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** Abyssal, telepathy 120 ft.
- **Challenge** 19

## Traits

***Death Throes.*** Camlash explodes when reduced to 0 hit points, and each creature within 30 feet of Camlash must make a DC 21 Dexterity saving throw, taking `dice:20d6|noform|avg|text(70)` (`20d6`) fire damage on a failed save or half as much damage on a successful one. The explosion ignites flammable objects in that area that aren't being worn or carried.

***Magic Resistance.*** Camlash has advantage on saving throws against spells and other magical effects.

***Spider Aura.*** Camlash is surrounded by tiny biting spiders that magically appear and disappear from moment to moment. At the start of each of Camlash's turns, each creature within 10 feet of Camlash takes `dice:3d6|noform|avg|text(10)` (`3d6`) poison damage and must succeed on a DC 21 Constitution saving throw or have the [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed) condition until the start of Camlash's next turn.

## Actions

***Multiattack.*** Camlash makes one Flaming Whip attack and one Lightning Blade attack. Camlash can replace one of these attacks with Teleport.

***Flaming Whip.*** *Melee Weapon Attack:* `dice:1d20+15|noform|text(+15)` to hit, reach 30 ft., one target. *Hit:* `dice:5d6+8|noform|avg|text(25)` (`5d6 + 8`) fire damage, and if the target is a creature, it must succeed on a DC 21 Strength saving throw or be pulled up to 25 feet toward Camlash.

***Lightning Blade.*** *Melee Weapon Attack:* `dice:1d20+15|noform|text(+15)` to hit, reach 10 ft., one target. *Hit:* `dice:3d8+8|noform|avg|text(21)` (`3d8 + 8`) slashing damage plus `dice:3d8|noform|avg|text(13)` (`3d8`) lightning damage.

***Teleport.*** Camlash magically teleports, along with any equipment she is wearing or carrying, up to 120 feet to an unoccupied space she can see.
```
^statblock