---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/10
- monster/environment/planar
- monster/environment/urban
- monster/size/medium
- monster/type/fey
aliases: ["Fear Smith"]
---
# Fear Smith
*Source: Tome of Beasts 1 (2023 Edition) p. 169*  

*This well-dressed figure appears elven, save for its featureless face and taloned hands.*

Known as a fiarsídhe among themselves, fear smiths are servants of shadow fey courts and other, similar dark fey courts. While its mouth is closed, a fear smith's face is featureless save for rows of deep wrinkles. Opening the large mouth in the center of its face reveals long needlelike teeth surrounding a single, massive eye.

## Icy-Cold Eyes

Fear smiths often serve as torturers or are dispatched to demoralize the court's enemies. Their stare stops enemies cold, making it easy for heavily-armed warriors to trap and finish a foe.

## Devour Fear

Fear smiths feed off strong emotions, and their favorite meal is terror. The fey prefer prolonging the death of victims, and, when free to indulge, a fear smith stalks its victim for days before attacking, hinting at its presence to build dread.

## Hoods and Masks

Fear smiths favor fine clothing and high fashion, donning hooded cloaks or masks when discretion is required. Eerily well-mannered and respectful, fear smiths enjoy feigning civility and playing the part of nobility, speaking genteelly but with a thick, unidentifiable accent.

## Statblock

```ad-statblock
title: Fear Smith
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Fear%20Smith.webp#token)
*Medium fey, Chaotic Neutral*

- **Armor Class** 17 (natural armor)
- **Hit Points** 149 (`23d8 + 46`)
- **Speed** 40 ft., climb 15 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|11 (+0)|17 (+3)|14 (+2)|11 (+0)|15 (+2)|18 (+4)|

- **Proficiency Bonus** +4
- **Saving Throws** Wisdom +6
- **Skills** Intimidation +8, Stealth +7
- **Senses** blindsight 30 ft., passive Perception 12
- **Damage Resistances** bludgeoning, piercing, slashing from attacks not made with cold iron weapons
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened)
- **Languages** Common, Elvish, Sylvan
- **Challenge** 10

## Traits

***Distortion Gaze.*** Those who meet the gaze of the fear smith experience the world seeming to twist at unnatural angles beneath their feet. When a creature that can see the fear smith's eye starts its turn within 30 feet of the fear smith, the fear smith can force the creature to make a DC 16 Wisdom saving throw if the fear smith isn't [incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated) and can see the creature. On a failed save, the creature is disoriented until the start of its next turn. While disoriented, a creature can't take the Dash or Disengage action, and when it moves for the first time on its turn, it must succeed on a DC 16 Dexterity saving throw or fall [prone](2-Mechanics/CLI/rules/conditions.md#Prone).

Unless surprised, a creature can avert its eyes to avoid the saving throw at the start of its turn. If the creature does so, it can't see the fear smith until the start of its next turn, when it can avert its eyes again. If the creature looks at the fear smith in the meantime, it must immediately make the save.

***Hidden Eye.*** The fear smith has advantage on saving throws against being [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded).

***Magic Resistance.*** The fear smith has advantage on saving throws against spells and other magical effects.

***Spellcasting.*** The fear smith casts one of the following spells, requiring no verbal or material components and using Charisma as the spellcasting ability (spell save DC 16):

**At will**: [detect thoughts](2-Mechanics/CLI/spells/detect-thoughts.md), [fear](2-Mechanics/CLI/spells/fear.md)

**2/day each**: [charm person](2-Mechanics/CLI/spells/charm-person.md), [command](2-Mechanics/CLI/spells/command.md)

## Actions

***Multiattack.*** The fear smith makes three Claw attacks. It can replace one attack with a use of Heart-Stopping Stare.

***Claw.*** *Melee Weapon Attack:* `dice:1d20+7|noform|text(+7)` to hit, reach 5 ft., one target. *Hit:* `dice:2d8+3|noform|avg|text(12)` (`2d8 + 3`) slashing damage plus `dice:2d8|noform|avg|text(9)` (`2d8`) psychic damage. If the target is disoriented by Distortion Gaze, the fear smith regains hp equal to the amount of psychic damage dealt.

***Heart-Stopping Stare.*** The fear smith terrifies a creature within 30 feet of it with a look. The target must succeed on a DC 16 Wisdom saving throw or take `dice:3d8|noform|avg|text(13)` (`3d8`) psychic damage and be [stunned](2-Mechanics/CLI/rules/conditions.md#Stunned) until the end of its next turn. The fear smith regains hp equal to the psychic damage dealt.
```
^statblock

## Environment

planar, urban