---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/mabjov
- monster/cr/9
- monster/size/medium
- monster/type/humanoid/human
statblock: inline
aliases: ["Pelyious Avhoste"]
---
# [Pelyious Avhoste](Mechanics\bestiary\npc/pelyious-avhoste-mabjov.md)
*Source: Minsc and Boo's Journal of Villainy p. 120*  

Pelyious is a Halruaan sky captain who hires out his services to those with a desperate need to get somewhere quickly. His skyship is one of the fastest in all Faerûn, designed by his uncle, Zythan Oolorius Avhoste, the famed Halruaan designer.

Charismatic, cultured and sophisticated, Pelyious is a lover of ancient art and music. He professes an admiration for the extinct Netherese—precursors to the Halruaan people—and the ancient kingdom of Mezro. His skyship is decorated with artifacts and paintings from these cultures, and he enjoys showing off his impressive collection to his guests. He is also an excellent musician and delights in playing complex compositions from the "lost ages" that haven't been heard in centuries.

Though a bit pretentious, Pelyious is unfailingly courteous and polite. He has utter disdain for those who do not share his refinement, viewing them as barbarous, rude, or just plain uncouth.

Pelyious is a skilled ship captain and an excellent swordsman. He has also been mentored in the magical arts by his uncle Zythan. This combination of skills makes him an unpredictable and dangerous opponent; someone who can engage in close melee combat or use magical spells from range.

However, unbeknown to most, Pelyious and his crew are also faithful servants of Bhaal, the God of Murder. Beneath his cultured veneer lurks a bloodthirsty monster (a lycanthropic form he learned through an ancient Mezro ritual), and he occasionally plans "murder rituals" where he turns his entire Halruaan skyship into a slaughterhouse. Victims in these massacres are not merely killed, but often tortured, mutilated, and eventually skinned. While most of the remains are tossed over the side of the airship when it crosses the oceans, the hearts and other vital organs of his victims are used for ritual feasts to celebrate the slaughter.

Pelyious prefers to reserve these ritual killing sprees for those that have insulted him, tried to cheat him, or offended his honor in some manner. However, if no suitable candidates have made themselves available, Pelyious sometimes has to settle on victims that he genuinely likes, for the Lord of Murder can only wait so long for his sacrifices. Pelyious shows no remorse when forced to slaughter those he considers friends, as his devotion to Bhaal supersedes all other loyalties.

Pelyious crews his airship with a family of wolfweres. Most stay in their human forms when there are passengers on board, though the alpha, who is also the wife of Pelyious, likes to take the role of a wolf that Pelyious has tamed.

```statblock
"name": "Pelyious Avhoste (MaBJoV)"
"size": "Medium"
"type": "humanoid"
"subtype": "human"
"alignment": "Neutral Evil"
"ac": !!int "12"
"ac_class": "15 with [mage armor](Mechanics/spells/mage-armor.md)"
"hp": !!int "143"
"hit_dice": "22d8 + 44"
"stats":
- !!int "18"
- !!int "14"
- !!int "14"
- !!int "17"
- !!int "11"
- !!int "13"
"speed": "30 ft., swim 30 ft."
"saves":
  "Dexterity": !!int "6"
  "Strength": !!int "8"
"skillsaves":
  "Stealth": !!int "6"
  "Perception": !!int "8"
"damage_immunities": "poison; bludgeoning, piercing, slashing damage from nonmagical\
  \ weapons that aren't silvered"
"condition_immunities": "[poisoned](Mechanics/Rules/conditions.md#Poisoned)"
"senses": "darkvision 60 ft., passive Perception 18"
"languages": "Abyssal, Common, Draconic"
"cr": "9"
"traits":
- "desc": "Pelyious casts one of the following spells, using Intelligence as the spellcasting\
    \ ability (spell save DC 15, +7 to hit with spell attacks):\n\nAt will:\
    \ [fire bolt](Mechanics/spells/fire-bolt.md), [light](Mechanics/spells/light.md),\
    \ [mage hand](Mechanics/spells/mage-hand.md), [prestidigitation](Mechanics/spells/prestidigitation.md)\n\
    \n1/day each: [cone of cold](Mechanics/spells/cone-of-cold.md), [counterspell](Mechanics/spells/counterspell.md),\
    \ [fly](Mechanics/spells/fly.md), [greater invisibility](Mechanics/spells/greater-invisibility.md)\n\
    \n2/day each: [detect magic](Mechanics/spells/detect-magic.md), [mage armor](Mechanics/spells/mage-armor.md),\
    \ [shield](Mechanics/spells/shield.md), [suggestion](Mechanics/spells/suggestion.md)"
  "name": "Spellcasting"
- "desc": "Pelyious can hold his breath for 15 minutes."
  "name": "Hold Breath"
"actions":
- "desc": "In Humanoid form, Pelyious makes two Scimitar attacks or two Hand Crossbow\
    \ attacks. In hybrid form, he can substitute one Scimitar attack for a Bite attack."
  "name": "Multiattack (Humanoid or Hybrid Form)"
- "desc": "Melee Weapon Attack: +8 to hit, reach 5 ft., one target. Hit: 7 (1d6\
    \ + 4) slashing damage plus 7 (2d6) poison damage."
  "name": "Scimitar (Humanoid or Hybrid Form)"
- "desc": "Ranged Weapon Attack: +6 to hit, range 30/90 ft., one target. Hit:\
    \ 6 (1d6 + 3) piercing damage plus 7 (2d6) poison damage."
  "name": "Hand Crossbow (Humanoid or Hybrid Form)"
- "desc": "Melee Weapon Attack: +8 to hit, reach 5 ft., one target. Hit: 9 (1d10\
    \ + 4) piercing damage. If the target is Medium or smaller, it is [grappled](Mechanics/Rules/conditions.md#Grappled)\
    \ (escape DC 16) and until this grapple ends, the target is [restrained](Mechanics/Rules/conditions.md#Restrained),\
    \ and Pelyious can't Bite another target."
  "name": "Bite (Hybrid Form Only)"
- "desc": "Pelyious polymorphs into a crocodile-hu- manoid hybrid, or back into his\
    \ true form, which is Humanoid. His statistics are the same in each form. Any\
    \ equipment he is wearing or carrying isn't transformed. He reverts to his true\
    \ form if he dies."
  "name": "Change Shape"
"bonus_actions":
- "desc": "Pelyious teleports up to 30 feet to an unoccupied space he can see and\
    \ may use Change Shape."
  "name": "Slippery Step (2/Day)"
"source":
- "MaBJoV"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/MaBJoV/Pelyious%20Avhoste.webp"
```
^statblock