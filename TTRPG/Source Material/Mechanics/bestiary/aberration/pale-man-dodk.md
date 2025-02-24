---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/dodk
- monster/cr/13
- monster/size/medium
- monster/type/aberration
statblock: inline
aliases: ["Pale Man"]
---
# [Pale Man](Mechanics\bestiary\aberration/pale-man-dodk.md)
*Source: Dungeons of Drakkenheim p. 212*  

Friedrich Von Lichten ambitiously explored the mutagenic effects of delerium after Drakkenheim's destruction, and was among the first to fully describe the effects of eldritch contamination upon the human body. He was ejected from the Amethyst Academy when it was discovered he was using apprentices as test subjects. So grave was his trespass, that the Academy notified the Silver Order of his existence, putting a death bounty on his head. Both The Silver Order and the Amethyst Academy have been searching for him since.

-     - **Personality Trait.** Witness my power, understand that I am the future. Some may call me a god, and I would not correct them.    
-     - **Ideal.** We must embrace the Haze, and allow contamination to change us, make us better.    
-     - **Bonds.** The Amethyst Academy lacks vision. I will show them the true power of delerium.    
-     - **Flaw.** It is not enough that I merely outsmart my foes, they must be shown their weakness and failure.    

Friedrich von Lichten has fully embraced contamination and transformed into a monster, and is now the Pale Man (see Appendix A of*Dungeons of Drakkenheim*for game statistics). He has maintained his intellect, and drapes his hunched and withered figure in a black cloak. Beneath his paper-thin skin are wriggling and writhing things. His lidless eyes are sunken, his teeth are prominent, yellowing and decaying. One can just make out a sickly green tongue that darts out when he speaks. He talks in a stunted, almost exasperated tone.

He presents his estate as a safehouse for the lost and forgotten.

The Pale Man sows the rumours that he can help contaminated people so he can use them as test subjects for his experiments. When he meets a transformed or contaminated creature, he presents himself as a helpful expert, offering to treat any individual left in his care. He never actually cures contamination, but sometimes helps other transformed monsters become somewhat lucid so he can make better use of them as minions. The Pale Man spends most of his time in the repurposed master bedroom of the estate he uses as his laboratory, and gives orders only to his most trusted thralls.

```statblock
"name": "Pale Man (DoDk)"
"size": "Medium"
"type": "aberration"
"alignment": "Neutral"
"ac": !!int "12"
"ac_class": "15 with [mage armor](Mechanics/spells/mage-armor.md)"
"hp": !!int "120"
"hit_dice": "16d8 + 48"
"stats":
- !!int "10"
- !!int "15"
- !!int "17"
- !!int "20"
- !!int "15"
- !!int "12"
"speed": "30 ft., climb 30 ft."
"saves":
  "Wisdom": !!int "7"
  "Intelligence": !!int "10"
  "Constitution": !!int "8"
"skillsaves":
  "Perception": !!int "7"
  "History": !!int "10"
  "Arcana": !!int "10"
"damage_resistances": "bludgeoning, piercing, slashing from nonmagical attacks"
"damage_immunities": "necrotic, poison"
"condition_immunities": "[charmed](Mechanics/Rules/conditions.md#Charmed), [frightened](Mechanics/Rules/conditions.md#Frightened),\
  \ [paralyzed](Mechanics/Rules/conditions.md#Paralyzed), [petrified](Mechanics/Rules/conditions.md#Petrified),\
  \ [poisoned](Mechanics/Rules/conditions.md#Poisoned), [restrained](Mechanics/Rules/conditions.md#Restrained)"
"senses": "darkvision 60 ft., passive Perception 15"
"languages": "Common and any 5 other languages"
"cr": "13"
"traits":
- "desc": "The Pale Man is a 16th-level spellcaster. Its spellcasting ability is Intelligence\
    \ (spell save DC 18, +10 to hit with spell attacks). The Pale Man has the following\
    \ wizard spells prepared:\n\nCantrips (at will): [chill touch](Mechanics/spells/chill-touch.md),\
    \ [mage hand](Mechanics/spells/mage-hand.md), [mending](Mechanics/spells/mending.md),\
    \ [prestidigitation](Mechanics/spells/prestidigitation.md), [shocking grasp](Mechanics/spells/shocking-grasp.md)\n\
    \n1st level (4 slots): [delerium orb](Mechanics/spells/delerium-orb-dodk.md),\
    \ [mage armor](Mechanics/spells/mage-armor.md), [magic missile](Mechanics/spells/magic-missile.md),\
    \ [shield](Mechanics/spells/shield.md)\n\n2nd level (3 slots): [hold person](Mechanics/spells/hold-person.md),\
    \ [invisibility](Mechanics/spells/invisibility.md), [warp bolt](Mechanics/spells/warp-bolt-dodk.md)\n\
    \n3rd level (3 slots): [counterspell](Mechanics/spells/counterspell.md), [lightning\
    \ bolt](Mechanics/spells/lightning-bolt.md), [purge contamination](Mechanics/spells/purge-contamination-dodk.md)\n\
    \n4th level (3 slots): [delerium blast](Mechanics/spells/delerium-blast-dodk.md),\
    \ [forced evolution](Mechanics/spells/forced-evolution-dodk.md)\n\n5th level\
    \ (3 slots): [conjure the deep haze](Mechanics/spells/conjure-the-deep-haze-dodk.md)\n\
    \n6th level (1 slots): [chain lightning](Mechanics/spells/chain-lightning.md),\
    \ [siphon contamination](Mechanics/spells/siphon-contamination-dodk.md)\n\n7th\
    \ level (1 slots): [octarine spray](Mechanics/spells/octarine-spray-dodk.md)\n\
    \n*8th level (1 slots): [antimagic field](Mechanics/spells/antimagic-field.md)\n\
    \nThese spells are from Appendix D of Dungeons of Drakkenheim."
  "name": "Spellcasting"
- "desc": "If the Pale Man fails a saving throw, it can choose to succeed instead."
  "name": "Legendary Resistance (3/Day)"
- "desc": "The Pale Man can occupy another creature's space and vice versa, and the\
    \ Pale Man can move through any opening large enough for a Tiny insect."
  "name": "Insect Body"
- "desc": "When the Pale Man is reduced to 0 hit points, it breaks apart into a swarm\
    \ of insects in the same space. Unless the swarm is destroyed, the Pale Man swarm\
    \ returns to its cocoon and reforms 1d6 days later."
  "name": "Crawling Flesh"
"actions":
- "desc": "Melee Spell Attack: +8 to hit, reach 10 ft., one target. Hit: 10\
    \ (3d6) necrotic damage, and the target must succeed on a DC 16 Constitution\
    \ saving throw or receive one level of contamination."
  "name": "Contaminating Touch"
- "desc": "Each creature within 30 feet of the Pale Man must succeed on a DC 16 Dexterity\
    \ saving throw or take 22 (5d8) necrotic damage and be [restrained](Mechanics/Rules/conditions.md#Restrained)\
    \ by masses of swarming fleshy bugs. The affected creature takes 22 (5d8) necrotic\
    \ damage at the start of each of the Pale Man's turns. The creature can repeat\
    \ the saving throw at the end of each of its turns, ending the effect on itself\
    \ on a success."
  "name": "Infest the Flesh (Recharge 6)"
"legendary_actions":
- "desc": "The Pale Man casts one cantrip."
  "name": "Cantrip (Costs 1 Action)"
- "desc": "The Pale Man moves its speed without provoking opportunity attacks."
  "name": "Slither (Costs 2 Actions)"
- "desc": "Each creature [restrained](Mechanics/Rules/conditions.md#Restrained) by\
    \ the Pale Man's Infest the Flesh must succeed on a DC 16 Constitution saving\
    \ throw or gain one level of contamination."
  "name": "Contaminate (Costs 3 Actions)"
"source":
- "DoDk"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/DoDk/Pale%20Man.webp"
```
^statblock