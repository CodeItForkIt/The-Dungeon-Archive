---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/coa
- monster/cr/10
- monster/size/medium
- monster/type/aberration
aliases: ["Lesser Tyrant Shadow"]
---
# Lesser Tyrant Shadow
*Source: Chains of Asmodeus p. 255*  

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

## Statblock

```ad-statblock
title: Lesser Tyrant Shadow
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/CoA/Lesser%20Tyrant%20Shadow.webp#token)
*Medium aberration, Lawful Evil*

- **Armor Class** 20 (natural armor)
- **Hit Points** 114 (`12d8 + 60`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|20 (+5)|18 (+4)|20 (+5)|18 (+4)|16 (+3)|18 (+4)|

- **Proficiency Bonus** +4
- **Saving Throws** Intelligence +8, Wisdom +7
- **Skills** Arcana +8, Deception +12, Perception +7, Stealth +12
- **Senses** passive Perception 17
- **Damage Resistances** fire
- **Damage Immunities** necrotic; poison; psychic; bludgeoning, piercing, slashing from nonmagical attacks
- **Condition Immunities** [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded), [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** understands all, telepathy 300 ft.
- **Challenge** 10

## Traits

***Empath.*** The shadow uses telepathy to sense nearby creatures. The shadow can see a creature if that creature has thoughts and is within the range of the shadow's telepathy. The shadow can't see creatures immune to telepathy.

***Undying Connection.*** The shadow was originally spawned from a specific devil and, if the shadow is slain, it returns to life in `dice:1d20|noform|avg|text(10)` (``) days within 1 mile of that devil. The shadow is killed permanently only if its progenitor devil is slain first.

## Actions

***Multiattack.*** The shadow makes two Claw attacks.

***Claw.*** *Melee Weapon Attack:* `dice:1d20+9|noform|text(+9)` to hit, reach 5 ft., one target. *Hit:* `dice:2d6+5|noform|avg|text(12)` (`2d6 + 5`) necrotic damage, plus `dice:1d6|noform|avg|text(3)` (`1d6`) psychic damage.

***Cloak of Shadows.*** The shadow bends darkness around itself, and now has the [invisible](2-Mechanics/CLI/rules/conditions.md#Invisible) condition for 1 minute. The invisibility ends if the shadow is subjected to a [Daylight](2-Mechanics/CLI/spells/daylight.md) spell or similar.

***Empathic Link.*** The shadow attempts to form a link between itself and a creature it can see. The target must make a DC 16 Intelligence saving throw, taking `dice:1d12|noform|avg|text(6)` (`1d12`) psychic damage on a success. On a failed save, the creature and the shadow are linked. While linked, every time the shadow is damaged, the creature takes half of that damage as psychic damage. The creature may repeat the saving throw at the end of each of its turns, taking `dice:1d12|noform|avg|text(6)` (`1d12`) psychic damage on a failed save, or ending the effect on a successful one.

## Bonus Actions

***Change Shape.*** The shadow transforms into a Beast, Humanoid or Fiend that it has an Empathic Link with, or back into its true form. In a new form, the shadow retains its align ment, hit points, hit dice, telepathy, and Intelligence, Wisdom, and Charisma scores, as well as this action. Its statistics and capabilities are otherwise replaced by those of the new form, except any class features, lair actions, or legendary actions of that form.
```
^statblock