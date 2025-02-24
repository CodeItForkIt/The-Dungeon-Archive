---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/hwcs
- monster/cr/5
- monster/size/large
- monster/type/undead
aliases: ["Cobblefright"]
---
# Cobblefright
*Source: Humblewood Campaign Setting p. 180*  

Cobblefrights are undead monstrosities created through dark necromancy. Rumored to have been orig-inally devised by the mad necromancer Lathrus of the Night's Call, cobblefrights are made by linking several birdfolk skeletons together to form one frightening creature with enhanced physical properties. Among those who have studied Lathrus' research, only the most reckless have tried to create a cobblefright of their own, often to disastrous effect.

## Horror of Horrors

Cobblefrights are generally pieced together from the skeletons of five or six birdfolk. The combination of multiple bodies allows not only for a larger and more robust design, but also vastly increases the quantity of necromantic energies cobblefrights contain. This increased capacity for power provides cobblefrights with tremendous strength, as much as a dozen birdfolk combined. It also grants cobblefright bones greater durability. Their remarkable power and resilience is somewhat of a double-edged sword, as cobblefrights also require a large amount of necromantic energy to be sustained. The surviving records of cobblefright creators note that, quite unexpectedly, the creatures developed the ability to drain the life force of other living beings, replenishing their own energy in the process. This makes cobblefrights useful as independent sentries, so long as they have a steady supply of living beings to fuel them.

## Chaotic Psyche

The discordant parts that comprise cobblefrights exert tremendous strain on the bodies of these creatures. The source of this strain is rooted in the same magic that allows birdfolk skeletons to recall skills they once knew in life: the bones remember. Remnants of the soul such as memories, desires, fears, skills, and certain forms of knowledge are imprinted on the bones of the departed. When activated by necromantic energy, these conflicting impressions swirl chaotically within cobblefrights. Since cobblefrights are composed of multiple bodies, often originating from differing times, places, and walks of life, the impressions contained within the creatures are particularly volatile and chaotic. This constant internal conflict requires large and regular supplies of energy to keep cobblefrights stable, but it also grants them a surprising degree of resistance against those who would seek to wrest control of the creatures away from their creator. However, necromancers must be careful to maintain control over these dangerous creatures. Damaged cobblefrights will readily harvest their maker as an immediate source of life energy.

## Statblock

```ad-statblock
title: Cobblefright
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/HWCS/Cobblefright.webp#token)
*Large undead, Chaotic Evil*

- **Armor Class** 15 (natural armor)
- **Hit Points** 102 (`12d10 + 36`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|19 (+4)|11 (+0)|16 (+3)| 6 (-2)| 8 (-1)| 5 (-3)|

- **Proficiency Bonus** +3
- **Saving Throws** Constitution +6, Wisdom +2
- **Skills** ⏤
- **Senses** darkvision 60 ft., passive Perception 9
- **Damage Immunities** poison
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** understands Auran, Birdfolk, and any other languages it knew in life, but can't speak
- **Challenge** 5

## Traits

***Berserk.*** Whenever the cobblefright starts its turn with 40 hit points or fewer, roll a `dice:d6|noform|avg` (`d6`). On a 6, the cobblefright goes berserk. On each of its turns while berserk, the cobblefright attacks the nearest creature it can see. If no creature is near enough to move to and attack, the cobblefright attacks an object, with preference for an object smaller than itself. Once the cobblefright goes berserk, it continues to do so until it is destroyed or regains all its hit points.

## Actions

***Multiattack.*** The cobblefright makes three claw attacks. One of those attacks can be replaced by a grab attack.

***Claw.*** *Melee Weapon Attack:* `dice:1d20+7|noform|text(+7)` to hit, reach 5 ft., one target. *Hit:* `dice:1d4+4|noform|avg|text(8)` (`1d4 + 4`) piercing damage.

***Grab.*** *Melee Weapon Attack:* `dice:1d20+7|noform|text(+7)` to hit, reach 5 ft., one target. *Hit:* The target is [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) (escape DC 15). The cobblefright can grapple up to 2 targets at once. Once at the start of its turn for each target it has [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) the cobblefright can squeeze its victim. The target must make a DC 15 Strength saving throw, taking `dice:2d8+4|noform|avg|text(13)` (`2d8 + 4`) bludgeoning damage on a failed save.

***Soul Siphon.*** One creature the cobblefright has [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) must make a DC 14 Constitution saving throw, taking `dice:2d10|noform|avg|text(11)` (`2d10`) necrotic damage on a failed save, or half that amount on a success. The target's hit point maximum is reduced by the amount of necrotic damage taken, and the cobblefright regains hit points equal to that amount. The reduction lasts until the target finishes a short or long rest.
```
^statblock