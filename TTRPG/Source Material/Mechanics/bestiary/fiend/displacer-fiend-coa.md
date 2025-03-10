---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/coa
- monster/cr/9
- monster/size/large
- monster/type/fiend
statblock: inline
aliases: ["Displacer Fiend"]
---
# [Displacer Fiend](Mechanics\bestiary\fiend/displacer-fiend-coa.md)
*Source: Chains of Asmodeus p. 240*  

Long ago a Fey lord led his hunt into the Nine Hells to settle a score with an archfiend over mortals claimed by both. What fate the lord met is unknown, but of all his expedition, one particular faerie breed prospered in its new environment. A particularly vicious strain of displacer beast has become an entrenched new threat across many layers of the Nine Hells, prowling about the edges of fiendish communities and attacking mortal and infernal travelers alike.

## Stalking Horrors

Long ages in the Nine Hells have warped the original beasts into something more fiendish. Whilst still feline in shape, the displacer fiend's shoulders sprout with an explosion of writhing tentacles each tipped with a lamprey-like mouth. These tooth-lined maws drain life essence or infernal strength from their prey, providing the fiends with their sustenance. The mouths drip with a vitriol that causes agony to mortals, but acts as a tranquilizing balm to devils, permitting the Fiends to feast on them without waking their prey if they get the chance. Displacer fiends retain the innate stealth of their progenitors and slip from shadow to shadow across all but the most barren of infernal landscapes. Packs of them will follow travelers for long distances, waiting until the terrain most favors an ambush.

## Corruptors of Perception

Like their base stock, displacer fiends bend light around themselves, the visible monster always slightly shifted from its true location. These natural gifts have been fortified by the deceptive influence of the lower planes. The monsters also possess the ability to shift the perceived location of their victim and affect their prey's grasp of relative distance and place. Fighting them can be a nightmare of confusion, as allies, enemies and landscape features appear randomly close or far, huge or small—or the fighters find themselves viewing the battlefield from outside their own heads, trying to control their bodies like puppets. Even basic functions like proprioception—the knowledge of where one's limbs are when not directly observed—can be lost. This can lead to a complete loss of coordination, accidentally striking friends or falling into bogs or crevasses that seemed far distant.

## Monstrous Pets

Many large cities in the Nine Hells have feral populations of displacer fiends predating off the lowliest devils and breeding in hidden corners. Much of the time they're considered pests, but they do keep down populations of various infernal vermin, like halogs, that would otherwise be more troubling in their proliferation. Some devils actively cultivate their presence, encouraging them by staking out a lemure or imp every so often, as a human might leave a bowl of scraps for a cat. Devils aren't sentimental, but some find the viciousness and skulking cruelty of the displacer fiends oddly endearing.

```statblock
"name": "Displacer Fiend (CoA)"
"size": "Large"
"type": "fiend"
"alignment": "Neutral Evil"
"ac": !!int "16"
"ac_class": "natural armor"
"hp": !!int "135"
"hit_dice": "18d10 + 36"
"stats":
- !!int "17"
- !!int "19"
- !!int "14"
- !!int "8"
- !!int "13"
- !!int "10"
"speed": "40 ft."
"saves":
  "Dexterity": !!int "8"
  "Strength": !!int "7"
"skillsaves":
  "Athletics": !!int "7"
  "Stealth": !!int "12"
  "Perception": !!int "5"
  "Acrobatics": !!int "8"
"damage_resistances": "fire, poison"
"condition_immunities": "[charmed](Mechanics/Rules/conditions.md#Charmed), [frightened](Mechanics/Rules/conditions.md#Frightened)"
"senses": "darkvision 120 ft., passive Perception 15"
"languages": ""
"cr": "9"
"traits":
- "desc": "If the displacer fiend is subjected to an effect that allows it to make\
    \ a saving throw to take only half damage, it instead takes no damage if it succeeds\
    \ on the saving throw, and only half damage if it fails."
  "name": "Avoidance"
- "desc": "The displacer fiend projects a magical illusion that makes it appear to\
    \ be standing near its actual location, causing attack rolls against it to have\
    \ disadvantage. If it is hit by an attack, this trait is disrupted until the end\
    \ of its next turn. This trait is also disrupted while the displacer fiend is\
    \ [incapacitated](Mechanics/Rules/conditions.md#Incapacitated) or has a speed\
    \ of 0."
  "name": "Displacement"
"actions":
- "desc": "The displacer fiend makes three Tentacle attacks. It can replace one of\
    \ the attacks with a Bite attack."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +8 to hit, reach 5 ft., one target. Hit: 18\
    \ (4d6 + 4) piercing damage plus 7 (2d6) necrotic damage."
  "name": "Tentacle"
- "desc": "Melee Weapon Attack: +8 to hit, reach 10 ft., one target. Hit: 23\
    \ (3d12 + 4) piercing damage, and the target's Dexterity score is reduced by\
    \ 2 (1d4). The target is killed if this reduces its Dexterity to 0. The reduction\
    \ lasts until the target finishes a short or long rest."
  "name": "Bite"
"bonus_actions":
- "desc": "While in dim light or darkness, the displacer fiend can teleport up to\
    \ 60 feet, provided its destination is also in dim light or darkness."
  "name": "Shadowhop"
"source":
- "CoA"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/CoA/Displacer%20Fiend.webp"
```
^statblock