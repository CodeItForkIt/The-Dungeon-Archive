---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/coa
- monster/cr/14
- monster/size/large
- monster/type/fiend
aliases: ["Maelephant Nomad"]
---
# Maelephant Nomad
*Source: Chains of Asmodeus p. 245*  

Created with the sole purpose of protection, maelephants are the most loyal of the devils. They eschew personal possessions, dreams, and goals, and find happiness in the completion of their duty. While other devils may view them as simple and unintelligent, many recognize the importance and utility of maelephants. Infernal and common are often spoken languages, but maelephants also maintain their own unique language, which they use exclusively in communication with others of their kind.

## Elephantine Warriors

As their name would suggest, maelephants share many physical features with elephants. They stand on two legs, but have an elephant-like head and legs. Their trunk usually ends in a sharp spike, and their hands and feet are both clawed. When threatened, maelephants emit a cloud of toxins that cause brain damage and memory loss.

## Driven by Duty

Despite them being lower-ranked devils, their position as trustworthy guardians makes other lower devils respect maelephants. When not under active duty or protecting something, a maelephant might aimlessly wander the layers searching for a new charge. Some of these nomads wander many years before finally ending their search.

## Statblock

```ad-statblock
title: Maelephant Nomad
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/CoA/Maelephant%20Nomad.webp#token)
*Large fiend, Lawful Evil*

- **Armor Class** 16 ([chain mail](2-Mechanics/CLI/items/chain-mail.md))
- **Hit Points** 190 (`20d10 + 80`)
- **Speed** 40 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|22 (+6)|11 (+0)|18 (+4)|14 (+2)|17 (+3)|15 (+2)|

- **Proficiency Bonus** +5
- **Saving Throws** Strength +11, Constitution +9
- **Skills** Athletics +16, Insight +8, Intimidation +7, Perception +8
- **Senses** blindsight 30 ft., darkvision 120 ft., passive Perception 18
- **Damage Resistances** acid; fire; lightning; bludgeoning, piercing, slashing from nonmagical attacks
- **Condition Immunities** [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** Common, Infernal, Maelephant
- **Challenge** 14

## Traits

***Magic Resistance.*** The maelephant has advantage on saving throws against spells and other magical effects.

***Regenerative.*** At the start of its turn, if the maelephant has less than half its hit points, it regenerates 20 hit points. This trait doesn't function if the maelephant starts its turn with less than 1 hit point.

## Actions

***Multiattack.*** The maelephant makes two attacks using its Claw, Trunk, or a combination of the two.

***Claw.*** *Melee Weapon Attack:* `dice:1d20+11|noform|text(+11)` to hit, reach 5 ft., one target. *Hit:* `dice:2d10+6|noform|avg|text(17)` (`2d10 + 6`) slashing damage.

***Trunk.*** *Melee Weapon Attack:* `dice:1d20+11|noform|text(+11)` to hit, reach 10 ft., one target. *Hit:* `dice:3d6+6|noform|avg|text(16)` (`3d6 + 6`) piercing damage. If the target is a Medium or smaller creature, it has the [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) condition (escape DC 18). Until this grapple ends, the target has the [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) condition. While it is grappling a creature, the maelephant can't use its Trunk attack against other creatures.

***Noxious Breath (Recharge 5-6).*** The maelephant releases a cloud of noxious gas. All creatures in a 30-foot cone in front of the maelephant must make a DC 16 Constitution saving throw. Targets take `dice:12d6|noform|avg|text(42)` (`12d6`) acid damage on a failed save, or half as much damage on a successful one. In addition, on a failed save, the creature's Intelligence and Charisma scores become 1. The creature can't cast spells, activate magic items, understand language, or communicate in any intelligible way. The creature can, however, identify its friends, follow them, and even protect them. A feebled creature can repeat the save every minute, ending the effect on a success.

## Bonus Actions

***Reckless Charge.*** The maelephant moves up to 40 feet towards a creature it can see and if it moves at least 20 feet in a straight line, it may make a Claw attack. On a hit, the target takes an additional `dice:4d6|noform|avg|text(14)` (`4d6`) force damage and has the [prone](2-Mechanics/CLI/rules/conditions.md#Prone) condition.

## Reactions

***Defensive Stance.*** As a reaction to taking damage, the maelephant enters a defensive stance until the end of its next turn. While in a defensive stance, the maelephant moves at half speed and can't take bonus actions, but its AC increases by 5.
```
^statblock