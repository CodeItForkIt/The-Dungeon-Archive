---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/coa
- monster/cr/9
- monster/size/small
- monster/type/humanoid
statblock: inline
aliases: ["Tiax"]
---
# [Tiax](Mechanics\bestiary\npc/tiax-coa.md)
*Source: Chains of Asmodeus p. 266*  

A long-serving cleric of Cyric, the god of lies, Tiax is absolutely certain of many things—most of them entirely untrue. After twenty years in Cyric's clergy, Tiax's mind has been twisted by the god's many tricks. Still, even so flavored by fantasy and deception, the favor of a god often proves a very powerful boon indeed. Whatever dire trouble Tiax finds himself in, even if it be the flames of the Nine Hells, his god will devise means of delivering him to safety—though often just by the skin of his teeth.

All of these near misses and improbable escapes have only solidified Tiax's delusions of grandeur. Though he is well aware that it is Cyric's divine interference which saves him, Tiax tells everyone he encounters that he is actually a powerful sorcerer and thus hides his piety to Cyric and the divine power he has been granted in return.

As one might expect, Tiax's foremost attributes are exaggeration and deceit. Unfortunately, for the unsuspecting, Tiax's unthreatening and absurd demeanor can grant the illusion of harmlessness. His many lies appear outlandish and easily dismissed, and his erratic behavior borders on complete buffoonery. Some might even find his colorful, chaotic personality to be charming. Certainly, Koh Tam seems to tolerate him for one reason or another. But make no mistake, Tiax is dangerous. The wise should be wary.

```statblock
"name": "Tiax (CoA)"
"size": "Small"
"type": "humanoid"
"alignment": "Chaotic Neutral"
"ac": !!int "13"
"ac_class": "16 with [mage armor](Mechanics/spells/mage-armor.md)"
"hp": !!int "110"
"hit_dice": "20d6 + 40"
"stats":
- !!int "11"
- !!int "16"
- !!int "14"
- !!int "15"
- !!int "19"
- !!int "18"
"speed": "25 ft."
"saves":
  "Charisma": !!int "8"
  "Wisdom": !!int "8"
"skillsaves":
  "Deception": !!int "8"
  "Insight": !!int "8"
  "Performance": !!int "8"
  "Persuasion": !!int "8"
"senses": "darkvision 60 ft., passive Perception 14"
"languages": "Celestial, Common, Gnomish"
"cr": "9"
"traits":
- "desc": "Tiax casts one of the following spells, using Wisdom as the spellcasting\
    \ ability (spell save DC 16):\n\nAt will: [Bane](Mechanics/spells/bane.md),\
    \ [Disguise Self](Mechanics/spells/disguise-self.md), [Dispel Magic](Mechanics/spells/dispel-magic.md),\
    \ [Mage Armor](Mechanics/spells/mage-armor.md), [Mirror Image](Mechanics/spells/mirror-image.md),\
    \ [Thaumaturgy](Mechanics/spells/thaumaturgy.md)\n\n1/day each: [Bestow Curse](Mechanics/spells/bestow-curse.md),\
    \ [Blindness/Deafness](Mechanics/spells/blindness-deafness.md), [Blink](Mechanics/spells/blink.md),\
    \ [Charm Person](Mechanics/spells/charm-person.md), [Contagion](Mechanics/spells/contagion.md),\
    \ [Dimension Door](Mechanics/spells/dimension-door.md), [Dominate Person](Mechanics/spells/dominate-person.md),\
    \ [Hold Person](Mechanics/spells/hold-person.md), [Pass Without Trace](Mechanics/spells/pass-without-trace.md),\
    \ [Polymorph](Mechanics/spells/polymorph.md), [Teleport](Mechanics/spells/teleport.md)"
  "name": "Spellcasting"
- "desc": "Tiax has advantage on Intelligence, Wisdom, and Charisma saving throws\
    \ against magic."
  "name": "Gnome Cunning"
- "desc": "Tiax wears a [Ring of Resistance](Mechanics/items/ring-of-resistance-dmg.md)\
    \ that grants him resistance to radiant damage."
  "name": "Special Equipment"
"actions":
- "desc": "Melee Spell Attack: +8 to hit, reach 5 ft., one target. Hit: 37 (6d10\
    \ + 4) necrotic damage."
  "name": "Touch of Decay"
- "desc": "Tiax causes unholy fire to flare up in a creature's space within 60 feet\
    \ of him. The target must succeed on a DC 16 Dexterity saving throw or take 18\
    \ (4d8) necrotic damage plus 18 (4d8) poison damage."
  "name": "Unholy Firebolt"
"bonus_actions":
- "desc": "Tiax heals 70 hit points."
  "name": "Heal (2/Day)"
"source":
- "CoA"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/CoA/Tiax.webp"
```
^statblock