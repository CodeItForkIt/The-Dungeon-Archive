---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/veor
- monster/cr/15
- monster/size/large
- monster/type/fiend
aliases: ["Relentless Impaler"]
---
# Relentless Impaler
*Source: Vecna: Eve of Ruin p. 231*  

In the Domains of Dread, practitioners of foul magic perform a profane ritual that turns living creatures into fiendish killers. This ritual necessitates the use of a ceremonial stake, which is plunged into the heart of a living sacrifice. The hulking form of the relentless impaler then emerges from the sacrifice's pool of blood, spear in hand.

A relentless impaler is bound to the creature that wielded the ceremonial stake in the ritual that birthed it. As long as the original stake remains lodged in the heart of the ritual victim, the impaler can return over and over again to regenerate beside the victim's body, no matter how many times it is destroyed.

The impaler pursues its creator's agenda coldly and efficiently. It has no concern for its own self-preservation, knowing that, for itself at least, death isn't the end.

```ad-statblock
title: Relentless Impaler
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/VEoR/Relentless%20Impaler.webp#token)
*Large fiend, typically  Neutral Evil*

- **Armor Class** 16 (natural armor)
- **Hit Points** 184 (`16d10 + 96`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|23 (+6)|16 (+3)|22 (+6)|12 (+1)|15 (+2)|18 (+4)|

- **Proficiency Bonus** +5
- **Saving Throws** Strength +11, Dexterity +8, Charisma +9
- **Skills** Athletics +11, Perception +7, Survival +7
- **Senses** darkvision 120 ft., passive Perception 17
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened)
- **Languages** understands all languages but can't speak
- **Challenge** 15

## Traits

***Bloodheart Stake.*** The impaler is magically bound to the ceremonial stake and the sacrificed corpse the ritual caster used to create it. If the impaler is reduced to 0 hit points, it disappears, then re-forms `dice:1d8|noform|avg` (`1d8`) hours later in the nearest unoccupied space to the stake and regains all its hit points. The impaler dies only if it is reduced to 0 hit points while either the ceremonial stake is removed from the sacrifice's corpse or the impaler is on a different plane of existence from that corpse.

***Legendary Resistance (3/Day).*** If the impaler fails a saving throw, it can choose to succeed instead.

## Actions

***Multiattack.*** The impaler makes one Spike attack and two Wicked Spear attacks.

***Spike.*** *Melee Weapon Attack:* `dice:1d20+11|noform|text(+11)` to hit, reach 5 ft., one target. *Hit:* `dice:2d8+6|noform|avg|text(15)` (`2d8 + 6`) piercing damage, and the target's speed is halved until the start of the impaler's next turn.

***Wicked Spear.*** *Melee or Ranged Weapon Attack:* `dice:1d20+11|noform|text(+11)` to hit, reach 10 ft. or range 20/40 ft., one target. *Hit:* `dice:2d6+6|noform|avg|text(13)` (`2d6 + 6`) piercing damage plus `dice:3d8|noform|avg|text(13)` (`3d8`) necrotic damage.

***Spike Burst (Recharge 5-6).*** Twisted, spectral spikes shoot out from the impaler's body. Each creature within 30 feet of the impaler must make a DC 19 Dexterity saving throw, taking `dice:9d8|noform|avg|text(40)` (`9d8`) force damage on a failed save or half as much damage on a successful one.

## Legendary Actions

***Speed Spike.*** The impaler teleports up to 30 feet to an unoccupied space it can see. It can then make a Spike attack.

***Deepen Wounds (Costs 2 Actions).*** Each creature whose speed is currently reduced by the impaler's Spike attack takes `dice:4d8|noform|avg|text(18)` (`4d8`) necrotic damage.
```
^statblock