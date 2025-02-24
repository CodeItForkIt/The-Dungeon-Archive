---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/psi
- monster/cr/4
- monster/size/medium
- monster/type/undead
aliases: ["Geist: Horrifying Visage"]
---
# Geist: Horrifying Visage
*Source: Plane Shift: Innistrad p. 19*  

```ad-statblock
title: Geist: Horrifying Visage
*Medium undead, Any alignment*

- **Armor Class** 11
- **Hit Points** 45 (`10d8`)
- **Speed** 0 ft., fly 40 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
| 7 (-2)|13 (+1)|10 (+0)|10 (+0)|12 (+1)|17 (+3)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** ⏤
- **Senses** darkvision 60 ft., passive Perception 11
- **Damage Resistances** acid, fire, lightning, thunder, bludgeoning
- **Damage Immunities** cold, necrotic, poison
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled)
- **Languages** any languages it knew in life
- **Challenge** 4

## Traits

***Ethereal Sight.*** The geist can see 60 feet into the Ethereal Plane when it is on the Material Plane, and vice versa.

***Incorporeal Movement.*** The geist can move through other creatures and objects as if they were difficult terrain. It takes `dice:1d10|noform|avg|text(5)` (`1d10`) force damage if it ends its turn inside an object.

## Actions

***Withering Touch.*** *Melee Weapon Attack:* `dice:1d20+5|noform|text(+5)` to hit, reach 5 ft., one target *Hit:* `dice:4d6+3|noform|avg|text(17)` (`4d6 + 3`) necrotic damage.

***Etherealness.*** The geist enters the Ethereal Plane from the Material Plane, or vice versa. It is visible on the Material Plane while it is in the Border Ethereal, and vice versa, yet it can't affect or be affected by anything on the other plane.

***Possession (Recharge 6).*** One creature that the geist can see within 5 feet of it must succeed on a DC 13 Charisma saving throw or be possessed by the geist; the geist then disappears, and the target is [incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated) and loses control of its body. The geist now controls the body but doesn't deprive the target of awareness. The geist can't be targeted by any attack, spell, or other effect, except ones that turn undead, and it retains its alignment, Intelligence, Wisdom, Charisma, and immunity to being [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed) and [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened). It otherwise uses the possessed target's statistics, but doesn't gain access to the target's knowledge, class features, or proficiencies. The possession lasts until the body drops to 0 hit points, the geist ends it as a bonus action, or the geist is turned or forced out by an effect like the [dispel evil and good](2-Mechanics/CLI/spells/dispel-evil-and-good.md) spell. When the possession ends, the geist reappears in an unoccupied space within 5 feet of the body. The target is immune to this geist's Possession for 24 hours after succeeding on the saving throw or after the possession ends. The geist can instead target the corpse of a creature, effectively using its own life force to animate the corpse as a zombie. The animated corpse uses zombie statistics and returns to death if the geist ends the possession.

***Horrifying Visage.*** Black-aligned geists can make themselves terrible to behold, even when they are possessing the living. Each non-undead creature within 60 feet of the geist that can see it must succeed on a DC 13 Wisdom saving throw or be [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened) for 1 minute. If the save fails by 5 or more, the target also ages `1d4 × 10` years. A [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened) target can repeat the saving throw at the end of each of its turns, ending the [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened) condition on itself on a success. If a target's saving throw is successful or the effect ends for it, the target is immune to this geist's Horrifying Visage for the next 24 hours. The aging effect can be reversed with a [greater restoration](2-Mechanics/CLI/spells/greater-restoration.md) spell, but only within 24 hours of it occurring.
```
^statblock