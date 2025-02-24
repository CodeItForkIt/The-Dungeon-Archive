---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/14
- monster/environment/farmland
- monster/environment/urban
- monster/size/large
- monster/type/fiend
aliases: ["Cambium"]
---
# Cambium
*Source: Tome of Beasts 1 (2023 Edition) p. 49*  

*Unfolding impossibly from beneath voluminous robes, this creature's pockmarked, spindly arms end in clusters of narrow spikes. Its long, hollow, needle-like fingers and its many-jointed arms move with surprising speed and strength for such an emaciated creature.*

## Hunched and Robed

The cambium skulks through mortal society, hunched and contorted, concealing its nine-foot height and its supernumerary arms.

## Devours Bodily Humors

The source of a cambium's interest lies in every mortal body: the four humors. It drains these from victims in precise amounts, sometimes to fix its own imbalances, sometimes to concoct serums to sell in hellish markets. Its victims are left in a desperate state, eager for a corrective fix and willing to obey the cambium's every whim as servants and toadies.

## Abandons Victims

After a sufficient crop has been harvested, the cambium abandons these addicts to die slowly from violent withdrawals, and allows the local population to lie fallow for a decade or so.

## Statblock

```ad-statblock
title: Cambium
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Cambium.webp#token)
*Large fiend, Neutral Evil*

- **Armor Class** 19 (natural armor)
- **Hit Points** 264 (`23d10 + 138`)
- **Speed** 40 ft., fly 30 ft. (hover)

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|21 (+5)|16 (+3)|23 (+6)|17 (+3)|16 (+3)|18 (+4)|

- **Proficiency Bonus** +5
- **Saving Throws** Dexterity +8, Constitution +11, Intelligence +8, Wisdom +8, Charisma +9
- **Skills** Arcana +8, Deception +9, Insight +8, Medicine +8, Perception +8, Stealth +8
- **Senses** darkvision 60 ft., passive Perception 18
- **Damage Immunities** poison
- **Condition Immunities** [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned), [prone](2-Mechanics/CLI/rules/conditions.md#Prone)
- **Languages** Common, Draconic, Infernal
- **Challenge** 14

***Spellcasting.*** The cambium casts one of the following spells, requiring no material components and using Charisma as the spellcasting ability (spell save DC 17):

**At will**: [alter self](2-Mechanics/CLI/spells/alter-self.md), [detect thoughts](2-Mechanics/CLI/spells/detect-thoughts.md), [spare the dying](2-Mechanics/CLI/spells/spare-the-dying.md)

**1/day**: [plane shift](2-Mechanics/CLI/spells/plane-shift.md) (self only)

**3/day each**: [hold person](2-Mechanics/CLI/spells/hold-person.md), [protection from poison](2-Mechanics/CLI/spells/protection-from-poison.md), [heal](2-Mechanics/CLI/spells/heal.md)

## Actions

***Multiattack.*** The cambium makes four Needle Fingers or Poison Ray attacks. It can replace two attacks with a use of Spellcasting.

***Needle Fingers.*** *Melee Weapon Attack:* `dice:1d20+10|noform|text(+10)` to hit, reach 10 ft., one target. *Hit:* `dice:3d10+5|noform|avg|text(21)` (`3d10 + 5`) piercing damage.

***Poison Ray.*** *Ranged Spell Attack:* `dice:1d20+9|noform|text(+9)` to hit, range 60 ft., one target. *Hit:* `dice:4d8+4|noform|avg|text(22)` (`4d8 + 4`) poison damage, and the target must succeed on a DC 17 Constitution saving throw or become [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) until the end of its next turn.

## Bonus Actions

***Damage Ability.*** The cambium twists the bodily humors of a creature within 30 feet of it that isn't a Construct or Undead and that it hit with Needle Fingers in the past minute. The target must succeed on a DC 17 Constitution saving throw or its Strength, Dexterity, or Constitution score (the cambium's choice) is reduced by `dice:1d4|noform|avg` (`1d4`). The target falls [unconscious](2-Mechanics/CLI/rules/conditions.md#Unconscious) if this reduces an ability score to 0. This reduction lasts until the target finishes a long rest.

***Imbalance Humors.*** If the cambium has hit a creature that isn't a Construct or Undead with Needle Fingers in the past minute, it can cause a surge in one of the target's bodily humors, causing an imbalance. The target must succeed on a DC 17 Constitution saving throw or suffer one of the following effects of the cambium's choice. Unless noted otherwise, the target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

- **Sanguine Flux.** The target can't regain hp—naturally or magically—until after it finishes a long rest.  
- **Choleric Flux.** The target becomes confused for 1 minute. This effect works as if the target failed a saving throw against the [confusion](2-Mechanics/CLI/spells/confusion.md) spell, except the cambium doesn't have to maintain [concentration](2-Mechanics/CLI/rules/conditions.md#Concentration).  
- **Melancholic Flux.** The target is [incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated) and its speed is halved for 1 minute.  
- **Phlegmatic Flux.** The target is [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) for 1 minute.  
```
^statblock

## Environment

farmland, urban