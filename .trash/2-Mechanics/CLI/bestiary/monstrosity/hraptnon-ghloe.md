---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/ghloe
- monster/cr/18
- monster/size/gargantuan
- monster/type/monstrosity
aliases: ["Hraptnon"]
---
# Hraptnon
*Source: Grim Hollow: Lairs of Etharis p. 72*  

> [!quote]  
> 
> The magic our wizard used just bounced off the gigantic creature, and as our fighter slashed at it with her sword, the creature's blood spawned even more monsters.

## Salvage

A central spike growing from the hraptnon can be fashioned into a spear or lance by a proficient weaponsmith succeeding on a DC 20 Intelligence ([Arcana](2-Mechanics/CLI/rules/skills.md#Arcana)) check. This takes 10 days of work and 1000 gp of components. The spear or lance acts as a+3 weapon that does an additional `dice:2d6|noform|avg|text(7)` (`2d6`) force damage on a successful hit. This magical weapon can affect the hraptnon, unlike other magical weapons.

## Lore

- **DC 15 Intelligence ([History](2-Mechanics/CLI/rules/skills.md#History)).** The hraptnon lives in the Stillborn Forest, and it has never been seen outside of the forest bounds.  
- **DC 20 Intelligence ([Arcana](2-Mechanics/CLI/rules/skills.md#Arcana)).** No magical spells or weapons can hurt the hraptnon, and its blood can spawn creatures known as xakalonus.  
- **DC 25 Intelligence ([History](2-Mechanics/CLI/rules/skills.md#History)).** The hraptnon cannot be permanently killed unless its heart, which rests in a magical pool in a grove at the center of the Stillborn Forest, is found and destroyed. This heart, known as the Stillborn Heart, could be sold to a sage for a large sum of gold.  

> [!note] GM Advice
> 
> The hraptnon is a great example of a "puzzle monster," a beast that cannot be defeated until its secrets are revealed. Puzzle monsters can be a great deal of fun, especially to challenge extremely powerful parties. Just when the players think they've scored a potentially easy victory, they find that the threat remains.
> 
> The key to maximizing the impact of puzzle monsters like the hraptnon is to make sure not to reveal too much information too soon. Make the characters puzzle out the reality behind the monster, using resources and taking time to do so. When they are finally able to fully defeat the creature, their victory will be all the sweeter.
^gm-advice

## Statblock

```ad-statblock
title: Hraptnon
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/GHLoE/Hraptnon.webp#token)
*Gargantuan monstrosity, Chaotic Evil*

- **Armor Class** 18 (natural armor)
- **Hit Points** 264 (`16d20 + 96`)
- **Speed** 40 ft., burrow 20 ft., climb 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|21 (+5)|17 (+3)|22 (+6)|12 (+1)|17 (+3)|12 (+1)|

- **Proficiency Bonus** +6
- **Saving Throws** Strength +11, Dexterity +9, Constitution +12, Wisdom +9
- **Skills** Athletics +11, Perception +9
- **Senses** darkvision 120 ft., passive Perception 19
- **Damage Immunities** bludgeoning, piercing, slashing from magical weapons
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [stunned](2-Mechanics/CLI/rules/conditions.md#Stunned), [unconscious](2-Mechanics/CLI/rules/conditions.md#Unconscious)
- **Languages** Draconic
- **Challenge** 18

## Traits

***Legendary Resistance (3/Day).*** If the hraptnon fails a saving throw, it can choose to succeed instead.

***Magic Resistance.*** The hraptnon has advantage on saving throws against spells and other magical effects.

***Undying.*** Unless the hraptnon's Stillborn Heart is removed from its pool, the hraptnon's death is temporary. One of its countless xakalonus offspring grows into the hraptnon in 24 hours.

In addition, the hraptnon loses its immunities if the Stillborn Heart is removed from the pool.

## Actions

***Multiattack.*** The hraptnon makes three melee attacks: one bite and two claws. Alternatively, the hraptnon can make two spine attacks.

***Bite.*** *Melee Weapon Attack:* `dice:1d20+11|noform|text(+11)` to hit, reach 5 ft., one target. *Hit:* `dice:3d8+5|noform|avg|text(18)` (`3d8 + 5`) piercing damage, and the target must succeed on a DC 20 Constitution saving throw or be [incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated) until the end of the hraptnon's next turn.

***Claws.*** *Melee Weapon Attack:* `dice:1d20+11|noform|text(+11)` to hit, reach 10 ft., one target. *Hit:* `dice:4d10+5|noform|avg|text(27)` (`4d10 + 5`) slashing damage.

***Spine.*** *Melee Weapon Attack:* `dice:1d20+11|noform|text(+11)` to hit, range 60 ft., one target. *Hit:* `dice:4d8+5|noform|avg|text(23)` (`4d8 + 5`) piercing damage, and the target must succeed on a DC 20 Dexterity saving throw. On a failed save, the target is knocked [prone](2-Mechanics/CLI/rules/conditions.md#Prone) and [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained). The target must escape (DC 20) to remove the [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) condition and be able to stand.

## Reactions

***Spawn Xakalonus.*** If the hraptnon takes 20 points of damage or more from a single attack, it can spawn a xakalonus, which appears in a space adjacent to the hraptnon and attacks on the same initiative count as the hraptnon.

## Legendary Actions

***Claw.*** The hraptnon makes a claw attack.

***Baneful Howl (Costs 2 Actions).*** The hraptnon casts [bane](2-Mechanics/CLI/spells/bane.md) as a 3rd level spell (DC 20 to resist).

***Life Drain (Costs 3 Actions).*** One xakalonus within 30 feet of the hraptnon dies. The hraptnon regains hit points equal to half the hit points of the xakalonus that died.
```
^statblock