---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/ghloe
- monster/cr/14
- monster/size/large
- monster/type/undead
aliases: ["Lich Troll"]
---
# Lich Troll
*Source: Grim Hollow: Lairs of Etharis p. 121*  

> [!quote]  
> 
> Running away from a troll is smart. Running away from a troll that casts spells is wishful thinking.

## Salvage

Someone who has proficiency with jeweler's tools or woodcarver's tools can fashion the skull of a lich troll into a ring of regeneration. Doing so takes materials worth 5,000 gp, 10 days of work, and a successful DC 15 Intelligence or Wisdom check. Somebody must also cast greater restoration on the ring each day during the process. If the ring's wearer dies while wearing the ring, the soul of the lich has a 25 percent chance to take over the corpse and use it as a new body. But if the ring is created entirely in the area of a hallow spell with the everlasting rest effect, the tie to the lich's soul is broken

## Lore

- **DC 15 Intelligence ([History](2-Mechanics/CLI/rules/skills.md#History)).** The lich troll is remnants of early attempts of powerful spellcasters to transfer their souls into trolls.  
- **DC 20 Intelligence ([Arcana](2-Mechanics/CLI/rules/skills.md#Arcana)).** The lich troll is immune to poison and resistant to necrotic damage. It regenerates and can be killed only by acid, fire, or radiant damage  

## Statblock

```ad-statblock
title: Lich Troll
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/GHLoE/Lich%20Troll.webp#token)
*Large undead, Chaotic Evil*

- **Armor Class** 16 (natural armor)
- **Hit Points** 133 (`14d10 + 56`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|18 (+4)|14 (+2)|18 (+4)|15 (+2)|13 (+1)|12 (+1)|

- **Proficiency Bonus** +5
- **Saving Throws** Constitution +9, Intelligence +7, Wisdom +6
- **Skills** ⏤
- **Senses** truesight 60 ft., passive Perception 16
- **Damage Resistances** cold, necrotic
- **Damage Immunities** fire, poison
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** the languages it knew in life and Giant
- **Challenge** 14

## Traits

***Legendary Resistance (2/Day).*** If the lich troll fails a saving throw, it can choose to succeed instead.

***Regeneration.*** The lich troll regains 15 hit points at the start of its turn. If the lich troll takes acid or radiant damage, this trait doesn't function until the start of the lich troll's next turn. The lich troll dies only if it starts its turn with 0 hit points and doesn't regenerate.

***Spellcasting.*** The lich troll is an 11th-level spellcaster. Its spellcasting ability is Intelligence (spell save DC 15, `dice:1d20+7|noform|text(+7)` to hit with spell attacks). The lich troll has the following wizard spells prepared:

**Cantrips (at will)**: [chill touch](2-Mechanics/CLI/spells/chill-touch.md), [mage hand](2-Mechanics/CLI/spells/mage-hand.md), [prestidigitation](2-Mechanics/CLI/spells/prestidigitation.md), [ray of frost](2-Mechanics/CLI/spells/ray-of-frost.md)

**1st level (4 slots)**: [detect magic](2-Mechanics/CLI/spells/detect-magic.md), [magic missile](2-Mechanics/CLI/spells/magic-missile.md), [shield](2-Mechanics/CLI/spells/shield.md), [thunderwave](2-Mechanics/CLI/spells/thunderwave.md)

**2nd level (3 slots)**: [detect thoughts](2-Mechanics/CLI/spells/detect-thoughts.md), [invisibility](2-Mechanics/CLI/spells/invisibility.md), [mirror image](2-Mechanics/CLI/spells/mirror-image.md), [misty step](2-Mechanics/CLI/spells/misty-step.md)

**3rd level (3 slots)**: [animate dead](2-Mechanics/CLI/spells/animate-dead.md), [counterspell](2-Mechanics/CLI/spells/counterspell.md), [dispel magic](2-Mechanics/CLI/spells/dispel-magic.md), [haste](2-Mechanics/CLI/spells/haste.md)

**4th level (3 slots)**: [blight](2-Mechanics/CLI/spells/blight.md), [dimension door](2-Mechanics/CLI/spells/dimension-door.md)

**5th level (2 slots)**: [cloudkill](2-Mechanics/CLI/spells/cloudkill.md), [scrying](2-Mechanics/CLI/spells/scrying.md)

**6th level (1 slots)**: [create undead](2-Mechanics/CLI/spells/create-undead.md)

## Actions

***Multiattack.*** The lich troll makes two claw attacks. Alternately, the lich troll can cast [chill touch](2-Mechanics/CLI/spells/chill-touch.md) or ray of frost twice.

***Claw.*** *Melee Weapon Attack:* `dice:1d20+9|noform|text(+9)` to hit, reach 5 ft., one target. *Hit:* `dice:2d6+4|noform|avg|text(11)` (`2d6 + 4`) slashing damage plus `dice:2d6|noform|avg|text(7)` (`2d6`) cold damage.

## Legendary Actions

***Cantrip.*** The lich troll casts a cantrip.

***Claw.*** The lich troll makes a claw attack.
```
^statblock