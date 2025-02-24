---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/4
- monster/environment/underdark
- monster/size/tiny
- monster/type/humanoid/derro
aliases: ["Derro Fetal Savant"]
---
# Derro Fetal Savant
*Source: Tome of Beasts 1 (2023 Edition) p. 88*  

*This creature resembles a blue-skinned dwarven infant, no older than a year. Its limbs flail, its head lolls with an obvious lack of coordination, and it screams incessantly.*

Of the madness and insanity that resonates so strongly in derro society, perhaps none is as twisted as the derro fetal savant, born insane by the blessing of their eldritch masters and destined to lead their people further into madness.

## Soul Swapping

Only the rarest of derro are born with the ability to exchange souls with other creatures, and the babbling infants are treated with maddened reverence. Oddly, this unique power causes an extreme sensitivity to bright light.

## Carried into Battle

Placed in small, pillowed cages and borne aloft on hooked staves, the wild-eyed, magically gifted newborns are used to sow confusion among enemy ranks. Though typically carried into battle, fetal savants can make their cages float, freeing their carriers to better defend them when necessary.

## Statblock

```ad-statblock
title: Derro Fetal Savant
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Derro%20Fetal%20Savant.webp#token)
*Tiny humanoid (derro), Chaotic Evil*

- **Armor Class** 11
- **Hit Points** 32 (`13d4`)
- **Speed** 10 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
| 5 (-3)|12 (+1)|10 (+0)| 8 (-1)|12 (+1)|20 (+5)|

- **Proficiency Bonus** +2
- **Saving Throws** Wisdom +3, Charisma +7
- **Skills** Perception +3
- **Senses** darkvision 60 ft., passive Perception 13
- **Damage Immunities** psychic
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened)
- **Languages** Dwarvish, telepathy 60 ft.
- **Challenge** 4

## Traits

***Enchanted Cage.*** The savant is immune to damage and can't be the target of spells or effects as long as its cage exists. The cage has a flying speed of 30 feet while the savant is inside of it, moving at the mental command of the savant. When the cage is destroyed, the savant floats gently to the ground. The cage has AC 19, 75 hp, and is immune to piercing, poison, and psychic damage. A non-derro that touches the cage or hits it with a melee weapon attack while within 5 feet of it must succeed on a DC 15 Wisdom saving throw or take `dice:2d6|noform|avg|text(7)` (`2d6`) psychic damage and be [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened) until the end of its next turn. The cage disintegrates if exposed to sunlight for 1 hour.

***Maddening Babble.*** The savant constantly babbles eldritch nonsense while it can see any non-derro creatures and isn't [incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated). Each non-derro creature that starts its turn within 20 feet of the savant and can hear the babbling must succeed on a DC 15 Wisdom saving throw or be [incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated) until the start of its next turn.

***Sunlight Hypersensitivity.*** The savant takes 20 radiant damage when it starts its turn outside the cage and in sunlight.

## Actions

***Multiattack.*** The fetal savant makes two Psychic Burst attacks.

***Psychic Burst.*** *Melee or Ranged Spell Attack:* `dice:1d20+7|noform|text(+7)` to hit, reach 5 ft. or range 60 ft., one target. *Hit:* `dice:2d8+5|noform|avg|text(14)` (`2d8 + 5`) psychic damage.

***Soul Exchange (Recharge 6).*** The savant exchanges its soul with one Humanoid it can see within 20 feet of it. Its body becomes [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed), the target's soul inhabits the savant's [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed) body, and the savant inhabits the target's body, taking full control of it. The savant retains its alignment, its Intelligence, Wisdom, and Charisma scores, its Psychic Burst action, and its immunity to being [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed) and [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened). It otherwise uses the target's statistics, but doesn't gain access to the target's knowledge, class features, or proficiencies.

The exchange lasts until the target's body or the savant's body is reduced to 0 hp, the savant ends it as a bonus action, or the savant is forced out by an effect like the [dispel evil and good](2-Mechanics/CLI/spells/dispel-evil-and-good.md) spell. When the exchange ends, the target returns to its body, regaining control, and the savant's soul returns to its body, which is no longer [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed). The target is immune to this savant's Soul Exchange for 24 hours after succeeding on the saving throw or after the exchange ends.
```
^statblock

## Environment

underdark