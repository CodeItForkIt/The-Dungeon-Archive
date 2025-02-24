---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/mcv4ec
- monster/cr/5
- monster/size/medium
- monster/type/aberration
aliases: ["Nightmare Haunt"]
---
# Nightmare Haunt
*Source: Monstrous Compendium Volume 3: 4: Eldraine Creatures*  

Nightmare haunts are terrors from the minds of Eldraine's sleeping citizens, made tangible by the planeswalker Ashiok. These creatures can hurt the body and also attack the minds of dreamers afflicted by the Wicked Slumber.

Nightmare haunts appear as horrifying shadow creatures with forms evocative of their victims' deepest fears. Due to the collective trauma experienced by the people of Eldraine during the Phyrexian invasion, many nightmare haunts take the shape of those terrifying invaders, having multiple limbs and inhuman visages. Smoky purplish energy wafts from their forms, suggesting their connection to the Wicked Slumber.

> [!note] The Wicked Slumber
> 
> During the Phyrexian invasion of Eldraine, the high fae monarch Talion, the Kindly Lord, and a trio of witch sisters performed a grand ritual to create a sleeping curse. Even with the Phyrexians defeated, the curse remains and spreads unchecked through Eldraine due to interference from the planeswalker Ashiok and Eriette, one of the witches who helped create the curse. The Wicked Slumber affects rich and poor alike, causing them to fall into an endless sleep or roam as sleepwalkers. Animals are also affected, and even tree boughs droop as if exhausted in areas where the Wicked Slumber is prominent. Purple tendrils of wispy nightmares spread like vines across those areas and surround the bodies of those who sleep.
> 
> Heroes throughout Eldraine have ventured out to find a cure for the Wicked Slumber, but no one has yet discovered how to break the enchantment. It has even affected one of the Kindly Lord's daughters, the famed duelist Obyra. Meanwhile, Eriette and Ashiok conspire to build a nightmare realm in the ruins of Castle Ardenvale at the heart of the Wicked Slumber, replacing the virtuous court with one composed of sleepwalkers and dreamers guarded by nightmare haunts.
^the-wicked-slumber

```ad-statblock
title: Nightmare Haunt
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/MCV4EC/Nightmare%20Haunt.webp#token)
*Medium aberration, typically  Neutral Evil*

- **Armor Class** 13
- **Hit Points** 44 (`8d8 + 8`)
- **Speed** 30 ft., climb 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|14 (+2)|17 (+3)|13 (+1)| 9 (-1)|12 (+1)|17 (+3)|

- **Proficiency Bonus** +3
- **Saving Throws** ⏤
- **Skills** ⏤
- **Senses** blindsight 120 ft. (can't see beyond this radius), passive Perception 11
- **Damage Immunities** psychic
- **Condition Immunities** [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded), [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened)
- **Languages** Deep Speech, telepathy 120 ft.
- **Challenge** 5

## Traits

***Magic Resistance.*** The nightmare haunt has advantage on saving throws against spells and other magical effects.

***Somnophage.*** At the start of its turn, the nightmare haunt gains a number of temporary hit points equal to 5 times the number of [unconscious](2-Mechanics/CLI/rules/conditions.md#Unconscious) creatures within 30 feet of itself.

## Actions

***Multiattack.*** The nightmare haunt makes two Claw attacks.

***Claw.*** *Melee Weapon Attack:* `dice:1d20+6|noform|text(+6)` to hit, reach 5 ft., one target. *Hit:* `dice:1d6+3|noform|avg|text(6)` (`1d6 + 3`) slashing damage plus `dice:2d8|noform|avg|text(9)` (`2d8`) psychic damage.

***Tendrils of Slumber (Recharge 5-6).*** The nightmare haunt creates spectral tendrils that cover the ground in a 20-foot square that it can see within 30 feet of itself for 1 minute or until it uses this action again. When a creature other than the nightmare haunt enters the affected area for the first time or starts its turn there, the creature must succeed on a DC 14 Strength saving throw or take `dice:2d10|noform|avg|text(11)` (`2d10`) necrotic damage and have the [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) condition. The affected ground is also considered difficult terrain for creatures other than the nightmare haunt for the duration of its effect.

A creature that starts its turn in the area and is already [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) by the tendrils must repeat the saving throw. On a failed save, it has the [unconscious](2-Mechanics/CLI/rules/conditions.md#Unconscious) condition and instead of the [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) condition caused by the tendrils. On a successful save, the effect ends on the creature. An [unconscious](2-Mechanics/CLI/rules/conditions.md#Unconscious) creature remains asleep until it is no longer in the area with tendrils, takes any damage, or is targeted by a [remove curse](2-Mechanics/CLI/spells/remove-curse.md) spell or similar magic.

## Bonus Actions

***Shadow Stealth.*** While in dim light or darkness, the nightmare haunt takes the Hide action.
```
^statblock