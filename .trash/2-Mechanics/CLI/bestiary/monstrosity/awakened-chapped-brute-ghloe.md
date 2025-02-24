---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/ghloe
- monster/cr/7
- monster/size/large
- monster/type/monstrosity
aliases: ["Awakened Chapped Brute"]
---
# Awakened Chapped Brute
*Source: Grim Hollow: Lairs of Etharis p. 68*  

> [!quote]  
> 
> The callused skin of the merchant's hulking bodyguard ripples as if something beneath is trying to wriggle free.

## Salvage

Chapped brutes rarely carry treasure or equipment unless doing so as instructed by their master. An accomplished leatherworker can fashion the callused skin of a chapped brute into+1 armor—leather, studded leather, or hide—that grants the wearer resistance to necrotic damage and doesn't require attunement. This armor takes 10 extra days of work to fashion, and magical components worth 100 gp must be expended in its creation.

## Lore

- **DC 10 Intelligence ([Arcana](2-Mechanics/CLI/rules/skills.md#Arcana)).** The magical and alchemical process that creates these brutes leaves them resistant to necrotic damage.  
- **DC 15 Intelligence ([Nature](2-Mechanics/CLI/rules/skills.md#Nature)).** These beings are so volatile because of their creation process that when they are killed, they have a chance to transform into larger, deadlier forms.  
- **DC 20 Wisdom ([Medicine](2-Mechanics/CLI/rules/skills.md#Medicine)).** The final form of the chapped brute has a life force that fluctuates, so that it randomly gains and loses life force every few seconds.  

> [!note] GM Advice
> 
> You can use any chapped brute form as part of an encounter. You can also build encounters in which one chapped brute transforms into one or both of its larger forms. To do so, treat each form as a separate monster. Transformation can take up to 1 minute, allowing you to stagger the encounters, but it can occur as quickly as you need it to for your game.
^gm-advice

## Statblock

```ad-statblock
title: Awakened Chapped Brute
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/GHLoE/Awakened%20Chapped%20Brute.webp#token)
*Large monstrosity, Neutral Evil*

- **Armor Class** 14 (natural armor)
- **Hit Points** 126 (`12d10 + 60`)
- **Speed** 40 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|20 (+5)|10 (+0)|20 (+5)| 5 (-3)|10 (+0)| 5 (-3)|

- **Proficiency Bonus** +3
- **Saving Throws** ⏤
- **Skills** Athletics +8
- **Senses** blindsight 60 ft. (blind beyond this radius), passive Perception 10
- **Damage Resistances** necrotic
- **Condition Immunities** [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded)
- **Languages** understands one language but can't speak
- **Challenge** 7

## Traits

***Keen Hearing and Smell.*** The awakened chapped brute has advantage on Wisdom ([Perception](2-Mechanics/CLI/rules/skills.md#Perception)) checks that rely on hearing or smell. While [deafened](2-Mechanics/CLI/rules/conditions.md#Deafened) and unable to smell, the brute can't use its blindsight.

***Sure-Footed.*** The awakened chapped brute has advantage on Strength and Dexterity saving throws made against effects that would knock it [prone](2-Mechanics/CLI/rules/conditions.md#Prone).

## Actions

***Multiattack.*** The awakened chapped brute makes two tentacle attacks or one tentacle slam.

***Tentacle.*** *Melee Weapon Attack:* `dice:1d20+8|noform|text(+8)` to hit, reach 15 ft., one target. *Hit:* `dice:3d8+5|noform|avg|text(18)` (`3d8 + 5`) bludgeoning damage. If the target is Medium or smaller, it is [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) (escape DC 16). Until this grapple ends, the target is [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained), and the brute can't use the tentacle against another target. The awakened chapped brute has two tentacles.

***Tentacle Slam.*** The awakened chapped brute slams one or two targets [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) by it into a solid object or each other. Each target must make a DC 16 Strength saving throw. If the saving throw fails, the target takes `dice:3d8+5|noform|avg|text(18)` (`3d8 + 5`) bludgeoning damage and is [stunned](2-Mechanics/CLI/rules/conditions.md#Stunned) until the end of the awakened chapped brute's next turn. On a successful saving throw, the target takes half the damage and isn't [stunned](2-Mechanics/CLI/rules/conditions.md#Stunned).
```
^statblock