---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/5
- monster/environment/farmland
- monster/environment/urban
- monster/size/medium
- monster/type/fiend/shapechanger
aliases: ["Bouda"]
---
# Bouda
*Source: Tome of Beasts 1 (2023 Edition) p. 42*  

*A hulking, hyena-faced humanoid with a heavily scarred, oversized muzzle steps forward, clouds of gnats and fleas roiling around it.*

## Glowing Eyes and Teeth

Bouda are peopleeaters and despoilers of purity and family. Resembling oversized gnolls, the web of scars along their muzzles provides evidence of their gluttonous eating habits. Forever leering, their teeth glow as yellow as their eyes.

## Fly-Bedecked Shapechangers

Bouda lurk on society's fringes, shapechanging to blend in with mortals. They seek out happy families, consuming the most vulnerable members in the night and leaving gruesome trophies behind. They may mark a victim nights before attacking to terrify the helpless family.

## Gluttons

Bouda have a weakness: they are incorrigible gluttons. When presented with a fresh corpse, even in combat, they attempt to gorge on it or at least defile it for later consumption. Bouda are vindictive, seeking revenge on anything that drives them from a kill.

## Statblock

```ad-statblock
title: Bouda
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Bouda.webp#token)
*Medium fiend (shapechanger), Neutral Evil*

- **Armor Class** 15 (natural armor)
- **Hit Points** 93 (`11d8 + 44`)
- **Speed** 30 ft. (50 ft. in hyena form)

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|19 (+4)|14 (+2)|18 (+4)|10 (+0)|12 (+1)|15 (+2)|

- **Proficiency Bonus** +3
- **Saving Throws** Dexterity +5, Constitution +7, Wisdom +4, Charisma +5
- **Skills** Athletics +7, Deception +5, Intimidation +5, Perception +4, Stealth +5
- **Senses** magic. the bouda senses magic within 30 feet of it at will. this trait otherwise works like the detect magic spell but isn't itself magical., passive Perception 14
- **Damage Resistances** acid; lightning; bludgeoning, piercing, slashing from nonmagical attacks that aren't silvered
- **Damage Immunities** fire, poison
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** Celestial, Common, Infernal, telepathy 100 ft.
- **Challenge** 5

## Actions

***Multiattack.*** The bouda makes one Bite attack and one Mephitic Claw attack.

***Bite (Giant Hyena or Hybrid Form Only).*** *Melee Weapon Attack:* `dice:1d20+7|noform|text(+7)` to hit, reach 5 ft., one target. *Hit:* `dice:2d8+4|noform|avg|text(13)` (`2d8 + 4`) piercing damage plus `dice:3d6|noform|avg|text(10)` (`3d6`) poison damage.

***Mephitic Claw (Giant Hyena or Hybrid Form Only).*** *Melee Weapon Attack:* `dice:1d20+7|noform|text(+7)` to hit, reach 5 ft., one target. *Hit:* `dice:2d6+4|noform|avg|text(11)` (`2d6 + 4`) slashing damage, and the target must succeed on a DC 15 Constitution saving throw or become [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) until the end of its next turn.

***Ravenous Gorge.*** The bouda consumes the organs of a corpse within 5 feet of it that is less than 7 days old. It gains temporary hp equal to twice the dead creature's CR for 1 hour. The bouda can't use Ravenous Gorge on a corpse if it or another bouda has already use Ravenous Gorge on the corpse.

## Bonus Actions

***Change Shape.*** The bouda transforms into a human, a hyena, or back into its true form, which is a hyena-human hybrid. Its statistics, other than its speed, are the same in each form. Any equipment it is wearing or carrying isn't transformed. It reverts to its true form if it dies, then crumbles to dust moments later.

***Defiling Smear (1/Day).*** The bouda secretes a disgusting whitish-yellow substance with the viscosity of tar and smears the substance on an object, unoccupied space, or creature within 5 feet of it. An unwilling creature must succeed on a DC 15 Dexterity saving throw to avoid the smear. Each creature, other than a bouda or hyena, that starts its turn within 30 feet of the smeared target must succeed on a DC 15 Constitution saving throw or be [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) for 1 minute. If a creature's saving throw is successful or the effect ends for it, the creature is immune to that source of Defiling Smear for the next 24 hours. The stench of a smear remains potent for 7 days or until removed by the [greater restoration](2-Mechanics/CLI/spells/greater-restoration.md) spell or similar magic.
```
^statblock

## Environment

farmland, urban