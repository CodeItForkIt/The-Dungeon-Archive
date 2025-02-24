---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/ghloe
- monster/cr/1
- monster/size/medium
- monster/type/fey
aliases: ["Bone Trader"]
---
# Bone Trader
*Source: Grim Hollow: Lairs of Etharis p. 13*  

"Do you really need all of your bones? Are you sure I couldn't just snack on a few? I'll gladly pay you for them."

## Salvage

Bone trader lairs have many, many bones. Depending on how successful and powerful the bone trader is, it may also have the equipment and belongings of people it has killed or of the minions it employs. Its bone armor is infused with a peculiar magic.

Smashing the armor into a paste and mixing it with appropriate amounts of coagulant from a herbalism kit allows it to be applied it to a shield or weapon. This paste, called [ready gunk](2-Mechanics/CLI/items/ready-gunk-ghloe.md) (see Appendix A of Lairs of Etharis), can be completed with a successful Wisdom check (DC 10) by someone proficient with a herbalism kit. This process takes 10 minutes.

## Lore

- **DC 10 Intelligence ([History](2-Mechanics/CLI/rules/skills.md#History)).** A bone trader is most dangerous in its lair, where it can use its collection of bones to defend itself.  
- **DC 15 Intelligence ([Arcana](2-Mechanics/CLI/rules/skills.md#Arcana)).** A bone trader can charm its opponents and is often defended by a small gang of intimidated or charmed creatures.  
- **DC 20 Intelligence ([Nature](2-Mechanics/CLI/rules/skills.md#Nature)).** Like other fey, bone traders can be tantalized by a deal and may be willing to negotiate rather than fight, even if it seems to have the upper hand or is actively winning a battle  

## Statblock

```ad-statblock
title: Bone Trader
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/GHLoE/Bone%20Trader.webp#token)
*Medium fey, Neutral Evil*

- **Armor Class** 12 (15 with bone armor)
- **Hit Points** 22 (`5d8`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|10 (+0)|14 (+2)|11 (+0)|14 (+2)|15 (+2)|18 (+4)|

- **Proficiency Bonus** +2
- **Saving Throws** Constitution +2
- **Skills** Animal Handling +4, Perception +4
- **Senses** darkvision 60 ft., passive Perception 14
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed)
- **Languages** Sylvan, two other languages
- **Challenge** 1

## Traits

***Bone Armor (1/Day).*** A bone trader in its lair can use a bonus action to summon a temporary suit of bone armor that lasts for ten minutes or until dismissed by the bone trader. While wearing its bone armor, a bone trader has advantage on Wisdom saving throws and Charisma ([Intimidation](2-Mechanics/CLI/rules/skills.md#Intimidation)) checks.

***Speak with Beasts.*** The bone trader can communicate with beasts as if they shared a language.

## Actions

***Bone Club.*** *Melee Weapon Attack:* `dice:1d20+4|noform|text(+4)` to hit, reach 5 ft., one creature. *Hit:* `dice:1d8+2|noform|avg|text(6)` (`1d8 + 2`) bludgeoning damage.

***Skelesuck.*** *Melee Weapon Attack:* `dice:1d20+4|noform|text(+4)` to hit, reach 5 ft., one creature. *Hit:* `dice:1d4+2|noform|avg|text(4)` (`1d4 + 2`) piercing damage. The target must succeed on a DC 10 Constitution saving throw or have one of its bones sucked out, resulting in the piercing damage becoming a reduction in maximum hit points until magical healing is applied.

***Fey Charm.*** The bone trader targets one humanoid, goblinoid, fey, or beast it can see within 30 feet of it. The target must succeed on a DC 14 Wisdom saving throw or be magically [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed). The [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed) creature regards the bone trader as a trusted friend to be heeded and protected. Although the target isn't under the bone trader's control, it takes the bone trader's requests or actions in the most favorable way . Each time the bone trader or its allies do anything harmful to the target, it can repeat the saving throw, ending the effect on itself on a success. Otherwise, the effect lasts 24 hours or until the bone trader dies, is on a different plane of existence from the target, or ends the effect as a bonus action. If a target's saving throw is successful, the target is immune to the bone trader's fey charm for the next 24 hours.

The bone trader can have no more than one humanoid [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed) at a time, along with up to three beasts.
```
^statblock