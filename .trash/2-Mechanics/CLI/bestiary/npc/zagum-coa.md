---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/coa
- monster/cr/20
- monster/size/medium
- monster/type/fiend/devil
aliases: ["Zagum"]
---
# Zagum
*Source: Chains of Asmodeus p. 210*  

```ad-statblock
title: Zagum
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/CoA/Zagum.webp#token)
*Medium fiend (devil), Lawful Evil*

- **Armor Class** 19 (natural armor)
- **Hit Points** 255 (`30d8 + 120`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|17 (+3)|16 (+3)|18 (+4)|22 (+6)|25 (+7)|27 (+8)|

- **Proficiency Bonus** +6
- **Saving Throws** Intelligence +12, Wisdom +13, Charisma +14
- **Skills** Arcana +12, Deception +20, Insight +13, Intimidation +14, Performance +14, Persuasion +20
- **Senses** darkvision 120 ft., passive Perception 17
- **Damage Resistances** cold; bludgeoning, piercing, slashing from nonmagical attacks that aren't silvered
- **Damage Immunities** fire, poison, psychic
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** Celestial, Common, Draconic, Infernal, telepathy 120 ft.
- **Challenge** 20

## Traits

***Contractually Obligated.*** Zagum has advantage to hit creatures under an infernal contract and when he hits such creatures he delivers an additional `dice:2d8|noform|avg|text(9)` (`2d8`) damage of a type the target is most vulnerable to. A creature bound under an infernal contract also makes all saving throws against effects originating from Zagum with disadvantage.

***Devil's Sight.*** Magical darkness doesn't impede Zagum's darkvision.

***Magic Resistance.*** Zagum has advantage on saving throws against spells and other magical effects.

## Actions

***Multiattack.*** Zagum makes three attacks with Disarming Tongue or Oration.

***Disarming Tongue.*** *Melee Weapon Attack:* `dice:1d20+9|noform|text(+9)` to hit, reach 10 ft., one target. *Hit:* `dice:3d4+3|noform|avg|text(10)` (`3d4 + 3`) slashing damage. A target hit by this attack has vulnerability to psychic damage until the start of their next turn.

***Oration.*** *Ranged Spell Attack:* `dice:1d20+14|noform|text(+14)` to hit, range 60 ft., one target. *Hit:* `dice:6d8+8|noform|avg|text(35)` (`6d8 + 8`) psychic damage.

***Legal Jargon (Recharge 4-6).*** Zagum chooses a point he can see within 90 feet of him. All creatures within a 20-foot-radius sphere centered on that point must make a DC 22 Wisdom saving throw. Creatures that fail the save are confused for up to 1 minute and must roll a `dice:d10|noform|avg` (`d10`) at the start of each of their turns.

On a 1, a creature moves in a random direction then ends their turn. On a 2-6, a creature can't use actions this turn. On a 7-8, a creature must use their action to make a melee attack against a randomly determined creature within their reach that is not a Fiend. On a 9-10, a creature can move and act normally.

A confused creature may repeat the saving throw at the end of its turn, ending the effect on a success.
```
^statblock