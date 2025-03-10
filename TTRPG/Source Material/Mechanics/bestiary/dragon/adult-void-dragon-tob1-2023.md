---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/16
- monster/environment/planar
- monster/size/huge
- monster/type/dragon
statblock: inline
aliases: ["Adult Void Dragon"]
---
# [Adult Void Dragon](Mechanics\bestiary\dragon/adult-void-dragon-tob1-2023.md)
*Source: Tome of Beasts 1 (2023 Edition) p. 129*  

*A dragon seemingly formed of the night sky has bright white stars for eyes. Lesser stars twinkle in the firmament of the dragon's body.*

## Children of the Stars

Void dragons drift through the empty spaces beyond the boundaries of the mortal world and wander between the stars. They are aloof, mingling only with the otherworldly beings that live above and beyond the earth, including the incarnate forms of the stars themselves.

## Witnesses to the Void

Void dragons are intensely knowledgeable creatures, but they have seen too much, lingering at the edge of the Void itself. They carry a piece of that nothing with them, and it flows out of them to break the minds of lesser beings when the dragons fly into a rage.

## Voracious Scholars

Despite their removed existence and strange quirks, Void dragons still hoard treasure. Gems that glitter like the stars of their home are particularly prized. Their crowning piece, however, is knowledge. Void dragons jealously hoard scraps of forbidden and forgotten lore of any kind and spend most of their time at home poring over these treasures.

## A Void Dragon's Lair

Void dragons make their lairs deep in the freezing, airless space between the stars. When a Void dragon claims a home elsewhere, it prefers towering mountain peaks, valleys, or ruins at high elevation with a clear view of the sky. When encountered in its lair, an adult Void dragon has a challenge rating of 17 (18,000 XP), and an ancient Void dragon has a challenge rating of 25 (75,000 XP).

```statblock
"name": "Adult Void Dragon (ToB1-2023)"
"size": "Huge"
"type": "dragon"
"alignment": "Chaotic Neutral"
"ac": !!int "19"
"ac_class": "natural armor"
"hp": !!int "229"
"hit_dice": "17d12 + 119"
"stats":
- !!int "24"
- !!int "10"
- !!int "25"
- !!int "16"
- !!int "13"
- !!int "21"
"speed": "40 ft., fly 80 ft. (hover)"
"saves":
  "Charisma": !!int "10"
  "Dexterity": !!int "5"
  "Wisdom": !!int "6"
  "Constitution": !!int "12"
"skillsaves":
  "Stealth": !!int "5"
  "Perception": !!int "11"
  "History": !!int "13"
  "Arcana": !!int "13"
"damage_immunities": "cold"
"condition_immunities": "[charmed](Mechanics/Rules/conditions.md#Charmed), [frightened](Mechanics/Rules/conditions.md#Frightened)"
"senses": "blindsight 60 ft., darkvision 120 ft., passive Perception 21"
"languages": "Common, Draconic, Void Speech"
"cr": "16"
"traits":
- "desc": "Creatures with resistance to cold damage don't have resistance to the cold\
    \ damage dealt by the Void dragon. A creature with immunity to cold damage is\
    \ still immune to the dragon's cold damage."
  "name": "Chill of the Void"
- "desc": "The Void dragon doesn't require air, food, drink, sleep, or ambient pressure.\
    \ While traveling in the Void, the dragon magically glides on solar winds, covering\
    \ immense distances in short times."
  "name": "Expert Void Traveler"
- "desc": "If the dragon fails a saving throw, it can choose to succeed instead."
  "name": "Legendary Resistance (3/Day)"
"actions":
- "desc": "The dragon uses its Aura of Madness. It then makes one Bite attack and\
    \ two Claw attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +12 to hit, reach 10 ft., one target. Hit: 18\
    \ (2d10 + 7) piercing damage plus 10 (3d6) cold damage."
  "name": "Bite"
- "desc": "Melee Weapon Attack: +12 to hit, reach 5 ft., one target. Hit: 14\
    \ (2d6 + 7) slashing damage."
  "name": "Claw"
- "desc": "Melee Weapon Attack: +12 to hit, reach 15 ft., one target. Hit: 16\
    \ (2d8 + 7) bludgeoning damage."
  "name": "Tail"
- "desc": "Each creature of the dragon's choice that is within 120 feet of the dragon\
    \ and aware of it must succeed on a DC 18 Wisdom saving throw or suffer short-term\
    \ madness for 1 minute. A creature can repeat the saving throw at the end of each\
    \ of its turns, ending the effect on itself on a success. If a creature's saving\
    \ throw is successful or the effect ends for it, the creature is immune to the\
    \ dragon's Aura of Madness for the next 24 hours."
  "name": "Aura of Madness"
- "desc": "The dragon uses one of the following breath weapons.\n\n- Gravitic Breath.\
    \ The dragon exhales localized gravity in a 60‑foot cube, originating from the\
    \ dragon. When a creature ends a fall in the cube, it takes 1d10 bludgeoning\
    \ damage for every 10 feet it fell, to a maximum of 20d10. A creature that enters\
    \ the cube for the first time on a turn or starts its turn there must make a DC\
    \ 20 Dexterity saving throw. On a failure, the creature is [restrained](Mechanics/Rules/conditions.md#Restrained).\
    \ On a success, the creature's speed is halved as long as it remains in the cube.\
    \ A creature can repeat the saving throw at the end of each of its turns, ending\
    \ the effect on itself on a success. The cube lasts until the dragon's breath\
    \ weapon recharges.  \n- Stellar Breath. The dragon exhales star fire in a\
    \ 60-foot cone. Each creature in that area must make a DC 20 Dexterity saving\
    \ throw, taking 31 (9d6) fire damage and 31 (9d6) radiant damage on a failed\
    \ save, or half as much damage on a successful one.  "
  "name": "Breath Weapons (Recharge 5-6)"
"reactions":
- "desc": "The dragon adds 5 to its AC against one attack that would hit it, as it\
    \ twists reality to open a small rift in space to protect itself. To do so, the\
    \ dragon must be able to see the attacker. If the attack misses by 5 or more,\
    \ the dragon can choose to open a second, connected rift next to another creature\
    \ it can see within 30 feet of it to direct the attack at that creature instead,\
    \ using the original attack roll result against the new target's AC."
  "name": "Void Twist"
"legendary_actions":
- "desc": "The dragon makes a Wisdom ([Perception](Mechanics/Rules/skills.md#Perception))\
    \ check."
  "name": "Detect"
- "desc": "The dragon makes a Tail attack."
  "name": "Tail Attack"
- "desc": "The dragon twists the fabric of space around it, disappearing and reappearing\
    \ in an unoccupied space it can see within 120 feet of it. Each creature within\
    \ 10 feet of the dragon must succeed on a DC 20 Constitution saving throw or take\
    \ 14 (4d6) cold damage and be knocked [prone](Mechanics/Rules/conditions.md#Prone)."
  "name": "Void Slip (Costs 2 Actions)"
"lair_actions":
- "desc": "On initiative count 20 (losing initiative ties), the dragon takes a lair\
    \ action to cause one of the following effects; the dragon can't use the same\
    \ effect two rounds in a row:"
  "name": ""
- "desc": "- Orb of the Void. The Void briefly overlaps the dragon's lair in a\
    \ 20-foot-radius sphere of blackness punctuated by deep blue streaks and pinpoints\
    \ of light. The sphere is centered on a point the dragon can see within 120 feet\
    \ of the dragon. The sphere spreads around corners, is heavily obscured, and contains\
    \ no air (creatures must hold their breath). Each creature in the sphere when\
    \ it appears must make a DC 15 Constitution saving throw, taking 10 (3d6) cold\
    \ damage on a failed save, or half as much damage on a successful one. Any creature\
    \ that ends its turn in the sphere takes 10 (3d6) cold damage. The sphere lasts\
    \ until the dragon uses this lair action again or until the dragon dies.  \n-\
    \ Spatial Anomaly. The lair's connection to the Void briefly rips the fabric\
    \ of space, forcing two creatures the dragon can see within 120 feet of it to\
    \ suddenly exist at the same point in space and time. The laws of reality repel\
    \ the creatures back to their original positions as reality resets. The targets\
    \ aren't actually moved, but reality's reset forces each target to make a DC 15\
    \ Strength saving throw. On a failure, the creature takes 16 (3d10) force damage\
    \ and is knocked prone. On a success, the creature takes half the damage and isn't\
    \ knocked prone.  \n- Zero Gravity. Gravity stops working in a 50-foot radius,\
    \ 100-foot-high cylinder centered on a point the dragon can see within 120 feet\
    \ of it. Each creature in that cylinder drifts 10 feet away from the ground and\
    \ must succeed on a DC 15 Strength saving throw or be restrained. A flying creature\
    \ automatically succeeds on the saving throw, but its speed is halved unless it\
    \ can hover or flies magically. This effect lasts until initiative count 20 on\
    \ the next round.  "
  "name": ""
"regional_effects":
- "desc": "The region containing a legendary Void dragon's lair is warped by the dragon's\
    \ magic, which creates one or more of the following effects:"
  "name": ""
- "desc": "- Dark of the Void. Nonmagical illumination, including sunlight, can't\
    \ create bright light within 6 miles of the lair.  \n- Torn Veil. Within 3\
    \ miles of the lair, disembodied voices whisper in the night. Celestials, Fey,\
    \ and Fiends with a challenge rating of 2 or lower can choose to slip into the\
    \ Material Plane from their native planes or vice versa.  \n- Uncovered Knowledge.\
    \ Secrets have a way of coming to light within 6 miles of the lair. Clues are\
    \ inadvertently discovered, slips of the tongue hint at a hidden truth, and creatures\
    \ become morbidly curious for forbidden knowledge.  "
  "name": ""
- "desc": "If the dragon dies, these effects fade over the course of 1d10 days."
  "name": ""
"source":
- "ToB1-2023"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Adult%20Void%20Dragon.webp"
```
^statblock

## Environment

planar