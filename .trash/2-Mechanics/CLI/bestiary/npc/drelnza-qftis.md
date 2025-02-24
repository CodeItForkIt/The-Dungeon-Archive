---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/qftis
- monster/cr/15
- monster/size/medium
- monster/type/undead/vampire
aliases: ["Drelnza"]
---
# Drelnza
*Source: Quests from the Infinite Staircase p. 197*  

Drelnza is the vampire daughter of Iggwilv. She is the Witch Queen's greatest treasure, an immortal warrior who guards some of her mother's most precious belongings decades after the archmage's mysterious departure. The identity of Drelnza's father is unknown even to her.

Drelnza slumbers deep in the Lost Caverns of Tsojcanth, rising to dispatch those few who make it to Iggwilv's hoard. As a consequence of Drelnza's prolonged rest, she has yet to regain some of her vampiric powers.

In the years before Iggwilv's disappearance, Drelnza acted as general to a battalion of demons bound to serve the Witch Queen. Armed with her sentient longsword, Heretic, Drelnza terrorized the people of Perrenland.

```ad-statblock
title: Drelnza
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/QftIS/Drelnza.webp#token)
*Medium undead (vampire), Lawful Evil*

- **Armor Class** 18 ([plate armor](2-Mechanics/CLI/items/plate-armor.md))
- **Hit Points** 187 (`22d8 + 88`)
- **Speed** 30 ft., climb 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|18 (+4)|18 (+4)|18 (+4)|17 (+3)|15 (+2)|18 (+4)|

- **Proficiency Bonus** +5
- **Saving Throws** Dexterity +9, Intelligence +8, Wisdom +7, Charisma +9
- **Skills** Arcana +8, Deception +9, Perception +7
- **Senses** darkvision 120 ft., passive Perception 17
- **Damage Resistances** necrotic
- **Condition Immunities** [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion)
- **Languages** Abyssal, Common, Giant
- **Challenge** 15

## Traits

***Legendary Resistance (3/Day).*** If Drelnza fails a saving throw, she can choose to succeed instead.

***Special Equipment.*** Drelnza wields Heretic.

***Spider Climb.*** Drelnza can climb difficult surfaces, including upside down on ceilings, without needing to make an ability check.

***Sunlight Hypersensitivity.*** Drelnza takes 20 radiant damage when she starts her turn in sunlight. While in sunlight, she has disadvantage on attack rolls and ability checks.

## Actions

***Multiattack.*** Drelnza makes one Bite attack and one Heretic attack.

***Bite.*** *Melee Weapon Attack:* `dice:1d20+9|noform|text(+9)` to hit, reach 5 ft., one creature. *Hit:* `dice:1d6+4|noform|avg|text(7)` (`1d6 + 4`) piercing damage plus `dice:3d6|noform|avg|text(10)` (`3d6`) necrotic damage. The target's hit point maximum is reduced by an amount equal to the necrotic damage taken, and Drelnza regains hit points equal to that amount. The reduction lasts until the target finishes a long rest. The target dies if this effect reduces its hit point maximum to 0. A Humanoid slain in this way and then buried rises the following night as a vampire spawn under Drelnza's control.

***Heretic.*** *Melee Weapon Attack:* `dice:1d20+12|noform|text(+12)` to hit, reach 5 ft. one target. *Hit:* `dice:6d10+7|noform|avg|text(40)` (`6d10 + 7`) slashing damage, and the target must succeed on a DC 17 Constitution saving throw or have the [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed) condition until the start of Drelnza's next turn. Celestials have disadvantage on the saving throw.

***Charm.*** Drelnza targets one Humanoid she can see within 30 feet of herself. The target must succeed on a DC 17 Wisdom saving throw or have the [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed) condition. While [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed) in this way, the target regards Drelnza as a trusted friend to be heeded and protected. The target isn't under Drelnza's control, but it takes her requests and actions in the most favorable way.

Each time Drelnza or her allies do anything harmful to the target, it can repeat the saving throw, ending the effect on itself on a success. Otherwise, the effect lasts 24 hours or until Drelnza is destroyed, is on a different plane of existence than the target, or takes a bonus action to end the effect.

## Reactions

Drelnza can take up to three reactions per round but only one per turn.

***Move.*** Immediately after a creature Drelnza can see ends its turn, Drelnza moves up to her speed without provoking opportunity attacks.

***Parry.*** Drelnza adds 5 to her AC against one melee attack that would hit her. To do so, she must see the attacker and be wielding a melee weapon.
```
^statblock