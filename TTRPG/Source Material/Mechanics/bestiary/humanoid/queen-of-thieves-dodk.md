---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/dodk
- monster/cr/15
- monster/size/medium
- monster/type/humanoid
statblock: inline
aliases: ["Queen of Thieves"]
---
# [Queen of Thieves](Mechanics\bestiary\humanoid/queen-of-thieves-dodk.md)
*Source: Dungeons of Drakkenheim p. 217*  

> [!quote] A quote from The Queen of Thieves.  
> 
> Who I am is not as important as what I am. I am quicker than thought, more silent than contemplation, more slippery than a fading memory, and more unshakable than a guilty conscience. I deal in secrets and mendacity as lesser thieves deal in coins and larceny. I can fulfil your wildest dreams, or I can be your worst nightmare.

The Queen of Thieves is a scheming mastermind who controls the Drakkenheim underworld. She has transformed a hundred squabbling bands of brigands and outlaws into a burgeoning criminal empire. However, none know her true identity or origin, for she wears many faces. Though she is most infamously encountered as a lithe masked woman garbed in swashbuckling attire with a wide-brimmed hat and jewelled rapier, the Queen of Thieves adopts a variety of costumes, facial features, skin and hair colours, body shapes, ages, and genders depending on her mood and circumstances. As such, she typically confirms her identity by revealing some secret about whoever she is speaking with or demonstrating her uncanny ability to change appearance seemingly at-will.

-     - **Personality Trait.** I am never caught unprepared, and have contingencies for my contingencies. I speak with rakish confidence while casually exposing everything I know about others, and flaunt my ability to be anybody or anywhere.    
-     - **Ideal.** I indulge in playing mind games and manipulating people with the promise of profit. Instead of spilling blood, I spill secrets. My enemies are worthless as corpses. When I have to steal lives, I spend them dearly first.    
-     - **Bond.** Law is powerless in the chaos of the ruins. As long as anarchy reigns, so shall I.    
-     - **Flaw.** Anyone who trusts me is a terrible fool. Double-crossing is my nature. I expect everyone to betray me, and I'll relish the opportunity to defeat them when they try.    

Few amongst the Queen's Men have met the Queen of Thieves in person, and even fewer have attended the Court of Thieves. Most only know if they get a note attached to a Queen of Diamonds playing card, you better do what it says.

```statblock
"name": "Queen of Thieves (DoDk)"
"size": "Medium"
"type": "humanoid"
"alignment": "Neutral Evil"
"ac": !!int "23"
"ac_class": "canny defense, [mage armor](Mechanics/spells/mage-armor.md)"
"hp": !!int "120"
"hit_dice": "20d8 + 20"
"stats":
- !!int "10"
- !!int "20"
- !!int "13"
- !!int "20"
- !!int "16"
- !!int "19"
"speed": "30 ft."
"saves":
  "Dexterity": !!int "10"
  "Intelligence": !!int "10"
"skillsaves":
  "Sleight of Hand": !!int "10"
  "Deception": !!int "14"
  "Stealth": !!int "15"
  "Insight": !!int "8"
  "Perception": !!int "8"
  "Acrobatics": !!int "10"
  "Arcana": !!int "10"
  "Persuasion": !!int "9"
"condition_immunities": "[charmed](Mechanics/Rules/conditions.md#Charmed)"
"senses": "darkvision 60 ft., passive Perception 18"
"languages": "Common, Dwarvish, Elvish, Undercommon"
"cr": "15"
"traits":
- "desc": "The Queen of Thieves' innate spellcasting ability is Intelligence. She\
    \ can innately cast the following spells, requiring no material, somatic, or verbal\
    \ components:\n\nAt will: [detect thoughts](Mechanics/spells/detect-thoughts.md),\
    \ [disguise self](Mechanics/spells/disguise-self.md), [suggestion](Mechanics/spells/suggestion.md)"
  "name": "Innate Spellcasting"
- "desc": "The Queen of Thieves is a 20th-level spellcaster. Her spellcasting ability\
    \ is Intelligence (spell save DC 18, +10 to hit with spell attacks). She has\
    \ the following wizard spells prepared:\n\nCantrips (at will): [chill touch](Mechanics/spells/chill-touch.md),\
    \ [mage hand](Mechanics/spells/mage-hand.md), [message](Mechanics/spells/message.md),\
    \ [minor illusion](Mechanics/spells/minor-illusion.md), [prestidigitation](Mechanics/spells/prestidigitation.md)\n\
    \n1st level (4 slots): [feather fall](Mechanics/spells/feather-fall.md), [mage\
    \ armor](Mechanics/spells/mage-armor.md), [shield](Mechanics/spells/shield.md),\
    \ [sleep](Mechanics/spells/sleep.md)\n\n2nd level (3 slots): [mirror image](Mechanics/spells/mirror-image.md),\
    \ [misty step](Mechanics/spells/misty-step.md), [see invisibility](Mechanics/spells/see-invisibility.md)\n\
    \n3rd level (3 slots): [gaseous form](Mechanics/spells/gaseous-form.md), [hypnotic\
    \ pattern](Mechanics/spells/hypnotic-pattern.md), [major image](Mechanics/spells/major-image.md)\n\
    \n4th level (3 slots): [dimension door](Mechanics/spells/dimension-door.md),\
    \ [greater invisibility](Mechanics/spells/greater-invisibility.md), [polymorph](Mechanics/spells/polymorph.md)\n\
    \n5th level (3 slots): [dominate person](Mechanics/spells/dominate-person.md),\
    \ [scrying](Mechanics/spells/scrying.md), [seeming](Mechanics/spells/seeming.md)\n\
    \n6th level (2 slots): [eyebite](Mechanics/spells/eyebite.md), [mass suggestion](Mechanics/spells/mass-suggestion.md)\n\
    \n7th level (2 slots): [forcecage](Mechanics/spells/forcecage.md), [project\
    \ image](Mechanics/spells/project-image.md)\n\n8th level (1 slots): [feeblemind](Mechanics/spells/feeblemind.md)\n\
    \n9th level (1 slots): [foresight](Mechanics/spells/foresight.md)"
  "name": "Spellcasting"
- "desc": "The Queen of Thieves wears an [amulet of proof against detection and location](Mechanics/items/amulet-of-proof-against-detection-and-location.md)\
    \ and a [spymaster's signet](Mechanics/items/spymasters-signet-dodk.md). She wields\
    \ a [+3 rapier](Mechanics/items/3-weapon.md)."
  "name": "Special Equipment"
- "desc": "While the Queen of Thieves is wearing light or no armour and wielding no\
    \ shield, her AC includes her Intelligence modifier."
  "name": "Canny Defense"
- "desc": "The Queen of Thieves deals an extra 18 5d6 damage when she hits a target\
    \ with a weapon attack and has advantage on the attack roll, or when the target\
    \ is within 5 feet of an ally of the Queen of Thieves that isn't incapacitated\
    \ and she doesn't have disadvantage on the attack roll."
  "name": "Sneak Attack (1/Turn)"
- "desc": "If the Queen of Thieves fails a saving throw, she can choose to succeed\
    \ instead."
  "name": "Legendary Resistance (3/Day)"
- "desc": "Creatures are not aware when the Queen of Thieves reads their thoughts\
    \ or charms them. Additionally, when a spell cast by the Queen of Thieves that\
    \ causes creatures to become [charmed](Mechanics/Rules/conditions.md#Charmed)\
    \ ends, she can make the affected creatures lose their memories. They must succeed\
    \ on a DC 18 Intelligence saving throw or forget up to 8 hours of the time spent\
    \ [charmed](Mechanics/Rules/conditions.md#Charmed) by her. These memories can\
    \ be restored with a [heal](Mechanics/spells/heal.md) spell or similar magic."
  "name": "Memory Thief"
"actions":
- "desc": "Melee Weapon Attack: +13 to hit, reach 5 ft., one target Hit: 13\
    \ (1d8 + 8) piercing damage."
  "name": "+3 Rapier"
- "desc": "Ranged Weapon Attack: +10 to hit, range 20/60 ft., one target. Hit:\
    \ 7 (1d4 + 7) piercing damage."
  "name": "Dagger"
"reactions":
- "desc": "When she would take damage, the Queen of Thieves becomes [invisible](Mechanics/Rules/conditions.md#Invisible)\
    \ and teleports 60 feet to an unoccupied space she can see. At the same time,\
    \ an illusory double of her appears where she was standing and lasts for 1 minute.\
    \ The invisibility ends if the Queen of Thieves attacks or casts a spell, or after\
    \ 1 minute."
  "name": "Misdirection"
"legendary_actions":
- "desc": "The Queen of Thieves makes one melee or ranged attack."
  "name": "Attack"
- "desc": "The Queen of Thieves moves up to her speed without provoking opportunity\
    \ attacks."
  "name": "Move"
"source":
- "DoDk"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/DoDk/Queen%20of%20Thieves.webp"
```
^statblock