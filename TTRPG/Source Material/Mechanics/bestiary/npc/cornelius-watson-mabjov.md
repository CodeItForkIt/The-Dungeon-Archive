---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/mabjov
- monster/cr/12
- monster/size/medium
- monster/type/humanoid/human
statblock: inline
aliases: ["Cornelius Watson"]
---
# [Cornelius Watson](Mechanics\bestiary\npc/cornelius-watson-mabjov.md)
*Source: Minsc and Boo's Journal of Villainy p. 30*  

Doc Watson (only his mother calls him Cornelius) is the consummate academic. He has an eclectic collection of interests and rarely stays focused on a single subject for longer than a few months. He calls himself a doctor, though strangely, medicine has never been one of his interests. Supposedly the term comes from his time with a man who claimed the highest accolade one could achieve in the study of a single subject was called a "doctorate". The one interest that Doc Watson has consistently kept up with is magic and that is mainly because it remains the best tool to help him continue to learn.

Doc Watson was born to a minor noble family in Waterdeep. While he was a studious child who loved reading, he was a little aimless and his family despaired of him finding a trade. Luckily, after spending time with his eccentric uncle (who happened to be a minor wizard), Doc Watson discovered that he had a knack for magic.

To the disappointment of his family, Doc Watson didn't apply this magical skill to a respectable profession such as the Watchful Order of Magists and Protectors, the clergy of Mystra or the Academy of Stargazers. Instead, he tried his hand at an increasingly strange number of jobs, some of which his exasperated mother was certain he had invented entirely on his own. This included being a weather forecaster for the Waterdeep Port Authority and a columnist for the Weekly Waterdeep Gazette. The final straw was when Doc Watson tried his hand as an executive chef at the Inn of Barmy Blowhards. During his time there he claimed to have achieved the optimal Maillard reaction with a localized pyromance (getting the perfect sear on a steak using fire magic). It was at this point that his family cut off his monthly allowance.

Forced to find a new source of income, Doc Watson was convinced by a friend of his, Flimp Shagglecran, that he should try his hand at the age-old profession of adventuring. Adventuring turned out to be quite lucrative and exposed Doc Watson to all sorts of interesting people, places and monsters. Eventually, he and Flimp had accumulated enough wealth that they were able to found a new guild which they gave a descriptive, but exceedingly unoriginal, name: The Adventurer's Guild.

## Watson as a Contact

Watson becomes available as a contact for the Adventurer's Guild at 9th level. Doc Watson has maps to some of the most dangerous monster lairs in Faerûn. These lairs are also the location of fantastic troves of treasure.

**Monster Lair Maps Available from Watson**

| Monster Lair | Treasure Trove | Map Cost |
|--------------|----------------|----------|
| Gynosphinx | Roll on Treasure Hoard: Challenge 11-16 in DMG | 250 gp |
| Beholder | Roll on Treasure Hoard: Challenge 11-16 in DMG | 500 gp |
| Mummy lord | Roll on Treasure Hoard: Challenge 11-16 in DMG | 500 gp |
| Adult green dragon | Roll on Treasure Hoard: Challenge 11-16 in DMG | 750 gp |
| Adult red dragon | Roll on Treasure Hoard: Challenge 17+ in DMG | 1000 gp |
| Ancient black dragon | Roll twice on Treasure Hoard: Challenge 17+ in DMG | 5000 gp |
| Kraken | Roll twice on Treasure Hoard: Challenge 17+ in DMG | 5000 gp |
^monster-lair-maps-available-from-watson

```statblock
"name": "Cornelius Watson (MaBJoV)"
"size": "Medium"
"type": "humanoid"
"subtype": "human"
"alignment": "Neutral Good"
"ac": !!int "12"
"ac_class": "15 with [mage armor](Mechanics/spells/mage-armor.md)"
"hp": !!int "154"
"hit_dice": "28d8 + 28"
"stats":
- !!int "10"
- !!int "14"
- !!int "12"
- !!int "20"
- !!int "15"
- !!int "16"
"speed": "30 ft."
"saves":
  "Wisdom": !!int "6"
  "Intelligence": !!int "9"
"skillsaves":
  "Investigation": !!int "13"
  "Perception": !!int "6"
  "History": !!int "13"
  "Arcana": !!int "13"
"damage_resistances": "damage from spells"
"senses": "passive Perception 16"
"languages": "Celestial, Common, Dwarvish, Gnomish, Halfling, Infernal"
"cr": "12"
"traits":
- "desc": "Doc Watson casts one of the following spells using Intelligence as his\
    \ spellcasting ability (spell save DC 17):\n\nAt will: [detect magic](Mechanics/spells/detect-magic.md),\
    \ [identify](Mechanics/spells/identify.md), [mage armor](Mechanics/spells/mage-armor.md),\
    \ [Rary's telepathic bond](Mechanics/spells/rarys-telepathic-bond.md)\n\n1/day\
    \ each: [foresight](Mechanics/spells/foresight.md), [true seeing](Mechanics/spells/true-seeing.md)\n\
    \n2/day each: [clairvoyance](Mechanics/spells/clairvoyance.md), [locate object](Mechanics/spells/locate-object.md),\
    \ [scrying](Mechanics/spells/scrying.md)"
  "name": "Spellcasting"
- "desc": "Doc Watson has advantage on saving throws against spells and other magical\
    \ effects."
  "name": "Magic Resistance"
- "desc": "When Doc Watson or a creature he can see makes an attack roll, a saving\
    \ throw, or an ability check, Doc Watson can roll a d20 and choose to use this\
    \ roll in place of the attack roll, saving throw, or ability check. This trait\
    \ recharges after using the Spellcasting action."
  "name": "Portent (Recharge 6)"
"actions":
- "desc": "Doc Watson makes three Arcane Burst attacks."
  "name": "Multiattack"
- "desc": "Melee or Ranged Spell Attack: +9 to hit, reach 5 ft. or range 120 ft.,\
    \ one target. Hit: 32 (5d10 + 5) lightning damage."
  "name": "Arcane Burst"
"source":
- "MaBJoV"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/MaBJoV/Cornelius%20Watson.webp"
```
^statblock