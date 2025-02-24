---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/coa
- monster/cr/25
- monster/size/medium
- monster/type/fiend/devil
statblock: inline
aliases: ["Glasya"]
---
# [Glasya](Mechanics\bestiary\npc/glasya-coa.md)
*Source: Chains of Asmodeus p. 226*  

Glasya is known by many names: the Dark Prodigy, the Princess of the Nine Hells, and Lord of Malbolge. She maintains control over the erinyes and has a massive following within the downtrodden and the neglected royalty of the other planes. For a long time, she was simply a lesser archdevil, jumping between various courts as she saw fit. It wasn't until the Reckoning, which she helped instigate, that she claimed true power and became ruler of one of the nine layers.

Asmodeus, her father, and Glasya share much in common—particularly their cunning, ambition, and "dedication" to laws. Because of this, despite some of the hatred Glasya has towards her father, the two share a relationship of respect and support.

Even though she busies herself with many important undertakings to further cement her power, being surrounded by beautiful things is also important to Glasya. Similarly, she detests the ugly, punishing those she sees as disgusting. During her brief relationship with Mammon, she was rarely found in his swampy domain, choosing instead to roam other layers. Almost everything that interacts with Glasya either deeply loves or loathes her. She maintains a charming persona, often even converting spies from other archdevils to her side.

Perhaps contributing to her obsession with beauty, Glasya herself is considered stunning. Her jet-black hair and copper skin hide her infernal nature, though her large, leathery wings and small horns give it away. Due to her ability to polymorph at will, she can meet various other standards of beauty as well, always maintaining an outward charm—which helps conceal her foul core.

## Glasya's Lair

Glasya built her fortress lair, Ossiea, from the grotesquely enlarged and distorted skull of Malagard. Behind the walls of the skull, there are numerous opulent levels, within which Glasya conducts the business of ruling her realm or indulges her other interests.

```statblock
"name": "Glasya (CoA)"
"size": "Medium"
"type": "fiend"
"subtype": "devil"
"alignment": "Lawful Evil"
"ac": !!int "21"
"ac_class": "natural armor"
"hp": !!int "380"
"hit_dice": "40d8 + 200"
"stats":
- !!int "22"
- !!int "28"
- !!int "20"
- !!int "21"
- !!int "25"
- !!int "28"
"speed": "40 ft., fly 80 ft."
"saves":
  "Charisma": !!int "17"
  "Dexterity": !!int "17"
  "Wisdom": !!int "15"
  "Intelligence": !!int "13"
"skillsaves":
  "Intimidation": !!int "17"
  "Deception": !!int "25"
  "Stealth": !!int "25"
  "Perception": !!int "15"
  "Survival": !!int "15"
  "Persuasion": !!int "17"
"damage_resistances": "cold; necrotic; radiant; bludgeoning, piercing, slashing from\
  \ nonmagical attacks that aren't silvered"
"damage_immunities": "fire, poison"
"condition_immunities": "[charmed](Mechanics/Rules/conditions.md#Charmed), [poisoned](Mechanics/Rules/conditions.md#Poisoned)"
"senses": "blindsight 60 ft., darkvision 120 ft., passive Perception 25"
"languages": "Celestial, Common, Draconic, Infernal, telepathy 120 ft."
"cr": "25"
"traits":
- "desc": "When a creature moves to be within 120 feet of Glasya, they must succeed\
    \ on a DC 23 Wisdom saving throw or have the [charmed](Mechanics/Rules/conditions.md#Charmed)\
    \ condition, treating Glasya as an ally, until they leave the aura. A creature\
    \ that succeeds the saving throw is immune to this effect for 1 hour. Whenever\
    \ a [charmed](Mechanics/Rules/conditions.md#Charmed) creature takes damage, they\
    \ may repeat the saving throw, ending the effect on a success."
  "name": "Charm Aura"
- "desc": "Glasya deals an additional 13 (2d12) psychic damage when attacking a\
    \ [charmed](Mechanics/Rules/conditions.md#Charmed) creature, and her attacks don't\
    \ break charms."
  "name": "Dominating Presence"
- "desc": "Glasya regains 20 hit points at the start of her turn. If she takes radiant\
    \ damage this trait doesn't function at the start of her next turn. Glasya dies\
    \ only if she starts her turn with 0 hit points and is unable to regenerate. If\
    \ Glasya is killed, her body slowly regenerates, returning to life 9 (2d8) weeks\
    \ later."
  "name": "Fiendish Regeneration"
- "desc": "If Glasya fails a saving throw, she can choose to succeed instead."
  "name": "Legendary Resistance (3/Day)"
- "desc": "Glasya has advantage on saving throws against spells and other magical\
    \ effects."
  "name": "Magic Resistance"
"actions":
- "desc": "Glasya makes four attacks using Scourge of Shadow, Necrotic Grasp, or a\
    \ combination of the two. She can replace one of the attacks with Mesmerizing\
    \ Gaze."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +20 to hit, reach 10 ft., one target. Hit: 19\
    \ (3d4 + 12) slashing damage, plus 5 (2d4) necrotic damage. This attack scores\
    \ a critical on a roll of 18, 19, or 20."
  "name": "Scourge of Shadow"
- "desc": "Glasya summons necrotic hands to grope and claw at a creature she can see\
    \ within 90 feet of her. The target must make a DC 25 Constitution saving throw,\
    \ taking 20 (2d10 + 9) necrotic damage on a failed save, or half as much damage\
    \ on a successful one."
  "name": "Necrotic Grasp"
- "desc": "Glasya focuses her gaze in a 60-foot cone in front of her. Each creature\
    \ of her choice within the cone must make a DC 23 Charisma saving throw or have\
    \ the [charmed](Mechanics/Rules/conditions.md#Charmed) condition until the end\
    \ of their next turn. While [charmed](Mechanics/Rules/conditions.md#Charmed),\
    \ creatures automatically fail saving throws from abilities used by Glasya and\
    \ move to be as close to her as possible."
  "name": "Mesmerizing Gaze"
- "desc": "Glasya targets a creature she can see within 60 feet of her. The target\
    \ must make a DC 25 Constitution saving throw, taking 61 (7d8 + 30) necrotic\
    \ damage on a failed save, or half as much damage on a successful one. A Humanoid\
    \ killed by this ability rises at the start of Glasya's next turn as a zombie\
    \ permanently under her command."
  "name": "Deathly Exclamation (1/Day)"
"legendary_actions":
- "desc": "Glasya makes a Scourge of Shadow attack."
  "name": "Whip"
- "desc": "Glasya casts [Confusion](Mechanics/spells/confusion.md) (30-foot-radius,\
    \ spell save DC 25), but only lasting until the end of Glasya's next turn."
  "name": "Disorient (Costs 2 Actions)"
- "desc": "Glasya summons an allied [erinyes](Mechanics/bestiary/fiend/erinyes.md)\
    \ in an unoccupied space that she can see."
  "name": "Call Underling (Costs 3 Actions)"
"regional_effects":
- "desc": "The region containing Glasya's lair is corrupted by her presence, which\
    \ creates the following effect:"
  "name": ""
- "desc": "- Hag's Gaze. Every hour that a good creature travels within 1 mile\
    \ of the lair, a blast of fire erupts from one of the eye sockets of the lair.\
    \ If the target fails a DC 23 Dexterity saving throw, they take 42 (12d6) fire\
    \ damage, half on a successful save. If the creature was flying and fails the\
    \ saving throw, it falls. Only one such creature is targeted each hour.  "
  "name": ""
- "desc": "If Glasya dies, the effects fade over the course of 1d10 days."
  "name": ""
"lair_actions":
- "desc": "On initiative count 20 (losing initiative ties), Glasya can take one lair\
    \ action to cause the following effect or one from the archdevil lair action list\
    \ (page 214); she can't take the same lair action two rounds in a row:"
  "name": ""
- "desc": "- Change Appearance. Glasya polymorphs into a Small or Medium Humanoid\
    \ she has seen, or back into her true form. Her statistics, other than her size,\
    \ are the same in each form. Any equipment she is wearing or carrying isn't transformed.\
    \ She reverts to her true form if she dies.  "
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
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/CoA/Glasya.webp"
```
^statblock