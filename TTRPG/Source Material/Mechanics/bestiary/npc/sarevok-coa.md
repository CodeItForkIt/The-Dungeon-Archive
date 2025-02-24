---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/coa
- monster/cr/17
- monster/size/medium
- monster/type/humanoid
statblock: inline
aliases: ["Sarevok"]
---
# [Sarevok](Mechanics\bestiary\npc/sarevok-coa.md)
*Source: Chains of Asmodeus p. 48*  

Sarevok Anchev is a powerful Deathstalker. He is also one of the Bhaalspawn, the mortal offspring of the dead god Bhaal. Sarevok attempted to reclaim the divine seat of the Lord of Murder vacated by his immortal father's demise, but his plans were thwarted when he was slain by his half-brother, Abdel Adrian, who rejected his heritage and fought against his Bhaalspawn siblings.

Sarevok's spirit was sent to the Abyss as punishment. There he eventually crossed paths with Abdel a second time when his noble-hearted brother ventured into the lower realms on a dangerous quest to stop another Bhaalspawn named Melissan. Sarevok agreed to help Abdel kill Melissan, on the condition that Abdel helped him escape the eternal torments of the Abyss.

Abdel agreed, and Sarevok was reborn into the mortal world. After his rebirth, Sarevok was true to his word, and the two brothers fought side by side against their half-sister. Ultimately Melissan was defeated, and Sarevok was granted a second chance at life.

With his prodigious strength, his legendary skill in battle, and the Sword of Chaos—a life-stealing, enchanted blade—Sarevok became a famous (and feared) mercenary. Yet his many accomplishments brought him no joy. He felt no thrill at victory in battle, no delight in the routing of his enemies. The power he accumulated was bitter as ashes on his tongue, and he became a man haunted by his former life. The realization that no earthly achievements could ever compare to what he once almost had—immortality and godhood—left him broken and empty.

Sarevok plunged into a deep despair. To numb his pain, he indulged in every vice imaginable, squandering his wealth and health on alcohol, drugs, and fleeting comforts. While his divine heritage slowed his aging, it did not stop it entirely, and after decades of self-abuse he was eventually reduced to an old man begging in the streets of Baldur's Gate.

This was how his father—Bhaal, the reborn god of murder—found him. Bhaal recognized his own divine spark in the pathetic old man, and he sensed Sarevok still had potential. Bhaal recruited him to become the high priest of his fledgling clergy, giving Sarevok new purpose... and another chance to become an agent of death and destruction.

```statblock
"name": "Sarevok (CoA)"
"size": "Medium"
"type": "humanoid"
"alignment": "Neutral Evil"
"ac": !!int "21"
"ac_class": "plate armor of Bhaal"
"hp": !!int "190"
"hit_dice": "20d8 + 100"
"stats":
- !!int "23"
- !!int "10"
- !!int "21"
- !!int "11"
- !!int "18"
- !!int "14"
"speed": "30 ft."
"saves":
  "Wisdom": !!int "10"
  "Constitution": !!int "11"
"skillsaves":
  "Intimidation": !!int "14"
  "Religion": !!int "6"
  "History": !!int "6"
"damage_immunities": "acid, necrotic, poison"
"condition_immunities": "[charmed](Mechanics/Rules/conditions.md#Charmed), [frightened](Mechanics/Rules/conditions.md#Frightened),\
  \ [poisoned](Mechanics/Rules/conditions.md#Poisoned)"
"senses": "darkvision 60 ft., passive Perception 14"
"languages": "Abyssal, Common, Infernal"
"cr": "17"
"traits":
- "desc": "Sarevok casts one of the following spells, using Wisdom as the spellcasting\
    \ ability (spell save DC 18):\n\nAt will: [Resistance](Mechanics/spells/resistance.md),\
    \ [Thaumaturgy](Mechanics/spells/thaumaturgy.md)\n\n1/day each: [Animate Dead](Mechanics/spells/animate-dead.md),\
    \ [Antimagic Field](Mechanics/spells/antimagic-field.md), [Astral Projection](Mechanics/spells/astral-projection.md),\
    \ [Blade Barrier](Mechanics/spells/blade-barrier.md), [Command](Mechanics/spells/command.md),\
    \ [Contagion](Mechanics/spells/contagion.md), [Dispel Magic](Mechanics/spells/dispel-magic.md),\
    \ [Divination](Mechanics/spells/divination.md), [Etherealness](Mechanics/spells/etherealness.md),\
    \ [Fire Storm](Mechanics/spells/fire-storm.md), [Harm](Mechanics/spells/harm.md),\
    \ [Hold Person](Mechanics/spells/hold-person.md), [Silence](Mechanics/spells/silence.md)"
  "name": "Spellcasting"
- "desc": "Sarevok has advantage on saving throws against spells and other magical\
    \ effects."
  "name": "Magic Resistance"
- "desc": "If Sarevok is killed, he gains a new body in 24 hours, regaining all his\
    \ hit points. The new body appears on the altar of the temple of Bhaal beneath\
    \ Baldur's Gate. This ability ceases to function if a cleric of good alignment\
    \ casts [Hallow](Mechanics/spells/hallow.md) on the altar in the temple of Bhaal."
  "name": "Rejuvenation"
"actions":
- "desc": "Sarevok makes three Longsword attacks. He can replace one of the attacks\
    \ with Flames of Bhaal or Spellcasting."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +12 to hit, reach 5ft., one target. Hit: 10\
    \ (1d8 + 6) slashing damage or 11 (1d10 + 6) if wielded in two hands. The\
    \ target must succeed on a DC 18 Constitution saving throw or be cursed by Bhaal,\
    \ preventing it from regaining hit points. The curse lasts until removed by the\
    \ [Remove Curse](Mechanics/spells/remove-curse.md) spell or similar effect."
  "name": "Longsword"
- "desc": "Sarevok causes flames to engulf one creature that he can see within 60\
    \ feet. The target must succeed on a DC 18 Dexterity saving throw or take 18 (4d8)\
    \ necrotic damage. This damage can't be restored except by a [Lesser Restoration](Mechanics/spells/lesser-restoration.md)\
    \ spell or similar effect."
  "name": "Flames of Bhaal"
"legendary_actions":
- "desc": "Sarevok makes a Longsword attack."
  "name": "Slash"
- "desc": "Sarevok uses Flames of Bhaal."
  "name": "Unholy Flame"
- "desc": "Sarevok unleashes Bhaal's power. Creatures within 30 feet of Sarevok, including\
    \ ones behind barriers and around corners, can't regain hit points until the end\
    \ of Sarevok's next turn."
  "name": "Channel Bhaal's Hate (Costs 2 Actions)"
"source":
- "CoA"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/CoA/Sarevok.webp"
```
^statblock