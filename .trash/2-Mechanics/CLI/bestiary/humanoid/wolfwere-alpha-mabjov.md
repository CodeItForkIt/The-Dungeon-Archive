---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/mabjov
- monster/cr/6
- monster/size/medium
- monster/type/humanoid
aliases: ["Wolfwere Alpha"]
---
# Wolfwere Alpha
*Source: Minsc and Boo's Journal of Villainy p. 154*  

> [!quote] A quote from MINSC  
> 
> I remember being told that wolfweres were nature's perfect predator. Boo disagreed with this though. There is nothing more fearsome than a pissed off space hamster!

> [!quote] A quote from Wolfwere  
> 
> Shhhh... close your eyes.
> 
> Dream of starlight, dream of sights unseen, and I shall join you soon.

Wolfweres are shapeshifters that have the natural form of a large wolf but can transform at will into both humanoid and bipedal hybrid shapes. These hateful creatures are much more intelligent than a normal wolf and use this preternatural cunning to hunt their favorite prey: humans. Although some believe them to be the offspring of werewolves and normal wolves—and this may very well be their origin—wolfweres are their own species and their form of lycanthropy is not a transmissible curse or disease. Like werewolves, wolfweres are repelled by wolfsbane but are vulnerable to iron rather than silver weapons.

## Strange Packs

Although some wolfweres are solitary, others choose to stay in familial bands. However, they most often run in packs of normal wolves or worgs. Wolfweres are able to influence and command these beasts, making them much more vicious and bolder. Rarely, a wolfwere may choose to blend in with human society. Wolfweres never associate with werewolves, as the two share a mutual hatred and will attack each other unprovoked.

## Myriad Forms

A wolfwere's natural form is similar in size and appearance to that of a dire wolf. In combat, they usually shift into a hybrid form, which is able to both bite and use weapons with its human-like hands. To trick stronger prey, a wolfwere dons a charismatic human shape. Unlike werewolves, wolfweres have no single humanoid form to revert to. Instead, a wolfwere can transform into any humanoid shape it desires, though they almost universally choose ones with great physical beauty. Wolfweres have the ability to sense what their particular prey would find attractive and assume a seductive disguise. Wolfweres have less control over their appearance when they involuntarily transform under a new moon, though they usually assume a shape they have taken on recently.

## A Sedating Melody

While in their humanoid forms, wolfweres have the ability to sing a song that induces a lethargy in their prey that is similar to a [slow](2-Mechanics/CLI/spells/slow.md) spell. Many wolfweres play stringed instruments and pose as bards to avoid arousing suspicion while they work their charms.

## Statblock

```ad-statblock
title: Wolfwere Alpha
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/MaBJoV/Wolfwere%20Alpha.webp#token)
*Medium humanoid, Chaotic Evil*

- **Armor Class** 12 (13 while in wolf/hybrid form)
- **Hit Points** 104 (`16d8 + 32`)
- **Speed** 30 ft. (40 ft. in dire wolf form)

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|20 (+5)|14 (+2)|14 (+2)|10 (+0)| 8 (-1)|16 (+3)|

- **Proficiency Bonus** +3
- **Saving Throws** ⏤
- **Skills** Perception +6
- **Senses** passive Perception 16
- **Damage Immunities** bludgeoning, piercing, slashing damage from nonmagical weapons that aren't iron
- **Languages** Common (can't speak in wolf form)
- **Challenge** 6

## Traits

***Keen Hearing and Smell.*** The wolfwere has advantage on Wisdom ([Perception](2-Mechanics/CLI/rules/skills.md#Perception)) checks that rely on hearing or smell.

***Pack Tactics.*** The wolfwere has advantage on an attack roll against a creature if at least one of the wolfwere's allies is within 5 feet of the creature and the ally isn't [incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated).

## Actions

***Multiattack (Hybrid form only).*** The wolfwere makes three attacks: one with its Bite and two with its Claws.

***Longsword (Humanoid form only).*** *Melee Weapon Attack:* `dice:1d20+8|noform|text(+8)` to hit, reach 5 ft., one target. *Hit:* `dice:1d8+5|noform|avg|text(10)` (`1d8 + 5`) slashing damage or `dice:1d10+6|noform|avg|text(11)` (`1d10 + 6`) slashing damage if used with two hands.

***Bite (Wolf or Hybrid form only).*** *Melee Weapon Attack:* `dice:1d20+8|noform|text(+8)` to hit, reach 5 ft., one target. *Hit:* `dice:2d6+5|noform|avg|text(12)` (`2d6 + 5`) piercing damage. If the target is a creature, it must succeed on a DC 15 Strength saving throw or be knocked [prone](2-Mechanics/CLI/rules/conditions.md#Prone).

***Claws (Hybrid form only).*** *Melee Weapon Attack:* `dice:1d20+8|noform|text(+8)` to hit, reach 5 ft., one target. *Hit:* `dice:2d4+5|noform|avg|text(10)` (`2d4 + 5`) slashing damage.

***Lethargic Song (Humanoid form only).*** The wolfwere plays a magical melody on an instrument. Every Humanoid within 200 feet of the wolfwere that hears the melody must succeed on a DC 16 Wisdom saving throw or be slowed for 10 minutes, as if the [slow](2-Mechanics/CLI/spells/slow.md) spell has been cast on them. A creature can repeat the saving throw at the end of each of its turns. If a creature's saving throw is successful, the effect ends on it. A target that successfully saves is immune to this wolfwere's melody for the next 24 hours.

***Change Shape.*** The wolfwere polymorphs into a wolf-hu- manoid hybrid or into a Humanoid (elf or human), or back into its true form, which is a dire wolf. Its statistics, other than its AC, are the same in each form. Any equipment it is wearing or carrying isn't transformed. It reverts to its true form if it dies.
```
^statblock