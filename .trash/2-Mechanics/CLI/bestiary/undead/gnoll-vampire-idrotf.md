---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/idrotf
- monster/cr/8
- monster/size/medium
- monster/type/undead/shapechanger
aliases: ["Gnoll Vampire"]
---
# Gnoll Vampire
*Source: Icewind Dale: Rime of the Frostmaiden p. 290*  

When a gnoll's ravenous hunger is so great that it craves flesh and blood even after death, it can rise as a vampire to continue its feeding frenzy.

A gnoll vampire is a savage predator that feeds on the blood of the living. It cackles maniacally when it catches the scent of its prey and quickly moves in for the kill, tearing away flesh with its claws, gorging on meat and blood, and leaving nothing behind but bones, gristle, and the victim's blood-spattered belongings.

Gnoll vampires are indiscriminate feeders that prefer the flesh and blood of humanoids, including other gnolls. Their noses can't stand the scent of perfumes, and their ears can't abide words spoken aloud in Celestial. They don't cast reflections in mirrors unless they want to.

Unlike normal vampires, gnoll vampires don't have coffins where they rest, and they have no such places to return to when their corporeal bodies are destroyed. They are undeterred by running water, and they can enter residences without invitation. When a gnoll vampire needs to travel quickly, it adopts the form of a giant, emaciated hyena. When it wants to catch its prey by surprise, it takes the form of a cloud of mist. After it feeds on a victim's blood, its mist form takes on a crimson hue for an hour or so before its colorlessness returns.

> [!note] Tekeli-Li and the Caves of Hunger
> 
> Tekeli-li was a [fang of Yeenoghu](2-Mechanics/CLI/bestiary/fiend/gnoll-fang-of-yeenoghu.md), a powerful gnoll whose pack invaded Icewind Dale more than a century ago. When the gnolls' wanton slaughter of reindeer herds threatened the survival of the Reghed tribes, the tribes banded together against the gnolls and routed them in the autumn of 1333 DR. Tekeli-li and his surviving kin fled across the tundra with the Reghed tribes in pursuit.
> 
> The wounded gnolls found an icy cleft on the edge of the Reghed Glacier and hid there for the winter. To keep their leader alive, the other gnolls allowed Tekeli-li to eat them one by one, yet his hunger would not abate. Auril came upon the starving, half-frozen creature and flung Tekeli-li into an icy tomb deep within the glacier. In doing so, the Frostmaiden sought to preserve what the gnoll had become—the embodiment of winter's remorseless consumption.
> 
> Tekeli-li exists today as a gnoll vampire that hasn't fed in decades. Adventurers who use the "Rime of the Frostmaiden" to create a passage through the glacier unknowingly release the starving gnoll vampire from its icy sepulcher. For more information about Tekeli-li's lair, the Caves of Hunger, see chapter 6.
^tekeli-li-and-the-caves-of-hunger

```ad-statblock
title: Gnoll Vampire
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/IDRotF/Gnoll%20Vampire.webp#token)
*Medium undead (shapechanger), Chaotic Evil*

- **Armor Class** 17 (natural armor)
- **Hit Points** 93 (`11d8 + 44`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|20 (+5)|18 (+4)|18 (+4)| 6 (-2)|12 (+1)| 9 (-1)|

- **Proficiency Bonus** +3
- **Saving Throws** Dexterity +7, Constitution +7
- **Skills** ⏤
- **Senses** darkvision 120 ft., passive Perception 11
- **Damage Resistances** necrotic; bludgeoning, piercing, slashing from nonmagical attacks
- **Languages** Abyssal, Gnoll
- **Challenge** 8

## Traits

***Keen Smell.*** The vampire has advantage on Wisdom ([Perception](2-Mechanics/CLI/rules/skills.md#Perception)) checks that rely on smell.

***Rampage.*** When it reduces a creature to 0 hit points with a melee attack on its turn, the vampire can take a bonus action to move up to half its speed and make a bite attack.

***Regeneration.*** The vampire regains 10 hit points at the start of its turn if it has at least 1 hit point and isn't in sunlight or running water. If the vampire takes radiant damage or damage from holy water, this trait doesn't function at the start of the vampire's next turn.

***Shapechanger.*** If the vampire isn't in sunlight, it can use its action to polymorph into a Large hyena or a Medium cloud of mist, or back into its true form.

While in hyena form, the vampire can't speak, and its walking speed is 50 feet. Its statistics, other than its size and speed, are unchanged. Anything it is wearing transforms with it, but nothing it is carrying does. It reverts to its true form if it dies.

While in mist form, the vampire can't take any actions, speak, or manipulate objects. it is weightless, has a flying speed of 20 feet, can hover, and can enter a hostile creature's space and stop there. In addition, if air can pass through a space, the mist can do so without squeezing, and it can't pass through water. It has advantage on Strength, Dexterity, and Constitution saving throws, and it is immune to all nonmagical damage, except the damage it takes from sunlight.

***Unusual Nature.*** The vampire doesn't require air.

***Vampire Weaknesses.*** The vampire has the following flaws:

*Enraged by Celestial.* If it hears words of Celestial spoken, the vampire must try to attack the source of those spoken words on its next turn. If these words come from multiple sources and from opposite directions, the vampire is [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained). Otherwise, it moves to attack what it perceives to be the closest source.

*Repulsed by Perfume.* The vampire has disadvantage on melee attack rolls made against any creature wearing perfume or carrying an open container of it.

*Stake to the Heart.* If a piercing weapon made of wood is driven into the vampire's heart while the vampire is [incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated) in its resting place, the vampire is [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed) until the stake is removed.

*Sunlight Hypersensitivity.* The vampire takes 20 radiant damage when it starts its turn in sunlight. While in sunlight, it has disadvantage on attack rolls and ability checks.

## Actions

***Multiattack (Vampire Form Only).*** The vampire makes two attacks: one with its bite and one with its claws.

***Bite (Hyena or Vampire Form Only).*** *Melee Weapon Attack:* `dice:1d20+8|noform|text(+8)` to hit, reach 5 ft., one creature. *Hit:* `dice:2d6+5|noform|avg|text(12)` (`2d6 + 5`) piercing damage plus `dice:2d8|noform|avg|text(9)` (`2d8`) necrotic damage. The target's hit point maximum is reduced by an amount equal to the necrotic damage taken, and the vampire regains hit points equal to that amount. The reduction lasts until the target finishes a long rest. the target dies if its hit point maximum is reduced to 0.

***Claws (Vampire Form Only).*** *Melee Weapon Attack:* `dice:1d20+8|noform|text(+8)` to hit, reach 5 ft., one target. *Hit:* `dice:2d4+5|noform|avg|text(10)` (`2d4 + 5`) slashing damage.

***Frightful Cackle (Hyena or Vampire Form Only).*** The vampire emits a bone-chilling cackle. Each creature of the vampire's choice that is within 120 feet of the vampire and can hear its cackle must succeed on a DC 15 Wisdom saving throw or become [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened) for 1 minute. A creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success. If a creature's saving throw is successful or the effect ends for it, the creature is immune to the vampire's Frightful Cackle for the next 24 hours.

***Sickening Gaze (Hyena or Vampire Form Only).*** The vampire targets one humanoid it can see within 30 feet of it. If the target can see the vampire, the target must succeed on a DC 15 Constitution saving throw against this magic or be [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) for 24 hours. A creature whose saving throw is successful is immune to this vampire's Sickening Gaze for 24 hours.
```
^statblock