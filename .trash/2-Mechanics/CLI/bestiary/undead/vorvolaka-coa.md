---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/coa
- monster/cr/14
- monster/size/medium
- monster/type/undead
aliases: ["Vorvolaka"]
---
# Vorvolaka
*Source: Chains of Asmodeus p. 258*  

There are always mortals who believe they can outwit the powers of the Nine Hells. One strategy is for a powerful evil creature to pledge its soul to the inferno, then seek the eternal unlife of a vampire to cheat the devils of their prize. The devils, of course, have seen it all before. Specialist teams hunt down the offenders and haul them to the Nine Hells where they're reshaped into vorvolakas, forever hungry for mortal blood in an underworld where such a commodity is vanishingly rare.

## The Ever-Hungry

A mockery of their original form, vorvolakas appear like vast tusked bats with a humanoid twist to their forms. Some faint semblance of their original features can just be discerned in their new bestial visage, just as an echo of their memories and personality persists in their fractured minds. They're almost never still or silent, shrieking out their gnawing hunger in their keening voices, jittering and clawing at one another, or circling like vultures across the brazen skies of the Nine Hells. Even as normal vampires are driven by their appetites, transformation into a vorvolaka increases that appetite a hundredfold, but the blood of mortals remains the only meal that sates them for even a moment. Seeing haughty vampires turned into ravenous monsters by their constant unfulfillable hunger is a torment that devils find highly amusing.

## Hell's Sentries

Many powerful devils—especially in the upper layers of Avernus and Dis—keep dovecotes of starving vorvolakas, tolerating their noise and squabbling in exchange for the chief service they provide. The creatures can scent the blood of mortals from miles away, flying into a frenzy at the first hint of a living being. Sometimes the monsters are kept caged, simply serving as a warning system so devils know that mortals are about. More often they're released into the skies to track down the intruders, with infernal huntsmen following in their wake to pick up the pieces.

## Frenzied Hunters

When they find living prey the vorvolakas descend in great squalling flocks, desperate to rend the mortals open and glut themselves on blood. They use their hooked claws and tusks to rip away armor and open up their prey, attacking with utter disregard for their own safety. Their flesh regenerates from most wounds—or else they would tear one another to pieces in their agony—and their hunger is such that only those of strongest faith can hold them back with prayer and holy symbol. Their screaming cries rend the ears of listeners, not only physically painful but imprinting the creatures' deep misery on all who hear. So evident is the despair of the creatures, their horror at their own tormented state, that those who have fought them and survived find themselves more moved to pity than any other emotion.

## Statblock

```ad-statblock
title: Vorvolaka
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/CoA/Vorvolaka.webp#token)
*Medium undead, Neutral Evil*

- **Armor Class** 18 (natural armor)
- **Hit Points** 190 (`20d8 + 100`)
- **Speed** 20 ft., fly 50 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|15 (+2)|19 (+4)|21 (+5)| 8 (-1)|13 (+1)|16 (+3)|

- **Proficiency Bonus** +5
- **Saving Throws** Constitution +10, Wisdom +6
- **Skills** Insight +6, Perception +11, Religion +4, Survival +6
- **Senses** darkvision 120 ft., passive Perception 21
- **Damage Resistances** bludgeoning, piercing, slashing from nonmagical attacks
- **Damage Immunities** necrotic
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed)
- **Languages** the languages it knew in life
- **Challenge** 14

## Traits

***Fear Aura.*** Any hostile creature that starts its turn within 20 feet of the vorvolaka must succeed on a DC 18 Wisdom saving throw or have [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened) condition until the start of the creature's next turn. If a creature's saving throw is successful, they're immune to the vorvolaka's Fear Aura for the next 24 hours. This ability does not function if the vorvolaka is [unconscious](2-Mechanics/CLI/rules/conditions.md#Unconscious).

***Magic Resistance.*** The vorvolaka has advantage on saving throws against spells and other magical effects.

***Regeneration.*** The vorvolaka regains 15 hit points at the start of its turn if it has at least 1 hit point. If the vorvolaka takes radiant damage, this trait doesn't function at the start of the vorvolaka's next turn.

## Actions

***Multiattack.*** The vorvolaka makes two Talon attacks. It can replace one of the attacks with Rend Armor (if available).

***Talon.*** *Melee Weapon Attack:* `dice:1d20+9|noform|text(+9)` to hit, reach 5 ft., one target. *Hit:* `dice:4d8+4|noform|avg|text(22)` (`4d8 + 4`) piercing damage plus `dice:4d6|noform|avg|text(14)` (`4d6`) necrotic damage.

***Rend Armor (Recharge 4-6).*** The vorvolaka makes a Talon attack against a creature. On a hit, the creature's AC is reduced by 2 for 1 minute. Creatures not wearing armor are immune to this effect, and the total reduction can't bring a creature below an AC of 10.
```
^statblock