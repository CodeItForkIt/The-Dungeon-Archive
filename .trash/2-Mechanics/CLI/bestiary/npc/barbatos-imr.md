---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/imr
- monster/cr/6
- monster/size/medium
- monster/type/humanoid/human
aliases: ["Barbatos"]
---
# Barbatos
*Source: Infernal Machine Rebuild p. 52*  

```ad-statblock
title: Barbatos
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/IMR/Barbatos.webp#token)
*Medium humanoid (human), Neutral Evil*

- **Armor Class** 15 ([studded leather](2-Mechanics/CLI/items/studded-leather-armor.md))
- **Hit Points** 78 (`12d8 + 24`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|11 (+0)|16 (+3)|14 (+2)|13 (+1)|14 (+2)|10 (+0)|

- **Proficiency Bonus** +3
- **Saving Throws** ⏤
- **Skills** Animal Handling +5, Deception +3, Perception +5, Stealth +6
- **Senses** passive Perception 13
- **Damage Resistances** poison
- **Languages** Common
- **Challenge** 6

## Traits

***Rust Monster Cloak.*** Any nonmagical weapon made of metal that hits Barbatos corrodes. After dealing damage, the weapon takes a permanent and cumulative -1 penalty to damage rolls. If its penalty drops to -5, the weapon is destroyed. Nonmagical ammunition made of metal that hits Barbatos is destroyed after dealing damage.

***Heart of the Troll.*** Barbatos regains 10 hit points at the start of his turn. If Barbatos takes acid or fire damage, this trait doesn't function at the start of Barbatos's next turn. Barbatos dies only if he starts his turn with 0 hit points and doesn't regenerate.

***Spellcasting.*** Barbatos is a 6th-level spellcaster. His spellcasting ability is Wisdom (spell save DC 13, `dice:1d20+5|noform|text(+5)` to hit with spell attacks). He has the following ranger spells prepared:

**1st level (4 slots)**: [ensnaring strike](2-Mechanics/CLI/spells/ensnaring-strike.md), [hail of thorns](2-Mechanics/CLI/spells/hail-of-thorns.md), [hunter's mark](2-Mechanics/CLI/spells/hunters-mark.md)

**2nd level (2 slots)**: [locate animals or plants](2-Mechanics/CLI/spells/locate-animals-or-plants.md)

## Actions

***Multiattack.*** Barbatos makes two bone shortsword attacks.

***Bone Shortsword.*** *Melee Weapon Attack:* `dice:1d20+6|noform|text(+6)` to hit, reach 5 ft., one target. *Hit:* `dice:1d6+3|noform|avg|text(6)` (`1d6 + 3`) piercing damage.

***Light Crossbow.*** *Ranged Weapon Attack:* `dice:1d20+6|noform|text(+6)` to hit, range 80/320 ft., one target. *Hit:* `dice:1d8+3|noform|avg|text(7)` (`1d8 + 3`) piercing damage, and the target must succeed on a DC 13 Constitution saving throw or be [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) for 1 hour. If the saving throw fails by 5 or more, the target is also [unconscious](2-Mechanics/CLI/rules/conditions.md#Unconscious). The target regains consciousness if it takes damage or if another creature takes an action to shake it.

***Cloak Sweep.*** Barbatos corrodes a nonmagical ferrous metal object he can see within 5 feet of himself. If the object isn't being worn or carried, the touch destroys a 1-foot cube of it. If the object is being worn or carried by a creature, the creature can make a DC 12 Dexterity saving throw to avoid Barbatos's touch.

If the object touched is either metal armor or a metal shield being worn or carried, it takes a permanent and cumulative 1 penalty to the AC it offers. Armor reduced to an AC of 10 or a shield that drops to a +0 bonus is destroyed. If the object touched is a held metal weapon, it rusts as described in Barbatos's Rust Monster Cloak trait.
```
^statblock