---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/mcv3mc
- monster/cr/19
- monster/size/gargantuan
- monster/type/dragon
aliases: ["Ender Dragon"]
---
# Ender Dragon
*Source: Monstrous Compendium Volume 3: Minecraft Creatures p. 5, Lightning Keep*  

The mighty Ender Dragon is one of a kind—a vast, flying creature with void-black scales and purple eyes. It soars above the central island of the End. No one can say whether it is a guardian or a prisoner of the End, but either way, the Ender Dragon challenges anyone who enters its domain.

The Ender Dragon buffets enemies with great wings, engulfs foes with its gaseous breath weapon, and delivers crushing bites with its powerful jaws. Its hide is strong enough to deflect all but the deadliest weapons.

> [!note] End Crystals
> 
> The Ender Dragon has a special relationship with the ten 40-foot-tall obsidian towers scattered around the central island of the End. At the top of each tower is an End crystal that sends a beam of healing energy to the Ender Dragon when it flies nearby. If slain, the Ender Dragon can be brought back to life by placing four End crystals on the portal that leads back to the Overworld.
> 
> **Crystal Healing.** When the Ender Dragon ends its turn within 60 feet of an End crystal, the crystal emits a healing beam that causes the dragon to regain 20 hit points. The dragon can benefit from such healing only once per turn.
> 
> **Crystal Statistics.** An End crystal is a Large object that has Armor Class 11; 30 hit points; vulnerability to bludgeoning and thunder damage; resistance to piercing and slashing damage; and immunity to poison and psychic damage. When a crystal is destroyed, it explodes in a 20-foot-radius sphere of destructive energy. Any creature in that area must make a DC 15 Dexterity saving throw, taking `dice:6d6|noform|avg|text(21)` (`6d6`) force damage on a failed save, or half as much damage on a successful one.
^end-crystals

```ad-statblock
title: Ender Dragon
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/MCV3MC/Ender%20Dragon.webp#token)
*Gargantuan dragon, Chaotic Evil*

- **Armor Class** 22 (natural armor)
- **Hit Points** 350 (`20d20 + 140`)
- **Speed** 30 ft., fly 120 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|27 (+8)|14 (+2)|25 (+7)|10 (+0)|15 (+2)|19 (+4)|

- **Proficiency Bonus** +6
- **Saving Throws** Constitution +13, Intelligence +6, Wisdom +8
- **Skills** Perception +14, Stealth +8
- **Senses** darkvision 240 ft., passive Perception 24
- **Damage Resistances** fire
- **Damage Immunities** necrotic
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened)
- **Languages** Draconic
- **Challenge** 19

## Traits

***Dragon Egg.*** When the Ender Dragon drops to 0 hit points, it radiates beams of purple light and then disappears, leaving behind an inert, jet-black dragon egg worth 5,000 gp.

***Legendary Resistance (4/Day).*** If the dragon fails a saving throw, it can choose to succeed instead.

## Actions

***Multiattack.*** The dragon makes one Bite attack and uses Beating Wings.

***Bite.*** *Melee Weapon Attack:* `dice:1d20+14|noform|text(+14)` to hit; reach 15 ft., one target. *Hit:* `dice:3d6+8|noform|avg|text(18)` (`3d6 + 8`) piercing damage plus `dice:2d6|noform|avg|text(7)` (`2d6`) necrotic damage.

***Beating Wings.*** The dragon beats its great wings. Each creature within 15 feet of the dragon must succeed on a DC 21 Dexterity saving throw or take `dice:1d4+8|noform|avg|text(10)` (`1d4 + 8`) bludgeoning damage, be pushed 10 feet away from the dragon, and have the [prone](2-Mechanics/CLI/rules/conditions.md#Prone) condition.

***Harmful Breath (Recharge 5-6).*** The dragon exhales putrid gas in a 60-foot cone. Each creature in that area must make a DC 21 Constitution saving throw, taking `dice:15d6|noform|avg|text(52)` (`15d6`) necrotic damage on a failed save, or half as much damage on a successful one. The dragon then chooses a point it can see where the cone makes contact with the ground. That point becomes the center of a 10-foot-high, 10-foot-radius cylinder of lingering gas that disappears at the start of the dragon's next turn. Any creature that starts its turn in the cylinder takes `dice:3d6|noform|avg|text(10)` (`3d6`) necrotic damage.
```
^statblock