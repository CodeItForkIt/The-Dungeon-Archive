---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/psz
- monster/cr/10
- monster/size/large
- monster/type/dragon
aliases: ["Zendikar Dragon"]
---
# Zendikar Dragon
*Source: Plane Shift: Zendikar p. 29*  

Dragons are the ultimate representation of the chaos, ferocity, and reckless independence of red mana. They are found across Zendikar in mountainous regions where red mana is plentiful, particularly in Akoum, though never in great numbers.

A dragon is an enormous reptilian monster with thick, tough scales and leathery wings. Sharp spines or thick plates run down its back, and most dragons have large horns. A dragon's body has a vaguely feline shape, with a long neck supporting a large head, and a long, thick tail lashing behind it. Its four legs end in sharp claws that are deadly weapons, and its mouth is full of sharp teeth. Even a young dragon is larger than a powerful warhorse, and the largest are on par with some of the larger Eldrazi (though not as mighty as the towering Eldrazi titans).

The dragons of Zendikar are not particularly intelligent, especially in comparison to the genius dragon Planeswalker Nicol Bolas. They are more aware than the average beast and perhaps slightly smarter than an ogre, but dragons are still driven primarily by their instincts—to hunt for prey and to guard their territories against any intruders. They are hot-tempered and ferocious, typically rending or incinerating anything they perceive as an enemy before even thinking to ask questions.

A dragon's most fearsome aspect is its ability to exhale a blast of fire from its mouth. As it draws breath, a red glow like that of molten metal forms around its mouth, and is sometimes visible in its neck and chest as well. The fire then erupts in a long stream or a broad cone, shaped by the dragon as it chooses. A dragon might strafe the ground with fire as it flies overhead, covering as much ground—and incinerating as many foes—as possible. A grounded dragon turns its head back and forth as it breathes, blanketing its foes in flame or creating a barrier of burning earth to cover its retreat.

The [young red dragon](2-Mechanics/CLI/bestiary/dragon/young-red-dragon.md) in the Monster Manual can represent the dragons of Zendikar, but its Intelligence score is only 8 (−1). This change has no effect on its other statistics.

```ad-statblock
title: Zendikar Dragon
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/PSZ/Zendikar%20Dragon.webp#token)
*Large dragon, Chaotic Evil*

- **Armor Class** 18 (natural armor)
- **Hit Points** 178 (`17d10 + 85`)
- **Speed** 40 ft., climb 40 ft., fly 80 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|23 (+6)|10 (+0)|21 (+5)| 8 (-1)|11 (+0)|19 (+4)|

- **Proficiency Bonus** +4
- **Saving Throws** Dexterity +4, Constitution +9, Wisdom +4, Charisma +8
- **Skills** Perception +8, Stealth +4
- **Senses** blindsight 30 ft., darkvision 120 ft., passive Perception 18
- **Damage Immunities** fire
- **Languages** Common, Draconic
- **Challenge** 10

## Actions

***Multiattack.*** The dragon makes three attacks: one with its bite and two with its claws.

***Bite.*** *Melee Weapon Attack:* `dice:1d20+10|noform|text(+10)` to hit, reach 10 ft., one target. *Hit:* `dice:2d10+6|noform|avg|text(17)` (`2d10 + 6`) piercing damage plus `dice:1d6|noform|avg|text(3)` (`1d6`) fire damage.

***Claw.*** *Melee Weapon Attack:* `dice:1d20+10|noform|text(+10)` to hit, reach 5 ft., one target. *Hit:* `dice:2d6+6|noform|avg|text(13)` (`2d6 + 6`) slashing damage.

***Fire Breath (Recharge 5-6).*** The dragon exhales fire in a 30-foot cone. Each creature in that area must make a DC 17 Dexterity saving throw, taking `dice:16d6|noform|avg|text(56)` (`16d6`) fire damage on a failed save, or half as much damage on a successful one.
```
^statblock