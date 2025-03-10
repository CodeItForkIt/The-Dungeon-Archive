---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/pabtso
- monster/cr/9
- monster/size/large
- monster/type/aberration
aliases: ["Oculorb"]
---
# Oculorb
*Source: Phandelver and Below: The Shattered Obelisk p. 214*  

Many oculorbs are dreamed into existence by beholders. The Far Realm's strange power can pervade a beholder's dreams, resulting in the birth of an oculorb.

Oculorbs resemble a slimy conglomeration of eyes in many sizes and shapes. They are dreaded even by the beholders that birth them. An oculorb is a tangle of negative emotions—the fury, melancholy, and obsession of its creator, all given gruesome, corporeal form. Like a beholder, an oculorb can fire beams of energy from its eyes, but an oculorb's eyes lack the more sophisticated magical nature of a beholder's eyestalks. Instead, an oculorb unleashes powerful waves of energy charged with negative emotions, cowing its foes with despair and ire.

```ad-statblock
title: Oculorb
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/PaBTSO/Oculorb.webp#token)
*Large aberration, typically  Chaotic Evil*

- **Armor Class** 13 (natural armor)
- **Hit Points** 127 (`15d10 + 45`)
- **Speed** 0 ft., fly 60 ft. (hover)

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|13 (+1)|10 (+0)|17 (+3)|14 (+2)|15 (+2)|19 (+4)|

- **Proficiency Bonus** +4
- **Saving Throws** Intelligence +6, Wisdom +6, Charisma +8
- **Skills** Investigation +6, Perception +10
- **Senses** truesight 60 ft., passive Perception 20
- **Condition Immunities** [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded), [prone](2-Mechanics/CLI/rules/conditions.md#Prone)
- **Languages** Deep Speech, telepathy 120 ft.
- **Challenge** 9

## Traits

***Magic Resistance.*** The oculorb has advantage on saving throws against spells and other magical effects.

***Watchful Eyes.*** The oculorb has advantage on initiative rolls and can't be surprised.

## Actions

***Multiattack.*** The oculorb makes two Dreadful Contact attacks or four Eye Beam attacks.

***Dreadful Contact.*** *Melee Weapon Attack:* `dice:1d20+5|noform|text(+5)` to hit, reach 5 ft., one creature. *Hit:* `dice:3d6+4|noform|avg|text(14)` (`3d6 + 4`) psychic damage, or `dice:6d6+4|noform|avg|text(25)` (`6d6 + 4`) psychic damage if the target has the [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened) condition.

***Eye Beam.*** *Ranged Spell Attack:* `dice:1d20+8|noform|text(+8)` to hit, range 120 ft., one creature. *Hit:* `dice:3d6+4|noform|avg|text(14)` (`3d6 + 4`) psychic damage.

***Antipathic Flood (Recharge 5-6).*** The oculorb releases a wave of negative emotions, choosing one of the following options:

***Weeping Eyes.*** The oculorb weeps, releasing a wave of crushing despair. Each creature within 30 feet of the oculorb must make a DC 16 Constitution saving throw. On a failed save, a creature's speed is reduced to 0 feet until the end of the oculorb's next turn, and if the creature was concentrating, its [concentration](2-Mechanics/CLI/rules/conditions.md#Concentration) is broken.

***Withering Glare.*** The oculorb's eyes unleash furious scarlet energy in a 60-foot cone. Each creature in that area must make a DC 16 Wisdom saving throw. On a failed save, a creature takes `dice:6d10|noform|avg|text(33)` (`6d10`) necrotic damage and has the [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened) condition for 1 minute. On a successful save, a creature takes half as much damage and isn't [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened). A [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened) creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a successful save.

## Reactions

***Obsessive Rebuke.*** When the oculorb is damaged by a creature it can see within 60 feet of itself, it forces the creature to make a DC 16 Wisdom saving throw. The creature takes `dice:3d6|noform|avg|text(10)` (`3d6`) psychic damage on a failed save, or half as much damage on a successful one.
```
^statblock