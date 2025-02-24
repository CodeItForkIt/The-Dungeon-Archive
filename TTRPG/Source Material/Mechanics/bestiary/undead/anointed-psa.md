---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/psa
- monster/cr/1-4
- monster/size/medium
- monster/type/undead
statblock: inline
aliases: ["Anointed"]
---
# [Anointed](Mechanics\bestiary\undead/anointed-psa.md)
*Source: Plane Shift: Amonkhet p. 34*  

Not every citizen of Naktamun proves to be worthy of the afterlife. Acolytes sometimes die before the Ceremony of Measurement, perhaps in training accidents. Many [initiates](Mechanics/backgrounds/initiate-psa.md) perish in one of the first four trials, before earning their five cartouches. [Viziers](Mechanics/backgrounds/vizier-psa.md) sometimes die before they have truly earned a place in the afterlife serving their gods. Without having proven themselves worthy, these poor souls have no place as Eternals in the afterlife—but neither have they committed a grievous sin that would warrant abandoning them to the Curse of Wandering as marauding [mummies](Mechanics/bestiary/undead/amonkhet-mummy-psa.md).

Fortunately, the beneficence of the God-Pharaoh is great enough to provide a role for these people. Called the anointed, they are carefully embalmed, protected from the Curse of Wandering, and allowed to spend another lifetime in service to the worthy. The God-Pharaoh promises that those who faithfully serve as the anointed will earn a place as attendants in the afterlife as well, and even an eternity of service in the afterlife is prefera-ble to an eternity subjected to the Curse of Wandering.

The bodies of the anointed are carefully wrapped in cloth and adorned with cartouches. In contrast to the cartouches of [initiates](Mechanics/backgrounds/initiate-psa.md) and [viziers](Mechanics/backgrounds/vizier-psa.md), these do not harbor the life essence of the deceased at their best. Instead, they coach the anointed for a particular form of service. With their cartouches in place, the anointed rise and join the ranks of serving [mummies](Mechanics/bestiary/undead/amonkhet-mummy-psa.md) who attend to the needs of daily life in Amonkhet.

## The Curse of Wandering

The Curse of Wandering is the greatest danger of the desert lands. A creature killed in the desert rises again as a [zombie](Mechanics/bestiary/undead/zombie.md) as soon as the moisture has dried from its flesh. As a result, the corpses of every kind of desert creature shamble across the dunes alongside the humanoid [zombies](Mechanics/bestiary/undead/zombie.md) of dissenters and would-be explorers. Most of these former humanoids are mindless marauders, though some tales speak of [mummies](Mechanics/bestiary/undead/amonkhet-mummy-psa.md) that have retained a sinister intelligence and even magical ability, becoming [mummy lords](Mechanics/bestiary/undead/amonkhet-mummy-lord-psa.md).

```statblock
"name": "Anointed (PSA)"
"size": "Medium"
"type": "undead"
"alignment": "Neutral Evil"
"ac": !!int "8"
"hp": !!int "22"
"hit_dice": "3d8 + 9"
"stats":
- !!int "13"
- !!int "6"
- !!int "16"
- !!int "3"
- !!int "6"
- !!int "5"
"speed": "20 ft."
"saves":
  "Wisdom": !!int "0"
"damage_immunities": "poison"
"condition_immunities": "[poisoned](Mechanics/Rules/conditions.md#Poisoned)"
"senses": "darkvision 60 ft., passive Perception 8"
"languages": "understands all languages it spoke in life but can't speak"
"cr": "1/4"
"traits":
- "desc": "If damage reduces the anointed to 0 hit points, it must make a Constitution\
    \ saving throw with a DC of 5 + the damage taken, unless the damage is radiant\
    \ or from a critical hit. On a success, the anointed drops to 1 hit point instead."
  "name": "Undead Fortitude"
"actions":
- "desc": "Melee Weapon Attack: +3 to hit, reach 5 ft., one target. Hit: 4 (1d6\
    \ + 1) bludgeoning damage."
  "name": "Slam"
"source":
- "PSA"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/PSA/Anointed.webp"
```
^statblock