---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/mpp
- monster/cr/17
- monster/size/large
- monster/type/fiend/yugoloth
aliases: ["Baernaloth"]
---
# Baernaloth
*Source: Morte's Planar Parade p. 20, Sigil and the Outlands, Turn of Fortune's Wheel*  

Baernaloths are tall, gaunt yugoloths who keep to the Gray Wastes of Hades. Their gray, desiccated skin stretches over their bones, and their heads resemble horned equine skulls with ember-like eyes. Sages endlessly debate the nature of baernaloths, and the*Books of Keeping*—ancient tomes detailing the true names of the first yugoloths—report no mention of baernaloths within. Some posit that these enigmatic yugoloths were created by a primal evil power before other yugoloths or that they come from an epoch before the current manifestation of the planes. Baernaloths refuse to say, but most obsess over secrets and obscene lore regarding the far-flung past and inscrutable future of the multiverse. Many of these rare scholars of the profane seek to manipulate reality on a grand scale, while others unleash horrific experiments on the planes. It's said the first demodands of Carceri were created by baernaloths.

Baernaloths spread discord and despair among any creatures they meet. They use their breath, thick with the gloom of Hades, to turn friends against each other and then savor the horror that rises when their victims realize how they've betrayed one another. Baernaloths use their wicked power to keep mortally wounded foes alive, sometimes indefinitely, to prolong their suffering. Even striking against a baernaloth brings misery—they can cause an attacker's old wounds to painfully reopen. All the while, baernaloths are disturbingly detached, observing their victims' agony without emotion.

## A Baernaloth's Lair

Whether in the hopeless realms of Hades or on the rare occasion they lurk on some other plane, baernaloths lair in remote mountain crags and secluded caves. Their lairs have ample places to house and restrain "guests," particularly those the baernaloths keep hovering at death's door.

The challenge rating of a baernaloth is 18 (20,000 XP) when it's encountered in its lair.

## Statblock

```ad-statblock
title: Baernaloth
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/MPP/Baernaloth.webp#token)
*Large fiend (yugoloth), typically  Neutral Evil*

- **Armor Class** 17 (natural armor)
- **Hit Points** 256 (`27d10 + 108`)
- **Speed** 40 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|19 (+4)|14 (+2)|18 (+4)|22 (+6)|16 (+3)|21 (+5)|

- **Proficiency Bonus** +6
- **Saving Throws** Constitution +10, Wisdom +9
- **Skills** Arcana +12, Insight +9, Perception +9
- **Senses** truesight 120 ft., passive Perception 19
- **Damage Resistances** cold; fire; lightning; necrotic; psychic; bludgeoning, piercing, slashing from nonmagical attacks
- **Damage Immunities** acid, poison
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** all, telepathy 120 ft.
- **Challenge** 17

## Traits

***Legendary Resistance (4/Day).*** If the baernaloth fails a saving throw, it can choose to succeed instead.

***Magic Resistance.*** The baernaloth has advantage on saving throws against spells and other magical effects.

***Spellcasting.*** The baernaloth casts one of the following spells, requiring no material components and using Intelligence as the spellcasting ability (spell save DC 20):

**At will**: [detect thoughts](2-Mechanics/CLI/spells/detect-thoughts.md), [phantasmal force](2-Mechanics/CLI/spells/phantasmal-force.md), [suggestion](2-Mechanics/CLI/spells/suggestion.md)

**1/day each**: [cloudkill](2-Mechanics/CLI/spells/cloudkill.md), [plane shift](2-Mechanics/CLI/spells/plane-shift.md) (self only), [scrying](2-Mechanics/CLI/spells/scrying.md) (as an action)

## Actions

***Multiattack.*** The baernaloth makes one Anguishing Bite attack and one Claw attack. It can also use Teleport.

***Anguishing Bite.*** *Melee Weapon Attack:* `dice:1d20+10|noform|text(+10)` to hit, reach 5 ft., one target. *Hit:* `dice:1d10+4|noform|avg|text(9)` (`1d10 + 4`) piercing damage plus `dice:3d6|noform|avg|text(10)` (`3d6`) psychic damage. If the target is a creature, it can't regain hit points until the start of the baernaloth's next turn.

***Claw.*** *Melee Weapon Attack:* `dice:1d20+10|noform|text(+10)` to hit, reach 10 ft., one target. *Hit:* `dice:2d6+4|noform|avg|text(11)` (`2d6 + 4`) slashing damage plus `dice:5d6|noform|avg|text(17)` (`5d6`) necrotic damage.

***Miasma of Discord (Recharge 5-6).*** The baernaloth exhales gray vapors that coalesce at a point it can see within 120 feet of itself. The vapors fill a 20-foot-radius sphere centered on that point, then vanish. Each non-yugoloth creature in that area must make a DC 19 Wisdom saving throw. On a failed save, the creature takes `dice:10d6|noform|avg|text(35)` (`10d6`) psychic damage and has the [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed) condition until the end of its next turn. A creature [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed) in this way treats its allies as foes, and the colors of its body and equipment become shades of gray. On a successful save, the creature takes half as much damage only.

***Summon Yugoloth (1/Day).*** The baernaloth has a 50 percent chance of summoning its choice of `dice:1d4|noform|avg` (`1d4`) mezzoloths, 1 arcanaloth, or 1 baernaloth (the mezzoloth and arcanaloth appear in the Monster Manual). A summoned yugoloth appears in an unoccupied space within 60 feet of the baernaloth, acts as an ally of the baernaloth, and can't summon other yugoloths. It remains for 1 minute, until it or the baernaloth dies, or until the baernaloth dismisses it as an action.

***Teleport.*** The baernaloth teleports, along with any equipment it is wearing or carrying, up to 120 feet to an unoccupied space it can see.

## Reactions

The baernaloth can take up to three reactions per round but only one per turn.

***Afflict Despair.*** When a creature that the baernaloth can see within 60 feet of itself hits with an attack roll or succeeds on a saving throw, the baernaloth forces the creature to reroll the `dice:d20|noform|avg` (`d20`) and use the new result.

***Inescapable Pain.*** When the baernaloth is damaged by another creature, that creature must make a DC 19 Constitution saving throw, taking `dice:4d6|noform|avg|text(14)` (`4d6`) necrotic damage on a failed save, or half as much damage on a successful one.

![Baernaloth](2-Mechanics/CLI/bestiary/legendary-group/baernaloth-mpp.md)
```
^statblock