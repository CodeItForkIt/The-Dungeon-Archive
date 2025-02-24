---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/mabjov
- monster/cr/23
- monster/size/large
- monster/type/aberration
statblock: inline
aliases: ["Ssendam, Lord of Madness"]
---
# [Ssendam, Lord of Madness](Mechanics\bestiary\npc/ssendam-lord-of-madness-mabjov.md)
*Source: Minsc and Boo's Journal of Villainy p. 107*  

> [!quote] A quote from Volo  
> 
> The lord of insanity is a difficult subject to find accurate information on. Mainly because most that encounter the primal slaad are left either catatonic, incoherent or psychotic. Ssendam is one of the two known slaadi lords, the other being Ygorl, lord of entropy. There are rumors of other slaadi that may rival the power of Ssendam and Ygorl. Netherese texts refer to them as void slaad and chronal slaad.

Ssendam is the Slaad Lord of Madness. She was born in the ancient days, when Primus, Lord of the Modrons, came to Limbo to bring order to chaos with his Spawning Stone. A shard of the Spawning Stone broke off in the god's hand and worked its way into his divine body. The wound made him feverish and clouded his thoughts; this was the first instance of what is now known as the chaos phage or "slaad fever".

Not wanting to bring the illness to his home plane of Mechanus, Primus purged himself before leaving Limbo. Not only did he expel the shard, but all the chaos that had touched his body, in a pile of vile excrement. Through the power of the Spawning Stone, this excrement transformed itself into the first slaad—Ssendam.

Ssendam is not interested in the realm of Limbo. Her only desire is to spread sickness and madness. To this end she travels to different mortal worlds, bringing with her the chaos phage. She has two forms, that of a golden amoeba or alternatively that of a golden slaad. As an amoeba, Ssendam moves through the waters of a mortal world, looking for a perfect host. When she finds that host, she allows her target to consume her by drinking water or wine. She then infects her host's mind and slowly turns them toward madness. This madness leads to an obsession with the slaad, the chaos phage, and Limbo.

Eventually, the host will find a way to bring slaad into their world. When there are enough of her kind, Ssendam completes her corruption of the host and transforms into her golden slaad form, utterly consuming her unfortunate living vessel. Her only goal after this transformation is spread the chaos phage to all corners of the world she now inhabits.

```statblock
"name": "Ssendam, Lord of Madness (MaBJoV)"
"size": "Large"
"type": "aberration"
"alignment": "Chaotic Evil"
"ac": !!int "19"
"ac_class": "natural armor"
"hp": !!int "299"
"hit_dice": "26d10 + 156"
"stats":
- !!int "20"
- !!int "24"
- !!int "22"
- !!int "20"
- !!int "18"
- !!int "26"
"speed": "30 ft., swim 30 ft."
"saves":
  "Charisma": !!int "15"
  "Dexterity": !!int "14"
  "Constitution": !!int "13"
"skillsaves":
  "Intimidation": !!int "15"
  "Deception": !!int "15"
  "Insight": !!int "18"
  "Perception": !!int "11"
  "Arcana": !!int "12"
"damage_resistances": "acid, cold, fire, lightning, thunder"
"damage_immunities": "necrotic; poison; bludgeoning, piercing, slashing from nonmagical\
  \ attacks"
"condition_immunities": "[charmed](Mechanics/Rules/conditions.md#Charmed), [exhaustion](Mechanics/Rules/conditions.md#Exhaustion),\
  \ [frightened](Mechanics/Rules/conditions.md#Frightened), [poisoned](Mechanics/Rules/conditions.md#Poisoned)"
"senses": "blindsight 60 ft., truesight 120 ft., passive Perception 21"
"languages": "all, telepathy 120 ft."
"cr": "23"
"traits":
- "desc": "Ssendam casts one of the following spells, requiring no material components\
    \ and using Charisma as the spellcasting ability (spell save DC 23):\n\nAt will:\
    \ [detect evil and good](Mechanics/spells/detect-evil-and-good.md), [detect magic](Mechanics/spells/detect-magic.md),\
    \ [detect thoughts](Mechanics/spells/detect-thoughts.md), [dispel magic](Mechanics/spells/dispel-magic.md),\
    \ [fear](Mechanics/spells/fear.md), [fly](Mechanics/spells/fly.md), [mass suggestion](Mechanics/spells/mass-suggestion.md),\
    \ [plane shift](Mechanics/spells/plane-shift.md)\n\n1/day each: [power word\
    \ kill](Mechanics/spells/power-word-kill.md), [power word stun](Mechanics/spells/power-word-stun.md)\n\
    \n2/day each: [finger of death](Mechanics/spells/finger-of-death.md), [flame\
    \ strike](Mechanics/spells/flame-strike.md)"
  "name": "Spellcasting"
- "desc": "Any creature (other than Undead or Constructs) that ends its turn within\
    \ 10 feet of Ssendam must succeed on a DC 20 Charisma saving throw or be inflicted\
    \ with a random short-term madness. If a creature succeeds against any madness\
    \ ability of Ssendam's, they are immune to Ssendam's madness for 1 hour."
  "name": "Aura of Madness"
- "desc": "If Ssendam fails a saving throw, she can choose to succeed instead."
  "name": "Legendary Resistance (3/Day)"
- "desc": "Ssendam has advantage on saving throws against spells and other magical\
    \ effects."
  "name": "Magic Resistance"
- "desc": "Ssendam's weapon attacks are magical."
  "name": "Magic Weapons"
- "desc": "Ssendam regains 40 hit points at the start of her turn if she has at least\
    \ 1 hit point."
  "name": "Regeneration (Golden Amoeba Form Only)"
"actions":
- "desc": "Ssendam makes three attacks: one with her Touch of Madness and two with\
    \ her Chaos Staff."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +12 to hit, reach 5 ft., one target. Hit: 10\
    \ (1d10 + 5) slashing damage plus 11 (2d10) necrotic damage. A target that\
    \ fails a DC 20 Charisma saving throw is inflicted with a random short-term madness.\
    \ If it is already mad, the existing madness is replaced with a random long-term\
    \ madness."
  "name": "Touch of Madness"
- "desc": "Melee Weapon Attack: +12 to hit, reach 5 ft., one target. Hit: 12\
    \ (2d6 + 5) bludgeoning damage plus 11 (2d10) necrotic damage. The target\
    \ must succeed on a DC 19 Constitution saving throw or have the [stunned](Mechanics/Rules/conditions.md#Stunned)\
    \ condition for 1 minute. The target may repeat the saving throw at the end of\
    \ each of their turns, ending the effect on a success."
  "name": "Chaos Staff"
- "desc": "Ssendam summons 1d4 + 1 [death slaadi](Mechanics/bestiary/aberration/death-slaad.md).\
    \ A summoned slaad appears in an unoccupied space within 60 feet of Ssendam, acts\
    \ as an ally of Ssendam, and can't summon other slaadi. It remains for 1 minute,\
    \ until it or Ssendam dies, or until Ssendam dismisses it as an action."
  "name": "Summon Slaadi (1/Day)"
- "desc": "Ssendam magically teleports, along with any equipment she is wearing or\
    \ carrying, up to 120 feet to an unoccupied space she can see."
  "name": "Teleport"
"bonus_actions":
- "desc": "Ssendam polymorphs into a Small or Medium-sized Humanoid, into a Small\
    \ Aberration that looks like a golden amoeba, or back into this, her golden slaad\
    \ form. Any equipment she is wearing or carrying isn't transformed. She reverts\
    \ to her true form if she dies. Her statistics in the Humanoid forms, other than\
    \ her size, are the same.\n\nWhile in her amoeba form, Ssendam also has the same\
    \ statistics with the following changes. She can't take any actions (except her\
    \ Change Shape action), speak, or manipulate objects. She has a movement speed\
    \ of 40 feet and can enter a hostile creature's space and stop there. In addition,\
    \ Ssendam can move through a space as narrow as 1 inch wide without squeezing.\
    \ She has advantage on Strength and Dexterity saving throws, and has resistance\
    \ to all damage except psychic and radiant."
  "name": "Change Shape"
"reactions":
- "desc": "When damaged, Ssendam uses her reaction to activate Change Shape to transform\
    \ into her golden amoeba form. Doing this reduces the damage to 0."
  "name": "Amoeba"
"legendary_actions":
- "desc": "Ssendam makes one Chaos Staff attack."
  "name": "Chaos Staff"
- "desc": "Ssendam uses her Teleport action."
  "name": "Teleport"
- "desc": "Ssendam forces every creature suffering from madness within 60 feet of\
    \ her to use their reaction to attack another creature within 5 feet of them."
  "name": "Subversion (Costs 2 Actions)"
"source":
- "MaBJoV"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/MaBJoV/Ssendam%2C%20Lord%20of%20Madness.webp"
```
^statblock