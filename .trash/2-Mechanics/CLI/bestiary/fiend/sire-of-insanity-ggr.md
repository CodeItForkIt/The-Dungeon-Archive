---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/ggr
- monster/cr/12
- monster/size/huge
- monster/type/fiend/demon
aliases: ["Sire of Insanity"]
---
# Sire of Insanity
*Source: Guildmasters' Guide to Ravnica p. 197*  

Rakdos nightclubs, where visitors can indulge any dark desire and revel in sadistic spectacle, are the favored haunts of the demons known as sires of insanity. Lurking in an underground vault beneath a Rakdos operation, a sire of insanity feasts on the violence, torment, and depravity unfolding above. Occasionally, cultists bring would-be recruits to the demon's presence, and—true to its name—the sire of insanity breaks the new cultist's mind.

A sire of insanity is a bloated demon resembling a bipedal lizard. It stands some thirty feet tall and weighs many thousands of pounds, so it tends to keep hidden away in its subterranean lair, working its evil from the shadows.

## Demons

Just as angels are incarnations of the ideals of justice, demons embody depraved impulses: selfishness, cruelty, hatred, greed, and lust for power. Demons are strongly associated with the Cult of Rakdos; in fact, the demons of Ravnica might have been created by Rakdos in the same way that angels were created by the Boros Legion's founder. As a demon lord who has chosen to live in Ravnica, Rakdos claims authority over all the demons of this world-even if some of them, ambitious and headstrong as demons are, rebel against his authority.

Demons are agents of destruction that work their acts of terror in plain sight under the auspices of the Cult of Rakdos. They exhibit their cruelty in dramatic performances that leave the audience members blood-soaked but ecstatic. They incite mob riots that raze entire city blocks. The only thing demons fear is Rakdos himself, who doesn't tolerate rivals and hates to be upstaged.

### Demonic "Devils"

The creatures called "devils" in Ravnica are minor demons akin to [quasits](2-Mechanics/CLI/bestiary/fiend/quasit.md). While the larger demons embody evil qualities such as blood lust and torment, these lesser demons reflect the whimsical and chaotic side of Rakdos and his cult. Their mischievous antics cause disorder and destruction out of proportion to the demons' small size.

### Diabolic Demons

Many of the demons of Ravnica are monstrous, winged creatures of human-like form. They are best represented by the statistics of the [nalfeshnee](2-Mechanics/CLI/bestiary/fiend/nalfeshnee.md), the [shadow demon](2-Mechanics/CLI/bestiary/fiend/shadow-demon.md), or the [vrock](2-Mechanics/CLI/bestiary/fiend/vrock.md) in the Monster Manual. Demons associated with the Cult of Rakdos often have fiery attacks that make them similar to barbed devils or horned devils, except that they are demons. (They are chaotic evil, they speak Abyssal and not Infernal, and they lack Devil's Sight.)

## Statblock

```ad-statblock
title: Sire of Insanity
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/GGR/Sire%20of%20Insanity.webp#token)
*Huge fiend (demon), Chaotic Evil*

- **Armor Class** 17 (natural armor)
- **Hit Points** 157 (`15d12 + 60`)
- **Speed** 40 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|23 (+6)| 6 (-2)|19 (+4)|14 (+2)|19 (+4)|22 (+6)|

- **Proficiency Bonus** +4
- **Saving Throws** Constitution +8, Intelligence +6, Wisdom +8, Charisma +10
- **Skills** Deception +10, Intimidation +10
- **Senses** truesight 120 ft., passive Perception 14
- **Damage Resistances** cold; fire; lightning; bludgeoning, piercing, slashing from nonmagical attacks
- **Damage Immunities** poison
- **Condition Immunities** [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** Abyssal, Common, telepathy 120 ft.
- **Challenge** 12

## Traits

***Aura of Mind Erosion.*** Any creature that starts its turn within 30 feet of the sire must make a DC 18 Wisdom saving throw. On a successful save, the creature is immune to this aura for the next 24 hours. On a failed save, the creature has disadvantage for 1 minute on Wisdom and Charisma checks and on Wisdom and Charisma saves. At the start of each of its turns, the sire can suppress this aura until the start of its next turn.

***Magic Resistance.*** The sire has advantage on saving throws against spells and other magical effects.

***Innate Spellcasting.*** The sire's innate spellcasting ability is Charisma (spell save DC 18, `dice:1d20+10|noform|text(+10)` to hit with spell attacks). The sire can innately cast the following spells, requiring no material components:

**At will**: [clairvoyance](2-Mechanics/CLI/spells/clairvoyance.md), [crown of madness](2-Mechanics/CLI/spells/crown-of-madness.md), [major image](2-Mechanics/CLI/spells/major-image.md), [suggestion](2-Mechanics/CLI/spells/suggestion.md)

**1/day each**: [confusion](2-Mechanics/CLI/spells/confusion.md), [mass suggestion](2-Mechanics/CLI/spells/mass-suggestion.md)

## Actions

***Multiattack.*** The sire makes two attacks: one with its bite and one with its claws.

***Bite.*** *Melee Weapon Attack:* `dice:1d20+10|noform|text(+10)` to hit, reach 5 ft., one creature. *Hit:* `dice:3d12+6|noform|avg|text(25)` (`3d12 + 6`) piercing damage plus `dice:3d10|noform|avg|text(16)` (`3d10`) psychic damage.

***Claws.*** *Melee Weapon Attack:* `dice:1d20+10|noform|text(+10)` to hit, reach 10 ft., one target. *Hit:* `dice:1d8+6|noform|avg|text(10)` (`1d8 + 6`) slashing damage plus `dice:2d8|noform|avg|text(9)` (`2d8`) psychic damage.
```
^statblock