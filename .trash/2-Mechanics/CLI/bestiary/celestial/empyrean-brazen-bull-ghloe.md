---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/ghloe
- monster/cr/10
- monster/size/huge
- monster/type/celestial
aliases: ["Empyrean Brazen Bull"]
---
# Empyrean Brazen Bull
*Source: Grim Hollow: Lairs of Etharis p. 100*  

> [!quote]  
> 
> The smell of smoke and incense consumed the castle walls, and we heard the furious and gleeful bellows of the most immense bull we'd ever seen. As our battlements burned and crumbled, we knew all was lost.

## Salvage

The exploded metal hide of the Empyrean brazen bull can be harvested to make gleaming and radiant [brazen armor](2-Mechanics/CLI/items/brazen-armor-ghloe.md) (see Appendix A of Lairs of Etharis). A proficient armor smith can make a suit of [brazen armor](2-Mechanics/CLI/items/brazen-armor-ghloe.md) by succeeding on a DC 20 Strength ([Athletics](2-Mechanics/CLI/rules/skills.md#Athletics)) check and using 2500 gp of components. This process takes 20 days to complete.

## Lore

- **DC 10 Intelligence ([Nature](2-Mechanics/CLI/rules/skills.md#Nature)).** Wildfires that seem to begin with hoofprints are sometimes found during the dry season in farmland, and bright spots on the horizon that look like a massive cow are often reported at the same time.  
- **DC 15 Intelligence ([Religion](2-Mechanics/CLI/rules/skills.md#Religion)).** The Empyrean brazen bull is a beast of burden for angels, used for besieging enemies.  
- **DC 20 Intelligence ([Arcana](2-Mechanics/CLI/rules/skills.md#Arcana)).** The Empyrean brazen bull explodes when it dies, and luck be with all in the wake of the blast.  

## Statblock

```ad-statblock
title: Empyrean Brazen Bull
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/GHLoE/Empyrean%20Brazen%20Bull.webp#token)
*Huge celestial, Lawful Good*

- **Armor Class** 16 (natural armor)
- **Hit Points** 162 (`12d12 + 84`)
- **Speed** 50 ft., fly 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|26 (+8)|10 (+0)|25 (+7)|14 (+2)|17 (+3)|21 (+5)|

- **Proficiency Bonus** +4
- **Saving Throws** Strength +12, Constitution +11, Wisdom +7, Charisma +9
- **Skills** Athletics +12, Perception +7
- **Senses** darkvision 120 ft., passive Perception 17
- **Damage Resistances** acid; cold; lightning; bludgeoning, piercing, slashing from nonmagical attacks
- **Damage Immunities** fire, necrotic, poison, radiant
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [prone](2-Mechanics/CLI/rules/conditions.md#Prone), [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained)
- **Languages** Celestial
- **Challenge** 10

## Traits

***Celestial Arsenal.*** The Empyrean brazen bull's weapon attacks are magical. When it hits with any weapon, the weapon deals an extra `dice:4d8|noform|avg|text(18)` (`4d8`) radiant damage (included in the attack).

***Death Throes.*** When the Empyrean brazen bull dies, it explodes, and each creature within 20 feet of it must make a DC 17 Dexterity saving throw, taking 21 `dice:6d6|noform|avg` (`6d6`) fire and `dice:6d6|noform|avg|text(21)` (`6d6`) radiant damage on a failed save, or half as much damage on a successful one.

***Soulfire Nimbus.*** At the start of each of the Empyrean brazen bull's turns, each creature within 5 feet of it takes `dice:3d6|noform|avg|text(10)` (`3d6`) radiant damage. A creature that touches the Empyrean brazen bull or hits it with a melee attack while within 5 feet of it takes `dice:3d6|noform|avg|text(10)` (`3d6`) radiant damage.

***Siege Monster.*** The Empyrean brazen bull deals double damage to objects and structures.

***Unrelenting Charge.*** If the Empyrean brazen bull moves at least 20 feet straight toward a creature and then hits it with a gore attack on the same turn, that target must succeed on a DC 20 Strength saving thrown or be knocked [prone](2-Mechanics/CLI/rules/conditions.md#Prone). If the target is [prone](2-Mechanics/CLI/rules/conditions.md#Prone), the Empyrean brazen bull can make one attack with its bite or hooves against it as a bonus action.

## Actions

***Bite.*** *Melee Weapon Attack:* `dice:1d20+12|noform|text(+12)` to hit, reach 10 ft., one target., *Hit:* `dice:3d10+8|noform|avg|text(24)` (`3d10 + 8`) bludgeoning damage plus `dice:4d8|noform|avg|text(18)` (`4d8`) radiant damage. If the target is a creature, it is [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) (escape DC 20). Until this grapple ends, the target is [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained), and the Empyrean brazen bull can't bite another target.

***Gore.*** *Melee Weapon Attack:* `dice:1d20+12|noform|text(+12)` to hit, reach 10 ft., one target. *Hit:* `dice:3d12+8|noform|avg|text(27)` (`3d12 + 8`) piercing damage and `dice:4d8|noform|avg|text(18)` (`4d8`) radiant damage.

***Hooves.*** *Melee Weapon Attack:* `dice:1d20+12|noform|text(+12)` to hit, reach 5 feet., one target. *Hit:* `dice:3d10+8|noform|avg|text(24)` (`3d10 + 8`) bludgeoning damage and `dice:4d8|noform|avg|text(18)` (`4d8`) radiant damage.

***Swallow.*** The Empyrean brazen bull makes one bite attack against a Medium or smaller creature it is grappling. If the attack hits, that creature takes the bite's damage and is swallowed, and the grapple ends. While swallowed, the creature is [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded) and [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained), it has total cover against attacks and other effects outside the Empyrean brazen bull, and it takes `dice:6d6|noform|avg|text(21)` (`6d6`) fire damage at the start of each of theEmpyrean brazen bull's turns. If the Empyrean brazen bull takes 30 damage or more on a single turn from a creature inside it, the Empyrean brazen bull must succeed on a DC 15 Constitution saving throw at the end of that turn or regurgitate all swallowed creatures, which fall [prone](2-Mechanics/CLI/rules/conditions.md#Prone) in a space within 10 feet of the empyrean brazen bull. If the Empyrean brazen bull dies, a swallowed creature is no longer [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) by it and can escape from the corpse using 15 feet of movement, exiting [prone](2-Mechanics/CLI/rules/conditions.md#Prone).
```
^statblock