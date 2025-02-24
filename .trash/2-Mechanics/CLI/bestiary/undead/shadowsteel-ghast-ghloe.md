---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/ghloe
- monster/cr/7
- monster/size/medium
- monster/type/undead
aliases: ["Shadowsteel Ghast"]
---
# Shadowsteel Ghast
*Source: Grim Hollow: Lairs of Etharis p. 84*  

> [!quote]  
> 
> Shards of dark metal pierce the skin of the foul creature. The metal pushes out from within the abomination rather than the other way.

## Salvage

Taking 1 hour to extract the shards of Shadowsteel from a Shadowsteel ghoul, someone can collect an amount worth 250 gp. A Shadowsteel ghast yields a quantity worth 500 gp.

## Lore

- **DC 15 Intelligence ([Religion](2-Mechanics/CLI/rules/skills.md#Religion)).** Those who use Shadowsteel to power curses can become Shadowsteel ghouls upon death. These undead creatures seek out more of the metal. As the creature ages, it can regain a semblance of the arcane power it had in life, empowering similar creatures and cursing nearby foes.  

## Statblock

```ad-statblock
title: Shadowsteel Ghast
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/GHLoE/Shadowsteel%20Ghast.webp#token)
*Medium undead, Chaotic Evil*

- **Armor Class** 16 (natural armor)
- **Hit Points** 118 (`17d8 + 42`)
- **Speed** 40 ft., climb 40 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|16 (+3)|14 (+2)|17 (+3)|14 (+2)|13 (+1)| 8 (-1)|

- **Proficiency Bonus** +3
- **Saving Throws** Intelligence +5, Wisdom +4
- **Skills** Arcana +5, Perception +4
- **Senses** darkvision 120 ft., passive Perception 14
- **Damage Resistances** necrotic
- **Damage Immunities** poison
- **Condition Immunities** [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** two languages known in life
- **Challenge** 7

## Traits

***Magic Resistance.*** The Shadowsteel ghast has advantage on saving throws against spells and other magical effects.

***Shadowsteel Coat.*** The Shadowsteel ghast is coated in metal armor made of Shadowsteel.

***Shadowsteel Miasma.*** Creatures of the Shadowsteel ghast's choice that start their turn within 30 feet of the ghast must roll a `dice:d4|noform|avg` (`d4`) and subtract the number rolled from any attack roll or saving throw they make until the start of their next turn. Only one miasma can affect a given creature at a time. A creature that rolls a natural 20 on any attack roll or saving throw while in a Shadowsteel miasma is immune to the miasma of any Shadowsteel ghast for 1 hour.

***Turning Defiance.*** The Shadowsteel ghast and any Shadowsteel ghouls within 30 feet of it have advantage on saving throws against effects that turn undead.

***Innate Spellcasting.*** The Shadowsteel ghast's innate spellcasting ability is Intelligence (spell save DC 13, `dice:1d20+5|noform|text(+5)` to hit with spell attacks). It can innately cast the following spells, requiring no components:

**At will**: [chill touch](2-Mechanics/CLI/spells/chill-touch.md), [shocking grasp](2-Mechanics/CLI/spells/shocking-grasp.md) (both 17th level)

**2/day**: [bestow curse](2-Mechanics/CLI/spells/bestow-curse.md)

**3/day each**: [counterspell](2-Mechanics/CLI/spells/counterspell.md), [misty step](2-Mechanics/CLI/spells/misty-step.md), [shield](2-Mechanics/CLI/spells/shield.md)

## Actions

***Multiattack.*** The Shadowsteel ghast makes two claw attacks or casts one at-will spell and makes one claw attack.

***Claw.*** *Melee Weapon Attack:* `dice:1d20+6|noform|text(+6)` to hit, reach 5 ft., one target. *Hit:* `dice:2d8+3|noform|avg|text(12)` (`2d8 + 3`) slashing damage and `dice:2d6|noform|avg|text(7)` (`2d6`) necrotic damage. A cursed target must make an escalation check. If a target drops to 0 hit points due to this damage and isn't already cursed, they are randomly afflicted with one from among any of the curses in the Grim Hollow Campaign Guide (GM's choice).
```
^statblock