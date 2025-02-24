---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/mabjov
- monster/cr/12
- monster/size/huge
- monster/type/fiend/demon
aliases: ["Bebilith"]
---
# Bebilith
*Source: Minsc and Boo's Journal of Villainy p. 133*  

> [!quote] A quote from Volo  
> 
> It is said that the drow can imprison a Bebilith in a metal shell. This new creation is called a Retriever and is used by the dark elves to track down and exterminate their enemies.

Bebiliths, or Creepers of the Abyss, are arachnoid demons that prey upon other demons... though whether they do so out of hunger, cruelty, or a strange compulsion to inflict justice on their chaotic evil kin is unknown. Other demons typically leave the bebilith alone and killing them is considered a great taboo. Further adding to the intrigue of their strange mystique, it is believed several greater demonic beings pay homage to the bebiliths.

## Barbed Horrors

Massive, hulking hunters, bebiliths possess foreleg claws that can carve through the thickest armor like warm butter. They can cast webs imbued with searing green fire, and the venom from their bite causes victims to ignite with green flames that burn them alive from the inside out. While their spiderlike appearance suggests the demon queen Lolth created them, most Abyssal scholars have refuted that theory. Their origins are seemingly lost in time, though most suspect the bebilith are natural predators that roamed the Abyss long before other demons spread across it in their teeming hordes.

## Relentless Hunters

Though they typically feed upon other demons, a bebilith will attack any creature it encounters without hesitation. During the initial strike, they mark their prey using a combination of pheromones and demonic magic. Once marked, a bebilith can track its victim across any distance—the only way to escape pursuit is by killing the bebilith or fleeing the Abyss. Fortunately, bebiliths cannot be summoned to the prime material plane. However, the drow discovered a way to draw their spirits into mechanical, spider-like constructs called retrievers, which they use to hunt or track their enemies.

> [!note] Carcerus Prison
> 
> The demodands of the Carcerus prison in Ust Natha have tortured a small number of bebilith into doing their bidding. These bebilith can use their relentless hunter ability on anyone ever imprisoned in Carcerus.
^carcerus-prison

## Statblock

```ad-statblock
title: Bebilith
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/MaBJoV/Bebilith.webp#token)
*Huge fiend (demon), Chaotic Evil*

- **Armor Class** 17 (natural armor)
- **Hit Points** 189 (`18d12 + 72`)
- **Speed** 40 ft., climb 40 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|16 (+3)|22 (+6)|18 (+4)|11 (+0)|13 (+1)| 8 (-1)|

- **Proficiency Bonus** +4
- **Saving Throws** Constitution +8, Wisdom +5
- **Skills** Perception +5, Stealth +10
- **Senses** blindsight 30 ft., darkvision 60 ft., passive Perception 15
- **Damage Resistances** cold; lightning; bludgeoning, piercing, slashing from nonmagical attacks
- **Damage Immunities** fire, poison
- **Condition Immunities** [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** understands Abyssal but only speaks telepathically to its own kind, telepathy 120 ft.
- **Challenge** 12

## Traits

***Dark Sight.*** Magical darkness doesn't impede the bebilith's darkvision.

***Spider Climb.*** The bebilith can climb difficult surfaces, including upside down, without needing to make an ability check and ignores any movement restrictions caused by webbing.

## Actions

***Multiattack.*** The bebilith uses Poisoned Web (if available) and then makes one Bite attack and two Foreleg attacks.

***Bite.*** *Melee Weapon Attack:* `dice:1d20+7|noform|text(+7)` to hit, reach 5 ft., one target. *Hit:* `dice:2d12+3|noform|avg|text(16)` (`2d12 + 3`) piercing damage plus `dice:6d6|noform|avg|text(21)` (`6d6`) poison damage. Any creature that drops to zero hit points because of this attack ignites, suffering `dice:2d6|noform|avg|text(7)` (`2d6`) fire damage at the start of each of its turns until the creature's hit points are above zero.

***Foreleg.*** *Melee Weapon Attack:* `dice:1d20+7|noform|text(+7)` to hit, reach 10 ft., one target. *Hit:* `dice:4d8+3|noform|avg|text(21)` (`4d8 + 3`) slashing damage.

***Poisoned Web (Recharge 5-6).*** *Ranged Weapon Attack:* `dice:1d20+10|noform|text(+10)` to hit, range 30/60 ft., one creature. *Hit:* `dice:10d8+6|noform|avg|text(51)` (`10d8 + 6`) poison damage, and the target has the [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) condition until free of the web. While [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained), the target takes `dice:2d8|noform|avg|text(9)` (`2d8`) poison damage at the start of each of its turns. The target may use an action to make a DC 17 Strength check and if successful they are freed from the webbing. The webbing can also be attacked and destroyed (AC 12; 10 hit points; immunity to bludgeoning, fire, poison, and psychic damage). If an attack or spell doing fire damage is used on the webbing, the webbing ignites (but is otherwise unharmed). Any creature [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) by the webbing suffers an additional `dice:2d6|noform|avg|text(7)` (`2d6`) fire damage at the start of each of its turn.

***Stalker's Darkness (3/Day).*** The bebilith casts [darkness](2-Mechanics/CLI/spells/darkness.md).

## Bonus Actions

***Relentless Hunter.*** The bebilith may use a bonus action to mark prey that it has damaged. Only one creature can be marked at a time. The bebilith always knows the exact location of the marked prey on the current plane of existence, can't be surprised by it, and has advantage on all attack rolls against it.
```
^statblock