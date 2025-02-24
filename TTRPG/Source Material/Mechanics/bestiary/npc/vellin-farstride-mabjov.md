---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/mabjov
- monster/cr/9
- monster/size/small
- monster/type/humanoid/halfling
statblock: inline
aliases: ["Vellin Farstride"]
---
# [Vellin Farstride](Mechanics\bestiary\npc/vellin-farstride-mabjov.md)
*Source: Minsc and Boo's Journal of Villainy p. 62*  

> [!quote] A quote from MINSC  
> 
> COURAGE, FRIENDSHIP, AND the sound of steel on steel! These are the stuff of all great adventures. The fight for justice is hard, sweaty work, but when the times get tough, the tough get hamsters!

Vellin Farstride has earned his last name with a travelogue that would be the envy of any would-be explorer. Vellin specializes in hunting fiendish enemies and other extra planar threats. Vellin is almost always accompanied by his faithful wolf, Akela, and often rides the beast into battle.

Originally from the world of Oerth, Vellin arrived in Faerûn several years ago. Between those two worlds Vellin traveled the Astral Sea, hunted demons in the Blood War, dealt with hags in the Gray Waste and assassinated Infernal Dukes on Avernus. Vellin quickly fell in love with the vast and beautiful wilds of Faerûn and decided that it would be his home. In order to protect his new home, Vellin wanted to band together with formidable allies that could protect it from outer planar threats. He discovered that the Harpers had values that were closest to his own.

Vellin is adept at diplomacy and deception, out of necessity from having to deal with Fiendish powers. Though not physically intimidating, his quiet intensity and well-earned confidence can be very convincing. He prefers simple and direct language, even when dealing with nobles and royalty, but can employ eloquence and flattery when the need arises.

## Vellin as a Contact

Vellin is the primary contact for members of the Harpers at low levels. Vellin is an expert at obtaining mounts on short notice for those who need to get somewhere quickly. Each member of your group gets access to the type of mount requested. If any of the mounts die while under your control (or a member of your group), you can never use that type of mount again. Otherwise, you can use the mount as long as needed.

**Mounts via Vellin**

| Mount | Required Level | Terrain |
|-------|----------------|---------|
| Riding horses | 1 | Land |
| Camels | 1 | Desert |
| Dolphins | 3 | Water |
| Hippogriffons | 3 | Air |
| Giant striders | 7 | Fire |
| Polar bears | 7 | Cold |
^mounts-via-vellin

```statblock
"name": "Vellin Farstride (MaBJoV)"
"size": "Small"
"type": "humanoid"
"subtype": "halfling"
"alignment": "Neutral Good"
"ac": !!int "20"
"ac_class": "[studded leather](Mechanics/items/studded-leather-armor.md), [+1 shield](Mechanics/items/1-shield.md)"
"hp": !!int "195"
"hit_dice": "30d6 + 90"
"stats":
- !!int "11"
- !!int "20"
- !!int "16"
- !!int "11"
- !!int "14"
- !!int "11"
"speed": "25 ft."
"saves":
  "Dexterity": !!int "9"
  "Wisdom": !!int "6"
"skillsaves":
  "Nature": !!int "8"
  "Deception": !!int "4"
  "Stealth": !!int "13"
  "Perception": !!int "10"
  "Survival": !!int "10"
  "Persuasion": !!int "8"
"senses": "passive Perception 20"
"languages": "Abyssal, Common, Halfling, Infernal, telepathy 30 ft."
"cr": "9"
"traits":
- "desc": "Vellin is accompanied by Akela ([wolf](Mechanics/bestiary/beast/wolf.md)\
    \ with 18 hit points). Vellin can mount or dismount Akela using 5 feet of movement.\
    \ While mounted, Vellin can order Akela to Dash, Disengage, and Dodge. In addition,\
    \ Vellin has an [owl](Mechanics/bestiary/beast/owl.md) companion with 3 hit points.\
    \ On Vellin's turn, the owl can perform a flyby on a creature of Vellin's choice.\
    \ The next attack that Vellin makes against that creature has advantage."
  "name": "Animal Companions"
- "desc": "Vellin has advantage on saving throws against being [frightened](Mechanics/Rules/conditions.md#Frightened)."
  "name": "Brave"
- "desc": "When Vellin hits a Fiend with a weapon attack he deals an additional 7\
    \ (2d6) radiant damage."
  "name": "Fiend Slayer"
- "desc": "Vellin has advantage on Wisdom ([Perception](Mechanics/Rules/skills.md#Perception))\
    \ checks that rely on hearing or sight."
  "name": "Keen Hearing and Sight"
- "desc": "Vellin wields a +1 shortsword (silvered) and a +1 shield."
  "name": "Special Equipment"
"actions":
- "desc": "Vellin makes three Silvered Shortsword attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +10 to hit, reach 5 ft., one target. Hit: 9\
    \ (1d6 + 6) piercing damage."
  "name": "Silvered Shortsword"
"bonus_actions":
- "desc": "Vellin can take the Disengage or Hide action."
  "name": "Nimble Escape"
"source":
- "MaBJoV"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/MaBJoV/Vellin%20Farstride.webp"
```
^statblock