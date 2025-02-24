---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/hat-tg
- monster/cr/5
- monster/size/medium
- monster/type/humanoid/bard
aliases: ["Edgin Darvis"]
---
# Edgin Darvis
*Source: Honor Among Thieves: Thieves' Gallery*  

Edgin Darvis has a talent for improvisation and strategy. He's a musician and tale-teller who relies on charisma first—rather than magic or muscle—to escape trouble. Once a member of the Harpers, a spy organization dedicated to protecting Faerûn's common folk, Edgin has forsworn his oath and turned to thievery to support his family. Edgin's strong moral compass compels him to steal only from people he believes deserve to lose both coin and face.

Edgin's confidence and rakish demeanor make him a natural leader. With carefully chosen words, he inspires the members of his thieves' crew to greatness. But when his past mistakes come calling, Edgin must face the music. He now seeks to make amends to those he's wronged and to confront those who have wronged him.

```ad-statblock
title: Edgin Darvis
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/HAT-TG/Edgin%20Darvis.webp#token)
*Medium humanoid (bard), Chaotic Good*

- **Armor Class** 14 ([leather armor](2-Mechanics/CLI/items/leather-armor.md))
- **Hit Points** 110 (`17d8 + 34`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|14 (+2)|16 (+3)|14 (+2)|14 (+2)|16 (+3)|18 (+4)|

- **Proficiency Bonus** +3
- **Saving Throws** Dexterity +6, Charisma +7
- **Skills** Deception +7, Performance +10, Persuasion +10, Sleight of Hand +6
- **Senses** passive Perception 13
- **Languages** Common
- **Challenge** 5

***Spellcasting.*** Edgin casts one of the following spells, using Charisma as the spellcasting ability (spell save DC 15):

**At will**: [friends](2-Mechanics/CLI/spells/friends.md), [message](2-Mechanics/CLI/spells/message.md)

**1/day**: [suggestion](2-Mechanics/CLI/spells/suggestion.md)

**3/day each**: [charm person](2-Mechanics/CLI/spells/charm-person.md), [disguise self](2-Mechanics/CLI/spells/disguise-self.md)

## Actions

***Multiattack.*** Edgin makes two Reinforced Lute or Shortsword attacks.

***Reinforced Lute.*** *Melee Weapon Attack:* `dice:1d20+5|noform|text(+5)` to hit, reach 5 ft., one target. *Hit:* `dice:1d8+2|noform|avg|text(6)` (`1d8 + 2`) bludgeoning damage plus `dice:2d10|noform|avg|text(11)` (`2d10`) thunder damage.

***Shortsword.*** *Melee Weapon Attack:* `dice:1d20+6|noform|text(+6)` to hit, reach 5 ft., one target. *Hit:* `dice:1d6+3|noform|avg|text(6)` (`1d6 + 3`) piercing damage plus `dice:2d10|noform|avg|text(11)` (`2d10`) thunder damage.

***Disorienting Words.*** Edgin magically taunts up to three creatures he can see within 60 feet of himself. Each creature must succeed on a DC 15 Wisdom saving throw or take `dice:3d6|noform|avg|text(10)` (`3d6`) psychic damage and have disadvantage on the next attack roll it makes before the start of Edgin's next turn.

## Reactions

***Inspiring Words (3/Day).*** When a creature Edgin can see within 60 feet of himself fails an ability check, an attack roll, or a saving throw, Edgin grants the creature magical encouragement. The creature can roll a `dice:d8|noform|avg` (`d8`) and add the number rolled to the total, potentially turning the failure into a success.
```
^statblock