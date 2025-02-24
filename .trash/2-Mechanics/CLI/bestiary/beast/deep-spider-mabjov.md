---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/mabjov
- monster/cr/7
- monster/size/huge
- monster/type/beast
aliases: ["Deep Spider"]
---
# Deep Spider
*Source: Minsc and Boo's Journal of Villainy p. 151*  

Sword spiders are a type of giant arachnid that stalk the forests and caverns of Faerûn, walking on legs that resemble razor-sharp blades. These solitary predators move incredibly fast and with great stealth for their large size. The sword spider's sleek, 12-foot-long body is encased in a durable black exoskeleton covered in fine dark hairs. Although their eyesight is poor, sword spiders locate their prey using [tremorsense](2-Mechanics/CLI/rules/senses.md#Tremorsense) to feel for minute vibrations in the ground.

## Natural Weapons

All eight legs of a sword spider end in thick chitinous plates with serrated ridges. However, its primary weapons are its front two legs, which look like a pair of massive curved swords. Its victims are impaled upon these limbs and brought close enough for the spider to deliver its poisonous bite. Once slain, its prey is then chopped up into manageable morsels that can be fed into its cavernous maw lined with multiple rows of crooked fangs.

## Death From Above

Rather than trapping its food within a pre-constructed web, sword spiders prefer to wait for prey high up in tree branches and on cavern walls. (Despite their large frames, sword spiders retain the ability to cling to most surfaces, making them adept climbers.) Once it spots its prey, the spider sprays the creature with a restraining web and drops down with all eight of its lethal legs extended to impale its meal. When hunting in areas not conducive to this strategy, sword spiders instead stalk and chase their prey like big cats and are able to leap forward up to 30 feet, lashing out with their forelimbs.

## Deep Spiders

Sword spiders are native to the jungles of Mhair on the Chultan Peninsula in southwest Faerûn. Drow traders brought them to the Underdark where they were bred for use in battle under the control of Lolthite priestesses. These variants are called deep spiders and many have since escaped their pens and, with the ability to tolerate a wide range of climates, adapted quickly to their new subterranean homes. These creatures soon spread throughout the Underdark with many finding their way to the surface.

## Statblock

```ad-statblock
title: Deep Spider
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/MaBJoV/Deep%20Spider.webp#token)
*Huge beast, Unaligned*

- **Armor Class** 15 (natural armor)
- **Hit Points** 95 (`10d12 + 30`)
- **Speed** 30 ft., climb 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|20 (+5)|14 (+2)|16 (+3)| 6 (-2)|12 (+1)| 4 (-3)|

- **Proficiency Bonus** +3
- **Saving Throws** ⏤
- **Skills** Stealth +8
- **Senses** tremorsense 60 ft., passive Perception 11
- **Languages** —
- **Challenge** 7

## Traits

***Spider Climb.*** The deep spider can climb difficult surfaces, including upside down on ceilings, without needing to make an ability check.

***Web Sense.*** While in contact with a web, the deep spider knows the exact location of any other creature in contact with the same web.

***Web Walker.*** The deep spider ignores movement restrictions caused by webbing.

## Actions

***Multiattack.*** The deep spider makes one Bite attack and two Foreleg attacks.

***Bite.*** *Melee Weapon Attack:* `dice:1d20+8|noform|text(+8)` to hit, reach 5 ft., one target. *Hit:* `dice:2d8+5|noform|avg|text(14)` (`2d8 + 5`) piercing damage, and the target must make a DC 14 Constitution saving throw, taking `dice:4d8|noform|avg|text(18)` (`4d8`) poison damage on a failed save, or half as much damage on a successful one. If the poison damage reduces the target to 0 hit points, the target is stable but [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) for 1 hour, even after regaining hit points, and has the [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed) condition while [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) in this way.

***Foreleg.*** *Melee Weapon Attack:* `dice:1d20+8|noform|text(+8)` to hit, reach 5 ft., one target. *Hit:* `dice:4d6+5|noform|avg|text(19)` (`4d6 + 5`) slashing damage.
```
^statblock