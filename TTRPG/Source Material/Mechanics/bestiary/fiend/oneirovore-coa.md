---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/coa
- monster/cr/11
- monster/size/large
- monster/type/fiend
statblock: inline
aliases: ["Oneirovore"]
---
# [Oneirovore](Mechanics\bestiary\fiend/oneirovore-coa.md)
*Source: Chains of Asmodeus p. 248*  

The ancestors of these Fiends were servants of the divine and Fey which devoured the nightmares of mortals, bringing restful sleep. Imported into the Nine Hells and cultivated by devils, dream eaters, as they're also known, became a powerful weapon in subtly corrupting mortal minds. They can be found grazing wherever the toxic foliage of the Nine Hells grows, often guarded by low-status devils and hell hounds. When brought to weak points between the planes, their spirits seep into the mortal world. There they browse the dreaming minds of mortals. Often, they devour the hope and wonder that might inspire people to improve their lives.

## Placid Herds

Despite their fearsome-looking appearance, dream eaters are oddly passive for a denizen of the Nine Hells. When attacked, their first instinct is to lumber away at their sluggish pace, sending out high, mournful cries that attract every devil and infernal monster within earshot. Their angry herdsmen usually arrive in short order to see off the threat.

## Storehouses of Phantasms

Forced to fight, dream eaters' most potent defense is a release of their stored phantasmagoria. This can affect attackers in several ways. A release of nightmares taints the way that non-devils view the world around them, transforming everything—including allies—into hideous sources of fear and threat, whilst the dream eaters themselves fade into the infernal landscape. On the other hand, a release of hope and wonder leaves mortal attackers in a dazed and euphoric state, suddenly taken by wild fancies to accomplish impossible and reckless feats that see them charging off across the hellish landscape, the fight forgotten. The same expulsion of positive dream imagery has a powerful caustic effect against infernal creatures, affecting devils much as a skunk's blast against regular predators.

```statblock
"name": "Oneirovore (CoA)"
"size": "Large"
"type": "fiend"
"alignment": "Unaligned"
"ac": !!int "19"
"ac_class": "natural armor"
"hp": !!int "237"
"hit_dice": "19d10 + 133"
"stats":
- !!int "16"
- !!int "12"
- !!int "25"
- !!int "12"
- !!int "10"
- !!int "10"
"speed": "20 ft."
"saves":
  "Intelligence": !!int "5"
  "Constitution": !!int "11"
"skillsaves":
  "Nature": !!int "5"
  "Insight": !!int "4"
  "Perception": !!int "4"
  "Survival": !!int "4"
"damage_resistances": "fire; poison; bludgeoning, piercing, slashing from nonmagical\
  \ attacks that aren't silvered"
"damage_immunities": "psychic"
"condition_immunities": "[blinded](Mechanics/Rules/conditions.md#Blinded), [charmed](Mechanics/Rules/conditions.md#Charmed),\
  \ [frightened](Mechanics/Rules/conditions.md#Frightened)"
"senses": "truesight 60 ft., passive Perception 14"
"languages": ""
"cr": "11"
"actions":
- "desc": "Melee Weapon Attack: +7 to hit, reach 10 ft., one target. Hit: 16\
    \ (2d12 + 3) force damage."
  "name": "Stomp"
- "desc": "The oneirovore manipulates the perception of nearby creatures, sending\
    \ them into a panic. Creatures of the oneirovore's choice that it can see within\
    \ 60 feet must make a DC 19 Charisma saving throw. On a failed save, the creature\
    \ has the [charmed](Mechanics/Rules/conditions.md#Charmed) condition, their vision\
    \ distorted such that they view their allies as creatures of pure fear and hatred.\
    \ While [charmed](Mechanics/Rules/conditions.md#Charmed), a creature will use\
    \ their actions to attack their allies with intent to kill. A [charmed](Mechanics/Rules/conditions.md#Charmed)\
    \ creature may repeat the saving throw at the end of each turn, ending the effect\
    \ on a success."
  "name": "Realize Nightmares (Recharge 4-6)"
- "desc": "The oneirovore lets out an earsplitting shriek, calling for infernal reinforcements.\
    \ Creatures that are not Fiends that are within 120 feet of the oneirovore must\
    \ make a DC 19 Constitution saving throw, taking 55 (10d10) thunder damage on\
    \ a failed save, or half as much damage on a successful one. Any lesser devils\
    \ within a 1-mile-radius, centered on the oneirovore, are required by contract\
    \ to come to its aid upon hearing its Warning Cry. Higher ranking devils may investigate\
    \ if they desire, but the call holds no magical sway over them."
  "name": "Warning Cry (1/Day)"
"source":
- "CoA"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/CoA/Oneirovore.webp"
```
^statblock