---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/mabjov
- monster/cr/9
- monster/size/small
- monster/type/humanoid/gnome
aliases: ["Flimp Shagglecran"]
---
# Flimp Shagglecran
*Source: Minsc and Boo's Journal of Villainy p. 32*  

Flimpius Theodore Shagglecran (known to his friends as Flimp) is a gnome artificer who hails from the island nation of Lantan. Flimp has an appearance unlike any other gnome on Faerûn. Dressed in plate armor with hooks and pouches for keeping his many inventions, Flimp is always accompanied by his ornery, but entirely mechanical, dog named Metallison.

Flimp spent his youth as many gnomes in Lantan do—studying with hopes to one day join the Gnomish Academy of Engineering. While he easily qualified to study at the Academy, Flimp quickly found that such a life was too boring for his tastes. To the consternation of his family and teachers, Flimp set off on a merchant ship headed north to the fabled city of Waterdeep. Halfway into the voyage, his ship was struck by misfortune and swamped during a powerful storm. Flimp found himself shipwrecked on a strange land with only a few other survivors with him. This turned out to be a blessing in disguise, for it was how he met his great friend and ally, the Waterhavian scholar Doc Watson.

Together the two of them were able to rebuild and modify the wrecked ship which they named the Kraken's Folly. The name was inspired by the ship's most unique addition, a magical steering wheel (stolen from the lair of a kraken) that allows the ship to sail between worlds. After convincing Doc Watson to give up academic life, the two new friends used the ship to launch an adventuring career. This career turned out to be so lucrative, that eventually they founded a joint venture they named "The Adventurer's Guild".

## Flimp as a Contact

Flimp is the primary contact for members of the Adventurer's Guild at low levels. Flimp can use his planar ship, the Kraken's Folly, to take adventurers to many exotic locations.

**Flimp's Planar Ship Transportation Costs**

| Location | Required Level | Cost |
|----------|----------------|------|
| Waterdeep | 1 | 10 gp per passenger |
| Baldur's Gate | 1 | 10 gp per passenger |
| Neverwinter | 1 | 10 gp per passenger |
| Athkatla | 1 | 10 gp per passenger |
| Lantan | 5 | 25 gp per passenger |
| Ust Natha | 5 | 50 gp per passenger |
| Icewind Dale | 5 | 50 gp per passenger |
| Port Nyanzaru | 5 | 25 gp per passenger |
| Abyss | 10 | 500 gp per passenger |
| Avernus | 10 | 500 gp per passenger |
| Githyanki City | 10 | 400 gp per passenger |
| City Of Greyhawk | 10 | 250 gp per passenger |
^flimps-planar-ship-transportation-costs

## Statblock

```ad-statblock
title: Flimp Shagglecran
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/MaBJoV/Flimp%20Shagglecran.webp#token)
*Small humanoid (gnome), Lawful Neutral*

- **Armor Class** 21 ([+2 plate](2-Mechanics/CLI/items/2-armor.md), [cloak of protection](2-Mechanics/CLI/items/cloak-of-protection.md))
- **Hit Points** 137 (`25d6 + 50`)
- **Speed** 25 ft., fly 25 ft., swim 60 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|14 (+2)|10 (+0)|14 (+2)|18 (+4)|12 (+1)|11 (+0)|

- **Proficiency Bonus** +4
- **Saving Throws** Constitution +6, Intelligence +8
- **Skills** Arcana +8, History +8, Medicine +5
- **Senses** darkvision 60 ft., passive Perception 11
- **Languages** Common, Dwarvish, Giant, Gnomish
- **Challenge** 9

## Traits

***Battle Smith.*** Flimp uses his Intelligence modifier for attack and damage rolls with his weapons.

***Gnome Cunning.*** Flimp has advantage on all Intelligence, Wisdom, and Charisma Saving Throws against magic.

***Special Equipment.*** Flimp wears a [cloak of the manta ray](2-Mechanics/CLI/items/cloak-of-the-manta-ray.md), a [cloak of protection](2-Mechanics/CLI/items/cloak-of-protection.md), +2 plate armor, and [winged boots](2-Mechanics/CLI/items/winged-boots.md). Flimp wields a +2 warhammer. These items vanish 4 days after Flimp dies.

***Spellcasting.*** Flimp casts one of the following spells using Intelligence as his spellcasting ability (spell save DC 16):

**At will**: [guidance](2-Mechanics/CLI/spells/guidance.md), [light](2-Mechanics/CLI/spells/light.md)

**1/day each**: [blink](2-Mechanics/CLI/spells/blink.md), [elemental weapon](2-Mechanics/CLI/spells/elemental-weapon.md), [fire shield](2-Mechanics/CLI/spells/fire-shield.md)

**2/day each**: [aid](2-Mechanics/CLI/spells/aid.md), [blur](2-Mechanics/CLI/spells/blur.md), [cure wounds](2-Mechanics/CLI/spells/cure-wounds.md), [shield](2-Mechanics/CLI/spells/shield.md)

## Actions

***Multiattack.*** Flimp makes two Magic Warhammer attacks.

***Magic Warhammer.*** *Melee Weapon Attack:* `dice:1d20+10|noform|text(+10)` to hit, reach 5 ft., one target. *Hit:* `dice:1d8+6|noform|avg|text(10)` (`1d8 + 6`) bludgeoning damage plus `dice:1d6|noform|avg|text(3)` (`1d6`) force damage.

***Hurl Acid (Recharge 6).*** Flimp hurls a vial of acid at a location within 60 feet. Every creature within 10 feet of the target location must succeed on a DC 16 Dexterity saving throw or take `dice:6d6|noform|avg|text(21)` (`6d6`) acid damage.

***Summon Steel Defender (1/Day).*** Flimp summons a [metallic panther](2-Mechanics/CLI/bestiary/construct/steel-defender-tce.md) to aid him in combat. The panther has 24 hit points and is immune to poison damage and the poison and [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed) conditions.

## Reactions

***Flash of Genius.*** When Flimp or another creature he can see within 30 feet of him makes an ability check or a saving throw, Flimp can use his reaction to add +4 to the roll.
```
^statblock