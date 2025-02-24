---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/psk
- monster/cr/10
- monster/size/medium
- monster/type/celestial
aliases: ["Angel"]
---
# Angel
*Source: Plane Shift: Kaladesh p. 27*  

Angels are mysterious, detached beings seldom glimpsed by mortal eyes. They are the living incarnations of white mana, and embody its inherent tendencies toward order and harmony. Some inventors view angels in the context of the Aether Cycle as an expression of a Great Design. Given divine inspiration and an utterly perfect stage of innovation, an angel is the constructed result—a living invention. Their masks, headdresses, and armor give them an almost mechanical appearance, but they are living beings with brightly colored skin almost entirely concealed beneath their armor and decorative robes. Because of their perfection, angels are believed to be immune to the final stages of the Aether Cycle, which would involve their destruction.

The people of Kaladesh do not worship angels or beseech their intervention in mortal affairs, and such prayers would go unheard anyway. The solitary angels interact with each other only in formal, nuanced rituals whose meanings are obscure. But the sight of an angel is thought to be a good omen, and in particular, it is believed to presage success with invention.

Use the statistics of a [deva](2-Mechanics/CLI/bestiary/celestial/deva.md) for an angel on Kaladesh. Some angels (such as the one shown on the Angel of Invention card (https://gatherer.wizards.com/pages/card/Details.aspx?multiverseid=547813)) wield four swords with their four arms. When such an angel uses the Multiattack action, it makes four attacks rather than two. However, its weapons deal only an extra `dice:1d10|noform|avg` (`1d10`) radiant damage from its Angelic Weapons trait, so that each sword attack deals `dice:1d6+4|noform|avg|text(7)` (`1d6 + 4`) slashing damage plus `dice:1d10|noform|avg|text(5)` (`1d10`) radiant damage on a hit.

```ad-statblock
title: Angel
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/PSK/Angel.webp#token)
*Medium celestial, Lawful Good*

- **Armor Class** 17 (natural armor)
- **Hit Points** 136 (`16d8 + 64`)
- **Speed** 30 ft., fly 90 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|18 (+4)|18 (+4)|18 (+4)|17 (+3)|20 (+5)|20 (+5)|

- **Proficiency Bonus** +4
- **Saving Throws** Wisdom +9, Charisma +9
- **Skills** Insight +9, Perception +9
- **Senses** darkvision 120 ft., passive Perception 19
- **Damage Resistances** radiant; bludgeoning, piercing, slashing from nonmagical attacks
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened)
- **Languages** all, telepathy 120 ft.
- **Challenge** 10

## Traits

***Angelic Weapons.*** The deva's weapon attacks are magical. When the deva hits with any weapon, the weapon deals an extra `dice:1d10|noform|avg` (`1d10`) radiant damage (included in the attack).

***Magic Resistance.*** The angel has advantage on saving throws against spells and other magical effects.

***Innate Spellcasting.*** The angel's spellcasting ability is Charisma (spell save DC 17). The angel can innately cast the following spells, requiring only verbal components:

**At will**: [detect evil and good](2-Mechanics/CLI/spells/detect-evil-and-good.md)

**1/day each**: [commune](2-Mechanics/CLI/spells/commune.md), [raise dead](2-Mechanics/CLI/spells/raise-dead.md)

## Actions

***Multiattack.*** The deva makes four melee attacks.

***Shortsword.*** *Melee Weapon Attack:* `dice:1d20+8|noform|text(+8)` to hit, reach 5 ft., one target. *Hit:* `dice:1d6+4|noform|avg|text(7)` (`1d6 + 4`) slashing damage plus `dice:1d10|noform|avg|text(13)` (`1d10`) radiant damage.

***Healing Touch (3/Day).*** The angel touches another creature. The target magically regains `dice:4d8+2|noform|avg|text(20)` (`4d8 + 2`) hit points and is freed from any curse, disease, poison, blindness, or deafness.

***Change Shape.*** The angel magically polymorphs into a humanoid or beast that has a challenge rating equal to or less than its own, or back into its true form. It reverts to its true form if it dies. Any equipment it is wearing or carrying is absorbed or borne by the new form (the angel's choice).

In a new form, the angel retains its game statistics and ability to speak, but its AC, movement modes, Strength, Dexterity, and special senses are replaced by those of the new form, and it gains any statistics and capabilities (except class features, legendary actions, and lair actions) that the new form has but that it lacks.
```
^statblock