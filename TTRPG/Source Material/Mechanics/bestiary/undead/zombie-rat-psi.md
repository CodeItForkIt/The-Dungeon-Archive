---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/psi
- monster/cr/0
- monster/size/tiny
- monster/type/undead
statblock: inline
aliases: ["Zombie Rat"]
---
# [Zombie Rat](Mechanics\bestiary\undead/zombie-rat-psi.md)
*Source: Plane Shift: Innistrad p. 17*  

Ghoulcallers are necromancers—mages who use black mana to call forth the dead from graveyards. These risen dead are called ghouls, or the unhallowed. The ghoulcaller fills the fragile mind of his or her creation with a single driving purpose, which the ghoul carries out to the best of its ability using whatever skills it has. The result is a grotesque parody of life: risen blacksmiths attempting to "reforge" their opponents, fallen warriors rasping incoherent battle cries, undead murderers reawakening their deadly slyness, and fallen mages trying to weave spells that often result in some horrible distortion of their original purpose.

The clergy of Avacyn perform rituals on the final resting places of the dead to ensure the Blessed Sleep, but during Avacyn's time in the Helvault, ghoulcallers had an easier time in their work. In this present age of Avacyn's madness, not only are necromancers easily able to plunder the graves of the fallen, but ghouls seem to arise spontaneously from graves across Innistrad.

The [zombies](Mechanics/bestiary/undead/zombie.md) in the *Monster Manual* describe the most common ghouls of Innistrad. More powerful necromancers might raise unhallowed dead with the statistics of [ghasts](Mechanics/bestiary/undead/ghast.md), [ghouls](Mechanics/bestiary/undead/ghoul.md), [mummies](Mechanics/bestiary/undead/mummy.md), or [wights](Mechanics/bestiary/undead/wight.md).

Ghouls also include zombie animals, often animated by necromancers to serve as familiars—most commonly [cats](Mechanics/bestiary/undead/zombie-cat-psi.md), [rats](Mechanics/bestiary/undead/zombie-rat-psi.md), and [snakes](Mechanics/bestiary/undead/zombie-snake-psi.md). These creatures have the statistics of the small animals in the *Monster Manual*, with the addition of the zombie's Undead Fortitude trait.

```statblock
"name": "Zombie Rat (PSI)"
"size": "Tiny"
"type": "undead"
"alignment": "Unaligned"
"ac": !!int "10"
"hp": !!int "1"
"hit_dice": "1d4 - 1"
"stats":
- !!int "2"
- !!int "11"
- !!int "9"
- !!int "2"
- !!int "10"
- !!int "4"
"speed": "20 ft."
"senses": "darkvision 30 ft., passive Perception 10"
"languages": ""
"cr": "0"
"traits":
- "desc": "If damage reduces the rat to 0 hit points, it must make a Constitution\
    \ saving throw with a DC of 5 + the damage taken, unless the damage is radiant\
    \ or from a critical hit. On a success, the rat drops to 1 hit point instead."
  "name": "Undead Fortitude"
"actions":
- "desc": "Melee Weapon Attack: +0 to hit, reach 5 ft., one target. Hit: 1 piercing\
    \ damage."
  "name": "Bite"
"source":
- "PSI"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/PSI/Zombie%20Rat.webp"
```
^statblock