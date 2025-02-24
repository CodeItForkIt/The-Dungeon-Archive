---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/mabjov
- monster/cr/10
- monster/size/medium
- monster/type/undead
statblock: inline
aliases: ["Aribeth de Tylmarande"]
---
# [Aribeth de Tylmarande](Mechanics\bestiary\npc/aribeth-de-tylmarande-mabjov.md)
*Source: Minsc and Boo's Journal of Villainy p. 108*  

Aribeth was once an elven paladin of Tyr, the Blind God of Justice. Renowned for her beauty and beloved for her kindness, she was the personal guard of Nasher Alagonder, the lord of the city of Neverwinter. But when her fiancé, Fenthick Moss, was unjustly hanged for treason, grief and a desire for vengeance corrupted her once noble spirit. She started down a path of revenge against her lord, her people, and even her god that ultimately ended with her own death.

After she was killed, the arch devil Mephistopheles sought out Aribeth's spirit in Hell. He made a bargain with the fallen paladin, offering her a chance to mete out justice once again as she had done when she served Tyr. Aribeth accepted and was returned to the world of the living.

The decades Aribeth had spent in hell, along with the betrayals she had experienced in her first life, had transformed her into a shell of a person. Devoid of conscience, remorse, and compassion, Mephistopheles made her into a hunter of those who had broken pacts made with the powers of Hell.

But despite his efforts to completely break her, Mephistopheles soon recognized that a tiny spark of Aribeth's former kindness and compassion remained, buried deep within her. In acknowledgement of this, he bestowed upon Aribeth an unholy sword called Void that would eat the souls of its victims, sparing them from being damned to the eternal suffering of the Nine Hells. However, Mephistopheles only granted Aribeth permission to use this sword to spare one out of every nine victims, knowing that choosing who to save and who to let suffer would be a constant burden that would eventually corrupt the last noble vestiges of Aribeth's soul.

But Aribeth was smart enough to understand her overlord's true plan. Instead of actively selecting who Void will spare, she makes the choice by using a simple, but extremely precise, scale that resembles the holy symbol she once carried as a priest of Tyr. When she encounters her victims, she asks them for a gold piece. If they give it to her, she places it on the scale, measuring the weight to the thousandth of an ounce. If the scale comes to balance on the last digit of "9", she will slay them with Void, sparing her the emotional burden of personally deciding who will be cast down and who will be spared.

Even now, though she still serves as an avatar of Mephistopheles, Aribeth is not evil in the strict sense. Her victims are never the innocent, and she only unleashes her savage justice upon those who deserve it through their own choices and actions. And she takes no pleasure in her duties; no cruel revelry in the suffering she inflicts. In this way she is more akin to a relentless force of nature—unstoppable and uncaring, but unbiased in her dispensation of dark justice.

```statblock
"name": "Aribeth de Tylmarande (MaBJoV)"
"size": "Medium"
"type": "undead"
"alignment": "Neutral Evil"
"ac": !!int "17"
"ac_class": "[half plate](Mechanics/items/half-plate-armor.md)"
"hp": !!int "120"
"hit_dice": "16d8 + 48"
"stats":
- !!int "16"
- !!int "14"
- !!int "16"
- !!int "10"
- !!int "13"
- !!int "16"
"speed": "30 ft."
"skillsaves":
  "Religion": !!int "4"
  "Perception": !!int "5"
"damage_immunities": "necrotic; bludgeoning, piercing, slashing from nonmagical weapons\
  \ that aren't silvered"
"condition_immunities": "[poisoned](Mechanics/Rules/conditions.md#Poisoned)"
"senses": "darkvision 60 ft., passive Perception 15"
"languages": "Common, Elvish, Infernal"
"cr": "10"
"traits":
- "desc": "Aribeth casts one of the following spells, using Charisma as the spellcasting\
    \ ability (spell save DC 15):\n\n1/day: [dispel magic](Mechanics/spells/dispel-magic.md)\n\
    \n2/day each: [aid](Mechanics/spells/aid.md), [command](Mechanics/spells/command.md),\
    \ [magic weapon](Mechanics/spells/magic-weapon.md), [searing smite](Mechanics/spells/searing-smite.md),\
    \ [shield of faith](Mechanics/spells/shield-of-faith.md)"
  "name": "Spellcasting"
- "desc": "Aribeth knows the distance to and direction of any creature that has broken\
    \ a pact with Mephistopheles, even if the creature and Aribeth are on different\
    \ planes of existence."
  "name": "Infernal Tracker"
- "desc": "Aribeth has advantage on saving throws against spells and other magical\
    \ effects."
  "name": "Magic Resistance"
- "desc": "Aribeth is accompanied by a [nightmare](Mechanics/bestiary/fiend/nightmare.md).\
    \ The nightmare allows Aribeth to use it as a mount."
  "name": "Nightmare"
- "desc": "Aribeth regains 20 hit points at the start of her turn. If Aribeth takes\
    \ radiant damage, this trait doesn't function at the start of Aribeth's next turn.\
    \ Aribeth's body is destroyed only if she starts her turn with 0 hit points and\
    \ doesn't regenerate."
  "name": "Regeneration"
- "desc": "Three [shadows](Mechanics/bestiary/undead/shadow.md) hide within the saddle\
    \ of Aribeth's nightmare. These shadows only come out if there is a creature within\
    \ 30 feet that is at 0 hit points. When that happens, a shadow emerges and attacks\
    \ the creature in order to make it fail a death saving throw. It continues to\
    \ do so until the creature is dead."
  "name": "Shadows"
- "desc": "While in sunlight, Aribeth has disadvantage on attack rolls, as well as\
    \ on Wisdom ([Perception](Mechanics/Rules/skills.md#Perception)) checks that rely\
    \ on sight."
  "name": "Sunlight Sensitivity"
"actions":
- "desc": "Aribeth makes three Void or Unholy Strike attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +7 to hit, reach 5 ft., one target. Hit: 7 (1d8\
    \ + 3) slashing damage or 8 (1d10 + 3) slashing damage if used with two hands,\
    \ plus 7 (2d6) necrotic damage. A creature reduced to 0 hit points from damage\
    \ dealt by the sword Void dies and can't be revived by any means short of a [wish](Mechanics/spells/wish.md)\
    \ spell."
  "name": "Void"
- "desc": "Ranged Spell Attack: +7 to hit, range 120 ft., one target. Hit: 12\
    \ (2d8 + 3) necrotic damage."
  "name": "Unholy Strike"
"reactions":
- "desc": "Aribeth adds 4 to her AC against one melee attack that would hit her. To\
    \ do so, Aribeth must see the attacker and be wielding a melee weapon."
  "name": "Parry"
"source":
- "MaBJoV"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/MaBJoV/Aribeth%20de%20Tylmarande.webp"
```
^statblock