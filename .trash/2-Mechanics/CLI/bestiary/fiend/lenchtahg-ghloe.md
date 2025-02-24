---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/ghloe
- monster/cr/5
- monster/size/medium
- monster/type/fiend
aliases: ["Lenchtahg"]
---
# Lenchtahg
*Source: Grim Hollow: Lairs of Etharis p. 51*  

> [!quote]  
> 
> The smoky, fiery form hisses and shrieks in a cacophony of anger and confusion. There's something almost holy in the sound.

## Salvage

The severed head of a lenchtahg is a potent magic object. To the right buyer—a necromancer, a daemon cultist, an evil alchemist, and the like—a lenchtahg head is worth 750 gp. The servants of the Arch Daemon Malikir guard the secrets of binding a lenchtahg, but hags and other wicked creatures with magical skills possess knowledge to convert a lenchtahg head into a construct with similar unholy power.

## Lore

- **DC 10 Intelligence ([Religion](2-Mechanics/CLI/rules/skills.md#Religion)).** Radiant damage heals a lenchtahg, which still has the flesh of a Seraph.  
- **DC 15 Intelligence ([Religion](2-Mechanics/CLI/rules/skills.md#Religion)).** Dowsing a Lenchtahg with a lot of water or any holy water can temporarily weaken it.  
- **DC 20 Intelligence ([Arcana](2-Mechanics/CLI/rules/skills.md#Arcana)).** The lenchtahg's head must be consecrated in a holy ceremony or otherwise rid of its evil to avoid the lenchtahg's rejuvenation. But those with the right knowledge can use the head to craft a magical servitor.  

> [!note] GM Advice
> 
> Those who use lenchtahg as troops in battle will use radiant magic to damage foes while at the same time healing the lenchtahg. This greatly heightens the strength of these monsters.
^gm-advice

## Statblock

```ad-statblock
title: Lenchtahg
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/GHLoE/Lenchtahg.webp#token)
*Medium fiend, Neutral Evil*

- **Armor Class** 15 (natural armor)
- **Hit Points** 110 (`13d8 + 52`)
- **Speed** 40 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|18 (+4)|11 (+0)|18 (+4)|10 (+0)|11 (+0)|13 (+1)|

- **Proficiency Bonus** +3
- **Saving Throws** ⏤
- **Skills** Perception +3
- **Senses** darkvision 120 ft., passive Perception 13
- **Damage Resistances** bludgeoning, piercing, slashing from nonmagical attacks
- **Damage Immunities** fire, poison, radiant
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** Abyssal, Celestial, Infernal
- **Challenge** 5

## Traits

***Berserk.*** Whenever the lenchtahg starts its turn with 54 hit points or fewer, roll a `dice:d6|noform|avg` (`d6`). On a 1, the lenchtahg recalls its former life and current agony, and it goes berserk. On each of its turns while berserk, the lenchtahg attacks the nearest creature it can see. It treats all creatures as enemies and makes any opportunity attack it can. Also, it has advantage on attack rolls, but all attack rolls against it have advantage. If no creature is near enough to move to and attack, the lenchtahg moves as far as it can toward the closest creature.

Once the lenchtahg goes berserk, it remains so until destroyed or it has more than 54 hit points. Also, a fiend can calm the lenchtahg. The lenchtahg must be able to understand the fiend, who must take an action to make a DC 15 Charisma ([Persuasion](2-Mechanics/CLI/rules/skills.md#Persuasion)) check. If the check succeeds, the lenchtahg ceases being berserk.

***Magic Resistance.*** The lenchtahg has advantage on saving throws against spells and other magical effects.

***Magic Weapons.*** The lenchtahg's weapon attacks are magical.

***Radiant Absorption.*** Whenever the lenchtahg is subjected to radiant damage from a source other than a lenchtahg, it takes no damage and instead regains hit points equal to half the radiant damage dealt to it.

***Rejuvenation.*** If the lenchtahg's head survives its demise, the head must be doused in holy water and ritually consecrated in a 1-hour ceremony or be the target of a [dispel evil and good](2-Mechanics/CLI/spells/dispel-evil-and-good.md) spell. If it isn't, then the lenchtahg reappears in 6 days, emerging from a fiery explosion in a 20-foot-radius sphere centered on the head. Creatures in that area must make a DC 15 Dexterity saving throw, taking 28 `dice:8d6|noform|avg` (`8d6`) damage on a failed saving throw, or half as much damage on a successful one. The head can't rejuvenate in a holy [hallow](2-Mechanics/CLI/spells/hallow.md) spell's area.

***Water Aversion.*** If drenched in 5 gallons or more of water, or any amount of holy water, the lenchtahg has disadvantage on attack rolls and ability checks until the end of its next turn.

## Actions

***Multiattack.*** The lenchtahg makes two claw attacks, makes one claw attack and uses radiant gaze once, or uses radiant gaze twice.

***Claw.*** *Melee Weapon Attack:* `dice:1d20+7|noform|text(+7)` to hit, reach 5 ft., one target. *Hit:* `dice:2d4+4|noform|avg|text(9)` (`2d4 + 4`) slashing damage and `dice:2d8|noform|avg|text(9)` (`2d8`) fire damage.

***Radiant Gaze.*** The lenchtahg targets one creature it can see within 60 feet of it with burning radiance. The target gains no benefit from cover and must succeed on a DC 15 Dexterity saving throw or take `dice:3d8|noform|avg|text(13)` (`3d8`) radiant damage.
```
^statblock