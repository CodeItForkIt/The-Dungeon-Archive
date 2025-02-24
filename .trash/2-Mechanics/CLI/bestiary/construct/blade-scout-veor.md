---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/veor
- monster/cr/7
- monster/size/medium
- monster/type/construct/warforged
aliases: ["Blade Scout"]
---
# Blade Scout
*Source: Vecna: Eve of Ruin p. 209*  

Blade scouts are responsible for exploring and charting Mournland regions not yet claimed by the Lord of Blades' legions.

## Blades of Eberron

In the aftermath of Eberron's Last War, a warforged called the Lord of Blades rose to fill the power vacuum left in the devastated Mournland. The Lord of Blades' followers, known as blades, formed a cult of personality that deifies the Lord of Blades and preaches a bloody, jingoistic doctrine of warforged superiority. The primary tenet of the blades is that non-warforged on the continent of Khorvaire must be slaughtered.

## Statblock

```ad-statblock
title: Blade Scout
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/VEoR/Blade%20Scout.webp#token)
*Medium construct (warforged), typically  Lawful Evil*

- **Armor Class** 18 (natural armor)
- **Hit Points** 105 (`14d8 + 42`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|14 (+2)|20 (+5)|16 (+3)|10 (+0)|19 (+4)|10 (+0)|

- **Proficiency Bonus** +3
- **Saving Throws** Dexterity +8, Wisdom +7
- **Skills** Acrobatics +8, Perception +7, Stealth +8
- **Senses** passive Perception 17
- **Damage Resistances** poison
- **Condition Immunities** [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** Common
- **Challenge** 7

## Traits

***Pack Tactics.*** The scout has advantage on an attack roll against a creature if at least one of the scout's allies is within 5 feet of the creature and the ally doesn't have the [incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated) condition.

## Actions

***Multiattack.*** The scout makes three Armblade or Bolt Launcher attacks. It can replace one of the attacks with a use of Snare Trap.

***Armblade.*** *Melee Weapon Attack:* `dice:1d20+8|noform|text(+8)` to hit, reach 5 ft., one target. *Hit:* `dice:2d6+5|noform|avg|text(12)` (`2d6 + 5`) slashing damage.

***Bolt Launcher.*** *Ranged Weapon Attack:* `dice:1d20+8|noform|text(+8)` to hit, range 80/320 ft., one target. *Hit:* `dice:1d8+5|noform|avg|text(9)` (`1d8 + 5`) piercing damage.

***Snare Trap (1/Day).*** The scout deploys a Tiny mechanical trap on a solid surface within 5 feet of itself. The trap is hidden, requiring a successful DC 17 Intelligence ([Investigation](2-Mechanics/CLI/rules/skills.md#Investigation)) check to find. The trap lasts for 1 minute. Whenever an enemy enters a space within 10 feet of the trap or starts its turn there, it must succeed on a DC 16 Dexterity saving throw or take `dice:6d6|noform|avg|text(21)` (`6d6`) piercing damage and have the [prone](2-Mechanics/CLI/rules/conditions.md#Prone) condition. A creature makes this saving throw only once per turn.

## Bonus Actions

***Dash.*** The scout moves up to its speed without provoking opportunity attacks.
```
^statblock