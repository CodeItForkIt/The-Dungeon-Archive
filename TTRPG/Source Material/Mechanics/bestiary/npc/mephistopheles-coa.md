---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/coa
- monster/cr/27
- monster/size/large
- monster/type/fiend/devil
statblock: inline
aliases: ["Mephistopheles"]
---
# [Mephistopheles](Mechanics\bestiary\npc/mephistopheles-coa.md)
*Source: Chains of Asmodeus p. 223*  

Mephistopheles is the lord of Cania, the eighth level of the Nine Hells, and the most formidable archdevil next to Asmodeus himself. He is famed as Hell's most powerful spellcaster and the wielder of a power known as Hellfire.

An ancient entity, rivaling Asmodeus in age, Mephistopheles has been responsible for many schemes to try and unseat the Lord of the Nine Hells. One of his most infamous was an alliance between himself, Dispater, Mammon, and Geryon. They conspired to take power from the other archdevils, Baalzebul, Zariel, Belial, and Moloch. With this increased power, Mephistopheles believed he could challenge Asmodeus himself. But he was betrayed by Geryon, who had secretly sided with Asmodeus. Despite the blatancy of his rebellion, Mephistopheles was the archdevil that suffered the least: not cursed like Mammon or Baalzebul; not cast down like Belial, Moloch or Geryon. This has led many to believe that there is some ancient secret to the relationship between Asmodeus and Mephistopheles, though what it could be is a mystery none have discovered.

As the foremost spellcaster of the Nine Hells, Mephistopheles often resorts to magic when forced to defend himself. But his greatest power comes from the ability to wield Hellfire itself. Created by tapping into the profane essence of the Nine Hells, Hellfire is unimaginably, unbearably hot. Mephistopheles can also shape Hellfire however he wishes, making it his most potent weapon.

## Mephistopheles' Lair

This archdevil's lair is the Citadel of Mephistar, located within the glacier of Nargus. This an elegantly carved ice palace and is home to Mephistopheles' private manor, along with living accommodations for numerous other devils.

```statblock
"name": "Mephistopheles (CoA)"
"size": "Large"
"type": "fiend"
"subtype": "devil"
"alignment": "Lawful Evil"
"ac": !!int "21"
"ac_class": "natural armor"
"hp": !!int "460"
"hit_dice": "40d10 + 240"
"stats":
- !!int "22"
- !!int "23"
- !!int "22"
- !!int "30"
- !!int "28"
- !!int "26"
"speed": "40 ft., fly 100 ft."
"saves":
  "Charisma": !!int "16"
  "Wisdom": !!int "17"
  "Intelligence": !!int "18"
"skillsaves":
  "Deception": !!int "24"
  "Insight": !!int "25"
  "Persuasion": !!int "24"
"damage_resistances": "acid; cold; bludgeoning, piercing, slashing from nonmagical\
  \ attacks that aren't silvered"
"damage_immunities": "fire, poison"
"condition_immunities": "[charmed](Mechanics/Rules/conditions.md#Charmed), [exhaustion](Mechanics/Rules/conditions.md#Exhaustion),\
  \ [frightened](Mechanics/Rules/conditions.md#Frightened), [poisoned](Mechanics/Rules/conditions.md#Poisoned)"
"senses": "darkvision 120 ft., passive Perception 19"
"languages": "all, telepathy 120 ft."
"cr": "27"
"traits":
- "desc": "Mephistopheles casts one of the following spells, requiring no material\
    \ components and using Intelligence as the spellcasting ability (spell save DC\
    \ 26):\n\nAt will: [Darkness](Mechanics/spells/darkness.md), [Detect Evil\
    \ and Good](Mechanics/spells/detect-evil-and-good.md), [Detect Magic](Mechanics/spells/detect-magic.md),\
    \ [Dispel Magic](Mechanics/spells/dispel-magic.md), [Geas](Mechanics/spells/geas.md)\
    \ (duration 1 year), [Greater Restoration](Mechanics/spells/greater-restoration.md),\
    \ [Hallow](Mechanics/spells/hallow.md), [Hold Monster](Mechanics/spells/hold-monster.md),\
    \ [Locate Creature](Mechanics/spells/locate-creature.md), [Locate Object](Mechanics/spells/locate-object.md),\
    \ [Major Image](Mechanics/spells/major-image.md), [Resurrection](Mechanics/spells/resurrection.md),\
    \ [Scrying](Mechanics/spells/scrying.md), [Suggestion](Mechanics/spells/suggestion.md),\
    \ [Wall of Fire](Mechanics/spells/wall-of-fire.md)\n\n1/day each: [Meteor\
    \ Swarm](Mechanics/spells/meteor-swarm.md), [Symbol](Mechanics/spells/symbol.md),\
    \ [Wish](Mechanics/spells/wish.md)"
  "name": "Spellcasting"
- "desc": "Magical darkness doesn't impede Mephistopheles' darkvision."
  "name": "Devil's Sight"
- "desc": "Mephistopheles regains 20 hit points at the start of his turn. If he takes\
    \ radiant damage this trait doesn't function at the start of his next turn. Mephistopheles\
    \ only dies if he starts his turn with 0 hit points and is unable to regenerate."
  "name": "Fiendish Regeneration"
- "desc": "Mephistopheles doesn't provoke opportunity attacks when he flies out of\
    \ an enemy's reach."
  "name": "Flyby"
- "desc": "Fire damage that Mephistopheles inflicts ignores resistances and immunities.\
    \ Mephistopheles is immune to this effect."
  "name": "Hellfire Mastery"
- "desc": "If Mephistopheles fails a saving throw, he can choose to succeed instead."
  "name": "Legendary Resistance (3/Day)"
- "desc": "Mephistopheles has advantage on saving throws against spells and other\
    \ magical effects."
  "name": "Magic Resistance"
"actions":
- "desc": "Mephistopheles makes three Ranseur attacks. He can replace one of the attacks\
    \ with Hellfire Lash (if available)."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +17 to hit, reach 10 ft., one target. Hit: 20\
    \ (2d10 + 9) piercing damage plus 18 (4d8) fire or cold damage (Mephistopheles'\
    \ choice)."
  "name": "Ranseur +3"
- "desc": "A bright streak of Hellfire appears at a point that Mephistopheles can\
    \ see within 150 feet of him. Each creature in a 20-foot-radius sphere centered\
    \ on that point must make a DC 22 Dexterity saving throw. Targets take 31 (9d6)\
    \ fire damage on a failed save, or half as much damage on a successful one."
  "name": "Hellfire Implosion (Recharge 4-6)"
- "desc": "Mephistopheles unleashes a 60-foot-long, 5-foot-wide lash of Hellfire that\
    \ ignites a 5-foot- radius sphere around where it strikes. Any targets in the\
    \ area of effect must make a DC 22 Dexterity saving throw, taking 36 (8d8) fire\
    \ damage on a failed save, or half as much on a successful one."
  "name": "Hellfire Lash (Recharge 5-6)"
"bonus_actions":
- "desc": "Mephistopheles' body and any equipment he is wearing or carrying turns\
    \ to ash, then he magically teleports up to 120 feet to an unoccupied space he\
    \ can see and reforms."
  "name": "Ashen Teleport"
"legendary_actions":
- "desc": "Mephistopheles uses his wings to generate a burst of heat. Each creature\
    \ within 10 feet of him must succeed on a DC 22 Dexterity saving throw or take\
    \ 9 (2d8) bludgeoning damage plus 9 (2d8) fire damage. Creatures that failed\
    \ the save also have the [prone](Mechanics/Rules/conditions.md#Prone) condition."
  "name": "Hellfire Wings"
- "desc": "Mephistopheles creates a rain of Hellfire at a point he can see within\
    \ 150 feet. Each creature within a 20-foot-radius sphere centered on that point\
    \ must make a DC 24 Dexterity saving throw. Targets take 38 (7d10) fire damage\
    \ on a failed save, or half as much damage on a successful one."
  "name": "Hellfire Storm (Costs 2 Actions)"
- "desc": "Mephistopheles summons an allied [horned devil](Mechanics/bestiary/fiend/horned-devil.md)\
    \ in an unoccupied space that he can see."
  "name": "Call Underling (Costs 3 Actions)"
"regional_effects":
- "desc": "The region containing Mephistopheles' lair is corrupted by his presence,\
    \ which creates the following effect:"
  "name": ""
- "desc": "- Geysers. Within 1 mile of Mephistopheles' lair, every 100 feet of\
    \ movement results in a flame geyser erupting. Creatures within 10 feet of a geyser\
    \ when it erupts must succeed on a DC 22 Dexterity saving throw or take 10 (3d6)\
    \ fire damage. The geyser continues erupting for 24 hours.  "
  "name": ""
- "desc": "If Mephistopheles dies, the effects fade over the course of 1d10 days."
  "name": ""
"lair_actions":
- "desc": "On initiative count 20 (losing initiative ties), Mephistopheles can take\
    \ one lair action to cause the following effect or one from the archdevil lair\
    \ action list (page 214); he can't take the same lair action two rounds in a row:"
  "name": ""
- "desc": "- Conjure Hellfire. Mephistopheles covers a 5-foot square with Hellfire.\
    \ Any creature that starts their turn in the Hellfire takes 27 (6d8) fire damage.\
    \ The Hellfire remains until Mephistopheles dismisses it.  "
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
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/CoA/Mephistopheles.webp"
```
^statblock