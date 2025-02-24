---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/coa
- monster/cr/30
- monster/size/large
- monster/type/fiend/devil
statblock: inline
aliases: ["Asmodeus"]
---
# [Asmodeus](Mechanics\bestiary\npc/asmodeus-coa.md)
*Source: Chains of Asmodeus p. 217*  

> [!quote] A quote from Asmodeus  
> 
> You mortals should take pride in how you can make a hell out of any heaven.

Various myths claim that Asmodeus, has existed since the dawn of time. Perhaps most intriguing among the myths is the Serpent of Law. In it, Asmodeus was initially named Ahriman and, together with his rival Jazirian, created the outer realms. Their conflict led both deities to become severely wounded, and Asmodeus lost the exchange by landing in the Nine Hells. Here, he used his allies and own strength to banish the previous inhabitants and become what he remains today—Overlord of the Nine Hells.

Since his time as ruler, Asmodeus has seen much upset: a trial by gods, the Blood War, and the Reckoning. Despite many attempts to oust him, Asmodeus has never left his throne—none have even gotten close. Helping cement his power are the Dark Eight, a group of pit fiends sworn to absolute loyalty that rule his armies.

Those that know Asmodeus would describe him as arrogant, extremely intelligent, strategic, and honorable. Whenever possible, he follows the laws and regulations (that he himself created), and rarely loses his temper. Some of his plots have taken thousands of years to come to fruition, with countless others continuing to this day. Whether his persona is genuine, or simply another tool in his plans, only Asmodeus himself knows.

Many groups pledge allegiance to Asmodeus, and being the ruler of the Nine Hells, he has a large quantity of followers and worshippers. His biggest goal, largely unknown by mortals, is the opposite—encourage disbelief in deities altogether. According to legend, instead of going to the god they refuse worship, atheists go directly to the Nine Hells. Asmodeus feeds on these souls, which give him the necessary nourishment to lick his wounds. To this end, worshippers and cults dedicated to Asmodeus frequently experience fluctuations in presence, in an attempt to push them to disbelief.

Some claim that his true form is that of a colossal serpent, with gaping wounds and a missing tail. However, no living creature has seen the true Asmodeus. He prefers to do business using one of his ten avatars, each a perfect gentleman, and handsome to boot. They can be identified by the Ruby Rod they each carry, an icon representative of the Dark Lord himself.

## Asmodeus's Lair

The master of the Nine Hells makes his lair in his citadel of Malsheem. Within its confines linger millions of devils, and all of them are subject to Asmodeus's will and whims.

```statblock
"name": "Asmodeus (CoA)"
"size": "Large"
"type": "fiend"
"subtype": "devil"
"alignment": "Lawful Evil"
"ac": !!int "22"
"ac_class": "natural armor"
"hp": !!int "725"
"hit_dice": "50d10 + 450"
"stats":
- !!int "30"
- !!int "21"
- !!int "28"
- !!int "25"
- !!int "30"
- !!int "30"
"speed": "30 ft., fly 120 ft. (hover)"
"saves":
  "Charisma": !!int "19"
  "Intelligence": !!int "16"
  "Strength": !!int "19"
  "Constitution": !!int "18"
"skillsaves":
  "Intimidation": !!int "19"
  "Deception": !!int "28"
  "Religion": !!int "16"
  "Insight": !!int "28"
  "Perception": !!int "19"
  "Arcana": !!int "16"
  "Persuasion": !!int "19"
"damage_resistances": "cold"
"damage_immunities": "fire; poison; bludgeoning, piercing, slashing from nonmagical\
  \ attacks that aren't silvered"
"condition_immunities": "[blinded](Mechanics/Rules/conditions.md#Blinded), [charmed](Mechanics/Rules/conditions.md#Charmed),\
  \ [frightened](Mechanics/Rules/conditions.md#Frightened), [paralyzed](Mechanics/Rules/conditions.md#Paralyzed),\
  \ [poisoned](Mechanics/Rules/conditions.md#Poisoned), [stunned](Mechanics/Rules/conditions.md#Stunned)"
"senses": "darkvision 120 ft., truesight 60 ft., passive Perception 29"
"languages": "all, telepathy 120 ft."
"cr": "30"
"traits":
- "desc": "Asmodeus casts one of the following spells, requiring no material components\
    \ and using Wisdom as the spellcasting ability (spell save DC 27):\n\nAt will:\
    \ [Bane](Mechanics/spells/bane.md), [Bestow Curse](Mechanics/spells/bestow-curse.md),\
    \ [Command](Mechanics/spells/command.md), [Cure Wounds](Mechanics/spells/cure-wounds.md),\
    \ [Darkness](Mechanics/spells/darkness.md), [Lesser Restoration](Mechanics/spells/lesser-restoration.md),\
    \ [Remove Curse](Mechanics/spells/remove-curse.md)\n\n1/day each: [Antimagic\
    \ Field](Mechanics/spells/antimagic-field.md), [Earthquake](Mechanics/spells/earthquake.md),\
    \ [Flame Strike](Mechanics/spells/flame-strike.md), [Gate](Mechanics/spells/gate.md),\
    \ [Heal](Mechanics/spells/heal.md), [Mass Heal](Mechanics/spells/mass-heal.md),\
    \ [Wish](Mechanics/spells/wish.md)"
  "name": "Spellcasting"
- "desc": "Asmodeus has advantage on saving throws against spells and other magical\
    \ effects. Spells of level 4 or lower can't damage Asmodeus."
  "name": "Antimagic Aura"
- "desc": "Asmodeus regains 40 hit points at the start of his turn. If he takes radiant\
    \ damage, this trait doesn't function at the start of his next turn. Asmodeus\
    \ dies only if he starts his turn with 0 hit points and doesn't regenerate. If\
    \ Asmodeus dies, his body regenerates, returning to life 13 (2d12) days later."
  "name": "Fiendish Regeneration"
- "desc": "If Asmodeus fails a saving throw, he can choose to succeed instead."
  "name": "Legendary Resistance (3/Day)"
- "desc": "When a creature moves to be within 120 feet of Asmodeus, they must succeed\
    \ on a DC 24 Wisdom saving throw or have the [frightened](Mechanics/Rules/conditions.md#Frightened)\
    \ condition until they leave the aura. While [frightened](Mechanics/Rules/conditions.md#Frightened),\
    \ creatures kneel before Asmodeus, taking no actions unless he commands otherwise.\
    \ If Asmodeus deals damage to a kneeling creature, the creature's [frightened](Mechanics/Rules/conditions.md#Frightened)\
    \ condition ends. A creature that succeeds the saving throw is immune to this\
    \ effect for 1 hour."
  "name": "Submission Aura"
"actions":
- "desc": "Asmodeus makes four attacks using Ruby Rod, Chilling Gaze, or a combination\
    \ of the two. He can replace one of the attacks with Hellish Smite."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +21 to hit, reach 5 ft., one target. Hit: 21\
    \ (2d8 + 12) necrotic damage, which also reduces the target's hit point maximum\
    \ by the damage taken. This damage can't reduce a target's hit point maximum below\
    \ 1. Any effect that removes a disease allows a creature's hit point maximum to\
    \ return to normal."
  "name": "Ruby Rod"
- "desc": "Ranged Spell Attack: +16 to hit, range 60 ft., one target. Hit: 18\
    \ (2d10 + 7) cold damage, and the target has a-1 penalty to all attack rolls\
    \ they make until the end of their next turn. This penalty can stack."
  "name": "Chilling Gaze"
- "desc": "Asmodeus targets a creature he can see within 300 feet of him, calling\
    \ down a bolt of hellish lightning. The target must make a DC 24 Dexterity saving\
    \ throw, taking 14 (4d6) lightning damage plus 14 (4d6) fire damage on a failed\
    \ save, or half as much damage on a successful one."
  "name": "Hellish Smite"
- "desc": "Asmodeus targets a creature he can see within 120 feet of him. The target\
    \ must make a DC 24 Intelligence saving throw, taking 45 (10d8) force damage\
    \ on a failed save, or half as much damage on a successful one. A creature that\
    \ failed the save is [stunned](Mechanics/Rules/conditions.md#Stunned) for up to\
    \ 1 minute. The [stunned](Mechanics/Rules/conditions.md#Stunned) creature can\
    \ repeat the saving throw at the end of each of its turns, ending the effect on\
    \ itself on a success, but taking the damage again on a failed save."
  "name": "Infernal Word: Stun (Recharge 4-6)"
- "desc": "Asmodeus targets a creature he can see within 120 feet of him. The target\
    \ must make a DC 24 Charisma saving throw, taking 44 (8d10) psychic damage on\
    \ a failed save, or half as much damage on a successful one. A creature that failed\
    \ the save has the [charmed](Mechanics/Rules/conditions.md#Charmed) condition\
    \ for up to 1 minute. While [charmed](Mechanics/Rules/conditions.md#Charmed),\
    \ a creature is controlled by Asmodeus, performing only actions that he suggests.\
    \ A [charmed](Mechanics/Rules/conditions.md#Charmed) creature can repeat the saving\
    \ throw at the end of each of its turns, ending the effect on itself on a success,\
    \ but taking the damage again on a failed save."
  "name": "Hell-Lord's Suggestion (Recharge 5-6)"
- "desc": "Asmodeus chooses a point he can see within 500 feet of him, which explodes\
    \ into a roaring inferno. All creatures within a 60-foot-radius sphere centered\
    \ on that point must make a DC 24 Dexterity saving throw, taking 70 (20d6) fire\
    \ damage on a failed save, or half as much damage on a successful one."
  "name": "Fires of the Nine Hells (Recharge 5-6)"
"reactions":
- "desc": "As a reaction to being the sole target of a spell, Asmodeus can attempt\
    \ to absorb the spell into the Ruby Rod.\n\nAsmodeus rolls ( + 2), and if the\
    \ result is higher than (10 + spell level), the spell is absorbed into the rod\
    \ and has no effect."
  "name": "Ruby Absorption"
"legendary_actions":
- "desc": "The Ruby Rod has 66 charges. Asmodeus may spend its charges to cast one\
    \ of the following spells from it, with a spell save DC of 20: [Lesser Restoration](Mechanics/spells/lesser-restoration.md)\
    \ (3 charges), [Wall of Force](Mechanics/spells/wall-of-force.md) (7 charges),\
    \ [Greater Restoration](Mechanics/spells/greater-restoration.md) (12 charges),\
    \ [Chain Lightning](Mechanics/spells/chain-lightning.md) (15 charges), [Prismatic\
    \ Spray](Mechanics/spells/prismatic-spray.md) (23 charges), [Globe of Invulnerability](Mechanics/spells/globe-of-invulnerability.md)\
    \ (33 charges)"
  "name": "Channel Ruby Rod"
- "desc": "Asmodeus makes a Ruby Rod attack."
  "name": "Strike (Costs 2 Actions)"
- "desc": "Asmodeus summons an allied [pit fiend](Mechanics/bestiary/fiend/pit-fiend.md)\
    \ in an unoccupied space that he can see."
  "name": "Call Underling (Costs 3 Actions)"
"regional_effects":
- "desc": "The region containing Asmodeus's lair is corrupted by his presence, which\
    \ creates the following effect:"
  "name": ""
- "desc": "- The Devil's Greeting. Within 500 miles of his lair, an illusory version\
    \ of Asmodeus (as if he has cast the [Project Image](Mechanics/spells/project-image.md)\
    \ spell) appears. Asmodeus attempts to communicate with any characters and decipher\
    \ their intentions. If they're hostile, Asmodeus pretends to prepare himself for\
    \ combat, in an effort to make the character's waste their resources.  "
  "name": ""
- "desc": "If Asmodeus dies, the effects fade over the course of 1d10 days."
  "name": ""
"lair_actions":
- "desc": "On initiative count 20 (losing initiative ties), Asmodeus can take one\
    \ lair action to cause the following effect or one from the archdevil lair action\
    \ list (page 214); he can't take the same lair action two rounds in a row:"
  "name": ""
- "desc": "- Cleansing Flame. Asmodeus selects one spell effect on himself or\
    \ a creature of his choice within 60 feet. That spell effect is removed.  "
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
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/CoA/Asmodeus.webp"
```
^statblock