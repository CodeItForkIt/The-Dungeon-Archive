---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/psz
- monster/cr/16
- monster/size/large
- monster/type/celestial
aliases: ["Linvala"]
---
# Linvala
*Source: Plane Shift: Zendikar p. 21*  

The angels of Zendikar are living manifestations of white mana, and they embody its inherent tendencies toward morality and order. Peace and harmony are their goals, though they are more concerned with reestablishing the natural order of the plane than with interfering in disputes between the lowly mortal races. Angels appear similar to female humans possessing two, four, or six feathered wings. Their eyes glow with inner light, and glowing golden rings surround their heads—usually positioned to cover their eyes.

Zendikar's people consider the angels to be aloof but benevolent. Their resistance to the Eldrazi broods in the ancient past is vaguely remembered in the myths of the humans, kor, and merfolk. Humans in particular venerate angels as divine protectors because of those myths.

You can represent most angels in Zendikar using the [deva](2-Mechanics/CLI/bestiary/celestial/deva.md) in the Monster Manual. For unique or more powerful angels, you can use the [planetar](2-Mechanics/CLI/bestiary/celestial/planetar.md) or [solar](2-Mechanics/CLI/bestiary/celestial/solar.md) instead. Perhaps [Linvala](2-Mechanics/CLI/bestiary/npc/linvala-psz.md) is a [planetar](2-Mechanics/CLI/bestiary/celestial/planetar.md) and [Iona](2-Mechanics/CLI/bestiary/npc/iona-psz.md) is a [solar](2-Mechanics/CLI/bestiary/celestial/solar.md).

```ad-statblock
title: Linvala
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/PSZ/Linvala.webp#token)
*Large celestial, Lawful Good*

- **Armor Class** 19 (natural armor)
- **Hit Points** 200 (`16d10 + 112`)
- **Speed** 40 ft., fly 120 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|24 (+7)|20 (+5)|24 (+7)|19 (+4)|22 (+6)|25 (+7)|

- **Proficiency Bonus** +5
- **Saving Throws** Constitution +12, Wisdom +11, Charisma +12
- **Skills** Perception +11
- **Senses** truesight 120 ft., passive Perception 21
- **Damage Resistances** radiant; bludgeoning, piercing, slashing from nonmagical attacks
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened)
- **Languages** all, telepathy 120 ft.
- **Challenge** 16

## Traits

***Angelic Weapons.*** Linvala's weapon attacks are magical. When Linvala hits with any weapon, the weapon deals an extra `dice:5d8|noform|avg` (`5d8`) radiant damage (included in the attack).

***Divine Awareness.*** Linvala knows if it hears a lie.

***Magic Resistance.*** Linvala has advantage on saving throws against spells and other magical effects.

***Innate Spellcasting.*** Linvala's spellcasting ability is Charisma (spell save DC 20). Linvala can innately cast the following spells, requiring no material components:

**At will**: [detect evil and good](2-Mechanics/CLI/spells/detect-evil-and-good.md), [invisibility](2-Mechanics/CLI/spells/invisibility.md) (self only)

**1/day each**: [commune](2-Mechanics/CLI/spells/commune.md), [control weather](2-Mechanics/CLI/spells/control-weather.md), [insect plague](2-Mechanics/CLI/spells/insect-plague.md)

**3/day each**: [blade barrier](2-Mechanics/CLI/spells/blade-barrier.md), [dispel evil and good](2-Mechanics/CLI/spells/dispel-evil-and-good.md), [flame strike](2-Mechanics/CLI/spells/flame-strike.md), [raise dead](2-Mechanics/CLI/spells/raise-dead.md)

## Actions

***Multiattack.*** Linvala makes two melee attacks.

***Greatsword.*** *Melee Weapon Attack:* `dice:1d20+12|noform|text(+12)` to hit, reach 5 ft., one target. *Hit:* `dice:4d6+7|noform|avg|text(21)` (`4d6 + 7`) slashing damage plus `dice:5d8|noform|avg|text(22)` (`5d8`) radiant damage.

***Healing Touch (4/Day).*** Linvala touches another creature. The target magically regains `dice:6d8+3|noform|avg|text(30)` (`6d8 + 3`) hit points and is freed from any curse, disease, poison, blindness, or deafness.
```
^statblock