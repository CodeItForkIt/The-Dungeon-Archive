---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/mabjov
- monster/cr/13
- monster/size/medium
- monster/type/humanoid/drow
statblock: inline
aliases: ["Viconia DeVir"]
---
# [Viconia DeVir](Mechanics\bestiary\npc/viconia-devir-mabjov.md)
*Source: Minsc and Boo's Journal of Villainy p. 126*  

> [!quote] A quote from MINSC & BOO!  
> 
> Me and Boo can attest that Viconia never helped us write the chapter about Ust Natha.

Viconia DeVir is an exiled drow cleric in the service of Shar, goddess of darkness and loss. Once a loyal priestess of Lolth in the great drow city of Menzoberranzan, Viconia and House DeVir first lost the Spider Queen's favor when she refused to sacrifice an infant, an act she saw as pointless. In a desperate attempt to appease Lolth, her own mother arranged for Viconia to be sacrificed herself. She was saved by her devoted brother, Valas, who freed her and slew their mother in the process. For this crime, Valas was transformed into a drider, a monstrous centaur-like creature with a drow torso grafted onto the body of an immense spider. These events contributed to the once great House DeVir's destruction at the hands of House Do'Urden nearly a century ago.

Viconia fled Menzoberranzan and soon left the Underdark altogether to evade retribution from Lolth's minions. Stripped of most of her spellcasting abilities, she eventually found solace and newfound power in the worship of Shar, an ancient deity outside the Dark Seldarine. Like Lolth, Shar is a cruel goddess who values strength and duplicity.

Viconia has now lived apart from drow society for almost a century. During that time, she traveled with the Bhaalspawn Abdel Adrian, but eventually their relationship soured. In recent years, Shar has directed her to work with elemental cults that worship the Elder Elemental Eye. Viconia has faithfully carried out her goddesses wishes, which has often put her into conflict with surface organizations such as the Lord's Alliance or the Harpers.

When not working with cults of elemental evil, Viconia travels the Underdark looking for fellow outcasts. She has put together a motely band including a pair of driders named Cackle and Backle and a deep spider that she has raised since she saved it from being eaten by its mother. She also rides an achaierai that lost the rest of its flock to a war band of dwarves.

```statblock
"name": "Viconia DeVir (MaBJoV)"
"size": "Medium"
"type": "humanoid"
"subtype": "drow"
"alignment": "Neutral Evil"
"ac": !!int "21"
"ac_class": "[cloak of protection](Mechanics/items/cloak-of-protection.md), [plate](Mechanics/items/plate-armor.md),\
  \ [shield](Mechanics/items/shield.md)"
"hp": !!int "135"
"hit_dice": "30d8"
"stats":
- !!int "25"
- !!int "14"
- !!int "10"
- !!int "14"
- !!int "20"
- !!int "14"
"speed": "30 ft."
"saves":
  "Wisdom": !!int "10"
  "Constitution": !!int "5"
"skillsaves":
  "Religion": !!int "12"
  "Insight": !!int "10"
  "Persuasion": !!int "7"
"damage_resistances": "necrotic"
"senses": "darkvision 60 ft., passive Perception 15"
"languages": "Celestial, Common, Elvish"
"cr": "13"
"traits":
- "desc": "Viconia casts one of the following spells, using Wisdom as the spellcasting\
    \ ability (spell save DC 18):\n\nAt will: [dancing lights](Mechanics/spells/dancing-lights.md),\
    \ [light](Mechanics/spells/light.md), [sanctuary](Mechanics/spells/sanctuary.md),\
    \ [thaumaturgy](Mechanics/spells/thaumaturgy.md)\n\n1/day each: [darkness](Mechanics/spells/darkness.md),\
    \ [divine word](Mechanics/spells/divine-word.md), [faerie fire](Mechanics/spells/faerie-fire.md),\
    \ [holy aura](Mechanics/spells/holy-aura.md)\n\n2/day each: [cure wounds](Mechanics/spells/cure-wounds.md),\
    \ [death ward](Mechanics/spells/death-ward.md), [lesser restoration](Mechanics/spells/lesser-restoration.md)"
  "name": "Spellcasting"
- "desc": "Viconia has advantage on saving throws against being [charmed](Mechanics/Rules/conditions.md#Charmed),\
    \ and magic can't put Viconia to sleep."
  "name": "Fey Ancestry"
- "desc": "While in dim light or darkness, Viconia has resistance to damage that isn't\
    \ force, psychic, or radiant."
  "name": "Living Shadow"
- "desc": "Viconia wears a [belt of giant strength](Mechanics/items/belt-of-giant-strength-dmg.md)\
    \ (fire) and a [cloak of protection](Mechanics/items/cloak-of-protection.md) and\
    \ wields a +3 mace. Without the belt, her strength is 12 and her speed is reduced\
    \ to 20 ft."
  "name": "Special Equipment"
- "desc": "While in sunlight, Viconia has disadvantage on attack rolls, as well as\
    \ on Wisdom ([Perception](Mechanics/Rules/skills.md#Perception)) checks that rely\
    \ on sight."
  "name": "Sunlight Sensitivity"
"actions":
- "desc": "Viconia attacks twice with her Magic Mace and uses her Spellcasting action."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +15 to hit, reach 5 ft., one target. Hit: 13\
    \ (1d6 + 10) bludgeoning damage plus 9 (2d8) necrotic damage."
  "name": "Magic Mace"
- "desc": "Each creature in a 10-foot-radius, 40-foot-high cylinder centered on a\
    \ point within 60 feet must make a DC 18 Dexterity saving throw. A creature takes\
    \ 28 (8d6) fire damage plus 28 (8d6) radiant damage on a failed save, or half\
    \ as much damage on a successful one."
  "name": "Sacred Cleansing (Recharge 4-6)"
"source":
- "MaBJoV"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/MaBJoV/Viconia%20DeVir.webp"
```
^statblock