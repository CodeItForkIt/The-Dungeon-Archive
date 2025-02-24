---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/15
- monster/environment/any
- monster/environment/planar
- monster/size/large
- monster/type/dragon
aliases: ["Star Drake"]
---
# Star Drake
*Source: Tome of Beasts 1 (2023 Edition) p. 146*  

*Twinkling motes of light move around the mottled, metallic scales of this dragon's body. Light reflections twinkle like starlight across its metallic scales.*

## Returned Travelers

A drake's curiosity sometimes drives it to seek experiences beyond its plane, and it finds companions with which it travels the multiverse. Such drakes return clearly changed in appearance, demeanor, and ability. Regardless of which type of drake embarked on the journey, the creature always returns as a star drake.

## Mortal Protectors

Star drakes consider themselves protectors of the Material Plane. They view those from other planes as meddlers in the affairs of humanoid races, regarding fiends and celestials as equally threatening. Star drakes might negotiate with, drive off, or destroy such meddlers.

## Unlikely Allies

Inexplicably, planewatchers can recognize when a drake that is exploring the planes is in the process of becoming a star drake, and they typically leave these drakes to their exploring. After a drake's metamorphosis, planewatchers often aid the drake, seeing it as a sort of kindred spirit.

## Statblock

```ad-statblock
title: Star Drake
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Star%20Drake.webp#token)
*Large dragon, Neutral*

- **Armor Class** 19 (natural armor)
- **Hit Points** 189 (`18d10 + 90`)
- **Speed** 40 ft., fly 100 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|20 (+5)|17 (+3)|21 (+5)|16 (+3)|24 (+7)|20 (+5)|

- **Proficiency Bonus** +5
- **Saving Throws** Dexterity +8, Constitution +10, Wisdom +12, Charisma +10
- **Skills** Arcana +8, History +8, Insight +12, Perception +12, Religion +8
- **Senses** truesight 120 ft., passive Perception 22
- **Damage Immunities** cold; fire; bludgeoning, piercing, slashing from nonmagical attacks
- **Condition Immunities** [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded), [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed)
- **Languages** Abyssal, Celestial, Common, Draconic, Infernal, Primordial
- **Challenge** 15

## Traits

***Magic Resistance.*** The drake has advantage on saving throws against spells and other magical effects.

***Nimbus of Swirling Stars.*** At the start of each of the drake's turns, each creature within 10 feet of it and that can see it must succeed on a DC 18 Constitution saving throw or be [incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated) until the end of its next turn.

***Planar Weapons.*** The drake's weapon attacks are magical. When it hits with any weapon, the weapon deals an extra `dice:4d8|noform|avg` (`4d8`) force damage (included in the attack).

## Actions

***Multiattack.*** The drake makes one Bite attack and two Claw attacks, or it makes four Searing Star attacks. If two Searing Star attacks hit one creature, that creature must succeed on a DC 18 Constitution saving throw or be [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded) until the end of its next turn.

***Bite.*** *Melee Weapon Attack:* `dice:1d20+10|noform|text(+10)` to hit, reach 10 ft., one target. *Hit:* `dice:2d10+5|noform|avg|text(16)` (`2d10 + 5`) piercing damage plus `dice:4d8|noform|avg|text(18)` (`4d8`) force damage.

***Claw.*** *Melee Weapon Attack:* `dice:1d20+10|noform|text(+10)` to hit, reach 5 ft., one target. *Hit:* `dice:2d6+5|noform|avg|text(12)` (`2d6 + 5`) slashing damage plus `dice:4d8|noform|avg|text(18)` (`4d8`) force damage.

***Searing Star.*** *Ranged Spell Attack:* `dice:1d20+12|noform|text(+12)` to hit, range 120 ft., one target. *Hit:* `dice:2d6+7|noform|avg|text(14)` (`2d6 + 7`) radiant damage plus `dice:2d8|noform|avg|text(9)` (`2d8`) force damage.

***Planar Traveler.*** The star drake can transport itself to a different plane of existence. This works like the [plane shift](2-Mechanics/CLI/spells/plane-shift.md) spell, except the drake can affect only itself and can't use this action to banish an unwilling creature to another plane.

***Plane-Altered Breath (Recharge 5-6).*** The drake exhales raw magic in a 60-foot cone. Each creature in that area must make a DC 18 Dexterity saving throw, taking `dice:10d10|noform|avg|text(55)` (`10d10`) force damage on a failed save, or half as much damage on a successful one.
```
^statblock

## Environment

any, planar