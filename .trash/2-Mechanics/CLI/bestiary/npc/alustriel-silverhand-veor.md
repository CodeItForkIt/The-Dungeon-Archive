---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/veor
- monster/cr/21
- monster/size/medium
- monster/type/humanoid/human
- monster/type/humanoid/wizard
aliases: ["Alustriel Silverhand"]
---
# Alustriel Silverhand
*Source: Vecna: Eve of Ruin p. 242*  

Lady Alustriel Silverhand, called the Shining Lady, has been an influential wizard and proponent of good across Toril for centuries. Alustriel is one of the Seven Sisters—immortal daughters of Mystra, the god of magic. The divine energy Mystra passed to Alustriel grants Alustriel incredible power over arcane magic.

Alustriel's youthful appearance as a human woman with silver hair gives no hint of her supernaturally extended life span. She typically wears long robes and wields a unicorn-headed staff, her*Staff of Silverymoon*.

## Personality

Alustriel's primary concerns are to spread kindness, reward virtue, and promote a culture of compassion throughout the multiverse. She is good at building alliances and quick to intervene when she senses a threat to the forces of good. She has traveled far and established safe houses across the planes—such as her sanctum in the city of Sigil. Alustriel doesn't seek personal glory or wealth; her style of influencing the cosmos is quiet yet steady.

## History

Like other Chosen of Mystra, Alustriel is concerned with preserving the Weave, the primary incarnation of magic that permeates Toril. She believes that the Weave favors those who act with mercy and compassion, seeks to deliver lives of security for all, and bolsters people's efforts when they seek to right wrongs and combat evil.

Nowhere are Alustriel and her deeds better known than in the Silver Marches and its capital, Silverymoon. Alustriel ruled Silverymoon for centuries, once disguised as a wizard named Elué Dualen and then later in her true form. She helped create Silverymoon's famous Moonbridge and cofounded the Lady's College, the first school in Faerûn for mages as students rather than as apprentices in service.

Alustriel stepped down as Silverymoon's high mage more than a century ago. Her son, Methrammar Aerasumé, now leads the city and works to uphold his mother's legacy.

Alustriel has partaken in countless adventures before and after her tenure as Silverymoon's high mage. She has befriended famous adventurers such as Drizzt Do'Urden, worked with prominent organizations like the Harpers, and helped prevent or undo many kinds of evil.

## Statblock

```ad-statblock
title: Alustriel Silverhand
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/VEoR/Alustriel%20Silverhand.webp#token)
*Medium humanoid (human, wizard), Chaotic Good*

- **Armor Class** 15 (18 with [mage armor](2-Mechanics/CLI/spells/mage-armor.md))
- **Hit Points** 272 (`32d8 + 128`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|12 (+1)|20 (+5)|18 (+4)|24 (+7)|23 (+6)|22 (+6)|

- **Proficiency Bonus** +7
- **Saving Throws** Constitution +11, Intelligence +14, Wisdom +13
- **Skills** Arcana +14, History +14, Insight +13, Religion +14
- **Senses** passive Perception 16
- **Damage Resistances** radiant
- **Damage Immunities** poison
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** Common, Draconic, Elvish
- **Challenge** 21

## Traits

***Ear of the Chosen.*** Whenever a creature on the same plane of existence as Alustriel speaks Alustriel's name, Alustriel hears her name and the next nine words the speaker utters.

***Legendary Resistance (3/Day).*** If Alustriel fails a saving throw, she can choose to succeed instead.

***Special Equipment.*** Alustriel carries a magic staff known as the Staff of Silverymoon. In the hands of anyone other than Alustriel, the Staff of Silverymoon is a Staff of Power.

***Spellcasting.*** Alustriel casts one of the following spells, using Intelligence as the spellcasting ability (spell save DC 22):

**At will**: [Dancing Lights](2-Mechanics/CLI/spells/dancing-lights.md), [Detect Magic](2-Mechanics/CLI/spells/detect-magic.md), [Mage Armor](2-Mechanics/CLI/spells/mage-armor.md) (self only), [Mage Hand](2-Mechanics/CLI/spells/mage-hand.md)

**1/day each**: [Telepathy](2-Mechanics/CLI/spells/telepathy.md), [Teleport](2-Mechanics/CLI/spells/teleport.md), [Time Stop](2-Mechanics/CLI/spells/time-stop.md)

**2/day each**: [Detect Thoughts](2-Mechanics/CLI/spells/detect-thoughts.md), [Dispel Magic](2-Mechanics/CLI/spells/dispel-magic.md), [Tongues](2-Mechanics/CLI/spells/tongues.md)

## Actions

***Multiattack.*** Alustriel makes three Staff of Silverymoon attacks or two Reproving Ray attacks.

***Staff of Silverymoon.*** *Melee Weapon Attack:* `dice:1d20+12|noform|text(+12)` to hit, reach 5 ft., one target. *Hit:* `dice:2d8+5|noform|avg|text(14)` (`2d8 + 5`) bludgeoning damage plus `dice:7d10|noform|avg|text(38)` (`7d10`) radiant damage.

***Reproving Ray.*** *Ranged Spell Attack:* `dice:1d20+14|noform|text(+14)` to hit, range 120 ft., one target. *Hit:* `dice:9d12+7|noform|avg|text(65)` (`9d12 + 7`) force damage, and if the target is a creature, it must make a DC 22 Charisma saving throw. On a failed save, the target has the [incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated) condition until the start of Alustriel's next turn. On a successful save, the target's speed is reduced by 10 feet until the start of Alustriel's next turn.

***Argent Blaze (Requires Silver Fire).*** Alustriel summons a 60- foot cone of silver fire. Each creature in that area must make a DC 22 Dexterity saving throw, taking `dice:14d10|noform|avg|text(77)` (`14d10`) radiant damage on a failed save or half as much damage on a successful one. Additionally, Alustriel or one creature of her choice within 60 feet of her then regains `dice:3d6|noform|avg|text(10)` (`3d6`) hit points.

## Bonus Actions

***Silver Fire (2/Day).*** Brilliant silver fire harmlessly wreathes Alustriel and empowers her. The silver fire lasts for 1 hour or until she has the [incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated) condition or uses another bonus action to quench it. While wreathed in silver fire, Alustriel gains truesight within 30 feet and can use her Argent Blaze action. In addition, Alustriel is unaffected by magic that would ascertain her alignment, creature type, thoughts, or truthfulness.

## Reactions

***Shining Counterspell.*** Alustriel interrupts a creature she can see within 60 feet of herself that is casting a spell. If the spell is 5th level or lower, it fails and has no effect. If the spell is 6th level or higher, Alustriel makes an Intelligence check (DC 10 plus the spell's level). On a successful check, the spell fails and has no effect. Whatever the spell's level, the caster takes `dice:2d10|noform|avg|text(11)` (`2d10`) radiant damage if the spell fails.
```
^statblock