---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/mabjov
- monster/cr/11
- monster/size/medium
- monster/type/humanoid/tiefling
statblock: inline
aliases: ["Eo Ashmajiir"]
---
# [Eo Ashmajiir](Mechanics\bestiary\npc/eo-ashmajiir-mabjov.md)
*Source: Minsc and Boo's Journal of Villainy p. 116*  

Born from the experiments of Belic Haphrat, a Red Wizard from the lands of Thay, Eo is a powerful tiefling sorceress. The offspring of a half-dragon and a succubus, Eo was raised by Belic as his own child, and showed an early affinity for magical gifts. As she grew older, Eo became increasingly useful to the Haphrat's families plans and schemes, eventually becoming a key cog in their complex machinations. Only then did Belic realize his daughter had been carefully manipulating him her entire life, working herself into a position of power and influence in his affairs so she could betray him. By then, however, it was too late, and Eo used her power to take control of Belic's mind, his family, and his wealth before ultimately discarding her adopted father when he ceased to be useful.

Eo is obsessed with her lineage, believing her bloodline makes her inherently superior to other beings. Her infatuation with her kinfolk—demons, devils, and dragons—has led her to walk the Nine Hells, playing dice games with demon lords and signing contracts with archdevils. She has sought audience with dragons of all kinds, including several of the most ancient wyrms in all of Faerûn. There are even rumors she possess a dragon orb, one of the most rare and powerful magical items.

The other driving influence in her life is the unbridled pursuit of hedonistic pleasure. Eo believes that the promise of the afterlife is a conspiracy by the gods to trick mortals into living lives of conformity, preparing them to be consigned to an eternity of sheer boredom after they die. In this way, Eo believes, the status quo of the Heavens and the Hells can be more easily maintained. Eo rebels against this status quo by pursuing earthly pleasures in all their forms, regardless of the long-term costs. She lives almost exclusively in the moment, relying on her wealth, fame, and privilege to protect her against any serious consequences of her actions.

Eo is a narcissist of the highest order, desiring attention, adulation, and unbridled praise at all times. Eager to be recognized as the most beautiful and the most powerful woman in history, she has spent much of her ill-gotten Thayvian fortune in a campaign to be elected Duke of Baldur's Gate. In her pursuit of political power, she continually tries to buy the love and loyalty of the populace with extravagant festivals where wine and illicit drugs are freely available in virtually unlimited quantities. While winning many of the ordinary citizens to her side, these public orgies have put her at odds with the reigning political establishment and various religious figures championing a more traditional morality.

Eo's only weakness is her children. Her son, Aeshma, has gone missing recently. Rumor has it that Eo gambled his soul away in a drunken game of cards with some fiendish lord, though there is no proof as to his fate. Whatever the truth may be, one thing is certain—Eo is desperate to find him... though whether for his sake or simply to protect her own reputation is up for debate.

```statblock
"name": "Eo Ashmajiir (MaBJoV)"
"size": "Medium"
"type": "humanoid"
"subtype": "tiefling"
"alignment": "Chaotic Neutral"
"ac": !!int "16"
"ac_class": "natural armor"
"hp": !!int "126"
"hit_dice": "28d8 + 0"
"stats":
- !!int "10"
- !!int "16"
- !!int "10"
- !!int "12"
- !!int "14"
- !!int "20"
"speed": "30 ft., fly 30 ft."
"saves":
  "Charisma": !!int "9"
  "Constitution": !!int "4"
"skillsaves":
  "Deception": !!int "9"
  "Arcana": !!int "9"
  "Persuasion": !!int "9"
"damage_resistances": "lightning"
"senses": "passive Perception 12"
"languages": "Abyssal, Celestial, Common, Draconic, Infernal, Undercommon"
"cr": "11"
"traits":
- "desc": "Eo casts one of the following spells, using Charisma as the spellcasting\
    \ ability (spell save DC 17, +9 to hit with spell attacks):\n\nAt will:\
    \ [detect magic](Mechanics/spells/detect-magic.md), [detect thoughts](Mechanics/spells/detect-thoughts.md),\
    \ [light](Mechanics/spells/light.md), [mage hand](Mechanics/spells/mage-hand.md),\
    \ [magic missile](Mechanics/spells/magic-missile.md), [prestidigitation](Mechanics/spells/prestidigitation.md),\
    \ [shield](Mechanics/spells/shield.md), [shocking grasp](Mechanics/spells/shocking-grasp.md)\n\
    \n1/day each: [chain lightning](Mechanics/spells/chain-lightning.md), [finger\
    \ of death](Mechanics/spells/finger-of-death.md), [power word stun](Mechanics/spells/power-word-stun.md),\
    \ [teleport](Mechanics/spells/teleport.md), [wish](Mechanics/spells/wish.md)\n\
    \n2/day each: [banishment](Mechanics/spells/banishment.md), [counterspell](Mechanics/spells/counterspell.md),\
    \ [dominate person](Mechanics/spells/dominate-person.md), [fireball](Mechanics/spells/fireball.md),\
    \ [lightning bolt](Mechanics/spells/lightning-bolt.md), [mirror image](Mechanics/spells/mirror-image.md),\
    \ [misty step](Mechanics/spells/misty-step.md)\n\n Eo uses wish to ensure she\
    \ has a simulacrum of herself at all times."
  "name": "Spellcasting"
- "desc": "When Eo uses Spellcasting to cast a spell that deals lightning damage,\
    \ that spell deals an additional 5 damage. When Eo casts a spell that deals a\
    \ type of damage from the following list, she can change that damage type to lightning:\
    \ acid, cold, fire, poison, thunder."
  "name": "Lightning Affinity"
"actions":
- "desc": "Melee or Ranged Spell Attack: +9 to hit, reach 5 ft. or range 90 ft.,\
    \ two targets. Hit: 27 (5d8 + 5) acid, cold, fire, lightning, poison or thunder\
    \ damage (Eo's choice)."
  "name": "Twinned Orbs"
- "desc": "Eo uses Spellcasting to cast [banishment](Mechanics/spells/banishment.md),\
    \ dominate person, finger of death, or power word stun. This spell targets a second\
    \ creature in range."
  "name": "Twinned Spell"
- "desc": "Eo emits a thin green ray at a creature within 60 feet. The target must\
    \ make a DC 17 Dexterity saving throw. On a failed save the target takes 89 (14d6\
    \ + 40) force damage. If this damage reduces the target to 0 hit points, it is\
    \ disintegrated. A disintegrated creature and everything it is wearing and carrying,\
    \ except magic items, are reduced to a pile of fine gray dust. The creature can\
    \ be restored to life only by means of a true resurrection or a [wish](Mechanics/spells/wish.md)\
    \ spell."
  "name": "Discharge (1/Day)"
"reactions":
- "desc": "As a reaction to taking damage, Eo surrounds her attacker with a coil of\
    \ lightning. The target must make a DC 17 Dexterity saving throw. It takes 16\
    \ (2d10 + 5) lightning damage on a failed save, half as much damage on a successful\
    \ one."
  "name": "Shocking Rebuke"
"source":
- "MaBJoV"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/MaBJoV/Eo%20Ashmajiir.webp"
```
^statblock