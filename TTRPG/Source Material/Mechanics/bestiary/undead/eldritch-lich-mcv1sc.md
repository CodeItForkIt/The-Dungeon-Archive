---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/mcv1sc
- monster/cr/15
- monster/size/medium
- monster/type/undead
aliases: ["Eldritch Lich"]
---
# Eldritch Lich
*Source: Monstrous Compendium Volume 1: Spelljammer Creatures p. 6*  

From beyond the stars, a Great Old One whispers promises of reality-defying knowledge and world-bending power. When a wizard or a warlock hears that whisper and listens too intently, they might set foot on the twisting path toward becoming an eldritch lich.

Like other liches, eldritch liches are spellcasters who have cheated death, but an eldritch lich does so by allowing a Great Old One to implant a Far Realm parasite in the lich. That parasite bestows undeath upon the spellcaster and causes strange tentacles to sprout from the body. The parasite's mouth is visible on the lich's torso, and the parasite guards the lich against destruction, reviving the lich a few days after death. Canny foes can sabotage an eldritch lich's revival by slaying the lich in a magic circle, thereby forcing the lich to return in a distorted form, robbed of most of its power.

An eldritch lich constantly hears bizarre whispers from the Far Realm, to which the lich nods and mutters. Occasionally, the lich uses its telepathy to share those whispers with the minds around it.

## Form of the Great Old One

Multiple entities bear the title Great Old One. You may roll on the Great Old Ones table to determine which entity gave an eldritch lich its parasite.

### Great Old Ones

`dice: [](eldritch-lich-mcv1sc.md#^form)`

| dice: d6 | Form |
|----------|------|
| 1 | Cthulhu |
| 2 | Tharizdun, the Chained God |
| 3 | Dendar, the Night Serpent |
| 4 | Ghaunadaur |
| 5 | Zargon, the Returner |
| 6 | That Which Lurks |
^form

## Statblock

```ad-statblock
title: Eldritch Lich
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/MCV1SC/Eldritch%20Lich.webp#token)
*Medium undead, typically  Neutral Evil*

- **Armor Class** 17 (natural armor)
- **Hit Points** 165 (`22d8 + 66`)
- **Speed** 30 ft., fly 30 ft. (hover)

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|11 (+0)|18 (+4)|16 (+3)|19 (+4)|14 (+2)|12 (+1)|

- **Proficiency Bonus** +5
- **Saving Throws** Intelligence +9, Wisdom +7
- **Skills** Arcana +14, Perception +7
- **Senses** truesight 120ft., passive Perception 17
- **Damage Resistances** necrotic, poison
- **Condition Immunities** [charmed](Mechanics/Rules/conditions.md#Charmed), [exhaustion](Mechanics/Rules/conditions.md#Exhaustion), [frightened](Mechanics/Rules/conditions.md#Frightened), [paralyzed](Mechanics/Rules/conditions.md#Paralyzed), [poisoned](Mechanics/Rules/conditions.md#Poisoned)
- **Languages** Common, Deep Speech, telepathy 120 ft.
- **Challenge** 15

## Traits

***Far Realm Parasite.*** Inside the lich's torso dwells a wormlike parasite that contains the lich's soul. When the lich dies, it implodes into the parasite, which then vanishes into the Far Realm. In `2d4` days, the parasite causes the lich to reappear within `1d4` miles of where it died. If the lich died inside a magic circle cast to contain Undead, the lich instead reappears as an [otyugh](Mechanics/bestiary/aberration/otyugh.md) with all the lich's memories.

***Legendary Resistance (4/Day).*** If the lich fails a saving throw, it can choose to succeed instead.

***Unusual Nature.*** The lich doesn't need air, food, drink, or sleep.

***Spellcasting.*** The lich casts one of the following spells, using Intelligence as the spellcasting ability (spell save DC 17):

**At will**: [detect magic](Mechanics/spells/detect-magic.md), [mage hand](Mechanics/spells/mage-hand.md), [prestidigitation](Mechanics/spells/prestidigitation.md)

**1/day each**: [arcane eye](Mechanics/spells/arcane-eye.md), [dimension door](Mechanics/spells/dimension-door.md), [plane shift](Mechanics/spells/plane-shift.md) (self only)

**2/day each**: [dispel magic](Mechanics/spells/dispel-magic.md), [hunger of Hadar](Mechanics/spells/hunger-of-hadar.md), [lightning bolt](Mechanics/spells/lightning-bolt.md)

## Actions

***Multiattack.*** The lich makes one Parasitic Tentacle attack or uses Spellcasting. The lich also uses Psychic Whisper twice.

***Parasitic Tentacle.*** *Melee Weapon Attack:* `+9` to hit, reach 10 ft., one creature. *Hit:* 25 (`6d6 + 4`) piercing damage plus 25 (`6d6 + 4`) necrotic damage. The target must succeed on a DC 17 Constitution saving throw or be [poisoned](Mechanics/Rules/conditions.md#Poisoned). The [poisoned](Mechanics/Rules/conditions.md#Poisoned) target can repeat the save at the end of each of its turns, ending the effect on itself on a success. The third time the target fails the save, the target dies and dissolves into a [gibbering mouther](Mechanics/bestiary/aberration/gibbering-mouther.md) that obeys the lich and uses the target's initiative.

***Psychic Whisper.*** The lich targets one creature it can see within 120 feet of itself. The target must succeed on a DC 17 Wisdom saving throw or take 25 (`6d6 + 4`) psychic damage and be [stunned](Mechanics/Rules/conditions.md#Stunned) until the end of the lich's next turn as incomprehensible whispers fill the target's mind.

## Reactions

***Far Realm Step.*** Immediately after taking damage, the lich, along with any equipment it is wearing or carrying, magically teleports up to 60 feet to an unoccupied space it can see.
```
^statblock