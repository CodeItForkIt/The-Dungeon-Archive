---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/mff
- monster/cr/23
- monster/size/large
- monster/type/aberration
aliases: ["Ygorl, Lord of Entropy"]
---
# Ygorl, Lord of Entropy
*Source: Mordenkainen's Fiendish Folio p. 20*  

The enigmatic being known as Ygorl was one of the first slaadi created after Primus unleashed the Spawning Stone upon Limbo. A powerful being suffused with entropic power, Ygorl delights in the act of unmaking and bringing chaos to any ecosystem it visits. Lesser slaadi follow close behind the lord of entropy, delighting and furthering the destruction it brings.

## Cycles of Chaos

As a personification of entropy, Ygorl is cursed to see things as they will become—broken and consumed by the march of eternity. It has no sense of empathy or compassion, driven only to unmake so that the resulting base elements of reality can fuel the multiverse's endless cycles of creation and destruction.

Speaking to Ygorl is a taxing endeavor, as the lord of entropy channels its thoughts as a stream of consciousness that is both disturbing and difficult to follow. Mortal creatures that have attempted to parley with Ygorl are known to have been driven to madness in the process.

## Death and Destruction

Ygorl's most notable possession is an adamantine scythe with the slaad word for death inscribed across the blade, which can reduce living creatures to ash. The lord of entropy also bears a set of obsidian tablets slung about its waist, upon which it inscribes destructive runes. Living creatures wither and rot within the entropic energy emanated by Ygorl's magic.

## Statblock

```ad-statblock
title: Ygorl, Lord of Entropy
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/MFF/Ygorl%2C%20Lord%20of%20Entropy.webp#token)
*Large aberration, Chaotic Neutral*

- **Armor Class** 20 (natural armor)
- **Hit Points** 325 (`26d10 + 182`)
- **Speed** 40 ft., climb 40 ft., swim 40 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|24 (+7)|18 (+4)|24 (+7)|20 (+5)|16 (+3)|26 (+8)|

- **Proficiency Bonus** +7
- **Saving Throws** Strength +14, Constitution +14, Charisma +15
- **Skills** Arcana +12, Deception +15, Intimidation +15, Persuasion +15
- **Senses** truesight 120 ft., passive Perception 13
- **Damage Resistances** acid, cold, fire, lightning, thunder
- **Damage Immunities** necrotic; poison; bludgeoning, piercing, slashing from nonmagical attacks
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** all, telepathy 120 ft.
- **Challenge** 23

## Traits

***Entropic Aura.*** Each creature that is not a construct or undead that ends its turn within 15 feet of Ygorl takes `dice:4d6|noform|avg|text(14)` (`4d6`) necrotic damage.

***Legendary Resistance (3/Day).*** If Ygorl fails a saving throw, it can choose to succeed instead.

***Magic Resistance.*** Ygorl has advantage on saving throws against spells and other magical effects.

***Innate Spellcasting.*** Ygorl's innate spellcasting ability is Charisma (spell save DC 23, `dice:1d20+15|noform|text(+15)` to hit with spell attacks). It can innately cast the following spells, requiring no material components:

**At will**: [blight](2-Mechanics/CLI/spells/blight.md), [blink](2-Mechanics/CLI/spells/blink.md), [chaos bolt](2-Mechanics/CLI/spells/chaos-bolt-xge.md)*, [detect magic](2-Mechanics/CLI/spells/detect-magic.md), [fly](2-Mechanics/CLI/spells/fly.md), [shield](2-Mechanics/CLI/spells/shield.md)

**1/day each**: [power word kill](2-Mechanics/CLI/spells/power-word-kill.md), [power word stun](2-Mechanics/CLI/spells/power-word-stun.md), [symbol](2-Mechanics/CLI/spells/symbol.md) (death only), [weird](2-Mechanics/CLI/spells/weird.md)

**2/day each**: [finger of death](2-Mechanics/CLI/spells/finger-of-death.md), [harm](2-Mechanics/CLI/spells/harm.md), [mental prison](2-Mechanics/CLI/spells/mental-prison-xge.md)*

**3/day each**: [circle of death](2-Mechanics/CLI/spells/circle-of-death.md), [enervation](2-Mechanics/CLI/spells/enervation-xge.md)*, [symbol](2-Mechanics/CLI/spells/symbol.md) (discord only)

* Spell from Xanathar's Guide to Everything

## Actions

***Multiattack.*** Ygorl makes three attacks: two with its scythe, and one with its Entropic Touch.

***Scythe.*** *Melee Weapon Attack:* `dice:1d20+14|noform|text(+14)` to hit, reach 10 ft., one creature. *Hit:* `dice:2d10+7|noform|avg|text(18)` (`2d10 + 7`) slashing damage plus `dice:3d12|noform|avg|text(19)` (`3d12`) necrotic damage. Any creature reduced to 0 hit points by this attack dies, with its body and everything it is wearing and carrying, except magic items, exploding into a cloud of ash. The creature can be restored to life only by means of a [wish](2-Mechanics/CLI/spells/wish.md) spell.

***Entropic Touch.*** *Melee Weapon Attack:* `dice:1d20+14|noform|text(+14)` to hit, reach 5 ft., one target. *Hit:* `dice:2d8+7|noform|avg|text(16)` (`2d8 + 7`) necrotic damage, and the target must succeed on a DC 22 Constitution saving throw or gain one level of [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion).

***Summon Slaadi (1/Day).*** Ygorl summons `dice:1d4+1|noform|avg` (`1d4 + 1`) [death slaadi](2-Mechanics/CLI/bestiary/aberration/death-slaad.md). A summoned slaad appears in an unoccupied space within 60 feet of Ygorl, acts as an ally of Ygorl, and can't summon other slaadi. It remains for 1 minute, until it or Ygorl dies, or until Ygorl dismisses it as an action.

***Teleport.*** Ygorl teleports, along with any equipment it is wearing or carrying, up to 120 feet to an unoccupied space it can see.

## Legendary Actions

***Scythe.*** Ygorl makes one attack with its scythe.

***Teleport.*** Ygorl uses its Teleport action.

***Call the Void (Costs 3 Actions).*** Each creature that is not a construct or undead within 30 feet of Ygorl must make a DC 22 Constitution saving throw against the lord of entropy's attempt to unmake life, taking `dice:12d6|noform|avg|text(42)` (`12d6`) necrotic damage on a failed save, or half as much damage on a successful one. Ygorl then regains a number of hit points equal to half the total damage taken by all affected creatures.
```
^statblock