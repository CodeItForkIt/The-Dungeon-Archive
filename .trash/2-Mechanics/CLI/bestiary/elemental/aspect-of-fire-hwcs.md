---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/hwcs
- monster/cr/12
- monster/size/gargantuan
- monster/type/elemental
aliases: ["Aspect of Fire"]
---
# Aspect of Fire
*Source: Humblewood Campaign Setting p. 179*  

> [!quote] A quote from Witness account of The Great Calamity  
> 
> "It flared so brightly as it consumed the trees... leaving naught but ashes in its wake."

The aspect of fire is an elemental creature of fire and molten rock, whose gargantuan frame could easily be mistaken for a small mountain. The aspect is not only a creature of heat and energy, but also of destruction and rage, and it appears to draw strength from the forests its flames consume.

## Primal Incarnation

A creature of legend, it is believed by some that this was the "being of fire and destruction" said to have caused the Great Calamity that created the Scorched Grove many centuries ago. The aspect possesses frightening power, enough to cause serious harm to the Wood and all those who inhabit it. Long has it been forgotten that the creature was conjured in a lost ritual. Shortly afterwards, it was sealed away beneath the Scorched Grove where its presence has continued to affect the region. Centuries of dormancy have weakened the aspect, as its essence has seeped into the surrounding land. Since being released, it has begun to amass power for itself by consuming plants, trees, and other living beings in flame. Once it attains enough energy to completely break the mystical fetters that tie it to the Scorched Grove, it will be an unstoppable force that could very well bring fiery ruin to all of Humblewood.

## Stirring in its Slumber

The strange occurrences of late have many prominent scholars baffled: unusually aggressive emberbats, the appearance of ashsnakes, the increased frequency of forest fires, and many other phenomena which have never been seen before in Humblewood. More than mere legend, the aspect is the reason for all of these. As a creature of primordial fire, it is inextricably bound to the plane of its element. Even as it slumbered beneath the Grove for generations, the aspect has stirred, its presence causing a weakening in the barrier which keeps the material plane separate from the plane of fire, allowing for weaker creatures to slip through.

The aspect's essence has also seeped into the Scorched Grove, causing the landscape to take on far stronger elemental properties than before. The fundamental shift in the Grove's nature has effectively thwarted the efforts of the Tenders, who have for so long sought to heal this burned land. As the aspect continues to grow in power, more of this harmful elemental energy will be released, and even more powerful creatures will arise from the flames. If this otherworldly power spreads across the forest unchecked, all of Humblewood might suffer the fate of the Scorched Grove.

## Statblock

```ad-statblock
title: Aspect of Fire
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/HWCS/Aspect%20of%20Fire.webp#token)
*Gargantuan elemental, Unaligned*

- **Armor Class** 15 (natural armor)
- **Hit Points** 174 (`12d20 + 48`)
- **Speed** 40 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|21 (+5)|13 (+1)|18 (+4)| 6 (-2)|15 (+2)|14 (+2)|

- **Proficiency Bonus** +4
- **Saving Throws** Wisdom +6
- **Skills** ⏤
- **Senses** darkvision 120 ft., passive Perception 12
- **Damage Resistances** bludgeoning, piercing, and slashing from nonmagical weapons
- **Damage Immunities** fire, poison
- **Condition Immunities** [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled), [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed), [petrified](2-Mechanics/CLI/rules/conditions.md#Petrified), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned), [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained), [unconscious](2-Mechanics/CLI/rules/conditions.md#Unconscious)
- **Languages** Ignan
- **Challenge** 12

## Traits

***Legendary Resistance (3/Day).*** If the Aspect of Fire fails a saving throw, it can choose to succeed instead.

***Molten Skin.*** Any creature who touches, makes a melee attack within 5 feet of, or ends their turn within 5 feet of the aspect takes `dice:2d10|noform|avg|text(11)` (`2d10`) fire damage. Flammable objects within 5 feet of the aspect burst into flames.

***Natural Light.*** The aspect gives off bright light in a 60-foot-radius and dim light for an additional 60 feet.

***Cooling.*** If the aspect of fire takes 50 or more cold damage in one round, its speed is reduced to 0 until the end of its next turn.

***Fuel for the Fire.*** The aspect of fire doesn't treat plant life as difficult terrain. Whenever the aspect begins its turn in a space of plant life that provides cover, it burns the plant life away from all spaces it is currently occupying, healing `dice:1d4|noform|avg` (`1d4`) hit points for each 5-foot square of such plant life it has consumed. If it heals for 17 or more damage in this way, it flares up, recharging its magma throw action.

## Actions

***Multiattack.*** The aspect makes two molten fist attacks.

***Molten Fist.*** *Melee Weapon Attack:* `dice:1d20+9|noform|text(+9)` to hit, reach 15 ft., one target. *Hit:* `dice:2d10+5|noform|avg|text(16)` (`2d10 + 5`) fire damage.

***Stomp.*** *Melee Weapon Attack:* `dice:1d20+9|noform|text(+9)` to hit, reach 5 ft., one target. *Hit:* `dice:3d10+5|noform|avg|text(20)` (`3d10 + 5`) fire damage. The target must succeed on a DC 17 Constitution saving throw or be knocked [prone](2-Mechanics/CLI/rules/conditions.md#Prone).

***Magma Throw (Recharge 5-6).*** The aspect hurls a ball of molten rock. Choose a location within 60 feet of the aspect. All creatures within 15 feet of the target location must make a DC 17 Dexterity saving throw. On a failure, a creature takes `dice:4d10|noform|avg|text(22)` (`4d10`) fire damage. On a success, the creature takes half as much damage.

## Legendary Actions

The aspect of fire can take 3 legendary actions, choosing from the options below. Only one legendary action option can be used at a time, and only at the end of another creature's turn. The aspect regains spent legendary actions at the start of its turn.

***Detect.*** The aspect makes a Wisdom ([Perception](2-Mechanics/CLI/rules/skills.md#Perception)) check.

***Molten Fist.*** The aspect makes a molten fist attack.

***Magma Barrage (Costs 2 Actions).*** The aspect of fire uses its magma throw action. It may use this ability if it has not yet been recharged by dealing 17 points of cold damage to itself. 
```
^statblock