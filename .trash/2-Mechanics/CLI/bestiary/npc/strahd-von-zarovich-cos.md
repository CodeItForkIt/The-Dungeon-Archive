---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/cos
- monster/cr/15
- monster/size/medium
- monster/type/undead/shapechanger
aliases: ["Strahd von Zarovich"]
---
# Strahd von Zarovich
*Source: Curse of Strahd p. 240*  

With his mind sharp and his heart dark, Strahd von Zarovich is a formidable foe. Courage and lives beyond measure have been lost to him. Reread chapter 1, "Into the Mists," to understand his personality and goals.

Although Strahd can be encountered almost anywhere in his domain, the vampire is always encountered in the place indicated by the card reading in chapter 1, unless he has been forced into his tomb in the catacombs of Castle Ravenloft.

## Strahd's Tactics

Because the entire adventure revolves around Strahd, you must play him intelligently and do everything you can to make him a terrifying and cunning adversary for the player characters.

When you run an encounter with Strahd, keep the following facts in mind:

- Strahd attacks at the most advantageous moment and from the most advantageous position.  
- Strahd knows when he's in over his head. If he begins taking more damage than he can regenerate, he moves beyond the reach of melee combatants and spellcasters, or he flies away (using summoned wolves or swarms of bats or rats to guard his retreat).  
- Strahd observes the characters to see who among them are most easily swayed, then tries to charm characters who have low Wisdom scores and use them as thralls. At the very least, he can order a [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed) character to guard him against other members of the adventuring party.  

## The Vampire's Minions

Whenever Strahd appears in a location other than his tomb or the place indicated by the card reading, roll a `dice:d20|noform|avg` (`d20`) and consult the Strahd's Minions table to determine what creatures he brings with him, if any.

## Strahd's Minions

`dice: [](strahd-von-zarovich-cos.md#^creatures)`

| dice: d20 | Creatures |
|-----------|-----------|
| 1–3 | `dice:1d4+2\\|noform\\|avg` (`1d4 + 2`) [dire wolves](2-Mechanics/CLI/bestiary/beast/dire-wolf.md) |
| 4–6 | `dice:1d6+3\\|noform\\|avg` (`1d6 + 3`) [ghouls](2-Mechanics/CLI/bestiary/undead/ghoul.md) |
| 7–9 | `dice:1d4+2\\|noform\\|avg` (`1d4 + 2`) [Strahd zombies](2-Mechanics/CLI/bestiary/undead/strahd-zombie-cos.md) (in this appendix) |
| 10–12 | `dice:2d4\\|noform\\|avg` (`2d4`) [swarms of bats](2-Mechanics/CLI/bestiary/beast/swarm-of-bats.md) |
| 13–15 | `dice:1d4+1\\|noform\\|avg` (`1d4 + 1`) [vampire spawn](2-Mechanics/CLI/bestiary/undead/vampire-spawn.md) |
| 16–18 | `dice:3d6\\|noform\\|avg` (`3d6`) [wolves](2-Mechanics/CLI/bestiary/beast/wolf.md) |
| 19–20 | None |
^creatures

If the characters are in a residence, Strahd's creatures break through doors and windows to reach them, or crawl up through the earth, or swoop down the chimney. The vampire spawn (all that's left of a party of adventurers that Strahd defeated long ago) can't enter the characters' location unless invited.

## Heart of Sorrow

Strahd can afford to be bold in his tactics, for he has additional protection in the form of a giant crystal heart hidden inside Castle Ravenloft.

Any damage that Strahd takes is transferred to the Heart of Sorrow (see chapter 4, area K20). If the heart absorbs damage that reduces it to 0 hit points, it is destroyed, and Strahd takes any leftover damage. The Heart of Sorrow has 50 hit points and is restored to that number of hit points each dawn, provided it has at least 1 hit point remaining. Strahd can, as a bonus action on his turn, break his link to the Heart of Sorrow so that it no longer absorbs damage dealt to him. Strahd can reestablish his link to the Heart of Sorrow as a bonus action on his turn, but only while in Castle Ravenloft.

The effect of the protection afforded by the Heart of Sorrow can be chilling to behold, as damage to Strahd is quickly undone. For example, a critical hit might dislocate Strahd's jaw, but only for a moment; then the vampire's jaw quickly resets itself.

The ability of the Heart of Sorrow to absorb damage is suppressed if it or Strahd is fully within an [antimagic field](2-Mechanics/CLI/spells/antimagic-field.md).

## Statblock

```ad-statblock
title: Strahd von Zarovich
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/CoS/Strahd%20von%20Zarovich.webp#token)
*Medium undead (shapechanger), Lawful Evil*

- **Armor Class** 16 (natural armor)
- **Hit Points** 144 (`17d8 + 68`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|18 (+4)|18 (+4)|18 (+4)|20 (+5)|15 (+2)|18 (+4)|

- **Proficiency Bonus** +5
- **Saving Throws** Dexterity +9, Wisdom +7, Charisma +9
- **Skills** Arcana +15, Perception +12, Religion +10, Stealth +14
- **Senses** darkvision 120 ft., passive Perception 22
- **Damage Resistances** necrotic; bludgeoning, piercing, slashing from nonmagical attacks
- **Languages** Abyssal, Common, Draconic, Elvish, Giant, Infernal
- **Challenge** 15

## Traits

***Shapechanger.*** If Strahd isn't in running water or sunlight, he can use his action to polymorph into a Tiny bat, a Medium wolf, or a Medium cloud of mist, or back into his true form.

While in bat or wolf form, Strahd can't speak. In bat form, his walking speed is 5 feet, and he has a flying speed of 30 feet. In wolf form, his walking speed is 40 feet. His statistics, other than his size and speed, are unchanged. Anything he is wearing transforms with him, but nothing he is carrying does. He reverts to his true form if he dies.

While in mist form, Strahd can't take any actions, speak, or manipulate objects. He is weightless, has a flying speed of 20 feet, can hover, and can enter a hostile creature's space and stop there. In addition, if air can pass through a space, the mist can do so without squeezing, and he can't pass through water. He has advantage on Strength, Dexterity, and Constitution saving throws, and he is immune to all nonmagical damage, except the damage he takes from sunlight.

***Legendary Resistance (3/Day).*** If Strahd fails a saving throw, he can choose to succeed instead.

***Misty Escape.*** When Strahd drops to 0 hit points outside his coffin, he transforms into a cloud of mist (as in the Shapechanger trait) instead of falling [unconscious](2-Mechanics/CLI/rules/conditions.md#Unconscious), provided that he isn't in running water or sunlight. If he can't transform, he is destroyed.

While he has 0 hit points in mist form, he can't revert to his vampire form, and he must reach his coffin within 2 hours or be destroyed. Once in his coffin, he reverts to his vampire form. He is then [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed) until he regains at least 1 hit point. After 1 hour in his coffin with 0 hit points, he regains 1 hit point.

***Regeneration.*** Strahd regains 20 hit points at the start of his turn if he has at least 1 hit point and isn't in running water or sunlight. If he takes radiant damage or damage from holy water, this trait doesn't function at the start of his next turn.

***Spider Climb.*** Strahd can climb difficult surfaces, including upside down on ceilings, without having to make an ability check.

***Vampire Weaknesses.*** Strahd has the following flaws:

*Forbiddance.* He can't enter a residence without an invitation from one of the occupants.

*Harmed by Running Water.* He takes 20 acid damage if he ends his turn in running water.

*Stake to the Heart.* If a piercing weapon made of wood is driven into his heart while he is [incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated) in his coffin, he is [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed) until the stake is removed.

*Sunlight Hypersensitivity.* While in sunlight, Strahd takes 20 radiant damage at the start of his turn, and he has disadvantage on attack rolls and ability checks.

***Spellcasting.*** Strahd is a 9th-level spellcaster. His spellcasting ability is Intelligence (spell save DC 18, `dice:1d20+10|noform|text(+10)` to hit with spell attacks). He has the following wizard spells prepared:

**Cantrips (at will)**: [mage hand](2-Mechanics/CLI/spells/mage-hand.md), [prestidigitation](2-Mechanics/CLI/spells/prestidigitation.md), [ray of frost](2-Mechanics/CLI/spells/ray-of-frost.md)

**1st level (4 slots)**: [comprehend languages](2-Mechanics/CLI/spells/comprehend-languages.md), [fog cloud](2-Mechanics/CLI/spells/fog-cloud.md), [sleep](2-Mechanics/CLI/spells/sleep.md)

**2nd level (3 slots)**: [detect thoughts](2-Mechanics/CLI/spells/detect-thoughts.md), [gust of wind](2-Mechanics/CLI/spells/gust-of-wind.md), [mirror image](2-Mechanics/CLI/spells/mirror-image.md)

**3rd level (3 slots)**: [animate dead](2-Mechanics/CLI/spells/animate-dead.md), [fireball](2-Mechanics/CLI/spells/fireball.md), [nondetection](2-Mechanics/CLI/spells/nondetection.md)

**4th level (3 slots)**: [blight](2-Mechanics/CLI/spells/blight.md), [greater invisibility](2-Mechanics/CLI/spells/greater-invisibility.md), [polymorph](2-Mechanics/CLI/spells/polymorph.md)

**5th level (1 slots)**: [animate objects](2-Mechanics/CLI/spells/animate-objects.md), [scrying](2-Mechanics/CLI/spells/scrying.md)

## Actions

***Multiattack (Vampire Form Only).*** Strahd makes two attacks, only one of which can be a bite attack.

***Unarmed Strike (Vampire or Wolf Form Only).*** *Melee Weapon Attack:* `dice:1d20+9|noform|text(+9)` to hit, reach 5 ft., one target. *Hit:* `dice:1d8+4|noform|avg|text(8)` (`1d8 + 4`) slashing damage, plus `dice:4d6|noform|avg|text(14)` (`4d6`) necrotic damage. If the target is a creature, Strahd can grapple it (escape DC 18) instead of dealing the slashing damage.

***Bite.*** *Melee Weapon Attack:* `dice:1d20+9|noform|text(+9)` to hit, reach 5 ft., one willing creature, or a creature that is [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) by Strahd, [incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated), or [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained). *Hit:* `dice:1d6+4|noform|avg|text(7)` (`1d6 + 4`) piercing damage plus `dice:3d6|noform|avg|text(10)` (`3d6`) necrotic damage. The target's hit point maximum is reduced by an amount equal to the necrotic damage taken, and Strahd regains hit points equal to that amount. The reduction lasts until the target finishes a long rest. The target dies if its hit point maximum is reduced to 0. A humanoid slain in this way and then buried in the ground rises the following night as a [vampire spawn](2-Mechanics/CLI/bestiary/undead/vampire-spawn.md) under Strahd's control.

***Charm.*** Strahd targets one humanoid he can see within 30 feet of him. If the target can see Strahd, the target must succeed on a DC 17 Wisdom saving throw against this magic or be [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed). The [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed) target regards Strahd as a trusted friend to be heeded and protected. The target isn't under Strahd's control, but it takes Strahd's requests and actions in the most favorable way and lets Strahd bite it.

Each time Strahd or his companions do anything harmful to the target, it can repeat the saving throw, ending the effect on itself on a success. Otherwise, the effect lasts 24 hours or until Strahd is destroyed, is on a different plane of existence than the target, or takes a bonus action to end the effect.

***Children of the Night (1/Day).*** Strahd magically calls `dice:2d4|noform|avg` (`2d4`) [swarms of bats](2-Mechanics/CLI/bestiary/beast/swarm-of-bats.md) or [swarms of rats](2-Mechanics/CLI/bestiary/beast/swarm-of-rats.md), provided that the sun isn't up. While outdoors, Strahd can call `dice:3d6|noform|avg` (`3d6`) [wolves](2-Mechanics/CLI/bestiary/beast/wolf.md) instead. The called creatures arrive in `dice:1d4|noform|avg` (`1d4`) rounds, acting as allies of Strahd and obeying his spoken commands. The beasts remain for 1 hour, until Strahd dies, or until he dismisses them as a bonus action.

## Legendary Actions

***Move.*** Strahd moves up to his speed without provoking opportunity attacks.

***Unarmed Strike.*** Strahd makes one unarmed strike.

***Bite (Costs 2 Actions).*** Strahd makes one bite attack.

![Strahd von Zarovich](2-Mechanics/CLI/bestiary/legendary-group/strahd-von-zarovich-cos.md)
```
^statblock