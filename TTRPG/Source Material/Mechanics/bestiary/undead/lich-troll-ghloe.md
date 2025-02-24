---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/ghloe
- monster/cr/14
- monster/size/large
- monster/type/undead
statblock: inline
aliases: ["Lich Troll"]
---
# [Lich Troll](Mechanics\bestiary\undead/lich-troll-ghloe.md)
*Source: Grim Hollow: Lairs of Etharis p. 121*  

> [!quote]  
> 
> Running away from a troll is smart. Running away from a troll that casts spells is wishful thinking.

## Salvage

Someone who has proficiency with jeweler's tools or woodcarver's tools can fashion the skull of a lich troll into a ring of regeneration. Doing so takes materials worth 5,000 gp, 10 days of work, and a successful DC 15 Intelligence or Wisdom check. Somebody must also cast greater restoration on the ring each day during the process. If the ring's wearer dies while wearing the ring, the soul of the lich has a 25 percent chance to take over the corpse and use it as a new body. But if the ring is created entirely in the area of a hallow spell with the everlasting rest effect, the tie to the lich's soul is broken

## Lore

- **DC 15 Intelligence ([History](Mechanics/Rules/skills.md#History)).** The lich troll is remnants of early attempts of powerful spellcasters to transfer their souls into trolls.  
- **DC 20 Intelligence ([Arcana](Mechanics/Rules/skills.md#Arcana)).** The lich troll is immune to poison and resistant to necrotic damage. It regenerates and can be killed only by acid, fire, or radiant damage  

```statblock
"name": "Lich Troll (GHLoE)"
"size": "Large"
"type": "undead"
"alignment": "Chaotic Evil"
"ac": !!int "16"
"ac_class": "natural armor"
"hp": !!int "133"
"hit_dice": "14d10 + 56"
"stats":
- !!int "18"
- !!int "14"
- !!int "18"
- !!int "15"
- !!int "13"
- !!int "12"
"speed": "30 ft."
"saves":
  "Wisdom": !!int "6"
  "Intelligence": !!int "7"
  "Constitution": !!int "9"
"damage_resistances": "cold, necrotic"
"damage_immunities": "fire, poison"
"condition_immunities": "[charmed](Mechanics/Rules/conditions.md#Charmed), [exhaustion](Mechanics/Rules/conditions.md#Exhaustion),\
  \ [poisoned](Mechanics/Rules/conditions.md#Poisoned)"
"senses": "truesight 60 ft., passive Perception 16"
"languages": "the languages it knew in life and Giant"
"cr": "14"
"traits":
- "desc": "The lich troll is an 11th-level spellcaster. Its spellcasting ability is\
    \ Intelligence (spell save DC 15, +7 to hit with spell attacks). The lich troll\
    \ has the following wizard spells prepared:\n\nCantrips (at will): [chill\
    \ touch](Mechanics/spells/chill-touch.md), [mage hand](Mechanics/spells/mage-hand.md),\
    \ [prestidigitation](Mechanics/spells/prestidigitation.md), [ray of frost](Mechanics/spells/ray-of-frost.md)\n\
    \n1st level (4 slots): [detect magic](Mechanics/spells/detect-magic.md), [magic\
    \ missile](Mechanics/spells/magic-missile.md), [shield](Mechanics/spells/shield.md),\
    \ [thunderwave](Mechanics/spells/thunderwave.md)\n\n2nd level (3 slots): [detect\
    \ thoughts](Mechanics/spells/detect-thoughts.md), [invisibility](Mechanics/spells/invisibility.md),\
    \ [mirror image](Mechanics/spells/mirror-image.md), [misty step](Mechanics/spells/misty-step.md)\n\
    \n3rd level (3 slots): [animate dead](Mechanics/spells/animate-dead.md), [counterspell](Mechanics/spells/counterspell.md),\
    \ [dispel magic](Mechanics/spells/dispel-magic.md), [haste](Mechanics/spells/haste.md)\n\
    \n4th level (3 slots): [blight](Mechanics/spells/blight.md), [dimension door](Mechanics/spells/dimension-door.md)\n\
    \n5th level (2 slots): [cloudkill](Mechanics/spells/cloudkill.md), [scrying](Mechanics/spells/scrying.md)\n\
    \n6th level (1 slots): [create undead](Mechanics/spells/create-undead.md)"
  "name": "Spellcasting"
- "desc": "If the lich troll fails a saving throw, it can choose to succeed instead."
  "name": "Legendary Resistance (2/Day)"
- "desc": "The lich troll regains 15 hit points at the start of its turn. If the lich\
    \ troll takes acid or radiant damage, this trait doesn't function until the start\
    \ of the lich troll's next turn. The lich troll dies only if it starts its turn\
    \ with 0 hit points and doesn't regenerate."
  "name": "Regeneration"
"actions":
- "desc": "The lich troll makes two claw attacks. Alternately, the lich troll can\
    \ cast [chill touch](Mechanics/spells/chill-touch.md) or ray of frost twice."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +9 to hit, reach 5 ft., one target. Hit: 11\
    \ (2d6 + 4) slashing damage plus 7 (2d6) cold damage."
  "name": "Claw"
"legendary_actions":
- "desc": "The lich troll casts a cantrip."
  "name": "Cantrip"
- "desc": "The lich troll makes a claw attack."
  "name": "Claw"
"source":
- "GHLoE"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/GHLoE/Lich%20Troll.webp"
```
^statblock