---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/mpmm
- monster/cr/4
- monster/environment/desert
- monster/environment/forest
- monster/environment/underdark
- monster/size/medium
- monster/type/monstrosity/warlock
aliases: ["Yuan-ti Nightmare Speaker"]
---
# Yuan-ti Nightmare Speaker
*Source: Mordenkainen Presents: Monsters of the Multiverse p. 275*  

Nightmare speakers are yuan-ti malison priests who make a pact with the Dendar the Night Serpent to feed their deity the fears and nightmares of their victims in exchange for power in the mortal world. These priests receive nightmarish visions from Dendar that they interpret as prophecies, and they then use their magic and influence to make these visions come true.

Nightmare speakers revel in torturing others, keeping their victims in a constant state of fear and dread. They prefer to terrify rather than kill their opponents. They manipulate communities for the purpose of acquiring more victims and enjoy the company of Undead.

```ad-statblock
title: Yuan-ti Nightmare Speaker
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/MPMM/Yuan-ti%20Nightmare%20Speaker.webp#token)
*Medium monstrosity (warlock), Typically  Neutral Evil*

- **Armor Class** 14 (natural armor)
- **Hit Points** 71 (`13d8 + 13`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|16 (+3)|14 (+2)|13 (+1)|14 (+2)|12 (+1)|16 (+3)|

- **Proficiency Bonus** +2
- **Saving Throws** Wisdom +3, Charisma +5
- **Skills** Deception +5, Stealth +4
- **Senses** darkvision 120 ft., passive Perception 11
- **Damage Immunities** poison
- **Condition Immunities** [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** Abyssal, Common, Draconic
- **Challenge** 4

## Traits

***Devil's Sight.*** Magical darkness doesn't impede the yuan-ti's [darkvision](2-Mechanics/CLI/rules/senses.md#Darkvision).

***Magic Resistance.*** The yuan-ti has advantage on saving throws against spells and other magical effects.

***Spellcasting (Yuan-ti Form Only).*** The yuan-ti casts one of the following spells, requiring no material components and using Charisma as the spellcasting ability (spell save DC 13):

**At will**: [animal friendship](2-Mechanics/CLI/spells/animal-friendship.md) (snakes only), [mage hand](2-Mechanics/CLI/spells/mage-hand.md), [message](2-Mechanics/CLI/spells/message.md), [prestidigitation](2-Mechanics/CLI/spells/prestidigitation.md)

**2/day each**: [darkness](2-Mechanics/CLI/spells/darkness.md), [fear](2-Mechanics/CLI/spells/fear.md)

**3/day**: [suggestion](2-Mechanics/CLI/spells/suggestion.md)

## Actions

***Multiattack.*** The yuan-ti makes one Constrict attack and one Scimitar attack, or it makes two Spectral Fangs attacks.

***Constrict.*** *Melee Weapon Attack:* `dice:1d20+5|noform|text(+5)` to hit, reach 10 ft., one target. *Hit:* `dice:2d6+3|noform|avg|text(10)` (`2d6 + 3`) bludgeoning damage, and the target is [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) (escape DC 14) if it is a Large or smaller creature. Until this grapple ends, the target is [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained). The yuan-ti can constrict only one creature at a time.

***Scimitar (Yuan-ti Form Only).*** *Melee Weapon Attack:* `dice:1d20+5|noform|text(+5)` to hit, reach 5 ft., one target. *Hit:* `dice:1d6+3|noform|avg|text(6)` (`1d6 + 3`) slashing damage.

***Spectral Fangs.*** *Ranged Spell Attack:* `dice:1d20+5|noform|text(+5)` to hit, range 120 ft., one target. *Hit:* `dice:3d8+3|noform|avg|text(16)` (`3d8 + 3`) necrotic damage.

***Invoke Nightmare (Recharges after a Short or Long Rest).*** The yuan-ti taps into the nightmares of one creature it can see within 60 feet of it and creates an illusory, immobile manifestation of the creature's deepest fears, visible only to that creature.

The target must make a DC 13 Intelligence saving throw. On a failed save, the target takes `dice:4d10|noform|avg|text(22)` (`4d10`) psychic damage and is [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened) of the manifestation, believing it to be real. The yuan-ti must concentrate to maintain the illusion (as if concentrating on a spell), which lasts for up to 1 minute and can't be harmed. The target can repeat the saving throw at the end of each of its turns, ending the illusion on a success or taking `dice:2d10|noform|avg|text(11)` (`2d10`) psychic damage on a failure.

## Bonus Actions

***Change Shape.*** The yuan-ti transforms into a Medium snake or back into its true form. Its statistics are the same in each form. Any equipment it is wearing or carrying isn't transformed. If it dies, it stays in its current form.
```
^statblock

## Environment

desert, forest, underdark