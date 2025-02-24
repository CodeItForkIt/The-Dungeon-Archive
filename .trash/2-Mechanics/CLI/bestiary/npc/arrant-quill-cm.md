---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/cm
- monster/cr/11
- monster/size/medium
- monster/type/humanoid/human
aliases: ["Arrant Quill"]
---
# Arrant Quill
*Source: Candlekeep Mysteries p. 157*  

Quill is a charismatic bard who carries himself with a quiet confidence that doesn't hint at the full extent of his skills or powers. His handsome features are marred by a scar that curves from the top of his left cheekbone down to his jaw, though he doesn't consider the scar disfiguring. If asked about the scar, he explains that he got it years ago when the man who burned down his home village slashed his face with a dagger. It serves as a grim reminder of his past.

Although outwardly friendly, Quill is driven by three selfish desires: to preserve his well-being, to alleviate his boredom, and to escape Wisteria Vale. He holds a grudge against the Harpers and Ryllia for imprisoning him in a place that reminds him of the people he lost in his childhood, though he also takes some comfort in being able to live out the life he could've had. His time spent alone with his thoughts in Wisteria Vale has led him to suspect that the Harpers were never going to find a cure, and that they were simply biding their time until he became complacent enough that they could kill him without his being a threat. Quill's corruption has convinced him that the Harpers have become a powerful force that must be taken down; he trusts only himself to identify and eliminate agents of tyranny.

As long as Quill remains in Wisteria Vale, he is immune to all damage and automatically succeeds on all saving throws. This feature is suppressed if Quill wills it (no action required) or while he is within 15 feet of Renekor the beholder.

```ad-statblock
title: Arrant Quill
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/CM/Arrant%20Quill.webp#token)
*Medium humanoid (human), Neutral Evil*

- **Armor Class** 14
- **Hit Points** 135 (`18d8 + 54`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|10 (+0)|18 (+4)|16 (+3)|16 (+3)|15 (+2)|20 (+5)|

- **Proficiency Bonus** +4
- **Saving Throws** Intelligence +7, Wisdom +6, Charisma +9
- **Skills** Arcana +11, Deception +9, History +7, Performance +13
- **Senses** passive Perception 12
- **Languages** Common, Draconic, Elvish, Undercommon
- **Challenge** 11

***Spellcasting.*** Quill casts one of the following spells using Charisma as the spellcasting ability (save DC 17):

**At will**: [light](2-Mechanics/CLI/spells/light.md), [mage hand](2-Mechanics/CLI/spells/mage-hand.md), [prestidigitation](2-Mechanics/CLI/spells/prestidigitation.md)

**1/day each**: [mind blank](2-Mechanics/CLI/spells/mind-blank.md), [teleport](2-Mechanics/CLI/spells/teleport.md)

**3/day each**: [detect magic](2-Mechanics/CLI/spells/detect-magic.md), [dispel magic](2-Mechanics/CLI/spells/dispel-magic.md), [faerie fire](2-Mechanics/CLI/spells/faerie-fire.md), [hold monster](2-Mechanics/CLI/spells/hold-monster.md)

## Actions

***Multiattack.*** Quill makes two attacks with his dagger and uses Supreme Mockery.

***Dagger.*** *Melee or Ranged Weapon Attack:* `dice:1d20+8|noform|text(+8)` to hit, reach 5 ft. or range 20/60 ft., one target. *Hit:* `dice:1d4+4|noform|avg|text(6)` (`1d4 + 4`) piercing damage.

***Quill's Fable (Recharge 6).*** Quill utters a short fable while targeting up to five creatures within 30 feet of him that he can see. Each target that can hear Quill's magical fable must make a DC 17 Wisdom saving throw, taking `dice:8d8|noform|avg|text(36)` (`8d8`) psychic damage on a failed save, or half as much damage on a successful one.

***Supreme Mockery.*** Quill hurls a string of insults laced with enchantments at a creature he can see within 60 feet of him. If the creature can hear Quill (though it need not understand him), it must succeed on a DC 17 Wisdom saving throw or take `dice:12d10|noform|avg|text(66)` (`12d10`) psychic damage and have disadvantage on the next attack roll it makes before the end of its next turn.
```
^statblock