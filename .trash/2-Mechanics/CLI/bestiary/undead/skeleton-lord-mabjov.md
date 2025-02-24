---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/mabjov
- monster/cr/9
- monster/size/medium
- monster/type/undead
aliases: ["Skeleton Lord"]
---
# Skeleton Lord
*Source: Minsc and Boo's Journal of Villainy p. 148*  

> [!quote] A quote from MINSC & BOO!  
> 
> Walking skeletons are a sure sign that some EVIL wizard is getting up to no good. Minsc is quite certain that skeletons should be sleeping in their graves-not ambulating around as if in search of midnight snacks! And now you say they have crowns and platemail and magic swords?! Are there no depths to which evil will not sink? And what does evil find down there, anyway? Boo would like to know!

Held together by necromantic energy, skeleton warriors are distinguished by their high intelligence and considerable battle prowess. All skeleton warriors retain the ability to understand languages they knew in life and most are capable of speech, standing in stark contrast to the mindless and far more common skeletons faced by most adventurers. Only the most skilled necromancers are able to raise a skeleton warrior, which are prized for use as bodyguards and sentinels. Necromancers must use the remains of powerful warriors in order to create a skeleton warrior. Even if a mage succeeds in their task, however, the creatures are difficult to control unless the mage has the golden circlet that contains the undead warrior's soul. Like other skeletons, skeleton warriors are resistant to most forms of damage but vulnerable to bludgeoning; blunt trauma is required to knock dry bones out of place. In addition, skeleton warriors are highly resistant to magical effects.

## Battle Beyond Death

Skeleton warriors are created from the remains of great fighters and retain their skills in undeath. Many are former adventurers or prominent lords who died in battle. Skeleton warriors wield fearsome two-handed greatswords and wear heavy, often ornate, armor that has tarnished with age.

## Undead Commanders

Skeleton warriors are typically solitary guardians and do not usually associate with other undead unless under the active control of a necromancer. In such cases, a skeleton warrior may lead a detachment of more dim-witted skeletons, directing them to use tactics normally out of reach.

## Skeleton Lords

Some skeleton warriors are created using the remains and souls of powerful lords such as kings or other nobility. These skeleton warriors are more powerful than others of their kind and radiate an aura of cold and fear that can chill the heart of even the bravest champion.

## Soul Circlets

When a skeleton warrior is created, its soul is trapped within a magical gold circlet, which is used to control the creature. This artifact is what binds a skeleton warrior to the Prime Material plane. Skeleton warriors are driven to recover their circlets and most that succeed choose to destroy the items, ending their ghoulish existence.

> [!note] Controlling Skeleton Warriors
> 
> Someone wearing a skeleton warrior or skeleton lord's golden circlet can use an action to take control of the undead creature if it is within 100 ft. There is no saving throw allowed against this control. This control is complete and allows the wearer of the golden circlet to issue commands through a telepathic link. The skeleton warrior or lord will do its best to obey simple commands such as "attack that creature" or "move over there". If the skeleton warrior or lord does not receive any orders it will defend itself as best as it is able.
^controlling-skeleton-warriors

## Statblock

```ad-statblock
title: Skeleton Lord
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/MaBJoV/Skeleton%20Lord.webp#token)
*Medium undead, Lawful Evil*

- **Armor Class** 18 ([plate](2-Mechanics/CLI/items/plate-armor.md))
- **Hit Points** 136 (`16d8 + 64`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|20 (+5)|14 (+2)|18 (+4)|18 (+4)|12 (+1)|12 (+1)|

- **Proficiency Bonus** +4
- **Saving Throws** ⏤
- **Skills** ⏤
- **Senses** darkvision 120 ft., passive Perception 11
- **Damage Vulnerabilities** bludgeoning from magical attacks
- **Damage Resistances** cold, necrotic
- **Damage Immunities** poison; bludgeoning, piercing, slashing from nonmagical attacks
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** all the languages it knew in life
- **Challenge** 9

## Traits

***Fear Aura.*** Any creature hostile to the skeleton lord that starts its turn within 20 feet of the skeleton lord must make a DC 17 Wisdom saving throw, unless the skeleton lord is [incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated). On a failed save, the creature has the [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened) condition until the start of its next turn. If a creature's saving throw is successful, then the creature is immune to the skeleton lord's Fear Aura for the next 24 hours.

***Magic Resistance.*** The skeleton lord has advantage on saving throws against spells and other magical effects.

***Magic Weapons.*** The skeleton lord's weapon attacks are magical and gain a +1 bonus to attack and damage rolls (included in the attack).

## Actions

***Multiattack.*** The skeleton lord makes three Greatsword attacks.

***Greatsword.*** *Melee Weapon Attack:* `dice:1d20+10|noform|text(+10)` to hit, reach 5 ft., one target. *Hit:* `dice:2d6+6|noform|avg|text(13)` (`2d6 + 6`) slashing damage.
```
^statblock