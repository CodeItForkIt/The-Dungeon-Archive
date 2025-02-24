---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/dodk
- monster/cr/13
- monster/size/large
- monster/type/aberration
aliases: ["Gravekeeper"]
---
# Gravekeeper
*Source: Dungeons of Drakkenheim p. 210*  

> [!quote] A quote from Overheard from a party of nobles in the Red Lion Hotel  
> 
> The Royal Crypts below Castle Drakken housed the bodies of kings and queens, dukes and nobles of generations gone. They were tended by the many gravekeepers who worked diligently to light the lanterns below so the dead could have safe passage to the light. I shudder to think what has become of those crypts, and their keepers, in these dark times.

The Gravekeeper is a hovering mass of writhing appendages. Amongst its horrid and grotesque form one can make out the many faces of long lost gravekeepers of Castle Drakken, but their expressions are twisted in horror of their last moments, and their eyes are hollow with a dim octarine light emanating from within. Covering the floating mass are hundreds of arms, several of them holding softly glowing lanterns. The lanterns glow with octarine flames that cast flickering shadows across the crypt. The Gravekeeper wanders amongst the dead, awakening them into grasping souls, clawing their way out of the many graves amongst the lordly tombs of the castle.


```ad-statblock
title: Gravekeeper
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/DoDk/Gravekeeper.webp#token)
*Large aberration, Chaotic Evil*

- **Armor Class** 18 (natural armor)
- **Hit Points** 210 (`20d10 + 100`)
- **Speed** 0 ft., fly 30 ft. (hover)

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|18 (+4)| 7 (-2)|21 (+5)|19 (+4)|17 (+3)|21 (+5)|

- **Proficiency Bonus** +5
- **Saving Throws** Constitution +10, Wisdom +8, Charisma +10
- **Skills** Perception +13
- **Senses** truesight 120 ft., passive Perception 23
- **Languages** all but does not speak
- **Challenge** 13

## Traits

***Dazzling Illumination.*** The Gravekeeper projects a brilliant corona of light which sheds bright light to a range of 60 feet, and causes attack rolls against it to have disadvantage. If it is hit by an attack, this trait is disrupted until the end of its next turn. This trait is also disrupted while the Gravekeeper is [incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated) or has a speed of 0.

***Legendary Resistance (3/Day).*** If the Gravekeeper fails a saving throw, it can choose to succeed instead.

## Actions

***Slam.*** *Melee Weapon Attack:* `dice:1d20+9|noform|text(+9)` to hit, reach 10 ft., one target. *Hit:* `dice:4d8+4|noform|avg|text(22)` (`4d8 + 4`) bludgeoning damage plus `dice:3d6|noform|avg|text(10)` (`3d6`) necrotic damage.

***Lantern Blast.*** Magical octarine beams flash from the Gravekeeper's many lanterns. Each beam has a different power. Each creature within 120 feet of the Gravekeeper which is not behind total cover rolls a `dice:d6|noform|avg` (`d6`) to determine which colour ray affects it. The DC for all saving throws is 18:

- **1. Dispelling Blast.** The targeted creature must succeed on an Intelligence saving throw or take `dice:10d6|noform|avg|text(35)` (`10d6`) psychic damage, and any spell or magical effect upon the target ends. A creature who fails this saving throw has their [concentration](2-Mechanics/CLI/rules/conditions.md#Concentration) broken on any spell they were actively maintaining.  
- **2. Forceful Blast.** The targeted creature must succeed on a Strength saving throw or take `dice:10d6|noform|avg|text(35)` (`10d6`) force damage, be pushed 20 feet away, and knocked [prone](2-Mechanics/CLI/rules/conditions.md#Prone).  
- **3. Blinding Blast.** The targeted creature must succeed on a Constitution saving throw or take `dice:10d6|noform|avg|text(35)` (`10d6`) radiant damage and be [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded) for 1 minute. A [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded) creature can repeat the saving throw on each of its turns, ending the effect on itself on a success.  
- **4. Contamining Blast.** The targeted creature must succeed on a Constitution saving throw or take `dice:10d6|noform|avg|text(35)` (`10d6`) necrotic damage and gain one level of contamination.  
- **5. Igniting Blast.** The targeted creature must succeed on a Dexterity saving throw or take `dice:10d6|noform|avg|text(35)` (`10d6`) fire damage, and catches fire; until someone takes an action to douse the fire, the target takes `dice:10d6|noform|avg|text(35)` (`10d6`) fire damage at the start of each of its turns.  
- **6. Freezing Blast.** The targeted creature must succeed on a Constitution saving throw or take `dice:10d6|noform|avg|text(35)` (`10d6`) cold damage, and it can't take a reaction until the end of its next turn. Moreover, on its next turn, it must choose whether it gets a move, an action, or a bonus action; it gets only one of the three. On a successful save, the target takes half as much damage and suffers none of the blast's other effects.  

## Legendary Actions

***Slam.*** The Gravekeeper makes a slam attack.

***Glide.*** The Gravekeeper moves its speed without provoking opportunity attacks.

***Lantern Blast (Costs 3 actions).*** The Gravekeeper uses its Lantern Blast.

![Gravekeeper](2-Mechanics/CLI/bestiary/legendary-group/gravekeeper-dodk.md)
```
^statblock