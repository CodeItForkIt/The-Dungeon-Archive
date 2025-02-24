---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/mabjov
- monster/cr/9
- monster/size/medium
- monster/type/humanoid/human
aliases: ["Lothar"]
---
# Lothar
*Source: Minsc and Boo's Journal of Villainy p. 80*  

Lothar is an Uthgardt barbarian and priest of the Raven Queen. He was born to the Uthgardt tribe of the Black Raven. His mother left him to be raised by her Uthgardt husband when Lothar was still young. Lothar was struck with wanderlust an early age, both because of a desire to see the world and a chance to escape the superstition of his people. Lothar can sense paths that are [invisible](2-Mechanics/CLI/rules/conditions.md#Invisible) to mortal senses. He can walk into a forest glade and emerge in the Feywild or track a stag through the snow to appear on the glacial fields of Elysium.

Eventually the wanderings of his youth took him into the Shadowfell. Unlike most, Lothar felt an affinity for the dread realm and had no desire to leave. In the years he spent there, he met his lifelong friend Borivik as well as coming into the service of the Raven Queen.

Unlike most faithful, Lothar's devotion to the Raven Queen was not something that came willingly. Lothar was infected with lycanthropy when he stayed with a family of wereravens disguised as simple merchants. Initially he searched for a cure to the supernatural affliction, but soon began to hear the whisperings of the Raven Queen. At first, she only spoke to him in his dreams, but her voice became more insistent as time went on. It was not long before her voice would encroach upon his thoughts day and night. Lothar realized that he could swear fealty to the enigmatic ruler of the Shadowfell or he could descend into madness. He chose the former.

Much like most who follow the Raven Queen, Lothar rarely understands her motivations or goals. It is his duty to find those he has seen in the visions that she sends him.

## Lothar as a Contact

Lothar is the primary contact for the Raven Circle at low levels. Lothar can take companions with him when he walks the paths between worlds. He will only take members of the Raven Circle on each unique journey once and he waits for one week before returning to Faerûn.

**Journeys with Lothar**

| Journey | Required Level |
|---------|----------------|
| Barovia | 1 |
| Suldanessellar | 1 |
| Other domain of dread | 3 |
| Shadowfell—evernight | 3 |
| Feywild | 5 |
| Elysium | 5 |
| Beastlands | 7 |
| The Outlands | 7 |
^journeys-with-lothar

## Statblock

```ad-statblock
title: Lothar
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/MaBJoV/Lothar.webp#token)
*Medium humanoid (human), Lawful Neutral*

- **Armor Class** 13
- **Hit Points** 210 (`28d8 + 84`)
- **Speed** 30 ft., fly 50 ft. in raven and hybrid forms

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|18 (+4)|16 (+3)|16 (+3)|11 (+0)|10 (+0)|10 (+0)|

- **Proficiency Bonus** +4
- **Saving Throws** ⏤
- **Skills** Insight +4, Perception +4, Stealth +7, Survival +8
- **Senses** darkvision 60 ft., passive Perception 14
- **Damage Immunities** bludgeoning, piercing, slashing damage from nonmagical weapons that aren't silvered
- **Languages** Common, Orc
- **Challenge** 9

## Traits

***Mimicry.*** Lothar can mimic simple sounds he has heard, such as a person whispering, a baby crying, or an animal chittering. A creature that hears the sounds can tell they are imitations with a successful DC 15 Wisdom ([Insight](2-Mechanics/CLI/rules/skills.md#Insight)) check.

***Spellcasting.*** Lothar casts one of the following spells, requiring no material components and using Charisma as the spellcasting ability (spell save DC 12, `dice:1d20+4|noform|text(+4)` to hit with spell attacks):

**At will**: [blade ward](2-Mechanics/CLI/spells/blade-ward.md), [eldritch blast](2-Mechanics/CLI/spells/eldritch-blast.md), [message](2-Mechanics/CLI/spells/message.md)

**1/day each**: [bane](2-Mechanics/CLI/spells/bane.md), [charm person](2-Mechanics/CLI/spells/charm-person.md), [daylight](2-Mechanics/CLI/spells/daylight.md), [faerie fire](2-Mechanics/CLI/spells/faerie-fire.md), [fear](2-Mechanics/CLI/spells/fear.md), [misty step](2-Mechanics/CLI/spells/misty-step.md), [plane shift](2-Mechanics/CLI/spells/plane-shift.md)

## Actions

***Multiattack (Humanoid or Hybrid Form Only).*** Lothar makes three Greataxe attacks.

***Greataxe (Humanoid or Hybrid Form Only).*** *Melee Weapon Attack:* `dice:1d20+8|noform|text(+8)` to hit, reach 5 ft., one target. *Hit:* `dice:1d12+4|noform|avg|text(10)` (`1d12 + 4`) slashing damage, `dice:1d12+8|noform|avg|text(14)` (`1d12 + 8`) while in a rage.

***Beak (Raven or Hybrid Form Only).*** *Melee Weapon Attack:* `dice:1d20+8|noform|text(+8)` to hit, reach 5 ft., one target. *Hit:* 1 piercing damage in raven form, or `dice:1d4+4|noform|avg|text(6)` (`1d4 + 4`) piercing damage in hybrid form. If the target is Humanoid, it must succeed on a DC 15 Constitution saving throw or be cursed with wereraven lycanthropy.

***Change Shape.*** Lothar can use his action to polymorph into a raven-humanoid hybrid, or into a Small raven, or back into his true form, which is Humanoid. His statistics, other than his size, are the same in each form. Any equipment he is wearing or carrying isn't transformed. Lothar reverts to his true form if he dies.

## Bonus Actions

***Rage.*** Lothar rages for 1 minute. During his rage he has advantage on Strength checks and Strength saving throws. He gains a +4 bonus to damage while he is in a rage. He has resistance to bludgeoning, piercing, and slashing damage while in a rage. Lothar can't cast spells while in a rage.
```
^statblock