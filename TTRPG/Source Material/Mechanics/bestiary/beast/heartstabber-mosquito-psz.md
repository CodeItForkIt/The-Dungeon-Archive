---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/psz
- monster/cr/1-8
- monster/size/tiny
- monster/type/beast
statblock: inline
aliases: ["Heartstabber Mosquito"]
---
# [Heartstabber Mosquito](Mechanics\bestiary\beast/heartstabber-mosquito-psz.md)
*Source: Plane Shift: Zendikar p. 27*  

The black mana that brews and festers in Zendikar's swamps infuses a wide variety of natural animals, creating large, deadly vermin—rats, bats, insects, scorpions, and spiders that spread death and decay with their bites, stings, or caustic saliva. The swamps of Guul Draz are home to many such creatures, from the enormous heartstabber mosquitoes (best represented with [stirge](Mechanics/bestiary/beast/stirge.md) statistics) to giant scorpions large enough to hold a struggling vampire in one claw. The gigantic, ant-like caustic crawlers (similar to [ankhegs](Mechanics/bestiary/monstrosity/ankheg.md)) shape burrows from stone with their acidic saliva, creating strangely smooth walls easily mistaken for ancient construction. Gloomhunter bats the size of griffins have reservoirs of vaporous mana in their heads, causing their bite to tear at the spirit as well as the flesh. These and other creatures can be built from the offerings in "appendix A of the Monster Manual".

```statblock
"name": "Heartstabber Mosquito (PSZ)"
"size": "Tiny"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "14"
"ac_class": "natural armor"
"hp": !!int "2"
"hit_dice": "1d4"
"stats":
- !!int "4"
- !!int "16"
- !!int "11"
- !!int "2"
- !!int "8"
- !!int "6"
"speed": "10 ft., fly 40 ft."
"senses": "darkvision 60 ft., passive Perception 9"
"languages": ""
"cr": "1/8"
"actions":
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one creature. Hit: 5\
    \ (1d4 + 3) piercing damage, and the mosquito attaches to the target. While\
    \ attached, the mosquito doesn't attack. Instead, at the start of each of the\
    \ mosquito's turns, the target loses 5 (1d4 + 3) hit points due to blood loss.\n\
    \nThe mosquito can detach itself by spending 5 feet of its movement. It does so\
    \ after it drains 10 hit points of blood from the target or the target dies. A\
    \ creature, including the target, can use its action to detach the mosquito."
  "name": "Blood Drain"
"source":
- "PSZ"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/PSZ/Heartstabber%20Mosquito.webp"
```
^statblock