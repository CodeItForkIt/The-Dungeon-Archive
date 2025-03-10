---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/mabjov
- monster/cr/3
- monster/size/large
- monster/type/beast
aliases: ["Sword Spider"]
---
# Sword Spider
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
title: Sword Spider
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/MaBJoV/Sword%20Spider.webp#token)
*Large beast, Unaligned*

- **Armor Class** 16 (natural armor)
- **Hit Points** 45 (`6d10 + 12`)
- **Speed** 30 ft., climb 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|16 (+3)|16 (+3)|14 (+2)| 6 (-2)|12 (+1)| 4 (-3)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** Stealth +7
- **Senses** tremorsense 60 ft., passive Perception 11
- **Languages** —
- **Challenge** 3

## Traits

***Spider Climb.*** The sword spider can climb difficult surfaces, including upside down on ceilings, without needing to make an ability check.

***Web Sense.*** While in contact with a web, the sword spider knows the exact location of any other creature in contact with the same web.

***Web Walker.*** The sword spider ignores movement restrictions caused by webbing.

## Actions

***Multiattack.*** The sword spider makes one Bite attack and two Foreleg attacks.

***Bite.*** *Melee Weapon Attack:* `dice:1d20+5|noform|text(+5)` to hit, reach 5 ft., one target. *Hit:* `dice:1d8+3|noform|avg|text(7)` (`1d8 + 3`) piercing damage, and the target must make a DC 12 Constitution saving throw, taking `dice:2d8|noform|avg|text(9)` (`2d8`) poison damage on a failed save, or half as much damage on a successful one. If the poison damage reduces the target to 0 hit points, the target is stable but [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) for 1 hour, even after regaining hit points, and has the [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed) condition while [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) in this way.

***Foreleg.*** *Melee Weapon Attack:* `dice:1d20+5|noform|text(+5)` to hit, reach 5 ft., one target. *Hit:* `dice:2d6+3|noform|avg|text(10)` (`2d6 + 3`) slashing damage.
```
^statblock