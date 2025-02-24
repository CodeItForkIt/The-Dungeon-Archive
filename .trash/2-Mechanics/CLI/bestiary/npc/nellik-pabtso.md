---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/pabtso
- monster/cr/9
- monster/size/large
- monster/type/fiend/yugoloth
aliases: ["Nellik"]
---
# Nellik
*Source: Phandelver and Below: The Shattered Obelisk p. 193*  

```ad-statblock
title: Nellik
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/PaBTSO/Nellik.webp#token)
*Large fiend (yugoloth), Neutral Evil*

- **Armor Class** 18 (natural armor)
- **Hit Points** 123 (`13d10 + 52`)
- **Speed** 40 ft., fly 60 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|20 (+5)|11 (+0)|19 (+4)|12 (+1)|10 (+0)|15 (+2)|

- **Proficiency Bonus** +4
- **Saving Throws** ⏤
- **Skills** Intimidation +6, Perception +4, Stealth +4
- **Senses** blindsight 60 ft., darkvision 60 ft., passive Perception 14
- **Damage Resistances** cold; fire; lightning; bludgeoning, piercing, slashing from nonmagical attacks
- **Damage Immunities** acid, poison
- **Condition Immunities** [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** Abyssal, Infernal, telepathy 60 ft.
- **Challenge** 9

## Traits

***Magic Resistance.*** Nellik has advantage on saving throws against spells and other magical effects.

***Magic Weapons.*** Nellik's weapon attacks are magical.

***Innate Spellcasting.*** Nellik's innate spellcasting ability is Charisma. Nellik can innately cast the following spells, requiring no material components:

**At will**: [darkness](2-Mechanics/CLI/spells/darkness.md), [detect magic](2-Mechanics/CLI/spells/detect-magic.md), [dispel magic](2-Mechanics/CLI/spells/dispel-magic.md), [invisibility](2-Mechanics/CLI/spells/invisibility.md) (self only), [mirror image](2-Mechanics/CLI/spells/mirror-image.md)

## Actions

***Multiattack.*** Nellik makes two melee attacks, or it makes one melee attack and teleports before or after the attack.

***Claw.*** *Melee Weapon Attack:* `dice:1d20+9|noform|text(+9)` to hit, reach 5 ft., one target. *Hit:* `dice:2d6+5|noform|avg|text(12)` (`2d6 + 5`) slashing damage. If the target is a creature, it must succeed on a DC 16 Constitution saving throw or take `dice:2d4|noform|avg|text(5)` (`2d4`) slashing damage at the start of each of its turns due to a fiendish wound. Each time Nellik hits the wounded target with this attack, the damage dealt by the wound increases by `dice:2d4|noform|avg|text(5)` (`2d4`). Any creature can take an action to stanch the wound with a successful DC 13 Wisdom ([Medicine](2-Mechanics/CLI/rules/skills.md#Medicine)) check. The wound also closes if the target receives magical healing.

***Greataxe.*** *Melee Weapon Attack:* `dice:1d20+10|noform|text(+10)` to hit, reach 5 ft., one target. *Hit:* `dice:2d12+6|noform|avg|text(19)` (`2d12 + 6`) slashing damage; if the target is an Aberration, it takes an additional `dice:1d12|noform|avg|text(6)` (`1d12`) slashing damage, and if it is grappling a creature, it must succeed on a DC 15 Strength saving throw or its grapple ends.

***Teleport.*** Nellik magically teleports, along with any equipment it is wearing or carrying, up to 60 feet to an unoccupied space it can see.
```
^statblock