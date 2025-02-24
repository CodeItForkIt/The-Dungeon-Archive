---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/ghloe
- monster/cr/22
- monster/size/large
- monster/type/celestial
aliases: ["Angel of Empyreus"]
---
# Angel of Empyreus
*Source: Grim Hollow: Lairs of Etharis p. 104*  

> [!quote]  
> 
> I am that which can cleanse temptation from the land and restore it once more to divinity. What a weak creature of flesh you are, blessed with free will and fickle fancy. I will reveal your weakness, wretched mortal.

## Salvage

The Angel of Empyreus wields a holy avenger. Upon its death, its intelligence inhabits the sword. To attune to it, a paladin character must agree to carry on the angel's mission to cleanse the land of immorality.

A cup of its blood can be made into a [potion of supreme healing](2-Mechanics/CLI/items/potion-of-supreme-healing.md) with a DC 10 Intelligence ([Religion](2-Mechanics/CLI/rules/skills.md#Religion)) check from someone proficient with alchemist's supplies. Six cups of blood can be taken from the Angel of Empyreus.

Its bones can be used in place of diamonds for use in raise dead and similar magic, up to the equivalent of 10,000 gp worth.

## Lore

- **DC 10 Intelligence ([Religion](2-Mechanics/CLI/rules/skills.md#Religion)).** The Arch Seraphs are attended by mighty angels who act as their lieutenants and execute the divine remnants' orders.  
- **DC 15 Intelligence ([History](2-Mechanics/CLI/rules/skills.md#History)).** Empyreus went into battle surrounded by an honor guard of fearsome celestials honed by aeons of divine war. Many of them remained at Empyreus' side at the end of the Four Divines' War, but not all remained loyal.  
- **DC 20 Intelligence ([History](2-Mechanics/CLI/rules/skills.md#History)).** Peasant revolts and religious zealotry are on the rise in the Altenheim hinterland. Most say it's the usual grievances, but some whisper that a commander of the celestial hosts leads the revolt, and its ranks swell by the day.  

## Statblock

```ad-statblock
title: Angel of Empyreus
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/GHLoE/Angel%20of%20Empyreus.webp#token)
*Large celestial, Lawful Neutral*

- **Armor Class** 21 (natural armor)
- **Hit Points** 445 (`33d10 + 264`)
- **Speed** 40 ft., fly 90 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|29 (+9)|23 (+6)|26 (+8)|25 (+7)|18 (+4)|30 (+10)|

- **Proficiency Bonus** +7
- **Saving Throws** Strength +16, Intelligence +14, Wisdom +11, Charisma +17
- **Skills** Arcana +14, Insight +11, Intimidation +17, Investigation +14, Perception +11, Religion +14
- **Senses** truesight 120 ft., passive Perception 21
- **Damage Resistances** fire; lightning; radiant; bludgeoning, piercing, slashing from nonmagical attacks
- **Damage Immunities** cold, necrotic, poison
- **Condition Immunities** [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded), [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [deafened](2-Mechanics/CLI/rules/conditions.md#Deafened), [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** all, telepathy 120 ft.
- **Challenge** 22

## Traits

***Celestial Arsenal.*** The Angel of Empyreus' weapon attacks are magical. When it hits with any weapon, the weapon deals an extra `dice:6d8|noform|avg|text(27)` (`6d8`) radiant damage (included in the attack).

***Authoritative Mien.*** The Angel of Empyreus can cast the [command](2-Mechanics/CLI/spells/command.md) spell at will (spell save DC 25).

***Divine Awareness.*** The Angel of Empyreus knows if it hears a lie.

***Holy Aura.*** The Angel of Empyreus can project a 60-ft. aura of holiness as a bonus action. The aura affects all creatures within its area unless the Angel of Empyreus chooses to exclude a creature from the effect. A creature remains under the aura's effect until it leaves the area, dies, or when the Angel of Empyrean chooses a new aura effect. Only one effect may be active at a time:

- **Judgement.** Creatures who start their turn in the aura must succeed on a DC 25 Charisma saving throw. On a failure, the creature gains a level of [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion) as intensified feelings of guilt, doubt, remorse, and selfcriticism overwhelm the affected creature. Creatures who succeed on the saving throw are immune to the effect for one hour.  
- **Valor.** Creatures who start their turn in the aura gain 15 temporary hit points, cannot be [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed) or [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), and have advantage on saving throws against spells and other magical effects  

## Actions

***Multiattack.*** The Angel of Empyreus can make three attacks with its holy avenger.

***Holy Avenger.*** *Melee Weapon Attack:* `dice:1d20+24|noform|text(+24)` to hit, reach 10 ft., one target. *Hit:* `dice:4d6+9|noform|avg|text(23)` (`4d6 + 9`) slashing damage plus `dice:6d8|noform|avg|text(27)` (`6d8`) radiant damage. If the target is a fiend or undead, it takes an additional `dice:4d10|noform|avg|text(22)` (`4d10`) radiant damage.

***Blazing Radiance (Recharge 5-6).*** The Angel of Empyreus unleashes holy fire in a 60-foot cone. Each creature in that area must succeed on a DC 25 Dexterity saving throw or take 35 `dice:10d6|noform|avg` (`10d6`) fire and `dice:10d6|noform|avg|text(35)` (`10d6`) radiant damage. Creatures take half damage on a success.

## Legendary Actions

***Fly.*** The Angel of Empyreus flies up to half its fly speed.

***Sword.*** The Angel of Empyreus makes a holy avenger attack.

***Hurl Sword (2 actions).*** The Angel of Empyreus hurls its sword in a 30-foot line that is 5-feet wide. Each creature in that line must succeed on a DC 24 Dexterity saving throw or take `dice:4d6+9|noform|avg|text(23)` (`4d6 + 9`) slashing damage plus `dice:6d8|noform|avg|text(27)` (`6d8`) radiant damage. The sword immediately returns to its hand.

***Recharge.*** The Angel of Empyreus recharges its Blazing Radiance.
```
^statblock