---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/veor
- monster/cr/23
- monster/size/medium
- monster/type/undead/vampire
aliases: ["Kas the Betrayer"]
---
# Kas the Betrayer
*Source: Vecna: Eve of Ruin p. 244*  

The Betrayer, the Bloody Handed, the Destroyer—Kas has earned many epithets during his long existence. He is a vampire, legendary swordfighter, and ruthless warlord, and he is driven primarily by one thing: his hatred for Vecna.

Kas resembles a well-muscled, raven-haired, human man in his thirties, though he is far older. His fangs reveal his vampiric nature.

## Personality

Kas is cruel, spiteful, and unrelenting in his pursuit of vengeance against Vecna. He readily lies, breaks promises, betrays allies, and taunts those who fall for his ruses. Kas has little use for those who can't validate his superiority or help advance his goals.

In*Vecna: Eve of Ruin*, Kas fools Tasha and Alustriel, two incredibly powerful wizards. In addition to defeating Vecna, Kas desperately wants the wizards to witness and acknowledge his strength.

## Statblock

```ad-statblock
title: Kas the Betrayer
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/VEoR/Kas%20the%20Betrayer.webp#token)
*Medium undead (vampire), Neutral Evil*

- **Armor Class** 18 ([plate](2-Mechanics/CLI/items/plate-armor.md))
- **Hit Points** 315 (`30d8 + 180`)
- **Speed** 40 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|26 (+8)|20 (+5)|22 (+6)|24 (+7)|19 (+4)|26 (+8)|

- **Proficiency Bonus** +7
- **Saving Throws** Constitution +13, Wisdom +11, Charisma +15
- **Skills** Arcana +14, Deception +22, Perception +11, Stealth +12
- **Senses** darkvision 120 ft., passive Perception 21
- **Damage Immunities** necrotic; poison; bludgeoning, piercing, slashing from nonmagical attacks
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** Abyssal, Common, Draconic, Infernal
- **Challenge** 23

## Traits

***Eager Betrayer.*** Kas adds `dice:1d10|noform|avg` (`1d10`) to his initiative rolls. He has advantage on attack rolls against any creature that has the [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened) condition.

***Legendary Resistance (3/Day).*** If Kas fails a saving throw, he can choose to succeed instead.

***Regeneration.*** Kas regains 20 hit points at the start of his turn if he has at least 1 hit point. If he takes radiant damage, this trait doesn't function at the start of his next turn.

***Special Equipment.*** Kas wears the Crown of Lies (see the Introduction of Vecna: Eve of Ruin).

***Spider Climb.*** Kas can climb difficult surfaces, including upside down on ceilings, without needing to make an ability check.

***Strength of the Night.*** Kas doesn't require a coffin, and he drinks blood to sow terror rather than for sustenance. If destroyed, Kas revives in `dice:1d100|noform|avg` (`1d100`) nights in an unoccupied space in Tovag, his Domain of Dread. He can be permanently destroyed only by having a stake driven through his heart and then being beheaded. The stake must be cut from a tree growing in soil from Oerth, Kas's home world.

***Sunlight Hypersensitivity.*** While in sunlight, Kas takes 20 radiant damage at the start of his turn, has disadvantage on attack rolls and ability checks, and can't use his Change Shape bonus action.

## Actions

***Multiattack.*** Kas makes three Vengeful Sword attacks. He can replace one of these attacks with a Bite attack.

***Vengeful Sword.*** *Melee Weapon Attack:* `dice:1d20+15|noform|text(+15)` to hit, reach 5 ft., one target. *Hit:* `dice:2d8+11|noform|avg|text(20)` (`2d8 + 11`) slashing damage. The sword scores a critical hit on a roll of 19 or 20.

***Bite.*** *Melee Weapon Attack:* `dice:1d20+15|noform|text(+15)` to hit, reach 5 ft., one creature. *Hit:* `dice:1d6+8|noform|avg|text(11)` (`1d6 + 8`) piercing damage plus `dice:3d6|noform|avg|text(10)` (`3d6`) necrotic damage. The target's hit point maximum is reduced by an amount equal to the necrotic damage taken, and Kas regains a number of hit points equal to that amount. The reduction lasts until the target finishes a long rest. The target dies if its hit point maximum is reduced to 0. A Humanoid slain in this way and then buried rises the following night as a vampire spawn under Kas's control.

## Bonus Actions

***Change Shape.*** Kas transforms into a Medium cloud of mist. While in this form, Kas has a flying speed of 20 feet, can hover, and can enter a hostile creature's space and stop there. While in mist form, Kas can pass through a space without squeezing as long as air can pass through that space, but he can't pass through water. Kas has advantage on Strength, Dexterity, and Constitution saving throws, and he is immune to all nonmagical damage except the damage he takes as part of his Vampire Weaknesses trait. While in mist form, Kas can't take any actions, speak, or manipulate objects.

***Menacing Glare.*** Kas targets one creature he can see within 60 feet of himself. The target must succeed on a DC 23 Wisdom saving throw or have the [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened) condition until the start of Kas's next turn.

## Reactions

***Parrying Riposte.*** Kas adds 3 to his AC against one melee attack roll that would hit him. He then makes one Vengeful Sword attack against the attacker if it is within his reach. On a hit, the target takes an additional `dice:2d8|noform|avg|text(9)` (`2d8`) slashing damage.

## Legendary Actions

***Move.*** Kas moves up to his speed without provoking opportunity attacks.

***Sword (Costs 2 Actions).*** Kas makes one Vengeful Sword attack.

***Rise, Fallen Soldier (Costs 3 Actions).*** Kas magically summons a specter. The specter appears in an unoccupied space within 30 feet of Kas, whom it obeys. The specter takes its turn immediately after Kas. It lasts for 1 hour, until Kas dies, or until Kas dismisses it as a bonus action. Kas can't have more than two specters summoned at a time.
```
^statblock