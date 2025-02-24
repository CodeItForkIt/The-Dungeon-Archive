---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/coa
- monster/cr/20
- monster/size/gargantuan
- monster/type/dragon
statblock: inline
aliases: ["Styx Dragon"]
---
# [Styx Dragon](Mechanics\bestiary\dragon/styx-dragon-coa.md)
*Source: Chains of Asmodeus p. 252*  

One of the only draconic beings that makes its home in the Nine Hells, the Styx dragon is an aquatic creature that lives within the River Styx. The waters of the Styx have no effect on its mental faculties or memories, and their breath weapon replicates the effects of the Styx. Their diet consists mostly of devils foolish enough to wander close to the banks of the Styx, though they prefer mortals and corpses over Fiends. Occasional Styx dragons have been spotted in non-infernal planes, possibly by traveling the Styx to their destination.

## Unusual Dragons

Unlike other Dragons, the scales of the Styx dragon have no effect on their capabilities, and range from darker hues all the way up to chromatic scales, though they always appear muddied. They have no wings and very small limbs, relying primarily on their tails for mobility and combat. Their serpentine body lends itself to muddy nests along the banks of the Styx and quick underwater travel. Good captains know where Styx dragon clutches are along the river, and steer their boats specifically to avoid the creatures.

```statblock
"name": "Styx Dragon (CoA)"
"size": "Gargantuan"
"type": "dragon"
"alignment": "Chaotic Evil"
"ac": !!int "17"
"ac_class": "natural armor"
"hp": !!int "296"
"hit_dice": "16d20 + 128"
"stats":
- !!int "27"
- !!int "14"
- !!int "26"
- !!int "19"
- !!int "20"
- !!int "19"
"speed": "30 ft., burrow 20 ft., swim 60 ft."
"saves":
  "Charisma": !!int "10"
  "Dexterity": !!int "8"
  "Wisdom": !!int "11"
  "Constitution": !!int "14"
"skillsaves":
  "Athletics": !!int "21"
  "Insight": !!int "11"
  "Perception": !!int "11"
  "Survival": !!int "17"
"damage_resistances": "damage from spells"
"damage_immunities": "cold, poison"
"condition_immunities": "[blinded](Mechanics/Rules/conditions.md#Blinded), [poisoned](Mechanics/Rules/conditions.md#Poisoned)"
"senses": "blindsight 120 ft., passive Perception 21"
"languages": "Draconic, Infernal"
"cr": "20"
"traits":
- "desc": "The dragon can breathe air and water."
  "name": "Amphibious"
- "desc": "Creatures afflicted with this disease are incapable of regaining hit points\
    \ in any way until the disease is cured. Additionally, as their flesh starts to\
    \ rot, a creature with this disease takes 36 (8d8) necrotic damage after each\
    \ long rest they finish."
  "name": "Stygian Wasting"
- "desc": "The dragon is immune to all negative effects from the River Styx."
  "name": "Styx Dweller"
"actions":
- "desc": "The dragon can use its Frightful Presence. It then makes three attacks\
    \ using its Bite, Tail, or a combination of the two. It can replace one of the\
    \ attacks with Constrict."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +14 to hit, reach 5 ft., one target. Hit: 19\
    \ (2d10 + 8) piercing damage plus 7 (2d6) poison damage, and the target must\
    \ make a DC 19 Constitution saving throw. On a failed save, the target contracts\
    \ Stygian Wasting."
  "name": "Bite"
- "desc": "Melee Weapon Attack: +14 to hit, reach 10 ft., one target. Hit: 15\
    \ (2d6 + 8) bludgeoning damage. If the target is a Large or smaller creature,\
    \ it has the [grappled](Mechanics/Rules/conditions.md#Grappled) condition (escape\
    \ DC 22). The dragon can't make a Tail attack while a creature is [grappled](Mechanics/Rules/conditions.md#Grappled)\
    \ in this way."
  "name": "Tail"
- "desc": "The dragon tightens its grip on a creature [grappled](Mechanics/Rules/conditions.md#Grappled)\
    \ by its tail. The creature takes 27 (3d12 + 8) bludgeoning damage, has the\
    \ [restrained](Mechanics/Rules/conditions.md#Restrained) condition until the start\
    \ of the dragon's next turn, and must make a DC 19 Constitution saving throw.\
    \ On a failed save, the target contracts Stygian Wasting."
  "name": "Constrict"
- "desc": "Each creature of the dragon's choice that is within 120 feet of the dragon\
    \ must succeed on a DC 18 Wisdom saving throw or have the [frightened](Mechanics/Rules/conditions.md#Frightened)\
    \ condition for 1 minute. A creature can repeat the saving throw at the end of\
    \ each of its turns, ending the effect on itself on a success. If a creature's\
    \ saving throw is successful or the effect ends for it, the creature is immune\
    \ to the dragon's Frightful Presence for the next 24 hours."
  "name": "Frightful Presence"
- "desc": "The dragon exhales poisonous Styx water in a 60-foot-long, 10-foot-wide\
    \ line. Each creature in that line must make a DC 19 Dexterity saving throw, taking\
    \ 54 (12d8) poison damage on a failed save, or half as much on a successful\
    \ one. Creatures that fail the save contract Stygian Wasting."
  "name": "Stygian Breath (Recharge 5-6)"
"legendary_actions":
- "desc": "The dragon makes a Wisdom ([Perception](Mechanics/Rules/skills.md#Perception))\
    \ check."
  "name": "Detect"
- "desc": "The dragon makes a Tail attack. If a creature is already [grappled](Mechanics/Rules/conditions.md#Grappled),\
    \ the dragon may use Constrict instead."
  "name": "Tail Attack"
- "desc": "If the dragon has successfully [restrained](Mechanics/Rules/conditions.md#Restrained)\
    \ a creature with the Constrict ability, it may throw them up to 100 feet away.\
    \ When it lands, the creature takes 21 (6d6) bludgeoning damage and must make\
    \ a DC 18 Constitution saving throw. On a failed save, the creature has the [unconscious](Mechanics/Rules/conditions.md#Unconscious)\
    \ condition for 10 minutes."
  "name": "Death Throw (Costs 3 Actions)"
"source":
- "CoA"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/CoA/Styx%20Dragon.webp"
```
^statblock