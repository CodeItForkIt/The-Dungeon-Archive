---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/mpp
- monster/cr/1
- monster/size/medium
- monster/type/plant
aliases: ["Razorvine Blight"]
---
# Razorvine Blight
*Source: Morte's Planar Parade p. 42, Sigil and the Outlands*  

Travelers of Sigil and the Lower Planes take care to avoid razorvine, a creeping plant named for its prickly stems and cutting leaves. While razorvine is normally a mere environmental nuisance or deterrent, razorvine that absorbs the blood of a vampiric passerby can awaken into a terror known as a razorvine blight.

Razorvine blights lay ambushes on well-traveled paths by standing still to appear as ordinary razorvine. When unassuming travelers pass by the seemingly inanimate plant, the blight strikes, revealing its twisted, humanlike form and lashing out with razor-sharp vines to feed its bloodlust.

While razorvine blights are usually dangerous, in Sigil they sometimes mimic the behaviors of the city's other inhabitants—for better or worse. At least one blight, known as Patch, spreads copies of itself across the city, creating a spy network of copies with mysterious goals.

```ad-statblock
title: Razorvine Blight
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/MPP/Razorvine%20Blight.webp#token)
*Medium plant, typically  Neutral Evil*

- **Armor Class** 12
- **Hit Points** 27 (`5d8 + 5`)
- **Speed** 30 ft., climb 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|10 (+0)|15 (+2)|13 (+1)| 5 (-3)|10 (+0)| 3 (-4)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** Stealth +4
- **Senses** blindsight 60 ft. (can't see beyond this radius), passive Perception 10
- **Condition Immunities** [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded), [deafened](2-Mechanics/CLI/rules/conditions.md#Deafened)
- **Languages** understands Common but can't speak
- **Challenge** 1

## Traits

***False Appearance.*** If the blight is motionless at the start of combat, it has advantage on its initiative roll. If a creature hasn't observed the blight move or act, that creature must succeed on a DC 18 Intelligence ([Investigation](2-Mechanics/CLI/rules/skills.md#Investigation)) check to discern that the blight is animate.

***Spider Climb.*** The blight can climb difficult surfaces, including upside down on ceilings, without needing to make an ability check.

## Actions

***Multiattack.*** The blight makes two Claw attacks.

***Claw.*** *Melee Weapon Attack:* `dice:1d20+4|noform|text(+4)` to hit (with advantage if the target is missing any of its hit points), reach 10 ft., one target. *Hit:* `dice:1d6+2|noform|avg|text(5)` (`1d6 + 2`) slashing damage.

***Life-Draining Vines (Recharge 6).*** Snaking vines erupt from the blight. Each creature within 10 feet of it must make a DC 12 Dexterity saving throw, taking `dice:2d8|noform|avg|text(9)` (`2d8`) slashing damage on failed save, or half as much damage on a successful one. If at least one of the creatures that failed this save isn't a Construct or an Undead, the blight regains 9 hit points.
```
^statblock