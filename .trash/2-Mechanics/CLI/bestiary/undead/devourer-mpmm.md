---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/mpmm
- monster/cr/13
- monster/environment/underdark
- monster/size/large
- monster/type/undead
aliases: ["Devourer"]
---
# Devourer
*Source: Mordenkainen Presents: Monsters of the Multiverse p. 93*  

Of all the abominations unleashed by [Orcus](2-Mechanics/CLI/bestiary/npc/orcus-mpmm.md), devourers are among the most feared. These tall, mummy-like Undead wander the planes, consuming souls and spreading Orcus's creed of replacing all life with everlasting death.

A lesser demon that proves itself to Orcus might be granted the privilege of becoming a devourer. The Prince of Undeath transforms such a demon into an 8-foot-tall, desiccated biped with a hollowed-out ribcage, then fills the new creature with a hunger for souls. Orcus grants each new devourer the essence of a less fortunate demon to power the devourer's first foray into the planes. Most devourers remain in the Abyss or on the Astral or Ethereal Plane, pursuing Orcus's schemes and interests in those realms. When Orcus sends devourers to the Material Plane, he often sets them on a mission to create, control, and lead a plague of Undead. [Skeletons](2-Mechanics/CLI/bestiary/undead/skeleton.md), [zombies](2-Mechanics/CLI/bestiary/undead/zombie.md), [ghouls](2-Mechanics/CLI/bestiary/undead/ghoul.md), [ghasts](2-Mechanics/CLI/bestiary/undead/ghast.md), and [shadows](2-Mechanics/CLI/bestiary/undead/shadow.md) are particularly attracted to the presence of a devourer.

Devourers hunt Humanoids with the intent of consuming them body and soul. After a devourer brings a target to the brink of death, it pulls the victim's body in and traps the creature within its own ribcage. As the victim tries to stave off death (usually without success), the devourer tortures its soul with telepathic noise. When the victim expires, it undergoes a horrible transformation, springing forth from the devourer's body to begin its new existence as an Undead servitor of the monster that spawned it.

```ad-statblock
title: Devourer
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/MPMM/Devourer.webp#token)
*Large undead, Typically  Chaotic Evil*

- **Armor Class** 16 (natural armor)
- **Hit Points** 189 (`18d10 + 90`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|20 (+5)|12 (+1)|20 (+5)|13 (+1)|10 (+0)|16 (+3)|

- **Proficiency Bonus** +5
- **Saving Throws** ⏤
- **Skills** ⏤
- **Senses** darkvision 120 ft., passive Perception 10
- **Damage Resistances** cold, fire, lightning
- **Damage Immunities** poison
- **Condition Immunities** [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** Abyssal, telepathy 120 ft.
- **Challenge** 13

## Traits

***Unusual Nature.*** A devourer doesn't require air, drink, or sleep.

## Actions

***Multiattack.*** The devourer makes two Claw attacks and can use either Imprison Soul or Soul Rend, if available.

***Claw.*** *Melee Weapon Attack:* `dice:1d20+10|noform|text(+10)` to hit, reach 5 ft., one target. *Hit:* `dice:2d6+5|noform|avg|text(12)` (`2d6 + 5`) slashing damage plus `dice:6d6|noform|avg|text(21)` (`6d6`) necrotic damage.

***Imprison Soul.*** The devourer chooses a living Humanoid with 0 hit points that it can see within 30 feet of it. That creature is teleported inside the devourer's ribcage and imprisoned there. While imprisoned in this way, the creature is [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) and has disadvantage on death saving throws. If the creature dies while imprisoned, the devourer regains 25 hit points and immediately recharges Soul Rend. Additionally, at the start of its next turn, the devourer regurgitates the slain creature as a bonus action, and the creature becomes an undead. If the victim had 2 or fewer Hit Dice, it becomes a [zombie](2-Mechanics/CLI/bestiary/undead/zombie.md). If it had 3 to 5 Hit Dice, it becomes a [ghoul](2-Mechanics/CLI/bestiary/undead/ghoul.md). Otherwise, it becomes a [wight](2-Mechanics/CLI/bestiary/undead/wight.md). A devourer can imprison only one creature at a time.

***Soul Rend (Recharge 6).*** The devourer creates a vortex of life-draining energy in a 20-foot radius centered on itself. Each creature in that area must make a DC 18 Constitution saving throw, taking `dice:8d10|noform|avg|text(44)` (`8d10`) necrotic damage on a failed save, or half as much damage on a successful one.
```
^statblock

## Environment

underdark