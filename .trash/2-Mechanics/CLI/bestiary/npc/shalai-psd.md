---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/psd
- monster/cr/21
- monster/size/large
- monster/type/celestial
aliases: ["Shalai"]
---
# Shalai
*Source: Plane Shift: Dominaria p. 9*  

The most visible and recognized symbols of the Church of Serra are her angels—both those that were personally created by Serra and those that appeared spontaneously in the Cathedral at Sursi. Some angels live contemplative lives within the cathedrals, but most are active defenders of the faith, protecting Serra's people across the world. Powerful angels often take responsibility for large regions of the world. Lyra, for example, stands as the protector of Benalia, and Shalai plays a similar role in Llanowar. Serra's angels are believed to hear prayers addressed to Serra, and they have an uncanny tendency to arrive exactly when they are needed.

Any of the angels in the "Monster Manual" can serve as [Serra angels](2-Mechanics/CLI/bestiary/celestial/serra-angel-psd.md). The [deva](2-Mechanics/CLI/bestiary/celestial/deva.md) represents the most common angels, while the [planetar](2-Mechanics/CLI/bestiary/celestial/planetar.md) and [solar](2-Mechanics/CLI/bestiary/celestial/solar.md) are appropriate for powerful angels such as [Lyra](2-Mechanics/CLI/bestiary/npc/lyra-psd.md) and [Shalai](2-Mechanics/CLI/bestiary/npc/shalai-psd.md).

```ad-statblock
title: Shalai
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/PSD/Shalai.webp#token)
*Large celestial, Lawful Good*

- **Armor Class** 21 (natural armor)
- **Hit Points** 243 (`18d10 + 144`)
- **Speed** 50 ft., fly 150 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|26 (+8)|22 (+6)|26 (+8)|25 (+7)|25 (+7)|30 (+10)|

- **Proficiency Bonus** +7
- **Saving Throws** Intelligence +14, Wisdom +14, Charisma +17
- **Skills** Perception +14
- **Senses** truesight 120 ft., passive Perception 24
- **Damage Resistances** radiant; bludgeoning, piercing, slashing from nonmagical attacks
- **Damage Immunities** necrotic, poison
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** all, telepathy 120 ft.
- **Challenge** 21

## Traits

***Angelic Weapons.*** Shalai's weapon attacks are magical. When Shalai hits with any weapon, the weapon deals an extra `dice:6d8|noform|avg` (`6d8`) radiant damage (included in the attack).

***Divine Awareness.*** Shalai knows if it hears a lie.

***Magic Resistance.*** Shalai has advantage on saving throws against spells and other magical effects.

***Innate Spellcasting.*** Shalai's spellcasting ability is Charisma (spell save DC 25). It can innately cast the following spells, requiring no material components:

**At will**: [detect evil and good](2-Mechanics/CLI/spells/detect-evil-and-good.md), [invisibility](2-Mechanics/CLI/spells/invisibility.md) (self only)

**1/day each**: [commune](2-Mechanics/CLI/spells/commune.md), [control weather](2-Mechanics/CLI/spells/control-weather.md)

**3/day each**: [blade barrier](2-Mechanics/CLI/spells/blade-barrier.md), [dispel evil and good](2-Mechanics/CLI/spells/dispel-evil-and-good.md), [resurrection](2-Mechanics/CLI/spells/resurrection.md)

## Actions

***Multiattack.*** Shalai makes two greatsword attacks.

***Greatsword.*** *Melee Weapon Attack:* `dice:1d20+15|noform|text(+15)` to hit, reach 5 ft., one target. *Hit:* `dice:4d6+8|noform|avg|text(22)` (`4d6 + 8`) slashing damage plus `dice:6d8|noform|avg|text(27)` (`6d8`) radiant damage.

***Slaying Longbow.*** *Ranged Weapon Attack:* `dice:1d20+13|noform|text(+13)` to hit, range 150/600 ft., one target. *Hit:* `dice:2d8+6|noform|avg|text(15)` (`2d8 + 6`) piercing damage plus `dice:6d8|noform|avg|text(27)` (`6d8`) radiant damage. If the target is a creature that has 100 hit points or fewer, it must succeed on a DC 15 Constitution saving throw or die.

***Flying Sword.*** Shalai releases its greatsword to hover magically in an unoccupied space within 5 feet of it. If Shalai can see the sword, Shalai can mentally command it as a bonus action to fly up to 50 feet and either make one attack against a target or return to Shalai's hands. If the hovering sword is targeted by any effect, Shalai is considered to be holding it. The hovering sword falls if Shalai dies.

***Healing Touch (4/Day).*** Shalai touches another creature. The target magically regains `dice:8d8+4|noform|avg|text(40)` (`8d8 + 4`) hit points and is freed from any curse, disease, poison, blindness, or deafness.

## Legendary Actions

***Teleport.*** Shalai magically teleports, along with any equipment it is wearing or carrying, up to 120 feet to an unoccupied space it can see.

***Searing Burst (Costs 2 Actions).*** Shalai emits magical, divine energy. Each creature of its choice in a 10-foot radius must make a DC 23 Dexterity saving throw, taking `dice:4d6|noform|avg|text(14)` (`4d6`) fire damage plus `dice:4d6|noform|avg|text(14)` (`4d6`) radiant damage on a failed save, or half as much damage on a successful one.

***Blinding Gaze (Costs 3 Actions).*** Shalai targets one creature it can see within 30 feet of it. If the target can see it, the target must succeed on a DC 15 Constitution saving throw or be [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded) until magic such as the [lesser restoration](2-Mechanics/CLI/spells/lesser-restoration.md) spell removes the blindness.
```
^statblock