---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tdcsr
- monster/cr/16
- monster/size/large
- monster/type/construct
aliases: ["Platinum Golem"]
---
# Platinum Golem
*Source: Tal'Dorei Campaign Setting Reborn p. 243*  

Ageless and unstoppable guardians, golems are expertly crafted to execute their owners' every command without question. Vaguely humanoid in appearance and unfailingly loyal, these powerful constructs feel no agony or sympathy, require no sustenance or sleep, ignore bribes and bargains, and do as they are told without remorse or hesitation.

## Covetous Origins

During the "Age of Arcanum", magic inspired a deep arrogance in many of the gods' children, who assumed arcane gifts were proof of inevitable divinity. In response, many mortal folk experimented with manufacturing "life" of their own. The "dwarves" succeeded first, marrying divine gifts with technical skill to animate autonomous wardens as protectors of their ancestral halls. The "dwarves'" knowledge was quickly stolen and expanded upon by other folk, and creating golems eventually became less about proving that mortals can shape life as the gods do, and more about protecting life, wealth, and secrets from others.

## Platinum Golem

This animated construct plated in precious platinum is the primary choice of prestigious mages and paranoid dragons to guard their most precious treasures. Its clanking footsteps make its approach audible to all intruders, who should recognize that fleeing is the best option: for the golem's form is nigh-invulnerable, and its mighty fists can obliterate life with a single blow.

### Devoted Guardians

Their creators fashion platinum golems from the spirits of indomitable warriors who died failing to protect what they loved most. This final regret fuels the golem's need to execute its master's orders to perfection. Temples of the Platinum Dragon also craft these golems using divine rituals and imbue them with the unflinching devotion to justice epitomized by their god.

## Statblock

```ad-statblock
title: Platinum Golem
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/TDCSR/Platinum%20Golem.webp#token)
*Large construct, Unaligned*

- **Armor Class** 21 (natural armor)
- **Hit Points** 189 (`18d10 + 90`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|22 (+6)|10 (+0)|21 (+5)| 3 (-4)|12 (+1)| 1 (-5)|

- **Proficiency Bonus** +5
- **Saving Throws** ⏤
- **Skills** ⏤
- **Senses** darkvision 120 ft., passive Perception 11
- **Damage Immunities** acid; cold; fire; poison; psychic; bludgeoning, piercing, slashing from nonmagical attacks that aren't adamantine
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed), [petrified](2-Mechanics/CLI/rules/conditions.md#Petrified), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** understands the languages of its creator but can't speak
- **Challenge** 16

## Traits

***Divine Custodian.*** When the golem hits a creature with an [opportunity attack](2-Mechanics/CLI/rules/actions.md#Opportunity%20Attack), that creature's speed becomes 0 for the rest of the turn.

***Immutable Form.*** The golem is immune to any spell or effect that would alter its form.

***Magic Resistance.*** The golem has advantage on saving throws against spells and other magical effects.

***Magic Weapons.*** The golem's weapon attacks are magical.

## Actions

***Multiattack.*** The golem makes two melee attacks.

***Slam.*** *Melee Weapon Attack:* `dice:1d20+11|noform|text(+11)` to hit, reach 5 ft., one target. *Hit:* `dice:3d8+6|noform|avg|text(19)` (`3d8 + 6`) piercing damage.

***Mace.*** *Melee Weapon Attack:* `dice:1d20+11|noform|text(+11)` to hit, reach 10 ft., one target. *Hit:* `dice:3d10+6|noform|avg|text(22)` (`3d10 + 6`) bludgeoning damage.

***Radiant Blast (Recharge 6).*** The golem emits a burst of radiant light in a 20-foot radius. Each creature in the area must make a DC 18 Constitution saving throw. On a failed save, a creature takes `dice:4d8|noform|avg|text(18)` (`4d8`) radiant damage and is [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded) until the end of its next turn. On a success, the creature takes half as much damage and is not [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded).

## Reactions

***Divine Judgment.*** When a creature within 10 feet of the golem makes an attack against a target other than the golem, the golem can make a mace attack against that creature.
```
^statblock