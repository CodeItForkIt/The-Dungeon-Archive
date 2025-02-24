---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/mabjov
- monster/cr/9
- monster/size/medium
- monster/type/humanoid/half-orc
aliases: ["Nauk"]
---
# Nauk
*Source: Minsc and Boo's Journal of Villainy p. 54*  

Nauk is a half-orc warrior and senior member of the Flaming Fist in Baldur's Gate. He is also one of Faerûn's most notorious arms dealers. Nauk feeds the flames of civil strife in other nations, usually by providing assassins, mercenaries or magic. When outright war breaks out, the Flaming Fist is ready to offer their services for a hefty profit.

Nauk is one of the most well-connected members of the Flaming Fist. He has contacts and friends in almost every nation and city state in western Faerûn. Some of these come from his younger years as an adventurer, while others have been made through his arms deals.

Nauk is not above getting his hands dirty and has earned his nickname—the Bag Man. Sometimes his customers renege on a deal or are unable to pay for the services that he has provided. When this happens, Nauk enjoys making an object lesson out of the poor fool. Depending on who needs to be punished, Nauk either shows up with a small band of the Flaming Fist's hardest veterans or with a small army. No matter who he arrives with, Nauk always takes the lead.

Nauk dresses in full battle gear, even when just sitting down for a discussion with a possible client. This is because what he wears and wields are examples of what he can provide to a potential customer. This includes adamantine plate armor, multiple enchanted weapons and a dozen potions and other minor magic items. If he needs to convince a client of the effectiveness of what he has to sell, he will offer to fight the best warrior they can send at him.

## Nauk as a Contact

Nauk is the primary contact for members of the Flaming Fist at low levels. Magic items can be purchased from Nauk. He specializes in selling potions.

**Potions Available from Nauk**

| Potions | Required Level | Cost |
|---------|----------------|------|
| Potion of healing | 1 | 40 gp |
| Potion of climbing | 1 | 40 gp |
| Potion of healing—greater | 3 | 250 gp |
| Potion of fire breath | 3 | 250 gp |
| Potion of resistance | 3 | 250 gp |
| Potion of hill giant strength | 3 | 250 gp |
| Potion of water breathing | 3 | 200 gp |
| Potion of frost giant strength | 5 | 750 gp |
| Potion of heroism | 5 | 750 gp |
^potions-available-from-nauk

## Statblock

```ad-statblock
title: Nauk
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/MaBJoV/Nauk.webp#token)
*Medium humanoid (half-orc), Lawful Evil*

- **Armor Class** 18 ([plate](2-Mechanics/CLI/items/plate-armor.md))
- **Hit Points** 170 (`20d8 + 80`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|20 (+5)|12 (+1)|18 (+4)|10 (+0)|12 (+1)|14 (+2)|

- **Proficiency Bonus** +4
- **Saving Throws** Strength +9, Dexterity +5, Constitution +8
- **Skills** Intimidation +10, Persuasion +6
- **Senses** passive Perception 11
- **Languages** Common, Goblin, Orc, Undercommon
- **Challenge** 9

## Traits

***Potion Mishap.*** When Nauk uses the Imbibe Potion action more than once in an hour, roll `dice:1d4|noform|avg` (`1d4`) for what happens:

- 1. The potion works normally.  
- 2. The potion works normally. In addition, Nauk turns [invisible](2-Mechanics/CLI/rules/conditions.md#Invisible) for 1 minute or until Nauk attacks or casts a spell.  
- 3. The potion has no effect.  
- 4. Instead of the normal effect, the potion causes fire to explode out of Nauk's mouth in a 15 foot cone. Nauk and any creature in the cone take `dice:6d6|noform|avg|text(21)` (`6d6`) fire damage.  

***Relentless.*** When Nauk is reduced to 0 hit points but not killed outright, he can drop to 1 hit point instead. He can't use this feature again for 24 hours

***Special Items.*** Nauk wears [adamantine plate armor](2-Mechanics/CLI/items/adamantine-armor.md). He wields a [+1 maul](2-Mechanics/CLI/items/1-weapon.md) and a [+1 heavy crossbow](2-Mechanics/CLI/items/1-weapon.md) which is already factored into his stats. He has 2 [potions of resistance (cold)](2-Mechanics/CLI/items/potion-of-cold-resistance.md), 2 [potions of resistance (fire)](2-Mechanics/CLI/items/potion-of-fire-resistance.md), 2 [potions of resistance (lightning)](2-Mechanics/CLI/items/potion-of-lightning-resistance.md). He has 2 [potions of heroism](2-Mechanics/CLI/items/potion-of-heroism.md) and 4 [potions of superior healing](2-Mechanics/CLI/items/potion-of-superior-healing.md).

## Actions

***Multiattack.*** Nauk makes three Magic Maul attacks. Nauk may substitute one of those attacks for the Imbibe Potion action.

***Magic Maul.*** *Melee Weapon Attack:* `dice:1d20+10|noform|text(+10)` to hit, reach 5 ft., one creature. *Hit:* `dice:2d6+6|noform|avg|text(13)` (`2d6 + 6`) bludgeoning damage.

***Heavy Crossbow.*** *Ranged Weapon Attack:* `dice:1d20+6|noform|text(+6)` to hit, ranged 100/400 ft., one target. *Hit:* `dice:1d10+2|noform|avg|text(7)` (`1d10 + 2`) piercing damage.

***Imbibe Potion.*** Nauk drinks a potion from the following list:

- Potion of heroism: Nauk gains 10 temporary hit points for 1 hour. For the same duration, Nauk is under the effect of the [bless](2-Mechanics/CLI/spells/bless.md) spell (no [concentration](2-Mechanics/CLI/rules/conditions.md#Concentration) required).  
- Potion of resistance: Nauk gains resistance from one damage type for 1 hour. Nauk chooses from one of these damage types: cold, fire, lightning.  
- Potion of superior healing: Nauk regains 28 hit points.  

## Reactions

***Parry.*** Nauk adds 4 to his AC against one melee attack that would hit him. To do so, Nauk must see the attacker and be wielding a melee weapon.
```
^statblock