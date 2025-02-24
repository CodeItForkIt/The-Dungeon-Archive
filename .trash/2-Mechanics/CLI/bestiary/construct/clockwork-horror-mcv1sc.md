---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/mcv1sc
- monster/cr/2
- monster/size/small
- monster/type/construct
aliases: ["Clockwork Horror"]
---
# Clockwork Horror
*Source: Monstrous Compendium Volume 1: Spelljammer Creatures p. 4*  

Clockwork horrors are ruthless insectile automatons—eldritch machines encased in adamantine or some other precious metal. They roam Wildspace in commandeered spelljamming ships, gathering the precious metals and crystals they need to build more of their kind. Clockwork horrors have no goal beyond replication and will stop at nothing to create new clockwork horrors. The time it takes for a clockwork horror to build another of its kind, assuming it has the requisite materials, is approximately ten days.

The body of a clockwork horror is about two feet in diameter, but the legs give it an overall diameter of four feet. Embedded in the front of its head is a crystal that enables the clockwork horror to see.

Clockwork horrors communicate with each other by means of clicks, whirs, and similar mechanical sounds that imitate the Thri-kreen language perfectly, leading some to speculate the first clockwork horror was the brainchild of a thri-kreen artificer. A horror can also emit light from its crystal eye, issuing dot-and-dash messages to other creatures that can see the light. Creatures besides clockwork horrors can learn this blinking light code, which is called Ziklight.

When another creature gets in its way, a clockwork horror attacks that creature with its razor-sharp mandibles and two tiny rotating saws mounted at the tips of its forelimbs. A horror can also discharge bolts of lightning from a short lightning rod embedded in its body.

When a clockwork horror dies, the magic that created it consumes it over a period of 1 minute. Its metallic body and crystal eye degrade rapidly until nothing is left but a small heap of glittering dust.

```ad-statblock
title: Clockwork Horror
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/MCV1SC/Clockwork%20Horror.webp#token)
*Small construct, typically  Lawful Evil*

- **Armor Class** 18 (natural armor)
- **Hit Points** 60 (`8d6 + 32`)
- **Speed** 30 ft., climb 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|14 (+2)|14 (+2)|18 (+4)|13 (+1)|14 (+2)|10 (+0)|

- **Proficiency Bonus** +2
- **Saving Throws** Strength +4, Wisdom +4
- **Skills** Perception +6
- **Senses** darkvision 120 ft., passive Perception 16
- **Damage Immunities** lightning, poison
- **Condition Immunities** [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded), [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [deafened](2-Mechanics/CLI/rules/conditions.md#Deafened), [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed), [petrified](2-Mechanics/CLI/rules/conditions.md#Petrified), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** Thri-kreen, Ziklight
- **Challenge** 2

## Traits

***Shutdown.*** If targeted by [dispel magic](2-Mechanics/CLI/spells/dispel-magic.md), the horror must succeed on a Constitution saving throw against the caster's spell save DC or fall [unconscious](2-Mechanics/CLI/rules/conditions.md#Unconscious) for 1 minute or until it takes any damage.

***Unusual Nature.*** The horror doesn't require air, food, drink, or sleep.

## Actions

***Multiattack.*** The horror makes one Bite attack and two Rotating Saw attacks, or it makes two Lightning Jolt attacks.

***Bite.*** *Melee Weapon Attack:* `dice:1d20+4|noform|text(+4)` to hit, reach 5 ft., one target. *Hit:* `dice:1d8+2|noform|avg|text(6)` (`1d8 + 2`) piercing damage.

***Rotating Saw.*** *Melee Weapon Attack:* `dice:1d20+4|noform|text(+4)` to hit, reach 5 ft., one target. *Hit:* `dice:1d4+2|noform|avg|text(4)` (`1d4 + 2`) slashing damage.

***Lightning Jolt.*** *Ranged Spell Attack:* `dice:1d20+4|noform|text(+4)` to hit, range 120 ft., one target. *Hit:* `dice:1d10+2|noform|avg|text(7)` (`1d10 + 2`) lightning damage.

***Spelljamming Helm Interface.*** The horror attaches to a spelljamming helm it can see within 5 feet of itself and attunes to the helm instantly. If another creature is already attuned to the helm, that creature's attunement to the helm ends when the horror's attunement begins. The horror can operate the helm even though it isn't a spellcaster. The horror can detach from the helm as a bonus action, which ends its attunement to the helm.
```
^statblock