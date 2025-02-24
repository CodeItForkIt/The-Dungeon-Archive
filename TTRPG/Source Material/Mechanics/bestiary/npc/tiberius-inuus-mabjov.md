---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/mabjov
- monster/cr/9
- monster/size/medium
- monster/type/humanoid/human
statblock: inline
aliases: ["Tiberius Inuus"]
---
# [Tiberius Inuus](Mechanics\bestiary\npc/tiberius-inuus-mabjov.md)
*Source: Minsc and Boo's Journal of Villainy p. 44*  

> [!quote] A quote from Volo  
> 
> The Inuus brothers have agreed to be patrons for a new book that I intend to title "Volo's Guide to Faerûn's Faiths". The Church of Sune is to have the largest chapter of course.

Tiberius Inuus is a powerful paladin of Sune and head of the Sisters and Brothers of the Ruby Rose, a holy order of warriors and paladins sworn to the service of the goddess of beauty. He is devoted to spreading the love and beauty of Sune to every corner of Faerûn.

Tiberius and his twin, Naes, were born in the city of Waterdeep. Their father abandoned them when their mother, a cleric of Sune, died during childbirth and thus they were raised in the Temple of Beauty. Naes grew up to become a cleric and man of peace, but Tiberius was too filled with anger to follow that path. While his twin was able to forgive their father, Tiberius has used the anger from that abandonment to fuel his drive to destroy anything that threatens the Church of Sune.

Tiberius dreams of building the Sisters and Brothers of the Ruby Rose into the greatest military force for good in all Faerûn, free from the corruption of city state politics. When he finds a warrior whose ability he respects, Tiberius can be an extremely convincing evangelizer. Tiberius often leverages the large number of faithful amongst the nobility of the Lord's Alliance. He is able to ensure that the Ruby Rose are included in important battles against threats to the cities of the Sword Coast. While the veterans of the Order of the Gauntlet might view clerics of Sune as soft, they respect the Ruby Rose because of the efforts of Tiberius.

## Tiberius as a Contact

Tiberius is the primary contact for members of the Church of Sune at low levels. Items can be purchased from Tiberius. It takes a day for him to acquire the item from the church.

**Magic Items Available from Tiberius**

| Minor Magic Item | Required Level | Cost |
|------------------|----------------|------|
| Decanter of endless water | – | 100 gp |
| Keoghtom's ointment | – | 100 gp |
| Philter of love | – | 50 gp |
| Potion of healing | – | 40 gp |
| Periapt of health | – | 100 gp |
| Sending stones | – | 100 gp |
| Spell scroll (1)—charm person, disguise self, guiding bolt, shield of faith, sleep | – | 25 gp |
| Spell scroll (2)—prayer of healing, suggestion | – | 250 gp |
| Spell scroll (3)—beacon of hope, leomund's tiny hut, revivify | – | 500 gp |
| Potion of greater healing | 5 | 250 gp |
| Elixir of health | 5 | 100 gp |
| Spell scroll (4)—death ward, fabricate, guardian of faith, mordenkainen's private sanctum | 5 | 2,500 gp |
| Spell scroll (5)—commune, creation, hallow, raise dead, seeming | 5 | 5,000 gp |
^magic-items-available-from-tiberius

```statblock
"name": "Tiberius Inuus (MaBJoV)"
"size": "Medium"
"type": "humanoid"
"subtype": "human"
"alignment": "Lawful Good"
"ac": !!int "18"
"ac_class": "[plate](Mechanics/items/plate-armor.md)"
"hp": !!int "170"
"hit_dice": "20d8 + 80"
"stats":
- !!int "18"
- !!int "12"
- !!int "18"
- !!int "11"
- !!int "11"
- !!int "16"
"speed": "30 ft."
"saves":
  "Wisdom": !!int "4"
  "Constitution": !!int "8"
"skillsaves":
  "Religion": !!int "4"
  "Persuasion": !!int "7"
"senses": "passive Perception 10"
"languages": "Celestial, Common"
"cr": "9"
"traits":
- "desc": "Tiberius Inuus has advantage on saving throws against being [frightened](Mechanics/Rules/conditions.md#Frightened)."
  "name": "Brave"
"actions":
- "desc": "Tiberius Inuus makes three Flame Tongue attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +8 to hit, reach 5 ft., one target. Hit: 11\
    \ (2d6 + 4) slashing damage plus 7 (2d6) fire damage."
  "name": "Flame Tongue"
- "desc": "Ranged Weapon Attack: +5 to hit, range 100/400 ft., one target. Hit:\
    \ 6 (1d10 + 1) piercing damage."
  "name": "Heavy Crossbow"
- "desc": "Tiberius Inuus touches a creature. The target magically regains 40 hit\
    \ points and is freed from any disease or poison."
  "name": "Touch of Sune"
"reactions":
- "desc": "When Tiberius Inuus is hit by an attack he can utter an oath of vengeance\
    \ against the creature that made the attack. He gains advantage on attack rolls\
    \ against that creature for 1 minute or until it drops to 0 hit points or falls\
    \ [unconscious](Mechanics/Rules/conditions.md#Unconscious)."
  "name": "Vengeance"
"source":
- "MaBJoV"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/MaBJoV/Tiberius%20Inuus.webp"
```
^statblock