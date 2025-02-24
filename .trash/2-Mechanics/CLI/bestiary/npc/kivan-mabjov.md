---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/mabjov
- monster/cr/7
- monster/size/medium
- monster/type/humanoid/elf
aliases: ["Kivan"]
---
# Kivan
*Source: Minsc and Boo's Journal of Villainy p. 48*  

Kivan is a highly skilled elven ranger, equally proficient in archery and melee combat. In his youth, Kivan was driven to avenge the death of his wife, Deheriana. He channeled that anger by serving the shadow druid Faldorn in various raids against towns and villages on the borders of civilization. But this anger was quelled when he met his future husband, the druid Cernd of the Emerald Enclave. He left Faldorn and joined the Emerald Enclave.

While life was good for many decades, his past eventually caught up with him. Faldorn joined the Emerald Enclave and quickly rose through the ranks to become one of the Enclave's Hierophants. She has been positioning herself to take one of the three spots in the Elder Circle—the three highest members of the Emerald Enclave.

Kivan is torn on what to do. He knows that Faldorn is secretly a shadow druid, but if he were to expose her, she would expose him as well. He would lose everything—the friends he has made, his position in the Enclave, but most of all the love of his husband, Cernd. Cernd has long battled against what he views as the corruption of the shadow druids.

Kivan is a blunt and taciturn elf who values bravery and skill in battle above all other qualities. He tirelessly hones his skills as a tracker and warrior.

## Kivan as a Contact

Kivan is the primary contact for members of the Emerald Enclave at low levels. Kivan can connect you with an animal or plant companion for a short duration. Your group can only have one of these companions at a time. Once the companion has helped you for a 24-hour period you can make an [Animal Handling](2-Mechanics/CLI/rules/skills.md#Animal%20Handling), [Nature](2-Mechanics/CLI/rules/skills.md#Nature) or [Persuasion](2-Mechanics/CLI/rules/skills.md#Persuasion) check (depending on the creature) to convince them to stay with you for another 24 hours. Each time you make this check it increases by 1. If the companion dies while helping you, you can never gain the aid of that type of creature again. If the companion leaves your service without dying, then you can ask Kivan for another companion after one month has passed.

**Animal and Plant Companions via Kivan**

| Magical Plant and Animal Companion | Required Level | Skill Check |
|------------------------------------|----------------|-------------|
| Overly enthusiastic blink dog | 1 | DC 15 [Animal Handling](2-Mechanics/CLI/rules/skills.md#Animal%20Handling) |
| Sulky needle blight | 1 | DC 15 [Nature](2-Mechanics/CLI/rules/skills.md#Nature) |
| Air headed satyr | 3 | DC 15 [Persuasion](2-Mechanics/CLI/rules/skills.md#Persuasion) |
| Prankster vine blight | 3 | DC 15 [Nature](2-Mechanics/CLI/rules/skills.md#Nature) |
| Sarcastic dryad | 5 | DC 15 [Persuasion](2-Mechanics/CLI/rules/skills.md#Persuasion) |
| Awakened tree with confusing wisdom | 7 | DC 20 [Nature](2-Mechanics/CLI/rules/skills.md#Nature) |
| Doom and gloom hamadryad | 7 | DC 20 [Persuasion](2-Mechanics/CLI/rules/skills.md#Persuasion) |
^animal-and-plant-companions-via-kivan

## Statblock

```ad-statblock
title: Kivan
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/MaBJoV/Kivan.webp#token)
*Medium humanoid (elf), Chaotic Good*

- **Armor Class** 16 ([studded leather](2-Mechanics/CLI/items/studded-leather-armor.md))
- **Hit Points** 132 (`24d8 + 24`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|16 (+3)|18 (+4)|12 (+1)|11 (+0)|14 (+2)|11 (+0)|

- **Proficiency Bonus** +3
- **Saving Throws** Dexterity +7, Wisdom +5
- **Skills** Nature +6, Perception +8, Stealth +10, Survival +8
- **Senses** passive Perception 18
- **Languages** Common, Elvish, Sylvan
- **Challenge** 7

## Traits

***Fey Ancestry.*** Kivan has advantage on saving throws against being [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), and magic can't put Kivan to sleep.

***Keen Hearing and Sight.*** Kivan has advantage on Wisdom ([Perception](2-Mechanics/CLI/rules/skills.md#Perception)) checks that rely on hearing or sight.

## Actions

***Multiattack.*** Kivan makes three Longsword attacks or three Longbow attacks.

***Longsword.*** *Melee Weapon Attack:* `dice:1d20+6|noform|text(+6)` to hit, reach 5 ft., one target. *Hit:* `dice:1d8+3|noform|avg|text(7)` (`1d8 + 3`) slashing damage or `dice:1d10+3|noform|avg|text(8)` (`1d10 + 3`) slashing damage if wielded with two hands.

***Longbow.*** *Ranged Weapon Attack:* `dice:1d20+7|noform|text(+7)` to hit, ranged 150/600 ft., one target. *Hit:* `dice:1d8+4|noform|avg|text(8)` (`1d8 + 4`) piercing damage.

***Volley (2/Day).*** Kivan makes a Longbow attack against any number of creatures he can see within 150 feet. He must make a separate attack roll with advantage for each target.

## Bonus Actions

***Kivan's Mark.*** Kivan designates one creature he can see within 60 feet as his prey. The first time each turn that Kivan hits his prey with a weapon attack, the prey takes an extra `dice:2d6|noform|avg|text(7)` (`2d6`) damage from the weapon.
```
^statblock