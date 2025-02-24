---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/7
- monster/environment/farmland
- monster/environment/urban
- monster/size/medium
- monster/type/undead
aliases: ["Dissimortuum"]
---
# Dissimortuum
*Source: Tome of Beasts 1 (2023 Edition) p. 106*  

*This twisted humanoid has gray flesh and black claws that drip blood. A bone mask is bound to its head by strips of putrid flesh, and a third arm hangs from the right side of the creature's body, its hand clutching a large sack stained with blood.*

## Plague Bringers

Dissimortuum are undead monstrosities constructed by necromancers to spread the undead plague, slowly but surely. These creatures are rare but tenacious. A dissimortuum obeys orders from the necromancer whose magic created it. When a dissimortuum kills, it collects body parts from its victims and keeps them in a sack that it carries with its third arm at all times. The monster sets down its sack of trophies only when pressed in combat, to make the most of its extra limb.

## Constructing Dissimortuum

Even when not following instructions, a dissimortuum seeks to create more of its own kind. The creature wanders graveyards, battlefields, and slums, searching for the gruesome components it needs to construct a mask and body for its undead offspring. The process is slow, taking up to a month to make a single mask, but a dissimortuum has plenty of time. The new creation is independent and not under the control of its maker or of the necromancer that might have created its maker.

> [!note] Dissimortuum's Cursed Mask
> 
> The dissimortuum's mask is nigh indestructible. When the creature is destroyed, its mask usually survives and breaks free. On its own, the object emits a faint magical aura with mixed enchantment and necromantic properties. It is a tempting souvenir, but any humanoid or giant foolish enough to don the mask is immediately wracked by pain and takes `dice:2d6|noform|avg|text(7)` (`2d6`) necrotic damage. The creature must succeed on a DC 15 Wisdom saving throw or become dominated by the mask. The domination arrives slowly. The creature acts normally for a day or two, but then the creature notices periods of time that cannot be accounted for. During these unremembered times, the creature gathers the grisly components needed to build a new body for the dissimortuum. This process takes a week, after which the creature is freed from domination as the dissimortuum arises anew and dons its mask once more.
^dissimortuums-cursed-mask

## Statblock

```ad-statblock
title: Dissimortuum
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Dissimortuum.webp#token)
*Medium undead, Chaotic Evil*

- **Armor Class** 15 (natural armor)
- **Hit Points** 112 (`15d8 + 45`)
- **Speed** 30 ft., climb 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|14 (+2)|10 (+0)|16 (+3)| 8 (-1)|11 (+0)|18 (+4)|

- **Proficiency Bonus** +3
- **Saving Throws** Constitution +6
- **Skills** ⏤
- **Senses** darkvision 60 ft., passive Perception 10
- **Damage Resistances** bludgeoning, piercing, slashing from nonmagical attacks
- **Damage Immunities** necrotic, poison
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** the languages of its creator
- **Challenge** 7

## Traits

***Spider Climb.*** The dissimortuum can climb difficult surfaces, including upside down on ceilings, without needing to make an ability check.

***Undead Nature.*** The dissimortuum doesn't require air, food, drink, or sleep.

## Actions

***Multiattack.*** The dissimortuum makes three Claw attacks. It can replace one Claw attack with a use of Terrifying Mask.

***Claw.*** *Melee Weapon Attack:* `dice:1d20+5|noform|text(+5)` to hit, reach 5 ft., one target. *Hit:* `dice:3d8+2|noform|avg|text(15)` (`3d8 + 2`) slashing damage.

***Terrifying Mask.*** Each non-Undead creature within 60 feet of the dissimortuum that can see it must succeed on a DC 15 Wisdom saving throw or be [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened) for 1 minute. A [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened) creature can repeat the saving throw, ending the effect on itself on a success. If a target's saving throw is successful or the effect ends for it, the target becomes immune to the dissimortuum's Terrifying Mask for the next 24 hours.
```
^statblock

## Environment

farmland, urban