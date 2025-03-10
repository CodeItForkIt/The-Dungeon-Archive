---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/mabjov
- monster/cr/15
- monster/size/medium
- monster/type/humanoid/human
statblock: inline
aliases: ["Edwin Odesseiron"]
---
# [Edwin Odesseiron](Mechanics\bestiary\npc/edwin-odesseiron-mabjov.md)
*Source: Minsc and Boo's Journal of Villainy p. 114*  

In many ways an archetypal Red Wizard, Edwin Odesseiron is an exceedingly arrogant conjuration mage hailing from the eastern nation of Thay. He originally traveled west to the Sword Coast on a mission to kill the Rashemi Wychlaran Dynaheir, both as part of a personal rivalry and under orders from his superior Red Wizards. Once his mission was accomplished, and Dynaheir was dead, Edwin remained on the Sword Coast in order to build up his own personal power without the oversight of the Zulkirs of Thay.

While Edwin had a falling out with the Red Wizards of Thay some time ago, he managed to repair the relationship by delivering one of the Nether Scrolls to the ruler of Thay—Szass Tam. His short time studying the Nether Scroll resulted in some calamitous results, but one of the spells he learned imparted him with the longevity of an elf.

While Edwin will often return to his homeland of Thay, he can most often be found in the city of Baldur's Gate. He has recently taken over Ramazith's Tower and adopted the identity of Lorroakan, the young mage who formerly lived in the tower (now dead by Edwin's hand).

Despite his inarguably high intelligence, Edwin seems to lack common sense. As a result, his grand schemes and power grabs are typically undone by his own hubris and oversights. Edwin almost universally treats others with disdain, openly insulting his "lessers." As much as Edwin detests those he views as his inferiors, he gets along no better with his betters. (His envy of the legendary wizard Elminster Aumar is particularly venomous.) Edwin has a simulacrum of himself that he uses to augment his power or send into dangerous situations. Since he doesn't respect the intelligence of anyone other than himself, he often finds himself engaged in conversation with his simulacrum.

```statblock
"name": "Edwin Odesseiron (MaBJoV)"
"size": "Medium"
"type": "humanoid"
"subtype": "human"
"alignment": "Lawful Evil"
"ac": !!int "13"
"ac_class": "18 with [staff of power](Mechanics/items/staff-of-power.md) and  [mage\
  \ armor](Mechanics/spells/mage-armor.md)"
"hp": !!int "195"
"hit_dice": "30d8 + 60"
"stats":
- !!int "10"
- !!int "16"
- !!int "14"
- !!int "20"
- !!int "15"
- !!int "16"
"speed": "30 ft."
"saves":
  "Wisdom": !!int "9"
  "Intelligence": !!int "12"
"skillsaves":
  "History": !!int "15"
  "Arcana": !!int "15"
"senses": "passive Perception 12"
"languages": "Abyssal, Aquan, Auran, Common, Ignan, Infernal, Terran, Thayan"
"cr": "15"
"traits":
- "desc": "Edwin casts one of the following spells, using Intelligence as the spellcasting\
    \ ability (spell save DC 18):\n\nAt will: [mage armor](Mechanics/spells/mage-armor.md),\
    \ [mirror image](Mechanics/spells/mirror-image.md), [shield](Mechanics/spells/shield.md),\
    \ [unseen servant](Mechanics/spells/unseen-servant.md)\n\n1/day each: [clone](Mechanics/spells/clone.md),\
    \ [maze](Mechanics/spells/maze.md), [meteor swarm](Mechanics/spells/meteor-swarm.md),\
    \ [teleport](Mechanics/spells/teleport.md)\n\n2/day each: [contingency](Mechanics/spells/contingency.md),\
    \ [counterspell](Mechanics/spells/counterspell.md), [dispel magic](Mechanics/spells/dispel-magic.md),\
    \ [fireball](Mechanics/spells/fireball.md), [simulacrum](Mechanics/spells/simulacrum.md),\
    \ [scrying](Mechanics/spells/scrying.md)"
  "name": "Spellcasting"
- "desc": "While holding the staff of power, Edwin casts one of the following spells\
    \ (spell save DC 18, +12 to hit with spell attacks). These spells require charges;\
    \ the staff has 20 charges, and it regains 2d8 + 4 expended charges daily at\
    \ dawn. 1 charge each: magic missile, ray of enfeeblement 2 charges: levitate\
    \ 5 charges each: cone of cold, fireball (5th level), hold monster, lightning\
    \ bolt (5th level), wall of force 6 charges: globe of invulnerability\n"
  "name": "Staff Spellcasting"
- "desc": "If Edwin has the [incapacitated](Mechanics/Rules/conditions.md#Incapacitated),\
    \ [paralyzed](Mechanics/Rules/conditions.md#Paralyzed), or [stunned](Mechanics/Rules/conditions.md#Stunned)\
    \ condition, a [contingency](Mechanics/spells/contingency.md) spell triggers,\
    \ casting [dispel magic](Mechanics/spells/dispel-magic.md) at 6th level, targeting\
    \ Edwin. He also has a body created by the [clone](Mechanics/spells/clone.md)\
    \ spell stored in a cavern one mile beneath the city of Baldur's Gate."
  "name": "Contingency"
- "desc": "Edwin is always accompanied by a simulacrum of himself. The copy is identical\
    \ to him in all respects except that it has 58 hit points, does not have the staff\
    \ of power and can only cast the 'at will' spells available in Edwin's Spellcasting\
    \ feature."
  "name": "Simulacrum"
- "desc": "Edwin wields a [staff of power](Mechanics/items/staff-of-power.md). While\
    \ held the staff grants a +2 bonus to attack and damage rolls made with it, and\
    \ a +2 bonus to armor class, saving throws, and spell attack rolls (all factored\
    \ into Edwin's statistics)."
  "name": "Special Equipment"
"actions":
- "desc": "Edwin makes a Staff of Power attack or uses Spellcasting or Staff Spellcasting.\
    \ He then makes two Elemental Blast attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +7 to hit, reach 5 ft., one target. Hit: 5 (1d6\
    \ + 2) bludgeoning damage or 6 (1d8 + 2) bludgeoning damage if wielded with\
    \ two hands. Edwin can expend one of the staff's charges to deal an extra 14 (4d6)\
    \ force damage on a hit."
  "name": "Staff of Power"
- "desc": "Ranged Spell Attack: +12 to hit, range 120 ft., one target. Hit:\
    \ 38 (6d10 + 5) acid, cold, lightning, or fire damage."
  "name": "Elemental Blast"
- "desc": "Edwin creates a 20-foot-radius sphere of poisonous fog centered on a point\
    \ within 120 feet. The cloud spreads around corners but lasts only until the start\
    \ of Edwin's next turn. When a creature enters the cloud's area for the first\
    \ time on a turn or starts its turn there, that creature must make a DC 18 Constitution\
    \ saving throw. The creature takes 45 (10d8) poison damage on a failed save,\
    \ or half as much damage on a successful one. Creatures are affected even if they\
    \ hold their breath or don't need to breathe."
  "name": "Edwin's Choking Cloud (Recharge 6)"
"bonus_actions":
- "desc": "Edwin magically summons three [hell hounds](Mechanics/bestiary/fiend/hell-hound.md).\
    \ The summoned hell hounds appear in an unoccupied space within 60 feet of Edwin,\
    \ and act as Edwin's allies. They remain for 10 minutes, until they or Edwin dies,\
    \ or until Edwin dismisses them as an action."
  "name": "Summon Hell Hounds"
"reactions":
- "desc": "As a reaction to taking damage, Edwin teleports up to 30 feet to an unoccupied\
    \ space that he can see."
  "name": "Edwin's Evasive Footwork"
"source":
- "MaBJoV"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/MaBJoV/Edwin%20Odesseiron.webp"
```
^statblock