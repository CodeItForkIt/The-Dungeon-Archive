---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/mabjov
- monster/cr/1-4
- monster/size/small
- monster/type/aberration
aliases: ["Gibberling"]
---
# Gibberling
*Source: Minsc and Boo's Journal of Villainy p. 141*  

> [!quote] A quote from Volo  
> 
> Gibberlings are appropriately named, for they babble, or should I say gibber, incessantly. They are unpredictable and thus barely worthy of any kind of research. Thus, why I didn't include them in my book "Volo's Guide to Monsters".

> [!quote] A quote from Gibberling  
> 
> SKREEEEEEEEGLURKLGLURKL! blarkblarkblarkblark. JagAjaGaJaGaJagAjAga!?

Gibberlings are small, feral humanoids believed to have originally come from the Far Realm, a distant plane characterized by chaos and madness. However, just how these creatures reached the Prime Material Plane and Faerûn is unknown. Regardless, these deadly, wild creatures have become an increasingly common sight for unfortunate travelers along the Sword Coast who stray from major roads at night. Luckily, the gibberlings' intense fear of all sources of light, including fire, make safeguarding camps and settlements a simple task.

## Madness Made Flesh

Gibberlings are short, squat creatures roughly the same height as the average gnome, though their hunched posture makes them appear to be even smaller. Thick black fur covers most of their muscular bodies, though bare patches of sickly gray skin are found on their faces, arms, and legs. Jetblack eyes and a perpetual deranged grin adorn the bestial face of a gibberling, which is framed by pointed ears topped with hairy tufts.

## Chattering Hunger

Gibberlings roam the wilderness in large groups, largely preferring to stay within dense forests and caverns. They are exclusively carnivorous and do not hesitate to eat the flesh of their fallen kin. Gibberlings are rarely able to surprise their prey, as they constantly shriek, howl, and chatter. Although these vocalizations appear to be a form communication, the few linguists who study these creatures have concluded that these noises are not a language.

## Unpredictable Combatants

Even a novice adventurer could make short work of a single gibberling, though they always travel in packs. If left unchecked, these groups swell to vast hordes that devour everything in their path. Despite their animalistic behavior, gibberlings are intelligent enough to wield weapons, albeit ones stolen from victims rather than forged themselves. When such arms are unavailable, gibberlings improvise using rocks, bones, and large sticks. Gibberlings lack any sense of self-preservation; with no concept of retreat, a gibberling always fights to the death.

## Statblock

```ad-statblock
title: Gibberling
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/MaBJoV/Gibberling.webp#token)
*Small aberration, Chaotic Neutral*

- **Armor Class** 12
- **Hit Points** 7 (`2d6`)
- **Speed** 25 ft., burrow 5 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|10 (+0)|15 (+2)|10 (+0)| 6 (-2)| 8 (-1)| 8 (-1)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** Stealth +4
- **Senses** darkvision 60 ft., passive Perception 9
- **Damage Resistances** psychic
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened)
- **Languages** —
- **Challenge** 1/4

## Traits

***Light Sensitivity.*** While in bright light, gibberlings have disadvantage on attack rolls, as well as on Wisdom ([Perception](2-Mechanics/CLI/rules/skills.md#Perception)) checks that rely on sight.

***Reckless.*** At the start of its turn, the gibberling can gain advantage on all melee weapon attack rolls during that turn, but attack rolls against it have advantage until the start of its next turn.

## Actions

***Dagger.*** *Melee Weapon Attack:* `dice:1d20+4|noform|text(+4)` to hit, reach 5 ft., one target. *Hit:* `dice:1d4+2|noform|avg|text(4)` (`1d4 + 2`) piercing damage.

***Swarm.*** *Melee Weapon Attack:* `dice:1d20+4|noform|text(+4)` to hit, reach 5 ft., one target. If the target is a Medium or smaller creature, it has the [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) condition (escape DC 10). All gibberlings within 5 feet of the target can use a reaction to make a Dagger attack with advantage on the attack roll.

***Burrow.*** The gibberling burrows into the dirt, giving itself the [prone](2-Mechanics/CLI/rules/conditions.md#Prone) condition. It has advantage on Dexterity ([Stealth](2-Mechanics/CLI/rules/skills.md#Stealth)) checks while it is [prone](2-Mechanics/CLI/rules/conditions.md#Prone).
```
^statblock