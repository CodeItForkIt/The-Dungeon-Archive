---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/9
- monster/environment/planar
- monster/size/large
- monster/type/fiend
aliases: ["Arx"]
---
# Arx
*Source: Tome of Beasts 1 (2023 Edition) p. 26*  

*This spike-covered insectoid stands at the ready with a wicked spear grasped by two limbs. It decompresses its wings impossibly to fashion a pair of walls behind it, held together and connected to the insectoid by a stretchy pink goo.*

Arxes are fiendish creatures who serve other fiends as mobile field defenses. They can detach their elytra, the hardened shells that cover their wings, to provide cover for commanders who wish to direct their armies from forward lines. They use their telepathy and excellent vision to feed accurate overviews of the battlefield to these leaders, who use this intel to direct troops and make attacks from behind the arx's wall.

## Hirable Mercenaries

When they aren't fighting for legions of devils or demons, arxes willingly accept payment for their services. They are steadfast combatants who reliably follow orders, but they show no concern about individual allies over greater tactical advantages.

## Statblock

```ad-statblock
title: Arx
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Arx.webp#token)
*Large fiend, Lawful Evil*

- **Armor Class** 17 (natural armor)
- **Hit Points** 171 (`18d10 + 72`)
- **Speed** 30 ft., fly 20 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|20 (+5)| 8 (-1)|19 (+4)|11 (+0)|15 (+2)| 8 (-1)|

- **Proficiency Bonus** +4
- **Saving Throws** Strength +9
- **Skills** Athletics +9, Perception +6
- **Senses** darkvision 90 ft., passive Perception 16
- **Damage Resistances** cold, fire, lightning, poison
- **Languages** Abyssal, Infernal, telepathy 60 ft.
- **Challenge** 9

## Traits

***Immutable Form.*** The arx is immune to any spell or effect that would alter its form.

***Magic Resistance.*** The arx has advantage on saving throws against spells and other magical effects.

***Spiky Hide.*** A creature that touches the arx or hits it with a melee attack while within 5 feet of it takes `dice:1d8|noform|avg|text(4)` (`1d8`) piercing damage. This trait also applies to the arx's walls.

## Actions

***Multiattack.*** The arx makes two Claw attacks and one Spear attack.

***Claw.*** *Melee Weapon Attack:* `dice:1d20+9|noform|text(+9)` to hit, reach 5 ft., one target. *Hit:* `dice:3d8+5|noform|avg|text(18)` (`3d8 + 5`) slashing damage.

***Spear.*** *Melee or Ranged Weapon Attack:* `dice:1d20+9|noform|text(+9)` to hit, reach 5 ft. or range 20/60 ft., one target. *Hit:* `dice:2d6+5|noform|avg|text(12)` (`2d6 + 5`) piercing damage, or `dice:2d8+5|noform|avg|text(14)` (`2d8 + 5`) piercing damage if used with two hands to make a melee attack.

***Wall Smash.*** If the arx has its wall set up (see Emplace Wall), it can briefly close the panels of the wall in on each other. Each creature other than the arx between the panels in a 10-foot cone from the corner where the panels meet must make a DC 16 Dexterity saving throw, taking `dice:8d6|noform|avg|text(28)` (`8d6`) bludgeoning damage on a failed save, or half as much damage on a successful one.

## Bonus Actions

***Emplace Wall (Recharge 3-6).*** The arx extends its hardened elytra and casts them into the ground, creating a wall. The wall is 3 inches thick and is composed of two 10-foot-by-10-foot panels. The panels must connect perpendicular to each other, forming a corner behind the arx. If the wall falls in a creature's space when the arx places it, the creature must make a DC 16 Dexterity saving throw. On a failure, the creature takes `dice:3d6|noform|avg|text(10)` (`3d6`) bludgeoning damage, and the arx determines to which side of the wall the creature is pushed. On a success, the creature takes half the damage and decides to which side of the wall it is pushed.

Each 10-foot panel has AC 17 and 50 hp. If a panel is destroyed, the arx can place only one panel of wall with this bonus action. If both panels are destroyed, the arx can't use this bonus action again until it finishes a long rest or until its elytra are restored with a [regenerate](2-Mechanics/CLI/spells/regenerate.md) spell or similar magic.

While the arx has at least one wall emplaced, it must remain within 15 feet of at least one of its walls. The arx can retract the walls into its body, ending this effect, as a bonus action.
```
^statblock

## Environment

planar