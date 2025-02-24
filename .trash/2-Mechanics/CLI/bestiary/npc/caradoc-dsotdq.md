---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/dsotdq
- monster/cr/8
- monster/size/medium
- monster/type/undead
aliases: ["Caradoc"]
---
# Caradoc
*Source: Dragonlance: Shadow of the Dragon Queen p. 193*  

Seneschal of Lord Soth and a former Knight of Solamnia, Caradoc burned when Dargaard Keep was consumed in the fires of the Cataclysm. As with many of Soth's retainers, Caradoc was cursed with undeath. Being duplicitous and cowardly at his core, the seneschal didn't return as a skeletal knight but rather as an intangible spirit. Caradoc's Undead form suits him well, allowing him to possess the living and use unwilling tongues to spread his lies. However, Caradoc is tethered to his scorched bones, which collect dust in Dargaard Keep. He can leave the accursed castle while possessing the body of a Humanoid, but he's swiftly pulled back if caught beyond its walls without a host.

```ad-statblock
title: Caradoc
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/DSotDQ/Caradoc.webp#token)
*Medium undead, Neutral Evil*

- **Armor Class** 14
- **Hit Points** 110 (`20d8 + 20`)
- **Speed** 0 ft., fly 40 ft. (hover)

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
| 1 (-5)|18 (+4)|12 (+1)|15 (+2)|13 (+1)|19 (+4)|

- **Proficiency Bonus** +3
- **Saving Throws** Intelligence +5, Wisdom +4
- **Skills** Deception +7, Insight +4, Perception +4
- **Senses** darkvision 60 ft., passive Perception 14
- **Damage Resistances** acid; fire; lightning; thunder; bludgeoning, piercing, slashing from nonmagical attacks
- **Damage Immunities** cold, necrotic, poison
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled), [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed), [petrified](2-Mechanics/CLI/rules/conditions.md#Petrified), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned), [prone](2-Mechanics/CLI/rules/conditions.md#Prone), [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained)
- **Languages** Common, Solamnic
- **Challenge** 8

## Traits

***Bound Haunting.*** Caradoc's spirit is bound to Dargaard Keep. At the start of his turn, if he's outside the keep's walls and not possessing a creature using his Possession action, he must succeed on a DC 15 Charisma saving throw or vanish and reappear in an unoccupied space within the keep.

***Incorporeal Movement.*** Caradoc can move through other creatures and objects as if they were difficult terrain. He takes `dice:1d10|noform|avg|text(5)` (`1d10`) force damage if he ends his turn inside an object.

***Rejuvenation.*** If Caradoc dies, he reforms within Dargaard Keep in `dice:2d6|noform|avg` (`2d6`) days.

***Unusual Nature.*** Caradoc doesn't require air, food, drink, or sleep.

## Actions

***Multiattack.*** Caradoc makes two Withering Touch attacks.

***Withering Touch.*** *Melee Weapon Attack:* `dice:1d20+7|noform|text(+7)` to hit, reach 5 ft., one target. *Hit:* `dice:2d10+4|noform|avg|text(15)` (`2d10 + 4`) necrotic damage.

***Possession (Recharge 5-6).*** One Humanoid that Caradoc can see within 5 feet of himself must succeed on a DC 15 Charisma saving throw or be possessed by him; he then disappears, and the target is [incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated) and loses control of its body. Caradoc now controls the body but doesn't deprive the target of awareness. Caradoc can't be targeted by any attack, spell, or other effect, except ones that turn Undead, and he retains his alignment, Intelligence, Wisdom, and Charisma, immunity to being [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed) and [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), and his Divisive Whispers bonus action. He otherwise uses the possessed target's statistics but doesn't gain access to the target's knowledge, class features, or proficiencies.

The possession lasts until the body drops to 0 hit points, Caradoc ends it as a bonus action, or he is turned or forced out by an effect like the [dispel evil and good](2-Mechanics/CLI/spells/dispel-evil-and-good.md) spell. When the possession ends, Caradoc reappears in an unoccupied space within 5 feet of the body. The target is immune to Caradoc's Possession for 24 hours after succeeding on the saving throw or after the possession ends.

## Bonus Actions

***Divisive Whispers.*** Caradoc magically whispers to one creature within 60 feet of himself. The target must succeed on a DC 15 Wisdom saving throw, or the target must immediately use its reaction to make a melee attack against another creature of Caradoc's choice (wasting its reaction if there are no other creatures within reach).
```
^statblock