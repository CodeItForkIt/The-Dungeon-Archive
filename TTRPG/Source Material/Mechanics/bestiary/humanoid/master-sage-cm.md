---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/cm
- monster/cr/5
- monster/size/medium
- monster/type/humanoid/any-race
statblock: inline
aliases: ["Master Sage"]
---
# [Master Sage](Mechanics\bestiary\humanoid/master-sage-cm.md)
*Source: Candlekeep Mysteries p. 9*  

Candlekeep's resident lore experts are master sages and sages who dedicate themselves to scholarship above all.

```statblock
"name": "Master Sage (CM)"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Unaligned"
"ac": !!int "10"
"hp": !!int "54"
"hit_dice": "12d8"
"stats":
- !!int "8"
- !!int "10"
- !!int "10"
- !!int "20"
- !!int "18"
- !!int "11"
"speed": "30 ft."
"skillsaves":
  "Medicine": !!int "10"
  "Nature": !!int "11"
  "Investigation": !!int "11"
  "Religion": !!int "11"
  "Insight": !!int "7"
  "History": !!int "11"
  "Arcana": !!int "11"
"senses": "passive Perception 14"
"languages": "Common plus any five languages"
"cr": "5"
"traits":
- "desc": "The sage casts one of the following spells, using Intelligence as the spellcasting\
    \ ability (save DC 14, +6 to hit with spell attacks):\n\nAt will: [light](Mechanics/spells/light.md),\
    \ [mage hand](Mechanics/spells/mage-hand.md), [mending](Mechanics/spells/mending.md),\
    \ [prestidigitation](Mechanics/spells/prestidigitation.md), \n\n1/day each:\
    \ [banishment](Mechanics/spells/banishment.md), [contact other plane](Mechanics/spells/contact-other-plane.md),\
    \ [Drawmij's instant summons](Mechanics/spells/drawmijs-instant-summons.md), [legend\
    \ lore](Mechanics/spells/legend-lore.md), [locate creature](Mechanics/spells/locate-creature.md),\
    \ [planar binding](Mechanics/spells/planar-binding.md), [polymorph](Mechanics/spells/polymorph.md),\
    \ [protection from evil and good](Mechanics/spells/protection-from-evil-and-good.md),\
    \ [scrying](Mechanics/spells/scrying.md), [sending](Mechanics/spells/sending.md),\
    \ [true seeing](Mechanics/spells/true-seeing.md)\n\n3/day each: [comprehend\
    \ languages](Mechanics/spells/comprehend-languages.md), [detect magic](Mechanics/spells/detect-magic.md),\
    \ [dispel magic](Mechanics/spells/dispel-magic.md), , [identify](Mechanics/spells/identify.md),\
    \ [levitate](Mechanics/spells/levitate.md), [locate object](Mechanics/spells/locate-object.md),\
    \ , [Tenser's Floating Disk](Mechanics/spells/tensers-floating-disk.md), [unseen\
    \ servant](Mechanics/spells/unseen-servant.md)"
  "name": "Spellcasting"
"actions":
- "desc": "Melee Spell Attack: +8 to hit (with advantage if the target is wearing\
    \ armor made of metal), reach 5 ft., one creature. Hit: 13 (3d8) lightning\
    \ damage, and the target can't take reactions until the start of its next turn."
  "name": "Shocking Grasp (Cantrip)"
- "desc": "The sage creates a fiery explosion centered on a point it can see within\
    \ 150 feet of it. Each creature in a 20-foot-radius sphere centered on that point\
    \ must make a DC 14 Dexterity saving throw, taking 28 (8d6) fire damage on a\
    \ failed save, or half as much damage on a successful one. The fire spreads around\
    \ corners and ignites flammable objects in the area that aren't being worn or\
    \ carried."
  "name": "Fireball (3rd-Level Spell; 3/Day)"
"reactions":
- "desc": "When the sage is hit by an attack or targeted by a [magic missile](Mechanics/spells/magic-missile.md)\
    \ spell, it calls forth an [invisible](Mechanics/Rules/conditions.md#Invisible)\
    \ barrier of magical force that protects it. Until the start of its next turn,\
    \ the sage has a +5 bonus to AC, including against the triggering attack, and\
    \ it takes no damage from magic missile."
  "name": "Shield (1st-Level Spell; 3/Day)"
"source":
- "CM"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/CM/Master%20Sage.webp"
```
^statblock