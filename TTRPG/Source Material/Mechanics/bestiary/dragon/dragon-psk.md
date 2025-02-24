---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/psk
- monster/cr/17
- monster/size/huge
- monster/type/dragon
statblock: inline
aliases: ["Dragon"]
---
# [Dragon](Mechanics\bestiary\dragon/dragon-psk.md)
*Source: Plane Shift: Kaladesh p. 29*  

Dragons are the apex predators of the skies. They are usually found in rural areas, avoiding the crowds of air ships and thopters found above the cities of Kaladesh. Their favorite prey are the sky whales that drift through the aethersphere, but they also hunt leviathans, wurms, hydras, drakes, giants—and airships.

Dragons typically hunt by perching on a promontory or hilltop, remaining perfectly still as they wait for prey to come into view. With a single snap of its powerful wings, a dragon can launch itself into the air with lightning speed, hurtling toward its target like a deadly arrow.

Dragons resemble a cross between a lizard and a tiger, with powerful feline bodies covered in striped fur, reptilian heads crowned with long horns, and enormous leathery wings that propel them through the sky at tremendous speed. Their chests are adorned with elaborate patterns resembling fine filigree.

The [red dragon](Mechanics/bestiary/dragon/adult-red-dragon.md) statistics work well for the dragons of Kaladesh, though dragons rarely reach ancient age on that plane. They can spew great blasts of flame, but a dragon's preferred method of assault is to hold flame in its mouth as it attacks. This counts as a use of the dragon's breath weapon, but the dragon makes a special bite attack. On a hit, the bite attack deals its normal piercing damage plus the fire damage from the dragon's breath weapon, with no saving throw.

```statblock
"name": "Dragon (PSK)"
"size": "Huge"
"type": "dragon"
"alignment": "Chaotic Evil"
"ac": !!int "19"
"ac_class": "natural armor"
"hp": !!int "256"
"hit_dice": "19d12 + 133"
"stats":
- !!int "27"
- !!int "10"
- !!int "25"
- !!int "16"
- !!int "13"
- !!int "21"
"speed": "40 ft., climb 40 ft., fly 80 ft."
"saves":
  "Charisma": !!int "11"
  "Dexterity": !!int "6"
  "Wisdom": !!int "7"
  "Constitution": !!int "13"
"skillsaves":
  "Stealth": !!int "6"
  "Perception": !!int "13"
"damage_immunities": "fire"
"senses": "blindsight 60 ft., darkvision 120 ft., passive Perception 23"
"languages": "Common, Draconic"
"cr": "17"
"traits":
- "desc": "If the dragon fails a saving throw, it can choose to succeed instead."
  "name": "Legendary Resistance (3/Day)"
"actions":
- "desc": "The dragon can use its Frightful Presence. It then makes three attacks:\
    \ one with its bite and two with its claws."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +14 to hit, reach 10 ft., one target. Hit: 19\
    \ (2d10 + 8) piercing damage plus 7 (2d6) fire damage."
  "name": "Bite"
- "desc": "Melee Weapon Attack: +14 to hit, reach 5 ft., one target. Hit: 15\
    \ (2d6 + 8) slashing damage."
  "name": "Claw"
- "desc": "Melee Weapon Attack: +14 to hit, reach 15 ft., one target. Hit: 17\
    \ (2d8 + 8) bludgeoning damage."
  "name": "Tail"
- "desc": "Each creature of the dragon's choice that is within 120 feet of the dragon\
    \ and aware of it must succeed on a DC 19 Wisdom saving throw or become [frightened](Mechanics/Rules/conditions.md#Frightened)\
    \ for 1 minute. A creature can repeat the saving throw at the end of each of its\
    \ turns, ending the effect on itself on a success. If a creature's saving throw\
    \ is successful or the effect ends for it, the creature is immune to the dragon's\
    \ Frightful Presence for the next 24 hours."
  "name": "Frightful Presence"
- "desc": "The dragon exhales fire in a 60-foot cone. Each creature in that area must\
    \ make a DC 21 Dexterity saving throw, taking 63 (18d6) fire damage on a failed\
    \ save, or half as much damage on a successful one."
  "name": "Fire Breath (Recharge 5-6)"
- "desc": "Melee Weapon Attack: +14 to hit, reach 10 ft., one target. Hit: 19\
    \ (2d10 + 8) piercing damage plus 63 (18d6) fire damage. This counts as a\
    \ use of the dragon's breath weapon."
  "name": "Fiery Bite (Recharge 5-6)"
"legendary_actions":
- "desc": "The dragon makes a Wisdom ([Perception](Mechanics/Rules/skills.md#Perception))\
    \ check."
  "name": "Detect"
- "desc": "The dragon makes a tail attack."
  "name": "Tail Attack"
- "desc": "The dragon beats its wings. Each creature within 10 feet of the dragon\
    \ must succeed on a DC 22 Dexterity saving throw or take 15 (2d6 + 8) bludgeoning\
    \ damage and be knocked [prone](Mechanics/Rules/conditions.md#Prone). The dragon\
    \ can then fly up to half its flying speed."
  "name": "Wing Attack (Costs 2 Actions)"
"lair_actions":
- "desc": "On initiative count 20 (losing initiative ties), the dragon takes a lair\
    \ action to cause one of the following effects; the dragon can't use the same\
    \ effect two rounds in a row:"
  "name": ""
- "desc": "- Magma erupts from a point on the ground the dragon can see within 120\
    \ feet of it, creating a 20-foot-high, 5-foot-radius geyser. Each creature in\
    \ the geyser's area must make a DC 15 Dexterity saving throw, taking 21 (6d6)\
    \ fire damage on a failed save, or half as much damage on a successful one.  \n\
    - A tremor shakes the lair in a 60-foot radius around the dragon. Each creature\
    \ other than the dragon on the ground in that area must succeed on a DC 15 Dexterity\
    \ saving throw or be knocked [prone](Mechanics/Rules/conditions.md#Prone).  \n\
    - Volcanic gases form a cloud in a 20-foot-radius sphere centered on a point the\
    \ dragon can see within 120 feet of it. The sphere spreads around corners, and\
    \ its area is lightly obscured. It lasts until initiative count 20 on the next\
    \ round. Each creature that starts its turn in the cloud must succeed on a DC\
    \ 13 Constitution saving throw or be [poisoned](Mechanics/Rules/conditions.md#Poisoned)\
    \ until the end of its turn. While [poisoned](Mechanics/Rules/conditions.md#Poisoned)\
    \ in this way, a creature is [incapacitated](Mechanics/Rules/conditions.md#Incapacitated).\
    \  "
  "name": ""
- "desc": "At your discretion, a legendary ([adult](Mechanics/bestiary/dragon/adult-red-dragon.md)\
    \ or [ancient](Mechanics/bestiary/dragon/ancient-red-dragon.md)) red dragon can\
    \ use one or both of the following additional lair actions while in its lair:\n\
    \n- Noxious Smoke. A cloud of thick, dark smoke fills a 20-foot-radius sphere\
    \ centered on a point the dragon can see within 120 feet of it. The sphere spreads\
    \ around corners, and its area is heavily obscured. A creature other than the\
    \ dragon that starts its turn in the cloud or enters it for the first time on\
    \ its turn must succeed on a DC 15 Constitution saving throw or be [poisoned](Mechanics/Rules/conditions.md#Poisoned)\
    \ until the end of its turn. The cloud lasts until initiative count 20 on the\
    \ next round.  \n- Searing Heat. Searing heat spreads out in a 15-foot-radius\
    \ sphere centered on a point the dragon can see within 120 feet of it. Any creature\
    \ that enters the affected area or starts its turn there must make a DC 15 Constitution\
    \ saving throw, taking 10 (3d6) fire damage on a failed save, or half as much\
    \ damage on a successful one. The heat lasts until initiative count 20 on the\
    \ next round.  "
  "name": "Additional Lair Actions"
"regional_effects":
- "desc": "The region containing a legendary red dragon's lair is warped by the dragon's\
    \ magic, which creates one or more of the following effects:"
  "name": ""
- "desc": "- Small earthquakes are common within 6 miles of the dragon's lair.  \n\
    - Water sources within 1 mile of the lair are supernaturally warm and tainted\
    \ by sulfur.  \n- Rocky fissures within 1 mile of the dragon's lair form portals\
    \ to the Elemental Plane of Fire, allowing creatures of elemental fire into the\
    \ world to dwell nearby.  "
  "name": ""
- "desc": "If the dragon dies, these effects fade over the course of 1d10 days."
  "name": ""
- "desc": "Any of these effects might appear in the area around a red dragon's lair,\
    \ in addition to or instead of the effects described in the Monster Manual:\n\
    \n- Desertification. Precipitation is almost nonexistent within 6 miles of\
    \ the dragon's lair, making the land parched and arid and most plant life withered\
    \ and brown.  \n- Fiery Senses. The dragon can hear up to 30 feet through\
    \ any open flame within 1 mile of the dragon's lair.  \n- Ominous Flames.\
    \ Open flames within 6 miles of the dragon's lair are tinged dark red, hiss and\
    \ crackle constantly, and throw off embers and showers of sparks.  "
  "name": "Additional Regional Effects"
"source":
- "PSK"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/PSK/Dragon.webp"
```
^statblock