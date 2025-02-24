---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/qftis
- monster/cr/3
- monster/size/small
- monster/type/plant
aliases: ["Vegepygmy Moldmaker"]
---
# Vegepygmy Moldmaker
*Source: Quests from the Infinite Staircase p. 218*  

The oldest vegepygmies in a colony sometimes achieve control over the growth and propagation of the mold that bore them. These elders, known as moldmakers, can envelop foes in stifling layers of mold. Moldmakers often wear pauldrons made of lichen to denote their status.

## Vegepygmies

Also called mold folk, vegepygmies are fungal creatures that spring forth from the body of a Humanoid or Giant killed by russet mold, a poisonous fungus rumored to have originated from beyond the stars.

Vegepygmies gather in small bands, communicating with a combination of gestures, hisses, and rhythmic taps. While vegepygmies can sustain themselves by absorbing nutrients from soil and other organic matter, they prefer a carnivorous diet achieved through hunting and scavenging. Vegepygmies can live indefinitely so long as the climate remains hospitable to their fungal bodies.

To learn more about vegepygmies, see Monsters of the Multiverse.

## Statblock

```ad-statblock
title: Vegepygmy Moldmaker
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/QftIS/Vegepygmy%20Moldmaker.webp#token)
*Small plant, typically  Neutral*

- **Armor Class** 15 (natural armor)
- **Hit Points** 44 (`8d6 + 16`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|10 (+0)|14 (+2)|14 (+2)|10 (+0)|16 (+3)|11 (+0)|

- **Proficiency Bonus** +2
- **Saving Throws** Intelligence +2, Wisdom +5
- **Skills** Perception +5, Stealth +4
- **Senses** darkvision 60 ft., passive Perception 15
- **Damage Resistances** lightning, piercing
- **Languages** Vegepygmy
- **Challenge** 3

## Traits

***Plant Camouflage.*** The vegepygmy has advantage on Dexterity ([Stealth](2-Mechanics/CLI/rules/skills.md#Stealth)) checks it makes in any terrain with ample obscuring vegetation.

***Regeneration.*** The vegepygmy regains 7 hit points at the start of its turn. If it takes cold, fire, or necrotic damage, this trait doesn't function at the start of the vegepygmy's next turn. The vegepygmy dies only if it starts its turn with 0 hit points and doesn't regenerate.

## Actions

***Multiattack.*** The vegepygmy makes two Claw attacks.

***Claw.*** *Melee Weapon Attack:* `dice:1d20+4|noform|text(+4)` to hit, reach 5 ft., one target. *Hit:* `dice:3d6+2|noform|avg|text(12)` (`3d6 + 2`) slashing damage.

***Toxic Mold (2/Day).*** The vegepygmy targets a creature it can see within 60 feet of itself. If the target isn't a vegepygmy, it must make a DC 13 Constitution saving throw. On a failed save, the target takes `dice:3d8|noform|avg|text(13)` (`3d8`) poison damage and has the [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded) and [deafened](2-Mechanics/CLI/rules/conditions.md#Deafened) conditions for 1 minute as it becomes covered in a thick layer of mold. On a successful save, the target takes half as much damage only.

The target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.
```
^statblock