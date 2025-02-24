---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/psz
- monster/cr/1-2
- monster/size/medium
- monster/type/undead
aliases: ["Shade"]
---
# Shade
*Source: Plane Shift: Zendikar p. 28*  

Magic fueled by black mana can alter the natural cycle of life and death. Whether wielded by mortal wizards or demons, or simply an environmental manifestation of black mana's flow through the land, such magic can trap spirits between the realm of the living and the mysterious fate of the dead. These ghostly undead are as destructive and hateful as the magic that calls them into being. Zendikar's shades and wraiths can be represented by the [shadows](2-Mechanics/CLI/bestiary/undead/shadow.md) and [wraiths](2-Mechanics/CLI/bestiary/undead/wraith.md) in the Monster Manual.

Not all spirits are created with black mana, however, and not all are malevolent. The spirits of the dead sometimes linger in the world to protect their kin or communities, or to stand guard over sacred or important sites. These spirits can be dangerous, but they are not usually malicious. Both the kor and the Mul Daya elves remain in communion with the spirits of their dead kindred, entreating them for wisdom and protection. Such spirits are best described as the [ghosts](2-Mechanics/CLI/bestiary/undead/ghost.md) in the Monster Manual.

```ad-statblock
title: Shade
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/PSZ/Shade.webp#token)
*Medium undead, Chaotic Evil*

- **Armor Class** 12
- **Hit Points** 16 (`3d8 + 3`)
- **Speed** 40 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
| 6 (-2)|14 (+2)|13 (+1)| 6 (-2)|10 (+0)| 8 (-1)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** Stealth +4
- **Senses** darkvision 60 ft., passive Perception 10
- **Damage Vulnerabilities** radiant
- **Damage Resistances** acid; cold; fire; lightning; thunder; bludgeoning, piercing, slashing from nonmagical attacks
- **Damage Immunities** necrotic, poison
- **Condition Immunities** [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled), [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed), [petrified](2-Mechanics/CLI/rules/conditions.md#Petrified), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned), [prone](2-Mechanics/CLI/rules/conditions.md#Prone), [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained)
- **Languages** —
- **Challenge** 1/2

## Traits

***Amorphous.*** The shadow can move through a space as narrow as 1 inch wide without squeezing.

***Shadow Stealth.*** While in dim light or darkness, the shadow can take the Hide action as a bonus action. Its stealth bonus is also improved to +6.

***Sunlight Weakness.*** While in sunlight, the shadow has disadvantage on attack rolls, ability checks, and saving throws.

## Actions

***Strength Drain.*** *Melee Weapon Attack:* `dice:1d20+4|noform|text(+4)` to hit, reach 5 ft., one creature. *Hit:* `dice:2d6+2|noform|avg|text(9)` (`2d6 + 2`) necrotic damage, and the target's Strength score is reduced by `dice:1d4|noform|avg` (`1d4`). The target dies if this reduces its Strength to 0. Otherwise, the reduction lasts until the target finishes a short or long rest.

If a non-evil humanoid dies from this attack, a new shadow rises from the corpse `dice:1d4|noform|avg` (`1d4`) hours later.
```
^statblock