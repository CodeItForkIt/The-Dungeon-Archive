---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/ftd
- monster/cr/22
- monster/size/gargantuan
- monster/type/dragon/gem
aliases: ["Ancient Sapphire Dragon"]
---
# Ancient Sapphire Dragon
*Source: Fizban's Treasury of Dragons p. 214*  

The thunderous clash of conflict is part of the very nature of sapphire dragons. Militant and territorial, they defend their lairs fiercely, ambushing intruders and plotting assaults against their rivals. The sonic pulse of their breath weapon sows weakness, leaving the victims unable to fight back.

## Luminous Blue

Sapphire dragons' scales and wing membranes show varied shades of blue, ranging from the light tones of a spring sky to the rich, crystalline azure of sapphire gems and compressed glacial ice. In the light, the scales glitter and shine like luminous starbursts. The dragons' psionic nature is evident in the horn and bone structures of their bodies. Their tail barbs and horn tips are all separate pieces, but they float in place, held aloft by psychic energy while the dragons live. These levitating horns and spines shift slightly with the dragons' moods, bobbing in amusement or flaring with anger.

## Art of War

The warlike sapphire dragons devise strategies and ambushes based on their ability to maneuver underground. A sapphire dragon often refrains from striking immediately, preferring to assess intruders first in order to devise the most advantageous approach to dealing with them.

Sapphire dragons watch for signs of Aberrations and other creatures corrupted by the Far Realm. They frequently ally with emerald dragons, drawing on their kin's knowledge of occult phenomena to track the influence of the Far Realm. Armed with that knowledge, sapphire dragons stamp out alien influence before it spreads.

People who dwell or delve deep beneath the earth can easily find themselves at odds with a sapphire dragon if they cross into the dragon's territory. But sapphire dragons sometimes forge peaceful relationships with rock gnomes or deep gnomes, relying on these folk to help protect the territory surrounding their lairs.

## Martial Hoards

Sapphire dragons' favorite prizes are weapons and armor, records of military history and tactics, and magic items that protect against psychic damage or mental intrusion. The centerpiece of a sapphire dragon's hoard is usually a cataloged, orderly collection of war gear, which can contain ancient relics of immense power.

## A Sapphire Dragon's Lair

Sapphire dragons make their homes in extensive cave systems. As they grow older, they make increasingly complex renovations to their lairs, using their inherent magic and natural tunneling abilities to great effect. Eventually, a sapphire dragon's lair is a dizzying honeycomb of hidden passages, deceptively thin walls, and secret chambers that allow the dragon to travel from one end to the other unseen by intruders. The most secure lairs might feature no accessible entrances or exits at all, with the dragon relying on tunneling or shaping stone to come and go.

The challenge rating of a legendary sapphire dragon increases by 1 when it's encountered in its lair.

## Statblock

```ad-statblock
title: Ancient Sapphire Dragon
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/FTD/Ancient%20Sapphire%20Dragon.webp#token)
*Gargantuan dragon (gem), typically  Lawful Neutral*

- **Armor Class** 20 (natural armor)
- **Hit Points** 370 (`20d20 + 160`)
- **Speed** 40 ft., burrow 40 ft., climb 40 ft., fly 80 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|27 (+8)|14 (+2)|27 (+8)|21 (+5)|19 (+4)|20 (+5)|

- **Proficiency Bonus** +7
- **Saving Throws** Dexterity +9, Constitution +15, Wisdom +11, Charisma +12
- **Skills** History +12, Perception +18, Persuasion +19, Stealth +9
- **Senses** blindsight 60 ft., darkvision 120 ft., passive Perception 28
- **Damage Resistances** lightning, thunder
- **Condition Immunities** [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened)
- **Languages** Common, Draconic, telepathy 120 ft.
- **Challenge** 22

## Traits

***Legendary Resistance (3/Day).*** If the dragon fails a saving throw, it can choose to succeed instead.

***Spider Climb.*** The dragon can climb difficult surfaces, including upside down on ceilings, without needing to make an ability check.

***Tunneler.*** The dragon can burrow through solid rock at half its burrowing speed and can leave a 20-foot-diameter tunnel in its wake.

***Spellcasting (Psionics).*** The dragon casts one of the following spells, requiring no spell components and using Intelligence as the spellcasting ability (spell save DC 20):

**1/day each**: [dissonant whispers](2-Mechanics/CLI/spells/dissonant-whispers.md), [hold monster](2-Mechanics/CLI/spells/hold-monster.md), [meld into stone](2-Mechanics/CLI/spells/meld-into-stone.md), [telekinesis](2-Mechanics/CLI/spells/telekinesis.md), [teleport](2-Mechanics/CLI/spells/teleport.md)

## Actions

***Multiattack.*** The dragon makes one Bite attack and two Claw attacks.

***Bite.*** *Melee Weapon Attack:* `dice:1d20+15|noform|text(+15)` to hit, reach 15 ft., one target. *Hit:* `dice:2d10+8|noform|avg|text(19)` (`2d10 + 8`) piercing damage plus `dice:2d10|noform|avg|text(11)` (`2d10`) thunder damage.

***Claw.*** *Melee Weapon Attack:* `dice:1d20+15|noform|text(+15)` to hit, reach 10 ft., one target. *Hit:* `dice:2d6+8|noform|avg|text(15)` (`2d6 + 8`) slashing damage.

***Debilitating Breath (Recharge 5-6).*** The dragon exhales a pulse of high-pitched, nearly inaudible sound in a 90-foot cone. Each creature in that area must make a DC 23 Constitution saving throw. On a failed save, the creature takes `dice:10d10|noform|avg|text(55)` (`10d10`) thunder damage and is [incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated) until the end of its next turn. On a successful save, the creature takes half as much damage and isn't [incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated).

## Bonus Actions

***Change Shape.*** The dragon magically transforms into any creature that is Medium or Small, while retaining its game statistics (other than its size). This transformation ends if the dragon is reduced to 0 hit points or uses a bonus action to end it.

***Psychic Step.*** The dragon magically teleports to an unoccupied space it can see within 60 feet of it.

## Legendary Actions

***Claw.*** The dragon makes one Claw attack.

***Psionics (Costs 2 Actions).*** The dragon uses Psychic Step or Spellcasting.

***Telekinetic Fling (Costs 3 Actions).*** The dragon chooses one Medium or smaller object that isn't being worn or carried that it can see within 60 feet of it, and it magically hurls the object at a creature it can see within 60 feet of the object. The target must succeed on a DC 20 Dexterity saving throw or take `dice:12d6|noform|avg|text(42)` (`12d6`) bludgeoning damage.

![Sapphire Dragon](2-Mechanics/CLI/bestiary/legendary-group/sapphire-dragon-ftd.md)
```
^statblock