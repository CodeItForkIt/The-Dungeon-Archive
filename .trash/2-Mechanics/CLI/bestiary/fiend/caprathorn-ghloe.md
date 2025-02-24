---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/ghloe
- monster/cr/21
- monster/size/huge
- monster/type/fiend
aliases: ["Caprathorn"]
---
# Caprathorn
*Source: Grim Hollow: Lairs of Etharis p. 91*  

> [!quote]  
> 
> The temptation to aid a lost lamb should be tamped down when a thornlamm appears. Where there is one, there are many. And all lead back to a creature far more terrifying than any big, bad wolf.

## Salvage

The sphere of annihilation a caprathorn leaves behind can be controlled and taken. At the start of each day there is a 2% chance the sphere disappears forever.

## Lore

- **DC 10 Intelligence ([Arcana](2-Mechanics/CLI/rules/skills.md#Arcana)).** A caprathorn can detach a thornlamm to fight as its ally or consume one to heal.  
- **DC 15 Intelligence ([Arcana](2-Mechanics/CLI/rules/skills.md#Arcana)).** The caprathorn can entomb a fallen foe and unleash a field of disintegrating force. This annihilation field recharges if a creature the caprathorn has entombed dies.  
- **DC 20 Intelligence ([Arcana](2-Mechanics/CLI/rules/skills.md#Arcana)).** When a caprathorn dies, it implodes into a sphere of annihilation, which pulls nearby creatures toward it.  

## Statblock

```ad-statblock
title: Caprathorn
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/GHLoE/Caprathorn.webp#token)
*Huge fiend, Chaotic Evil*

- **Armor Class** 19 (natural armor)
- **Hit Points** 250 (`20d12 + 120`)
- **Speed** 40 ft., fly 40 ft. (hover)

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|25 (+7)|14 (+2)|23 (+6)|14 (+2)|17 (+3)|10 (+0)|

- **Proficiency Bonus** +7
- **Saving Throws** Intelligence +9, Wisdom +10, Charisma +7
- **Skills** Perception +10
- **Senses** truesight 120 ft., passive Perception 20
- **Damage Resistances** cold, fire, lightning
- **Damage Immunities** poison; bludgeoning, piercing, slashing from nonmagical attacks
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** all, telepathy 120 ft.
- **Challenge** 21

## Traits

***Charge.*** If the caprathorn moves at least 20 feet straight toward a target, and then hits it with a gore attack on the same turn, the target takes an extra `dice:4d8|noform|avg|text(18)` (`4d8`) bludgeoning damage. If the target is a creature, it must succeed on a DC 22 Strength saving throw or be pushed up to 10 feet away and knocked [prone](2-Mechanics/CLI/rules/conditions.md#Prone).

***Implosion.*** The caprathorn implodes when it dies, leaving behind a sphere of annihilation. Each creature within 60 feet of the caprathorn when this implosion occurs must succeed on a DC 21 Strength saving throw or be pulled 10 feet toward the sphere.

***Legendary Resistance (3/Day).*** If the caprathorn fails a saving throw, it can choose to succeed instead.

***Magic Resistance.*** The caprathorn has advantage on saving throws against spells and other magical effects.

***Magic Weapons.*** The caprathorn's weapon attacks are magical.

***Thornlamms.*** A caprathorn typically has three inanimate thornlamms (see that stat block) attached to its horns with vines. Attached thornlamms don't take damage separately, but whenever the caprathorn takes 50 or more damage in a single turn, one of the attached thornlamms dies.

While it has at least one thornlamm attached to its vines, the caprathorn can use a bonus action to consume or detach a thornlamm. If the caprathorn consumes a thornlamm, the caprathorn regains 21 hit points. When the caprathorn detaches a thornlamm, that thornlamm lands in a space within 10 feet of the caprathorn and takes a turn immediately after the caprathorn. The thornlamm obeys the caprathorn's verbal or telepathic commands (no action for the caprathorn). If issued no commands, the thornlamm acts independently, often attacking a creature that isn't its ally. A thornlamm can survive indefinitely detached from a caprathorn.

## Actions

***Multiattack.*** The caprathorn makes three attacks, one with its gore, one with its stomp, and one with its thorns.

***Gore.*** *Melee Weapon Attack:* `dice:1d20+14|noform|text(+14)` to hit, reach 10 ft., one target. *Hit:* `dice:4d8+7|noform|avg|text(25)` (`4d8 + 7`) bludgeoning damage.

***Stomp.*** *Melee Weapon Attack:* `dice:1d20+14|noform|text(+14)` to hit, reach 10 ft., one target. *Hit:* `dice:4d8+7|noform|avg|text(25)` (`4d8 + 7`) bludgeoning damage.

***Thorns.*** *Melee or Ranged Weapon Attack:* `dice:1d20+14|noform|text(+14)` to hit, reach 10 ft. or range 30/120 ft., one target. *Hit:* `dice:4d6+7|noform|avg|text(21)` (`4d6 + 7`) piercing damage. Being within 5 feet of a hostile creature doesn't cause the caprathorn to have disadvantage on the ranged attack roll.

## Legendary Actions

***Attack.*** The caprathorn makes one attack with its gore, stomp, or thorns.

***Detach Thornlamm.*** The caprathorn detaches a thornlamm as per the Thornlamms trait.

***Grow Thornlamm.*** Provided it has taken no damage from a silvered weapon this round, the caprathorn grows one thornlamm as per the Thornlamms trait. A caprathorn can have up to six attached thornlamms at a time.

***Consume Thornlamm (Costs 2 Actions).*** The caprathorn consumes an attached thornlamm, regaining 21 hit points.

***Entomb (Costs 2 Actions).*** The caprathorn chooses a creature that has 0 hit points that the caprathorn can see within 30 feet of it. The target must make a DC 18 Wisdom saving throw. On a success, the target is immune to this effect for 24 hours. If the save fails, the target is entombed deep within the earth in a sphere of magical force that is just large enough to contain the target. Nothing can pass through the sphere, nor can any creature teleport or use planar travel to get into or out of it. A caprathorn can entomb only one target at a time. This effect ends, returning the target to where it was before being entombed, if the target regains any hit points or the caprathorn dies.

***Annihilation Field (Costs 3 Actions; Recharges if an Entombed Creature Dies or after a Long Rest).*** A sphere of energy ripples out in a 30-foot-radius from the caprathorn. Each creature in that area must make a DC 18 Constitution saving throw, taking `dice:7d10|noform|avg|text(38)` (`7d10`) force damage on a failed save, or half a s much damage on a successful one. For objects that aren't worn or carried, this emanation destroys Small and smaller ones and damages larger ones. The circle destroys a wall of force or similar structures of force in the area instantly. A creature or object is disintegrated if it drops to 0 hit points due to this magic. A disintegrated creature or object turns to fine ash, and nonmagical objects a disintegrated creature wears or carries disintegrate with it.
```
^statblock