---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/mabjov
- monster/cr/4
- monster/size/medium
- monster/type/humanoid
statblock: inline
aliases: ["Wolfwere"]
---
# [Wolfwere](Mechanics\bestiary\humanoid/wolfwere-mabjov.md)
*Source: Minsc and Boo's Journal of Villainy p. 155*  

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

While in their humanoid forms, wolfweres have the ability to sing a song that induces a lethargy in their prey that is similar to a [slow](Mechanics/spells/slow.md) spell. Many wolfweres play stringed instruments and pose as bards to avoid arousing suspicion while they work their charms.

```statblock
"name": "Wolfwere (MaBJoV)"
"size": "Medium"
"type": "humanoid"
"alignment": "Chaotic Evil"
"ac": !!int "12"
"ac_class": "13 while in wolf/hybrid form"
"hp": !!int "55"
"hit_dice": "10d8 + 10"
"stats":
- !!int "18"
- !!int "14"
- !!int "12"
- !!int "10"
- !!int "8"
- !!int "15"
"speed": "30 ft. (40 ft. in dire wolf form)"
"skillsaves":
  "Perception": !!int "4"
"damage_immunities": "bludgeoning, piercing, slashing damage from nonmagical weapons\
  \ that aren't iron"
"senses": "passive Perception 13"
"languages": "Common (can't speak in wolf form)"
"cr": "4"
"traits":
- "desc": "The wolfwere has advantage on Wisdom ([Perception](Mechanics/Rules/skills.md#Perception))\
    \ checks that rely on hearing or smell."
  "name": "Keen Hearing and Smell"
- "desc": "The wolfwere has advantage on an attack roll against a creature if at least\
    \ one of the wolfwere's allies is within 5 feet of the creature and the ally isn't\
    \ [incapacitated](Mechanics/Rules/conditions.md#Incapacitated)."
  "name": "Pack Tactics"
"actions":
- "desc": "The wolfwere makes two attacks: one with its Bite and one with its Claws."
  "name": "Multiattack (Hybrid form only)"
- "desc": "Melee Weapon Attack: +7 to hit, reach 5 ft., one target. Hit: 9 (1d8\
    \ + 4) slashing damage or 10 (1d10 + 5) slashing damage if used with two hands."
  "name": "Longsword (Humanoid form only)"
- "desc": "Melee Weapon Attack: +7 to hit, reach 5 ft., one target. Hit: 11\
    \ (2d6 + 4) piercing damage. If the target is a creature, it must succeed on\
    \ a DC 14 Strength saving throw or be knocked [prone](Mechanics/Rules/conditions.md#Prone)."
  "name": "Bite (Wolf or Hybrid form only)"
- "desc": "Melee Weapon Attack: +7 to hit, reach 5 ft., one target. Hit: 9 (2d4\
    \ + 4) slashing damage."
  "name": "Claws (Hybrid form only)"
- "desc": "The wolfwere plays a magical melody on an instrument. Every Humanoid within\
    \ 200 feet of the wolfwere that hears the melody must succeed on a DC 13 Wisdom\
    \ saving throw or be slowed for 10 minutes, as if the [slow](Mechanics/spells/slow.md)\
    \ spell has been cast on them. A creature can repeat the saving throw at the end\
    \ of each of its turns. If a creature's saving throw is successful, the effect\
    \ ends on it. A target that successfully saves is immune to this wolfwere's melody\
    \ for the next 24 hours."
  "name": "Lethargic Song (Humanoid form only)"
- "desc": "The wolfwere polymorphs into a wolf-human- oid hybrid or into a Humanoid\
    \ (elf or human), or back into its true form, which is a dire wolf. Its statistics,\
    \ other than its AC, are the same in each form. Any equipment it is wearing or\
    \ carrying isn't transformed. It reverts to its true form if it dies"
  "name": "Change Shape"
"source":
- "MaBJoV"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/MaBJoV/Wolfwere.webp"
```
^statblock