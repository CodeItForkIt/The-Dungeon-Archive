---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/ghloe
- monster/cr/10
- monster/size/huge
- monster/type/celestial
statblock: inline
aliases: ["Empyrean Brazen Bull"]
---
# [Empyrean Brazen Bull](Mechanics\bestiary\celestial/empyrean-brazen-bull-ghloe.md)
*Source: Grim Hollow: Lairs of Etharis p. 100*  

> [!quote]  
> 
> The smell of smoke and incense consumed the castle walls, and we heard the furious and gleeful bellows of the most immense bull we'd ever seen. As our battlements burned and crumbled, we knew all was lost.

## Salvage

The exploded metal hide of the Empyrean brazen bull can be harvested to make gleaming and radiant [brazen armor](Mechanics/items/brazen-armor-ghloe.md) (see Appendix A of Lairs of Etharis). A proficient armor smith can make a suit of [brazen armor](Mechanics/items/brazen-armor-ghloe.md) by succeeding on a DC 20 Strength ([Athletics](Mechanics/Rules/skills.md#Athletics)) check and using 2500 gp of components. This process takes 20 days to complete.

## Lore

- **DC 10 Intelligence ([Nature](Mechanics/Rules/skills.md#Nature)).** Wildfires that seem to begin with hoofprints are sometimes found during the dry season in farmland, and bright spots on the horizon that look like a massive cow are often reported at the same time.  
- **DC 15 Intelligence ([Religion](Mechanics/Rules/skills.md#Religion)).** The Empyrean brazen bull is a beast of burden for angels, used for besieging enemies.  
- **DC 20 Intelligence ([Arcana](Mechanics/Rules/skills.md#Arcana)).** The Empyrean brazen bull explodes when it dies, and luck be with all in the wake of the blast.  

```statblock
"name": "Empyrean Brazen Bull (GHLoE)"
"size": "Huge"
"type": "celestial"
"alignment": "Lawful Good"
"ac": !!int "16"
"ac_class": "natural armor"
"hp": !!int "162"
"hit_dice": "12d12 + 84"
"stats":
- !!int "26"
- !!int "10"
- !!int "25"
- !!int "14"
- !!int "17"
- !!int "21"
"speed": "50 ft., fly 30 ft."
"saves":
  "Charisma": !!int "9"
  "Wisdom": !!int "7"
  "Strength": !!int "12"
  "Constitution": !!int "11"
"skillsaves":
  "Athletics": !!int "12"
  "Perception": !!int "7"
"damage_resistances": "acid; cold; lightning; bludgeoning, piercing, slashing from\
  \ nonmagical attacks"
"damage_immunities": "fire, necrotic, poison, radiant"
"condition_immunities": "[charmed](Mechanics/Rules/conditions.md#Charmed), [exhaustion](Mechanics/Rules/conditions.md#Exhaustion),\
  \ [frightened](Mechanics/Rules/conditions.md#Frightened), [prone](Mechanics/Rules/conditions.md#Prone),\
  \ [restrained](Mechanics/Rules/conditions.md#Restrained)"
"senses": "darkvision 120 ft., passive Perception 17"
"languages": "Celestial"
"cr": "10"
"traits":
- "desc": "The Empyrean brazen bull's weapon attacks are magical. When it hits with\
    \ any weapon, the weapon deals an extra 18 (4d8) radiant damage (included in\
    \ the attack)."
  "name": "Celestial Arsenal"
- "desc": "When the Empyrean brazen bull dies, it explodes, and each creature within\
    \ 20 feet of it must make a DC 17 Dexterity saving throw, taking 21 6d6 fire\
    \ and 21 (6d6) radiant damage on a failed save, or half as much damage on a\
    \ successful one."
  "name": "Death Throes"
- "desc": "At the start of each of the Empyrean brazen bull's turns, each creature\
    \ within 5 feet of it takes 10 (3d6) radiant damage. A creature that touches\
    \ the Empyrean brazen bull or hits it with a melee attack while within 5 feet\
    \ of it takes 10 (3d6) radiant damage."
  "name": "Soulfire Nimbus"
- "desc": "The Empyrean brazen bull deals double damage to objects and structures."
  "name": "Siege Monster"
- "desc": "If the Empyrean brazen bull moves at least 20 feet straight toward a creature\
    \ and then hits it with a gore attack on the same turn, that target must succeed\
    \ on a DC 20 Strength saving thrown or be knocked [prone](Mechanics/Rules/conditions.md#Prone).\
    \ If the target is [prone](Mechanics/Rules/conditions.md#Prone), the Empyrean\
    \ brazen bull can make one attack with its bite or hooves against it as a bonus\
    \ action."
  "name": "Unrelenting Charge"
"actions":
- "desc": "Melee Weapon Attack: +12 to hit, reach 10 ft., one target., Hit:\
    \ 24 (3d10 + 8) bludgeoning damage plus 18 (4d8) radiant damage. If the target\
    \ is a creature, it is [grappled](Mechanics/Rules/conditions.md#Grappled) (escape\
    \ DC 20). Until this grapple ends, the target is [restrained](Mechanics/Rules/conditions.md#Restrained),\
    \ and the Empyrean brazen bull can't bite another target."
  "name": "Bite"
- "desc": "Melee Weapon Attack: +12 to hit, reach 10 ft., one target. Hit: 27\
    \ (3d12 + 8) piercing damage and 18 (4d8) radiant damage."
  "name": "Gore"
- "desc": "Melee Weapon Attack: +12 to hit, reach 5 feet., one target. Hit:\
    \ 24 (3d10 + 8) bludgeoning damage and 18 (4d8) radiant damage."
  "name": "Hooves"
- "desc": "The Empyrean brazen bull makes one bite attack against a Medium or smaller\
    \ creature it is grappling. If the attack hits, that creature takes the bite's\
    \ damage and is swallowed, and the grapple ends. While swallowed, the creature\
    \ is [blinded](Mechanics/Rules/conditions.md#Blinded) and [restrained](Mechanics/Rules/conditions.md#Restrained),\
    \ it has total cover against attacks and other effects outside the Empyrean brazen\
    \ bull, and it takes 21 (6d6) fire damage at the start of each of theEmpyrean\
    \ brazen bull's turns. If the Empyrean brazen bull takes 30 damage or more on\
    \ a single turn from a creature inside it, the Empyrean brazen bull must succeed\
    \ on a DC 15 Constitution saving throw at the end of that turn or regurgitate\
    \ all swallowed creatures, which fall [prone](Mechanics/Rules/conditions.md#Prone)\
    \ in a space within 10 feet of the empyrean brazen bull. If the Empyrean brazen\
    \ bull dies, a swallowed creature is no longer [restrained](Mechanics/Rules/conditions.md#Restrained)\
    \ by it and can escape from the corpse using 15 feet of movement, exiting [prone](Mechanics/Rules/conditions.md#Prone)."
  "name": "Swallow"
"source":
- "GHLoE"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/GHLoE/Empyrean%20Brazen%20Bull.webp"
```
^statblock