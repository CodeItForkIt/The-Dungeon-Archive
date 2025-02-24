---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/coa
- monster/cr/22
- monster/size/gargantuan
- monster/type/aberration
aliases: ["Greater Tyrant Shadow"]
---
# Greater Tyrant Shadow
*Source: Chains of Asmodeus p. 256*  

> [!quote] A quote from Unknown  
> 
> The nine hells can only dream of the perfect oppression which mortals bring upon each other.

Alongside devils and monsters, the Nine Hells have given birth to more nebulous threats. Even raw negative emotion can be personified in the darkest reaches of the lower planes. Congealing into a shape that knows only hunger and the need to hunt. It stalks those filled with fears and insecurities that they refuse to acknowledge.

## Bred from Denial

Tyrant shadows are a threat unique to the Nine Hells. Mortals in the Nine Hells dwell in agony and terror by definition. However, the life of a devil is seldom happier. The infernal hierarchy is harsh and those above constantly abuse the Fiends beneath them whilst fearing usurpation at every turn. In contrast to the unruly hosts of the Abyss, devils are never permitted to give vent to the bitterness that is their lot, bound to a show of discipline and obedience. This festering misery, given no other outlet, manifests as an independent creature that breaks from the devil who generated it to pursue its own malevolent life. Tyrant shadows most often appear as huge-mawed stalking reptiles made from writhing shadows, unless they take on specific forms to exploit the fears of their prey.

## Shifting Stalkers

Tyrant shadows are strongly attracted to the kind of suppressed negative emotions that gave rise to them. The minds of strong mortals valiantly enduring the horrors of the Nine Hells without complaint draw them from far away, and they hunger both for the flesh and the fear such prey generate. A truly satisfying feast for the tyrants must be prepared properly. They stalk their targets over long hours, telepathically sensing what is most feared and shifting their forms to provide glimpses and hints of terror wherever their target looks. Mortals who break easily, giving swift vent to their fear or flying into berserk rages, are of little interest to them. A fear that slowly erodes through its host's iron discipline is savored like a well-aged wine. For the same reason, they gleefully prey on middling and lesser devils whose lives are a constant battle between bitterness and discipline. Those few mortals who are so confident in themselves as to know no fear at all—the most focused of monks or blessed of paladins perhaps—are effectively invisible to tyrant shadows.

## Personal Nemeses

Every tyrant shadow was spawned from the resentful core of a particular devil before taking up its own existence, and the presence of "their" devil continues to sustain the tyrant. As the devil rises in the internal hierarchy, so the tyrant grows stronger. As the tyrant hunts and feasts, so the devil's inner bitterness grows, driving them to greater acts of evil, and thus leading to their advancement. Much as they might deny it, even the greatest of devils are consumed with negative emotions. Archdevils command whole planes yet hate and envy the gods. Somewhere perhaps even Asmodeus has a stalking shadow feeding his malice even as his great status empowers it.

## Greater Tyrant Shadow's Lair

A greater tyrant shadow's lair is always within a few miles of the devil that spawned it, which means that the tyrant shadow itself may often relocate, following the movements of its progenitor, even across the layers of the Nine Hells themselves. Of the lair specifically, the tyrant shadow generally selects a suitably cavernous locale, with deep shadows, perfect for skulking and ambushes. Eroded canyons, abandoned dwellings, and even deep forests, though rare in the Nine Hells, are also suitable locations.

## Statblock

```ad-statblock
title: Greater Tyrant Shadow
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/CoA/Greater%20Tyrant%20Shadow.webp#token)
*Gargantuan aberration, Lawful Evil*

- **Armor Class** 18 (natural armor)
- **Hit Points** 372 (`24d20 + 120`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|25 (+7)|15 (+2)|20 (+5)|24 (+7)|16 (+3)|22 (+6)|

- **Proficiency Bonus** +7
- **Saving Throws** Intelligence +14, Wisdom +10
- **Skills** Arcana +14, Deception +20, Perception +10, Stealth +16
- **Senses** passive Perception 20
- **Damage Resistances** fire
- **Damage Immunities** necrotic; poison; psychic; bludgeoning, piercing, slashing from nonmagical attacks
- **Condition Immunities** [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded), [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** understands all, telepathy 300 ft.
- **Challenge** 22

## Traits

***Empath.*** The shadow uses telepathy to sense nearby creatures. The shadow can see a creature if that creature has thoughts and is within the range of the shadow's telepathy. The shadow can't see creatures immune to telepathy.

***Undying Connection.*** The shadow was originally spawned from a specific devil and, if the shadow is slain, it returns to life in `dice:1d20|noform|avg|text(10)` (``) days within 1 mile of that devil. The shadow is killed permanently only if its progenitor devil is slain first.

## Actions

***Multiattack.*** The shadow makes three Claw attacks. It can replace one of the attacks with Shadows of Death (if available).

***Claw.*** *Melee Weapon Attack:* `dice:1d20+14|noform|text(+14)` to hit, reach 5 ft., one target. *Hit:* `dice:4d6+7|noform|avg|text(21)` (`4d6 + 7`) necrotic damage, plus `dice:3d6|noform|avg|text(10)` (`3d6`) psychic damage.

***Cloak of Shadows.*** The shadow bends darkness around itself, and now has the [invisible](2-Mechanics/CLI/rules/conditions.md#Invisible) condition for 1 minute. The invisibility ends if the shadow is subjected to a [Daylight](2-Mechanics/CLI/spells/daylight.md) spell or similar.

***Empathic Link.*** The shadow attempts to form a link between itself and a creature it can see. The target must make a DC 22 Intelligence saving throw, taking `dice:4d12|noform|avg|text(26)` (`4d12`) psychic damage on a success. On a failed save, the creature and the shadow are linked. While linked, every time the shadow is damaged, the creature takes half of that damage as psychic damage. The creature may repeat the saving throw at the end of each of its turns, taking `dice:4d12|noform|avg|text(26)` (`4d12`) psychic damage on a failed save, or ending the effect on a successful one.

***Shadows of Death (Recharge 5-6).*** The shadow discharges inky-black shadows in a 90-foot-radius sphere around itself. Creatures in the shadows must succeed on a DC 22 Wisdom saving throw or take `dice:8d8|noform|avg|text(36)` (`8d8`) necrotic damage and have the [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened) condition for 1 minute. A [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened) creature may repeat the saving throw at the end of each of its turns, ending the effect on a successful save, but taking the damage again on a failed save.

## Bonus Actions

***Change Shape.*** The shadow transforms into a Beast, Humanoid or Fiend that it has an Empathic Link with, or back into its true form. In a new form, the shadow retains its align ment, hit points, hit dice, telepathy, and Intelligence, Wisdom, and Charisma scores, as well as this action. Its statistics and capabilities are otherwise replaced by those of the new form, except any class features, lair actions, or legendary actions of that form.

## Legendary Actions

***Shadow Blink.*** The shadow surrounds itself in black mist, then teleports up to 60 feet to an unoccupied space that it can see.

***Shapeshift.*** The shadow uses its Change Shape ability.

***Mind Spike (Costs 2 Actions).*** *Ranged Spell Attack:* `dice:1d20+14|noform|text(+14)` to hit, range 300 ft., one target. *Hit:* `dice:3d10+7|noform|avg|text(23)` (`3d10 + 7`) psychic damage.

![Greater Tyrant Shadow](2-Mechanics/CLI/bestiary/legendary-group/greater-tyrant-shadow-coa.md)
```
^statblock