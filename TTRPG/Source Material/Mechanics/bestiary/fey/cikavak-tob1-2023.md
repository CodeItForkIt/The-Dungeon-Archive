---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/1-8
- monster/environment/farmland
- monster/environment/forest
- monster/size/tiny
- monster/type/fey
statblock: inline
aliases: ["Cikavak"]
---
# [Cikavak](Mechanics\bestiary\fey/cikavak-tob1-2023.md)
*Source: Tome of Beasts 1 (2023 Edition) p. 57*  

*A dark gray comb flops atop the head of this remarkably ugly bird, and shapeless wattles dangle from its throat.*

## Dagger Beaks

Cikavaks use their elongated, dull-gray beaks to draw up nectar and other fluids—or to stab with the force of a dagger. Although it requires great effort to call up these homely birds, the magic is surprisingly common, known among peasants and townsfolk as well as mages. Once summoned, they remain faithful to their masters until death. While cikavaks don't speak, they comprehend the Common tongue and can speak with animals to help their master. They often magically silence the cries of more melodious birds.

## Potion Pouches

Cikavaks possess another odd ability: when fully distended, their ventral pouches hold up to half a gallon of almost any liquid. These resilient pouches take little or no damage from their contents, holding potions without ingesting them or even carrying acid without injury. Thieves make use of this ability, directing the birds to siphon up liquids, stealing honey from neighbors' beehives, as well as milk, beer, and wine. The most audacious thieves send their birds into magicians' towers, alchemists' shops, or the local apothecary to seize mercury, phlogiston, and more exotic substances. The cikavaks carry these stolen fluids back to their owners in their pouches. While normally strong flyers, when laden with liquids, their flight is clumsy at best.

## Folk Conjuration

To call a cikavak with folk magic rituals, a character must gather an egg from a black hen as well as 30 gp worth of herbs and colored chalks. Cast at sunset, the folk ritual requires half an hour and a successful DC 15 Intelligence ([Arcana](Mechanics/Rules/skills.md#Arcana)) check. The material components can be used multiple times, until the ritual succeeds. The hen's egg must then be carried and kept warm for 40 days. During this time, the ritual's caster must not bathe or be subject to any spell effects. The ritual's feeble magic is immediately dispelled if the ritual's caster uses any other sort of magic item or casts a spell while incubating the egg.

```statblock
"name": "Cikavak (ToB1-2023)"
"size": "Tiny"
"type": "fey"
"alignment": "Neutral"
"ac": !!int "12"
"hp": !!int "17"
"hit_dice": "7d4"
"stats":
- !!int "4"
- !!int "15"
- !!int "10"
- !!int "12"
- !!int "12"
- !!int "4"
"speed": "10 ft., fly 40 ft."
"skillsaves":
  "Stealth": !!int "6"
  "Perception": !!int "5"
"damage_resistances": "acid, fire, poison"
"senses": "darkvision 60 ft., passive Perception 15"
"languages": "understands Common but can't speak"
"cr": "1/8"
"traits":
- "desc": "The cikavak can magically communicate simple ideas, emotions, and images\
    \ telepathically with any creature that touches it and that can understand a language."
  "name": "Limited Telepathy"
- "desc": "The cikavak can communicate with Beasts as if they shared a language."
  "name": "Speak with Beasts"
"actions":
- "desc": "Melee Weapon Attack: +4 to hit, range 5 ft., one target. Hit: 4 (1d4\
    \ + 2) piercing damage."
  "name": "Beak"
- "desc": "The cikavak lets out a magical squawk in a 30-foot cone. Each creature\
    \ in that area must succeed on a DC 11 Constitution saving throw or be [deafened](Mechanics/Rules/conditions.md#Deafened)\
    \ and unable to speak for 1 minute. A creature can repeat the saving throw at\
    \ the end of each of its turns, ending the effect on itself on a success."
  "name": "Silencing Squawk (Recharge 6)"
"source":
- "ToB1-2023"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Cikavak.webp"
```
^statblock

## Environment

farmland, forest