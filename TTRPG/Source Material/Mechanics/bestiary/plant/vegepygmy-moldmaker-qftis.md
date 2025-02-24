---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/qftis
- monster/cr/3
- monster/size/small
- monster/type/plant
statblock: inline
aliases: ["Vegepygmy Moldmaker"]
---
# [Vegepygmy Moldmaker](Mechanics\bestiary\plant/vegepygmy-moldmaker-qftis.md)
*Source: Quests from the Infinite Staircase p. 218*  

The oldest vegepygmies in a colony sometimes achieve control over the growth and propagation of the mold that bore them. These elders, known as moldmakers, can envelop foes in stifling layers of mold. Moldmakers often wear pauldrons made of lichen to denote their status.

## Vegepygmies

Also called mold folk, vegepygmies are fungal creatures that spring forth from the body of a Humanoid or Giant killed by russet mold, a poisonous fungus rumored to have originated from beyond the stars.

Vegepygmies gather in small bands, communicating with a combination of gestures, hisses, and rhythmic taps. While vegepygmies can sustain themselves by absorbing nutrients from soil and other organic matter, they prefer a carnivorous diet achieved through hunting and scavenging. Vegepygmies can live indefinitely so long as the climate remains hospitable to their fungal bodies.

To learn more about vegepygmies, see Monsters of the Multiverse.

```statblock
"name": "Vegepygmy Moldmaker (QftIS)"
"size": "Small"
"type": "plant"
"alignment": "typically  Neutral"
"ac": !!int "15"
"ac_class": "natural armor"
"hp": !!int "44"
"hit_dice": "8d6 + 16"
"stats":
- !!int "10"
- !!int "14"
- !!int "14"
- !!int "10"
- !!int "16"
- !!int "11"
"speed": "30 ft."
"saves":
  "Wisdom": !!int "5"
  "Intelligence": !!int "2"
"skillsaves":
  "Stealth": !!int "4"
  "Perception": !!int "5"
"damage_resistances": "lightning, piercing"
"senses": "darkvision 60 ft., passive Perception 15"
"languages": "Vegepygmy"
"cr": "3"
"traits":
- "desc": "The vegepygmy has advantage on Dexterity ([Stealth](Mechanics/Rules/skills.md#Stealth))\
    \ checks it makes in any terrain with ample obscuring vegetation."
  "name": "Plant Camouflage"
- "desc": "The vegepygmy regains 7 hit points at the start of its turn. If it takes\
    \ cold, fire, or necrotic damage, this trait doesn't function at the start of\
    \ the vegepygmy's next turn. The vegepygmy dies only if it starts its turn with\
    \ 0 hit points and doesn't regenerate."
  "name": "Regeneration"
"actions":
- "desc": "The vegepygmy makes two Claw attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 12\
    \ (3d6 + 2) slashing damage."
  "name": "Claw"
- "desc": "The vegepygmy targets a creature it can see within 60 feet of itself. If\
    \ the target isn't a vegepygmy, it must make a DC 13 Constitution saving throw.\
    \ On a failed save, the target takes 13 (3d8) poison damage and has the [blinded](Mechanics/Rules/conditions.md#Blinded)\
    \ and [deafened](Mechanics/Rules/conditions.md#Deafened) conditions for 1 minute\
    \ as it becomes covered in a thick layer of mold. On a successful save, the target\
    \ takes half as much damage only.\n\nThe target can repeat the saving throw at\
    \ the end of each of its turns, ending the effect on itself on a success."
  "name": "Toxic Mold (2/Day)"
"source":
- "QftIS"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/QftIS/Vegepygmy%20Moldmaker.webp"
```
^statblock