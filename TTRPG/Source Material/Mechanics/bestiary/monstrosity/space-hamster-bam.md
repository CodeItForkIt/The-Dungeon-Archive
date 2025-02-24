---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/bam
- monster/cr/1-4
- monster/size/tiny
- monster/type/monstrosity
statblock: inline
aliases: ["Space Hamster"]
---
# [Space Hamster](Mechanics\bestiary\monstrosity/space-hamster-bam.md)
*Source: Boo's Astral Menagerie p. 56*  

The first space hamsters were created by wizards who used magic to shrink giant space hamsters to wee size, leading their creators to refer to them as miniature giant space hamsters. The magic also made the space hamsters smarter and telepathic.

These benign rodents are native to Wildspace, though countless numbers of them have found their way to worlds throughout the Material Plane, where they are known simply as hamsters. They keep their telepathic ability hidden from most other creatures they come near.

```statblock
"name": "Space Hamster (BAM)"
"size": "Tiny"
"type": "monstrosity"
"alignment": "typically  Neutral Good"
"ac": !!int "15"
"hp": !!int "10"
"hit_dice": "4d4"
"stats":
- !!int "1"
- !!int "20"
- !!int "10"
- !!int "6"
- !!int "12"
- !!int "6"
"speed": "20 ft., burrow 5 ft."
"skillsaves":
  "Stealth": !!int "7"
  "Perception": !!int "3"
"senses": "passive Perception 13"
"languages": "telepathy 5 ft."
"cr": "1/4"
"actions":
- "desc": "Melee Weapon Attack: +7 to hit, reach 5 ft., one target. Hit: 1 piercing\
    \ damage."
  "name": "Bite"
- "desc": "Melee Weapon Attack: +7 to hit, reach 5 ft., one creature. Hit: 8\
    \ (1d6 + 5) piercing damage, and the target must succeed on a DC 15 Dexterity\
    \ saving throw or be [blinded](Mechanics/Rules/conditions.md#Blinded) until the\
    \ start of the hamster's next turn."
  "name": "Go for the Eyes (Recharge 6)"
"bonus_actions":
- "desc": "The hamster takes the Dash or Disengage action."
  "name": "Escape"
"source":
- "BAM"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/BAM/Space%20Hamster.webp"
```
^statblock