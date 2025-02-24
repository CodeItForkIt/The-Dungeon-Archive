---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/mabjov
- monster/cr/13
- monster/size/medium
- monster/type/humanoid/half-elf
aliases: ["Jaheira"]
---
# Jaheira
*Source: Minsc and Boo's Journal of Villainy p. 60*  

Jaheira is a half-elf druid and an experienced leader within the organization known as the Harpers. She originally traveled to the Sword Coast with Khalid, her husband and fellow Harper, to investigate the Iron Crisis of 1368 DR on behalf of the secretive organization. Khalid was killed during the mission and Jaheira has never remarried. Although harsh and somewhat abrasive, Jaheira is fiercely loyal to the Harpers.

Born to a noble Tethyrian family loyal to King Alemander, Jaheira lost her parents at a young age at the hands of a mob during the country's violent civil war. She would have met the same fate, had a servant not saved her by smuggling her out of the castle. Chance led the pair to find a group of druids in the nearby forest, which took Jaheira in and raised her.

Jaheira believes that true balance and protection of nature can only come through action. When given no other choice, however, Jaheira strongly prefers to facilitate good over evil.

Jaheira has been a member of the Harpers for more than a century, though her elven blood gives her an appearance that is still relatively youthful. However, her age means that she is no longer an active Harper agent. Instead she seeks out those that she feels might help with the Harper cause and tries to recruit them. Jaheira is always on the lookout for an excuse to go back out on to the field and use her magic to destroy those who would harm the natural world or oppose the goals of the Harpers.

## Jaheira as a Contact

Jaheira becomes available as a contact for the Harpers at 9th level. Jaheira can put you in contact with a powerful Harper ally. These allies can come to your aid in a time of need. The cost is a magic item that Jaheira enchants. When you require assistance, you may read the magical rune and your item will vanish to be replaced by a powerful ally who will fight by your side for one hour.

**Allies via Jaheira**

| Ally | Required Level | Magic Item Sacrifice |
|------|----------------|----------------------|
| Mage, unicorn or Vellin (see entry in on next page) | 9 | Uncommon Boots, Cloak, Ring, Rod, Staff, Wand or Weapon |
| Assassin (named Arylin Moonblade), young silver dragon or deva | 12 | Uncommon Boots, Cloak, Ring, Rod, Staff, Wand or Weapon |
| Archmage (named either alustriel silverhand, Elminster Aumar or laeral silverhand), adult brass dragon or Jaheira | 14 | Rare Boots, Cloak, Ring, Rod, Staff, Wand or Weapon |
| Planetar | 16 | Rare Boots, Cloak, Ring, Rod, Staff, Wand or Weapon |
^allies-via-jaheira

## Statblock

```ad-statblock
title: Jaheira
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/MaBJoV/Jaheira.webp#token)
*Medium humanoid (half-elf), Neutral*

- **Armor Class** 11 (16 with [barkskin](2-Mechanics/CLI/spells/barkskin.md))
- **Hit Points** 150 (`20d8 + 60`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|14 (+2)|12 (+1)|16 (+3)|12 (+1)|20 (+5)|15 (+2)|

- **Proficiency Bonus** +5
- **Saving Throws** Constitution +8, Wisdom +10
- **Skills** Medicine +10, Nature +6, Perception +10
- **Senses** darkvision 60 ft., passive Perception 20
- **Languages** Common, Druidic, Elvish, Sylvan
- **Challenge** 13

## Traits

***Fey Ancestry.*** Jaheira has advantage on saving throws against being [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), and magic can't put Jaheira to sleep.

***Spellcasting.*** Jaheira casts ones of the following spells, using Wisdom as the spellcasting ability (spell save DC 18):

**At will**: [barkskin](2-Mechanics/CLI/spells/barkskin.md), [druidcraft](2-Mechanics/CLI/spells/druidcraft.md), [poison spray](2-Mechanics/CLI/spells/poison-spray.md), [produce flame](2-Mechanics/CLI/spells/produce-flame.md), [shillelagh](2-Mechanics/CLI/spells/shillelagh.md)

**1/day each**: [heal](2-Mechanics/CLI/spells/heal.md), [heroes' feast](2-Mechanics/CLI/spells/heroes-feast.md), [stoneskin](2-Mechanics/CLI/spells/stoneskin.md)

**2/day each**: [animal messenger](2-Mechanics/CLI/spells/animal-messenger.md), [commune with nature](2-Mechanics/CLI/spells/commune-with-nature.md) (as an action), [entangle](2-Mechanics/CLI/spells/entangle.md), [speak with animals](2-Mechanics/CLI/spells/speak-with-animals.md)

## Actions

***Multiattack.*** Jaheira makes three Quarterstaff attacks.

***Quarterstaff.*** *Melee Weapon Attack:* `dice:1d20+10|noform|text(+10)` to hit, reach 5 ft., one target. *Hit:* `dice:1d8+5|noform|avg|text(5)` (`1d8 + 5`) bludgeoning damage plus `dice:6d6|noform|avg|text(21)` (`6d6`) thunder damage.

***Cleansing Plague (Recharge 6).*** Jaheira targets a creature she can see within 60 feet and causes a swarm of flying insects to cover the creature. The creature must make a DC 18 Constitution saving throw, taking `dice:8d10|noform|avg|text(44)` (`8d10`) piercing damage on a failed save, or half as much damage on a successful one. If the target fails their saving throw they are also [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded) until the end of their next turn.

## Bonus Actions

***Mighty Summons (1/Day).*** Jaheira summons three CR 2 Beasts or six CR 1 Beasts. These summoned creatures have maximum hit points and the damage they inflict is considered magical for the purpose of overcoming immunity and resistance to nonmagical attacks and damage.
```
^statblock