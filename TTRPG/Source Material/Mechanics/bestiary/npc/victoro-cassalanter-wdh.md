---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/wdh
- monster/cr/10
- monster/size/medium
- monster/type/humanoid/half-elf
statblock: inline
aliases: ["Victoro Cassalanter"]
---
# [Victoro Cassalanter](Mechanics\bestiary\npc/victoro-cassalanter-wdh.md)
*Source: Waterdeep: Dragon Heist p. 218*  

The lord of House Cassalanter is a devilishly handsome half-elf who likes coin and power. He and his wife gained both by cutting a deal with Asmodeus-which involved trading away the souls of their three children.

Victoro is a priest of Asmodeus, though his devotion to the Lord of the Nine Hells is a secret known only to his wife and his closest friends. Most Waterdavians know him as a successful banker, philanthropist, and worshiper of Lathander. Some of his business profits go toward feeding and sheltering the poor. But behind this veneer of generosity, Victoro is a self-serving beast.

The soul of Victoro's eldest son, Osvaldo, is forever lost and can't be saved. To allay his guilt, Victoro has forged a plan to win back the souls of his young twins, Terenzio and Elzerina. Under the terms of the contract, their souls will be forfeit on their ninth birthdays, and that day is fast approaching. But Victoro can buy his way out of the obligation by providing, as the contract states, "one shy of a million gold coins and the sacrifice of one shy of a hundred unfortunate souls."

Victoro is well schooled, suave, slow to anger, and blessed with good health, long life, and immunity to disease. He dresses in the latest fashions and walks with a ruby-tipped cane, though not because he needs to. This cane has the magical properties of a rod of rulership.

```statblock
"name": "Victoro Cassalanter (WDH)"
"size": "Medium"
"type": "humanoid"
"subtype": "half-elf"
"alignment": "Lawful Evil"
"ac": !!int "15"
"ac_class": "[glamoured studded leather](Mechanics/items/glamoured-studded-leather.md),\
  \ [ring of protection](Mechanics/items/ring-of-protection.md)"
"hp": !!int "97"
"hit_dice": "15d8 + 30"
"stats":
- !!int "13"
- !!int "13"
- !!int "14"
- !!int "16"
- !!int "17"
- !!int "18"
"speed": "30 ft."
"saves":
  "Wisdom": !!int "7"
  "Constitution": !!int "6"
"skillsaves":
  "Religion": !!int "7"
  "Insight": !!int "7"
  "History": !!int "7"
  "Persuasion": !!int "8"
"damage_immunities": "poison"
"condition_immunities": "[poisoned](Mechanics/Rules/conditions.md#Poisoned)"
"senses": "darkvision 60 ft., passive Perception 13"
"languages": "Common, Draconic, Elvish, Infernal"
"cr": "10"
"traits":
- "desc": "Victoro is a 15th-level spellcaster. His spellcasting ability is Wisdom\
    \ (spell save DC 15, +7 to hit with spell attacks). Victoro has the following\
    \ cleric spells prepared:\n\nCantrips (at will): [guidance](Mechanics/spells/guidance.md),\
    \ [light](Mechanics/spells/light.md), [mending](Mechanics/spells/mending.md),\
    \ [spare the dying](Mechanics/spells/spare-the-dying.md), [thaumaturgy](Mechanics/spells/thaumaturgy.md)\n\
    \n1st level (4 slots): [charm person](Mechanics/spells/charm-person.md), [command](Mechanics/spells/command.md),\
    \ [detect magic](Mechanics/spells/detect-magic.md), [disguise self](Mechanics/spells/disguise-self.md),\
    \ [protection from evil and good](Mechanics/spells/protection-from-evil-and-good.md),\
    \ [sanctuary](Mechanics/spells/sanctuary.md)\n\n2nd level (3 slots): [augury](Mechanics/spells/augury.md),\
    \ [lesser restoration](Mechanics/spells/lesser-restoration.md), [mirror image](Mechanics/spells/mirror-image.md),\
    \ [pass without trace](Mechanics/spells/pass-without-trace.md), [spiritual weapon](Mechanics/spells/spiritual-weapon.md)\n\
    \n3rd level (3 slots): [blink](Mechanics/spells/blink.md), [clairvoyance](Mechanics/spells/clairvoyance.md),\
    \ [dispel magic](Mechanics/spells/dispel-magic.md), [magic circle](Mechanics/spells/magic-circle.md),\
    \ [protection from energy](Mechanics/spells/protection-from-energy.md)\n\n4th\
    \ level (3 slots): [banishment](Mechanics/spells/banishment.md), [dimension\
    \ door](Mechanics/spells/dimension-door.md), [divination](Mechanics/spells/divination.md),\
    \ [freedom of movement](Mechanics/spells/freedom-of-movement.md), [polymorph](Mechanics/spells/polymorph.md)\n\
    \n5th level (2 slots): [dominate person](Mechanics/spells/dominate-person.md),\
    \ [flame strike](Mechanics/spells/flame-strike.md), [modify memory](Mechanics/spells/modify-memory.md),\
    \ [insect plague](Mechanics/spells/insect-plague.md)\n\n6th level (1 slots):\
    \ [heal](Mechanics/spells/heal.md)\n\n7th level (1 slots): [divine word](Mechanics/spells/divine-word.md)\n\
    \n8th level (1 slots): [earthquake](Mechanics/spells/earthquake.md)"
  "name": "Spellcasting"
- "desc": "Victoro wears a [ring of protection](Mechanics/items/ring-of-protection.md)\
    \ and [glamoured studded leather](Mechanics/items/glamoured-studded-leather.md)\
    \ disguised to look like fine clothing. He carries a [rod of rulership](Mechanics/items/rod-of-rulership.md)\
    \ shaped like a ruby-tipped cane."
  "name": "Special Equipment"
- "desc": "Victoro has advantage on saving throws against being [charmed](Mechanics/Rules/conditions.md#Charmed),\
    \ and magic can't put him to sleep."
  "name": "Fey Ancestry"
- "desc": "Victoro can use an action to present the rod and command obedience from\
    \ each creature of his choice that he can see within 120 feet of him. Each target\
    \ must succeed on a DC 15 Wisdom saving throw or be [charmed](Mechanics/Rules/conditions.md#Charmed)\
    \ for 8 hours by Victoro. While [charmed](Mechanics/Rules/conditions.md#Charmed)\
    \ in this way, the creature regards Victoro as its trusted leader. If harmed by\
    \ Victoro or his companions, or commanded to do something contrary to its nature,\
    \ a target ceases to be [charmed](Mechanics/Rules/conditions.md#Charmed) in this\
    \ way. The rod can't be used again until the next dawn."
  "name": "Rod of Rulership"
"actions":
- "desc": "Victoro makes two attacks with his rapier."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 5 (1d8\
    \ + 1) piercing damage."
  "name": "Rapier"
- "desc": "Victoro becomes [invisible](Mechanics/Rules/conditions.md#Invisible) until\
    \ the end of his next turn. He becomes visible early immediately after he attacks\
    \ or casts a spell."
  "name": "Cloak of Shadows (2/Day)"
- "desc": "Victoro summons a [barbed devil](Mechanics/bestiary/fiend/barbed-devil.md).\
    \ The devil appears in an unoccupied space within 30 feet of Victoro, acts as\
    \ Victoro's ally, and can't summon other devils. It remains for 1 minute, until\
    \ it or Victoro dies, or until Victoro dismisses it as an action."
  "name": "Summon Devil (Recharges after 9 Days)"
"source":
- "WDH"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/WDH/Victoro%20Cassalanter.webp"
```
^statblock