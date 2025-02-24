---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/mcv2dc
- monster/cr/17
- monster/size/medium
- monster/type/humanoid/cleric
- monster/type/humanoid/human
aliases: ["Verminaard"]
---
# Verminaard
*Source: Monstrous Compendium Volume 2: Dragonlance Creatures p. 15*  

> [!quote]  
> 
> Ariakas,
> 
> As the Dragon Queen wills me to obey, here is my assessment of your servant, Verminaard of Nidus: Unchanged. The man remains a blustering dastard awash in blessings earned by his blood rather than his brains. He glories in Takhisis's favor and wields her power in manners both frivolous and brutal. In their bunks, his troops whisper of his zealotry and claim that those missing from their ranks have been sacrificed on his secret altar. I don't dismiss this possibility.
> 
> While his work progresses, it is the effort of an instrument as blunt as the mace he wields.
> 
> Verminaard thinks himself invincible, and I pray to her majesty that I'm present when she divests him of that delusion.
> 
> I hope you find these reports illuminating.
> 
> Ember

Dragon Highlord Verminaard leads the Red Dragon Army—the largest and most powerful of the Dragon Queen's forces—with fanatic zeal and ruthless might. Though prophesied to banish evil forces from the lands of Krynn, Verminaard was tempted by Takhisis and her promises of glory. Corrupted by the Dragon Queen, Verminaard rose to become one of her champions, claiming command of the fiercest among the Dragon Armies.

Verminaard's extreme devotion to Takhisis allows him to channel her unholy power on the battlefield, bolstering those under his command while raining cursed fire on his foes. His towering silhouette is often wreathed in the fire of Ember, his red dragon companion and adviser.

> [!note] Draconic Devotion
> 
> Verminaard's stat block references the Draconic Devotion monster trait. Though this trait does not appear in any of the creatures in this compendium, you will find several monsters with the Draconic Devotion trait terrorizing the lands of Krynn in the book Dragonlance: Shadow of the Dragon Queen.
^draconic-devotion

```ad-statblock
title: Verminaard
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/MCV2DC/Verminaard.webp#token)
*Medium humanoid (cleric, human), Lawful Evil*

- **Armor Class** 20 ([+2 plate armor](2-Mechanics/CLI/items/2-armor.md))
- **Hit Points** 143 (`22d8 + 44`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|22 (+6)|13 (+1)|15 (+2)|16 (+3)|18 (+4)|17 (+3)|

- **Proficiency Bonus** +6
- **Saving Throws** Wisdom +10, Charisma +9
- **Skills** Perception +16, Religion +9
- **Senses** darkvision 60 ft., passive Perception 26
- **Damage Immunities** fire
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened)
- **Languages** Abyssal, Common, Draconic
- **Challenge** 17

## Traits

***Draconic Command.*** Whenever a Dragon or a creature with the Draconic Devotion trait within 30 feet of Verminaard makes an attack roll, the creature can roll a `dice:d4|noform|avg` (`d4`) and add the number rolled to the attack roll.

***Legendary Resistance (3/Day).*** If Verminaard fails a saving throw, he can choose to succeed instead.

***Special Equipment.*** Verminaard wears [+2 plate armor](2-Mechanics/CLI/items/2-armor.md) and wields the mace [Nightbringer](2-Mechanics/CLI/items/nightbringer-mcv2dc.md), which grants him darkvision as well as immunity to fire damage and to the [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed) and [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened) conditions (included above).

***Spellcasting.*** Verminaard casts one of the following spells, requiring no material components and using Wisdom as the spellcasting ability (spell save DC 18):

**At will**: [light](2-Mechanics/CLI/spells/light.md), [thaumaturgy](2-Mechanics/CLI/spells/thaumaturgy.md)

**2/day each**: [bane](2-Mechanics/CLI/spells/bane.md), [fear](2-Mechanics/CLI/spells/fear.md), [freedom of movement](2-Mechanics/CLI/spells/freedom-of-movement.md), [greater restoration](2-Mechanics/CLI/spells/greater-restoration.md), [hold monster](2-Mechanics/CLI/spells/hold-monster.md), [revivify](2-Mechanics/CLI/spells/revivify.md)

## Actions

***Multiattack.*** Verminaard makes two Nightbringer attacks and uses Malediction.

***Nightbringer.*** *Melee Weapon Attack:* `dice:1d20+15|noform|text(+15)` to hit, reach 5 ft., one target. *Hit:* `dice:1d6+9|noform|avg|text(12)` (`1d6 + 9`) bludgeoning damage plus `dice:4d4|noform|avg|text(10)` (`4d4`) radiant damage. If the target is a creature, the target must succeed on a DC 20 Constitution saving throw or be [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded) until the start of Verminaard's next turn.

***Malediction.*** Verminaard utters an unholy word, causing profane fire to descend on one creature Verminaard can see within 60 feet of himself. The creature must make a DC 18 Dexterity saving throw, taking `dice:2d10|noform|avg|text(11)` (`2d10`) necrotic damage plus `dice:2d10|noform|avg|text(11)` (`2d10`) radiant damage on a failed save or half as much damage on a successful one.

## Bonus Actions

***Dragon Queen's Favor (5/Day).*** Verminaard or one creature he can see within 60 feet of himself magically regains `dice:2d12+4|noform|avg|text(17)` (`2d12 + 4`) hit points.

## Legendary Actions

***Tactical Movement.*** Verminaard moves up to his speed or commands a mount he is riding to move up to its speed. This movement doesn't provoke opportunity attacks.

***Fervent Strike (Costs 2 Actions).*** Verminaard makes one Nightbringer attack. If this attack hits, it deals an additional `dice:2d6|noform|avg|text(7)` (`2d6`) bludgeoning damage.

***Cast a Spell (Costs 3 Actions).*** Verminaard uses Spellcasting.
```
^statblock