---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/ghloe
- monster/cr/19
- monster/size/medium
- monster/type/undead
aliases: ["Elf Vampire (Ancient)"]
---
# Elf Vampire (Ancient)
*Source: Grim Hollow: Lairs of Etharis p. 106*  

> [!quote]  
> 
> She was ancient, tall and gaunt, imperious and fierce. Her skin was translucent and slightly luminous with the crimson fluid beneath lending it a bizarre, vibrating flush. Her anger and sorrow reached from her, sharing the sense of a time before my people cut and burned the forest. I wept.

## Elf Vampire Customization

As shown in the following stats, young and older elf vampires gain Turn Resistance and immunity to being charmed or rendered unconscious. Although some wood elves are an exception, most elf vampires do not take on animal form and, therefore, lack the Beast Form action. Young and older elf vampires also gain the Fey Majesty action, but until the vampire is ancient, as is the one in the stat block, they can affect only humanoids and beasts with this power.

## Salvage

An elf vampire's flesh turns to glittering powder when the vampire dies. This powder can still be used to make the ointment rendered vampire flesh can make. However, this dust can also be used as a material component for any enchantment spell or spell that deals necrotic damage. If a spellcaster uses the dust in this way, the spell save DC for the spell increases by 2. If the spell requires an attack roll, the caster scores a critical hit on a roll of 19 or 20, and any damage die for necrotic damage that rolls a 1 is treated as a 2. One vampire produces enough dust for two uses, plus one use per age category of the vampire beyond spawn.

## Lore

- **DC 15 Intelligence ([History](2-Mechanics/CLI/rules/skills.md#History)).** Elf vampires don't sleep, so they are aware all the time. And they can't be charmed or knocked unconscious.  
- **DC 15 Intelligence ([Religion](2-Mechanics/CLI/rules/skills.md#Religion)).** Fey ancestry combines with vampirism to render elf vampires resistant to effects that turn undead.  
- **DC 20 Intelligence ([Arcana](2-Mechanics/CLI/rules/skills.md#Arcana)).** Elf vampires can manipulate the minds of beasts and people. Legend says that ancient elf vampires can sway the minds of other creatures.  

## Statblock

```ad-statblock
title: Elf Vampire (Ancient)
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/GHLoE/Elf%20Vampire%20%28Ancient%29.webp#token)
*Medium undead, Any Evil alignment*

- **Armor Class** 18 (natural armor)
- **Hit Points** 209 (`22d8 + 110`)
- **Speed** 40 ft., climb 40 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|20 (+5)|20 (+5)|20 (+5)|15 (+2)|16 (+3)|16 (+3)|

- **Proficiency Bonus** +6
- **Saving Throws** Dexterity +11, Wisdom +9, Charisma +9
- **Skills** Arcana +8, Athletics +11, History +8, Perception +9, Stealth +11
- **Senses** blindsight 30 ft., darkvision 120 ft., passive Perception 19
- **Damage Resistances** necrotic; poison; bludgeoning, piercing, slashing from nonmagical attacks
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [unconscious](2-Mechanics/CLI/rules/conditions.md#Unconscious)
- **Languages** the languages known in life
- **Challenge** 19

## Traits

***Legendary Resistance (3/Day).*** If the vampire fails a saving throw, it can choose to succeed instead.

***Regeneration.*** The vampire regains 25 hit points at the start of its turn if it has at least 1 hit point. If the vampire takes radiant damage, it regains 10 hit points from the next use of this trait instead.

***Spider Climb.*** The vampire can climb difficult surfaces, including upside down on ceilings, without needing to make an ability check.

***Turn Resistance.*** The vampire has advantage on saving throws against any effect that turns undead.

***Vampire Weaknesses.*** The vampire has the following flaws:

***Forbiddance.*** The vampire can't enter a residence without an invitation from one of the occupants.

***Stake to the Heart.*** The vampire dies if a piercing weapon made of wood is driven into its heart while it is [incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated) in its resting place.

## Actions

***Multiattack.*** The vampire makes three attacks, only one of which can be a bite.

***Claws.*** *Melee Weapon Attack:* `dice:1d20+11|noform|text(+11)` to hit, reach 5 ft., one target. *Hit:* `dice:2d8+6|noform|avg|text(15)` (`2d8 + 6`) slashing damage. If the target is a creature, the vampire can grapple the target (escape DC 19).

***Bite.*** *Melee Weapon Attack:* `dice:1d20+11|noform|text(+11)` to hit, reach 5 ft., one creature. *Hit:* `dice:2d8+6|noform|avg|text(15)` (`2d8 + 6`) piercing damage and `dice:5d6|noform|avg|text(17)` (`5d6`) necrotic damage. The target's hit point maximum is reduced by an amount equal to the necrotic damage taken, and the vampire regains hit points equal to that amount. This reduction lasts until the target finishes a long rest. The target dies if this effect reduces its hit point maximum to 0. A humanoid slain in this way and then buried rises the following night as a vampire spawn under this vampire's control.

***Fey Majesty.*** The vampire targets one creature it can see within 30 feet of it. If the target can see or hear the vampire, the target must succeed on a DC 17 Charisma saving throw or be [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed). The [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed) target regards the vampire as a friend to be heeded and protected. Although not under the vampire's control, it takes the vampire's requests in the most favorable way and is a willing target for the vampire's bite.

While the target is [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), the vampire can communicate with the target telepathically within 300 feet. The vampire can use a bonus action to force the target to repeat the saving throw. If the save fails, the vampire can render the creature full of despair (disadvantage on ability checks and attack rolls) or confused (as the [confusion](2-Mechanics/CLI/spells/confusion.md) spell) for 1 minute. The creature can repeat the saving throw at the end of each of its turns, ending the despair or confusion on itself on a success.

Each time the vampire or the vampire's allies do anything harmful to the target, it can repeat the saving throw, ending the effect on a success. Otherwise, the effect lasts 24 hours or until the vampire dies, is on a different plane of existence than the target, or takes a bonus action to end the effect.

***Mist Form.*** The vampire polymorphs into a Medium cloud of mist, or back into its true form. Anything it wears or carries transforms with it. While in mist form, the vampire can't take any actions, speak, or manipulate objects. It is weightless, has a flying speed of 30 feet, can hover, and can enter a hostile creature's space and stop there. In addition, if air can pass through a space, the mist can do so without squeezing, but it can't pass through water. It has advantage on Strength, Dexterity, and Constitution saving throws. A vampire in mist form is immune to nonmagical damage, except damage from sunlight, and has resistance to damage other than radiant. The vampire reverts to its true form if it dies.

## Reactions

***Misty Escape.*** When it drops to 0 hit points outside its resting place, the vampire transforms into its Mist Form instead of falling [unconscious](2-Mechanics/CLI/rules/conditions.md#Unconscious). If the vampire can't transform, it dies.

While it has 0 hit points in mist form, the vampire dies if it takes damage three times or radiant damage once. It can't willingly revert to its vampire form, and it must reach its resting place within 2 hours or die. Once in its resting place, it reverts to its vampire form. It is then [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed) until it regains at least 1 hit point. After spending 1 hour in its resting place with 0 hit points, it regains 1 hit point.

## Legendary Actions

***Move and Claw.*** The vampire moves up to its speed and attacks once with its claws.

***Bite (2 Actions).*** The vampire makes one bite attack.

***Purify Blood (2 Actions).*** Even if the vampire can't take actions, one condition ends on it.
```
^statblock