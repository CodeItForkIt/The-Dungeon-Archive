---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/ghloe
- monster/cr/4
- monster/size/large
- monster/type/undead
aliases: ["Zombie Troll"]
---
# Zombie Troll
*Source: Grim Hollow: Lairs of Etharis p. 121*  

> [!quote]  
> 
> Running away from a troll is smart. Running away from a troll that casts spells is wishful thinking.

## Salvage

Someone who has proficiency with jeweler's tools or woodcarver's tools can fashion the skull of a lich troll into a ring of regeneration. Doing so takes materials worth 5,000 gp, 10 days of work, and a successful DC 15 Intelligence or Wisdom check. Somebody must also cast greater restoration on the ring each day during the process. If the ring's wearer dies while wearing the ring, the soul of the lich has a 25 percent chance to take over the corpse and use it as a new body. But if the ring is created entirely in the area of a hallow spell with the everlasting rest effect, the tie to the lich's soul is broken.

## Lore

- **DC 15 Intelligence ([History](2-Mechanics/CLI/rules/skills.md#History)).** The lich troll is remnants of early attempts of powerful spellcasters to transfer their souls into trolls.  
- **DC 20 Intelligence ([Arcana](2-Mechanics/CLI/rules/skills.md#Arcana)).** The lich troll is immune to poison and resistant to necrotic damage. It regenerates and can be killed only by acid, fire, or radiant damage.  

## Statblock

```ad-statblock
title: Zombie Troll
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/GHLoE/Zombie%20Troll.webp#token)
*Large undead, Neutral Evil*

- **Armor Class** 14 (natural armor, [shield](2-Mechanics/CLI/items/shield.md))
- **Hit Points** 85 (`9d10 + 36`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|19 (+4)| 6 (-2)|18 (+4)| 3 (-4)| 6 (-2)| 5 (-3)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** ⏤
- **Senses** darkvision 60 ft., passive Perception 8
- **Damage Resistances** cold, necrotic
- **Damage Immunities** poison
- **Condition Immunities** [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** understands Giant but can't speak
- **Challenge** 4

## Traits

***Regeneration.*** The zombie troll regains 10 hit points at the start of its turn. If the zombie troll takes acid or radiant damage, this trait doesn't function at the start of the zombie troll's next turn. The zombie troll dies only if it starts its turn with 0 hit points and doesn't regenerate.

## Actions

***Multiattack.*** The zombie troll makes two attacks.

***Morningstar.*** *Melee Weapon Attack:* `dice:1d20+6|noform|text(+6)` to hit, reach 5 ft., one target. *Hit:* `dice:2d8+4|noform|avg|text(13)` (`2d8 + 4`) bludgeoning damage.

***Unrelenting Brute.*** If a creature is hit by both morningstar attacks, the creature must take a DC 14 Strength saving throw or be knocked [prone](2-Mechanics/CLI/rules/conditions.md#Prone).
```
^statblock