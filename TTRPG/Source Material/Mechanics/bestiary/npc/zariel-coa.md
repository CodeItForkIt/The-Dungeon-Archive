---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/coa
- monster/cr/26
- monster/size/large
- monster/type/fiend/devil
statblock: inline
aliases: ["Zariel"]
---
# [Zariel](Mechanics\bestiary\npc/zariel-coa.md)
*Source: Chains of Asmodeus p. 235*  

Once a mighty angel charged with watching the tides of the Blood War, Zariel succumbed to the corrupting influence of the Nine Hells and fell from grace. Asmodeus admired Zariel's passion for war and offered her rulership of Avernus. She accepted his offer and was transformed by Asmodeus into an archdevil.

Zariel's rise came at the expense of Bel, her pit fiend predecessor. Zariel and Bel hate each other. To keep Bel busy and out of her sight, Zariel tasks him with forging weapons, armor, and gruesome demon-slaying machines.

## Zariel's Lair

Zariel makes her lair in a basalt citadel that rises up in Avernus. The stronghold, covering five square miles, is surrounded by walls reinforced with high turrets.

```statblock
"name": "Zariel (CoA)"
"size": "Large"
"type": "fiend"
"subtype": "devil"
"alignment": "Lawful Evil"
"ac": !!int "21"
"ac_class": "natural armor"
"hp": !!int "420"
"hit_dice": "29d10 + 261"
"stats":
- !!int "27"
- !!int "24"
- !!int "28"
- !!int "26"
- !!int "27"
- !!int "30"
"speed": "50 ft., fly 150 ft."
"saves":
  "Charisma": !!int "18"
  "Wisdom": !!int "16"
  "Intelligence": !!int "16"
"skillsaves":
  "Intimidation": !!int "18"
  "Perception": !!int "16"
"damage_resistances": "cold; fire; radiant; bludgeoning, piercing, slashing from nonmagical\
  \ attacks that aren't silvered"
"damage_immunities": "necrotic, poison"
"condition_immunities": "[charmed](Mechanics/Rules/conditions.md#Charmed), [exhaustion](Mechanics/Rules/conditions.md#Exhaustion),\
  \ [frightened](Mechanics/Rules/conditions.md#Frightened), [poisoned](Mechanics/Rules/conditions.md#Poisoned)"
"senses": "darkvision 120 ft., passive Perception 26"
"languages": "all, telepathy 120 ft."
"cr": "26"
"traits":
- "desc": "Zariel casts one of the following spells, requiring no material components\
    \ and using Charisma as the spellcasting ability (spell save DC 26):\n\nAt will:\
    \ [Alter Self](Mechanics/spells/alter-self.md) (can become Medium when changing\
    \ her appearance), [Detect Evil and Good](Mechanics/spells/detect-evil-and-good.md),\
    \ [Fireball](Mechanics/spells/fireball.md), [Invisibility](Mechanics/spells/invisibility.md)\
    \ (self only), [Major Image](Mechanics/spells/major-image.md), [Wall of Fire](Mechanics/spells/wall-of-fire.md)\n\
    \n2/day each: [Blade Barrier](Mechanics/spells/blade-barrier.md), [Dispel\
    \ Evil and Good](Mechanics/spells/dispel-evil-and-good.md), [Finger of Death](Mechanics/spells/finger-of-death.md)"
  "name": "Spellcasting"
- "desc": "Magical darkness doesn't impede Zariel's darkvision."
  "name": "Devil's Sight"
- "desc": "If Zariel fails a saving throw, she can choose to succeed instead."
  "name": "Legendary Resistance (3/Day)"
- "desc": "Zariel has advantage on saving throws against spells and other magical\
    \ effects."
  "name": "Magic Resistance"
- "desc": "Zariel regains 20 hit points at the start of her turn. If she takes radiant\
    \ damage, this trait doesn't function at the start of her next turn. Zariel dies\
    \ only if she starts her turn with 0 hit points and doesn't regenerate."
  "name": "Regeneration"
"actions":
- "desc": "Zariel makes three Flail or Longsword attacks. She can replace one attack\
    \ with a use of Horrid Touch, if available."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +16 to hit, reach 10 ft., one target. Hit: 17\
    \ (2d8 + 8) force damage plus 36 (8d8) fire damage."
  "name": "Flail"
- "desc": "Melee Weapon Attack: +16 to hit, reach 10 ft., one target. Hit: 17\
    \ (2d8 + 8) radiant damage or 19 (2d10 + 8) radiant damage when used with\
    \ two hands, plus 36 (8d8) fire damage."
  "name": "Longsword"
- "desc": "Zariel touches one creature within 10 feet of her. The target must succeed\
    \ on a DC 26 Constitution saving throw or take 44 (8d10) necrotic damage and\
    \ have the [poisoned](Mechanics/Rules/conditions.md#Poisoned) condition for 1\
    \ minute. While [poisoned](Mechanics/Rules/conditions.md#Poisoned) in this way,\
    \ the target has the [blinded](Mechanics/Rules/conditions.md#Blinded) and [deafened](Mechanics/Rules/conditions.md#Deafened)\
    \ conditions. The target can repeat the saving throw at the end of each of its\
    \ turns, ending the effect on itself on a success."
  "name": "Horrid Touch (Recharge 5-6)"
- "desc": "Zariel magically teleports, along with any equipment she is wearing or\
    \ carrying, up to 120 feet to an unoccupied space she can see."
  "name": "Teleport"
"legendary_actions":
- "desc": "Zariel uses Teleport."
  "name": "Teleport"
- "desc": "Zariel turns her magical gaze toward one creature she can see within 120\
    \ feet of her and commands it to burn. The target must succeed on a DC 26 Wisdom\
    \ saving throw or take 22 (4d10) fire damage."
  "name": "Immolating Gaze (Costs 2 Actions)"
"regional_effects":
- "desc": "The region containing Zariel's lair is warped by her magic, which creates\
    \ the following effect:"
  "name": ""
- "desc": "- Hellscape. The area within 9 miles of the lair is filled with screaming\
    \ voices and the stench of burning meat.  "
  "name": ""
- "desc": "If Zariel dies, these effects fade over the course of 1d10 days."
  "name": ""
"lair_actions":
- "desc": "On initiative count 20 (losing initiative ties), Zariel can take one lair\
    \ action to cause the following effect or one from the archdevil lair action list\
    \ (page 214); she can't take the same lair action two rounds in a row:"
  "name": ""
- "desc": "- Infernal Illusions. Zariel casts the [Major Image](Mechanics/spells/major-image.md)\
    \ spell four times, targeting different areas with it. Zariel prefers to create\
    \ images of intruders' loved ones being burned alive. Zariel doesn't need to concentrate\
    \ on the spells, which end on initiative count 20 of the next round. Each creature\
    \ that can see these illusions must succeed on a DC 26 Wisdom saving throw or\
    \ have the frightened condition for 1 minute. A frightened creature can repeat\
    \ the saving throw at the end of each of its turns, ending the effect on itself\
    \ on a success.  "
  "name": ""
- "desc": "- Attack. The archdevil uses one of their available melee or ranged\
    \ attacks against a single foe.  \n- Cast a Spell. The archdevil uses their\
    \ Spellcasting feature to cast an available spell. If the spell normally requires\
    \ [concentration](Mechanics/Rules/conditions.md#Concentration), it lasts for the\
    \ full duration instead.  \n- Deceitful Whispers. The archdevil whispers to\
    \ a creature they can see within 30 feet. The target must make a DC 22 Wisdom\
    \ saving throw. On a failed save, the target has the charmed condition until the\
    \ start of their next turn and must use their reaction immediately to make an\
    \ attack against one of the archdevil's enemies, chosen by the archdevil.  \n\
    - Fiendish Fortitude. The archdevil recharges one of their expended abilities.\
    \  \n- Frenzy. The archdevil casts [Haste](Mechanics/spells/haste.md) on themself.\
    \ The effect ends at initiative count 20 of the next round.  \n- Summon Underlings.\
    \ The archdevil summons allied devils. The devils summoned depends on the archdevil\
    \ using this feature. The summoned devils appear in unoccupied spaces which the\
    \ archdevil can see. The [Summoned Underlings](Mechanics/tables/archdevil-lair-action-list-summoned-underlings-coa.md)\
    \ table shows which devils each archdevil can summon.  \n- Teleport. The archdevil\
    \ teleports themself to an area they can see within 120 feet.  \n- Trap. The\
    \ archdevil casts the [Hold Monster](Mechanics/spells/hold-monster.md) spell.\
    \  "
  "name": ""
"source":
- "CoA"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/CoA/Zariel.webp"
```
^statblock