---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/16
- monster/environment/mountain
- monster/environment/planar
- monster/size/medium
- monster/type/fey
aliases: ["Snow Queen"]
---
# Snow Queen
*Source: Tome of Beasts 1 (2023 Edition) p. 184*  

*This severe elf has pale, almost white skin and tightly braided blond hair. Her gown is exquisite, fashioned of luminous blue fabric that catches light and shines from within. Lacy ice crystals accent the gown, and a snow-white mantle cascades from her shoulders. Icicles radiate in a crownlike halo behind her head, drifting gracefully through the air*.

Her Crystalline Majesty, Morrinn, is the cold-hearted Snow Queen, Daughter of Boreas. The Snow Queen rules a northern kingdom in the remote, frozen reaches of the world. Perpetually shrouded in snow and ice, her domain is inhospitable to outsiders. She rules from a castle of delicate spires carved entirely out of ice. The dwelling catches and reflects even the faintest glimmer of light, shining like a beacon and enticing travelers to risk the dangerous winter realm.

## Queen of Giants

The Snow Queen is proud and cruel to any who cross her. Her daughters, the ice maidens, roam her kingdom with ease. Travelers who can't give a good reason to be moving through the Queen's territory meet a quick end in the maidens' chilly embrace. The Snow Queen commands the loyalty of winter-born tribes of fraughashar, ogres, frost giants, thursir giants, and trollkin. She is said to have mocked both Thor and Loki and often leads their priests astray into winter storms.

## Fey Lords and Ladies

Fey are capricious, mischievous, and often dangerous beings. However, despite their chaotic reputations, they do follow a certain set of rules. These rules—widely misunderstood by outsiders—are codified and enforced by a cadre of lofty fey nobility. Befitting any courtly structure, the fey bow to lords and ladies: eldritch creatures of immense power who rule the courts.

### Heads of State

The fey lords and ladies are beings of high station and prodigious personal power. Each rules over at least a great city if not an entire nation. No matter the scope of a fey noble's domain, in his or her eyes, a fey ruler's word is law. Outsiders might not understand the edicts and interdicts of a fey noble, but that's no protection against the harsh penalties that await any who break them, knowingly or otherwise.

### Vacant Thrones

When a lord or lady of the fey dies, the court does not remain leaderless for long. Ambitious beings among the fey always hunger for more power and covet the stations of their superiors. After a traditional month or year of mourning, vicious power struggles winnow the weak and pave the way for the most cunning or the strongest to take the court's vacant throne.

## The Snow Queen's Lair

The Snow Queen's lair is a castle made of ice. Sunlight and moonlight flash through the delicate spires and translucent walls, setting the palace agleam even in the deepest night. The castle reflects its mistress: beautiful, cold, and unforgivingly deadly.

## Statblock

```ad-statblock
title: Snow Queen
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Snow%20Queen.webp#token)
*Medium fey, Neutral Evil*

- **Armor Class** 17 (natural armor)
- **Hit Points** 182 (`28d8 + 56`)
- **Speed** 40 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|16 (+3)|18 (+4)|14 (+2)|18 (+4)|20 (+5)|18 (+4)|

- **Proficiency Bonus** +5
- **Saving Throws** Dexterity +9, Constitution +7, Charisma +9
- **Skills** Perception +10, Stealth +9
- **Senses** blindsight 10 ft., darkvision 120 ft., passive Perception 20
- **Damage Resistances** bludgeoning, piercing, slashing from nonmagical attacks not made with cold iron weapons
- **Damage Immunities** cold
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened)
- **Languages** Common, Elvish, Giant, Sylvan
- **Challenge** 16

## Traits

***Ice Climb.*** When climbing on ice, the Snow Queen has a climbing speed of 20 feet, and she can climb difficult surfaces made of ice and snow, including upside down on ceilings, without needing to make an ability check.

***Icy Weapons.*** The Snow Queen's weapon attacks are magical. When she hits with any weapon, the weapon deals an extra `dice:2d6|noform|avg` (`2d6`) cold damage (included in the attack).

***Legendary Resistance (3/Day).*** If the Snow Queen fails a saving throw, she can choose to succeed instead.

***Snowsight.*** The Snow Queen can see through areas obscured by snowfall, sleet, rain, and other wintry precipitation without penalty.

***Snow Walk.*** The Snow Queen can move across icy surfaces without needing to make an ability check. Additionally, difficult terrain composed of ice or snow doesn't cost her extra movement.

## Actions

***Multiattack.*** The Snow Queen makes two Claw or Ice Bolt attacks.

***Claw.*** *Melee Weapon Attack:* `dice:1d20+9|noform|text(+9)` to hit, reach 5 ft., one target. *Hit:* `dice:2d6+4|noform|avg|text(11)` (`2d6 + 4`) slashing damage plus `dice:2d6|noform|avg|text(7)` (`2d6`) cold damage.

***Ice Bolt.*** *Ranged Spell Attack:* `dice:1d20+10|noform|text(+10)` to hit, range 120 ft., one target. *Hit:* `dice:2d8+4|noform|avg|text(13)` (`2d8 + 4`) piercing damage plus `dice:2d6|noform|avg|text(7)` (`2d6`) cold damage. The target's speed is reduced by 10 feet until the end of its next turn.

***Cold Snap (Recharge 5-6).*** The Snow Queen causes the temperature around her to drop dramatically. Each creature without 30 feet of the Snow Queen must make a DC 18 Constitution saving throw. On a failure, a creature takes `dice:12d6|noform|avg|text(42)` (`12d6`) cold damage and suffers one level of [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion). On a success, a creature takes half the damage and doesn't suffer [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion). A creature that is immune to cold damage doesn't suffer [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), even if it fails the saving throw. A creature that fails the saving throw by 5 or more is [petrified](2-Mechanics/CLI/rules/conditions.md#Petrified) in ice for 1 minute. A [petrified](2-Mechanics/CLI/rules/conditions.md#Petrified) creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success. A [petrified](2-Mechanics/CLI/rules/conditions.md#Petrified) creature that takes fire damage has advantage on the saving throw to end the effect.

## Legendary Actions

***Attack.*** The Snow Queen makes a Claw or Ice Bolt attack.

***Move.*** The Snow Queen moves up to her speed without provoking opportunity attacks.

***Snowblind.*** One creature the Snow Queen can see within 120 feet of her must succeed on a DC 18 Dexterity saving throw or be [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded) by swirling snow until the end of its next turn.

***Wintry Swirl (Costs 2 Actions).*** Each creature within 15 feet of the Snow Queen must succeed on a DC 18 Constitution saving throw or have vulnerability to cold damage until the end of its next turn. A creature with immunity to cold damage that fails this saving throw instead loses its immunity to cold damage but isn't vulnerable to it.

![Snow Queen](2-Mechanics/CLI/bestiary/legendary-group/snow-queen-tob1-2023.md)
```
^statblock

## Environment

mountain, planar