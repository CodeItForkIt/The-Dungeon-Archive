---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/psi
- monster/cr/11
- monster/size/medium
- monster/type/celestial
statblock: inline
aliases: ["Flight Goldnight Angel"]
---
# [Flight Goldnight Angel](Mechanics\bestiary\celestial/flight-goldnight-angel-psi.md)
*Source: Plane Shift: Innistrad p. 26*  

[Avacyn](Mechanics/bestiary/npc/avacyn-psi.md) was the archangel of Innistrad, revered across the plane as the source of hope, of protection, and of the Blessed Rest—a peaceful eternity of slumber in the grave. She offered the faithful magical wards against vampires and werewolves, a tranquil oblivion rather than the damned fate of a tormented spirit or undead abomination, and a distant hope that someday, their descendants might live in an Innistrad free from all the horrors of darkness.

Traditionally, three groups of angels known as flights or hosts served [Avacyn](Mechanics/bestiary/npc/avacyn-psi.md), each under the leadership of a lesser archangel.

## Flight Alabaster

The practical and sympathetic angels of Flight Alabaster were instrumental in maintaining Avacyn's wards against the supernatural evils of Innistrad. They preferred the use of spells to weapons, and engaged in battle only when they had exhausted other options. As a result, angels of other flights sometimes dismissed them as overly sentimental. Alabaster angels aided priests and cathars in maintaining the protective wards on city walls and at holy sites throughout the plane, and also aided Avacyn in conducting the spirits of the dead to their ultimate fate, dissolving into Innistrad's Æthereal essence. The leader of Flight Alabaster was [Bruna](Mechanics/bestiary/npc/bruna-psi.md), called the Light of Alabaster.

## Host of Herons

The Host of Herons comprised the angels of birth, rebirth, and purity, whose magic was said to ward humans against harm in life. This was always the smallest flight of angels, and its primary function was the scouting and tracking of werewolves and other marauding monsters. [Sigarda](Mechanics/bestiary/npc/sigarda-psi.md) led the Host of Herons, wielding a scythe shaped like the head of a heron.

## Flight Goldnight

Flight Goldnight was an army of soldier-angels focused on the martial strength of the church. These angels were characterized by pragmatism and strict observance of church law. They were strategists in battle and skillful leaders during armed conflicts, cultivating a martial mindset that made them more than willing to take up arms when the need arose. The leader of Flight Goldnight was [Gisela](Mechanics/bestiary/npc/gisela-psi.md), called the Blade of Goldnight or the Blade of the Church.

## The Madness of Avacyn

When the Eldrazi titan Emrakul first approached Innistrad, [Avacyn](Mechanics/bestiary/npc/avacyn-psi.md) perceived her influence as a contagion that must be expunged from the world. However, unable to identify the source of that contagion, [Avacyn](Mechanics/bestiary/npc/avacyn-psi.md) was driven mad, lashing out instead at every living thing. She led the angels in a vain effort to purge this corruption from the plane, viewing the humans they once protected as part of the maddening illness. The different flights of angels even began to war against each other, drastically reducing the number of angels on the plane.

Wielding fiery swords and clad in full armor, the soldier-angels of Flight Goldnight became the scourge of all mortal life on Innistrad. None could predict what would trigger their violent judgment or where they would strike next. The angels of Flight Alabaster had always been at the forefront of the church's efforts to root out and punish demon cultists, necromancers, and other heretics. With Emrakul's approach, they grew at least as mad as [Avacyn](Mechanics/bestiary/npc/avacyn-psi.md) herself. Their fervent obsession drove the forces of the Lunarch Inquisition, the church's efforts to root out sin among the human populace. The angels prodded the church to ever greater and more desperate action.

Amid the chaos, [Avacyn](Mechanics/bestiary/npc/avacyn-psi.md) created a new angelic flight to serve as her honor guard. Armed with moonsilver spears forged from shards of the broken Helvault, these angels of the Flight of Moonsilver served as sentries and guards at Thraben Cathedral, and flew alongside [Avacyn](Mechanics/bestiary/npc/avacyn-psi.md) into battle against any perceived threat to Innistrad.

Only [Sigarda](Mechanics/bestiary/npc/sigarda-psi.md) and the Host of Herons remained unaffected by Avacyn's madness, perhaps because they were the angels of purity. The survivors of this host retreated to their old haunt in Gavony's remote parish of Videns to maintain a safe distance from [Avacyn](Mechanics/bestiary/npc/avacyn-psi.md).

Angels that have gone mad can cast [flame strike](Mechanics/spells/flame-strike.md) once per day using their Innate Spellcasting trait. Additionally, the extra damage from their Angelic Weapons is half fire damage and half radiant damage.

```statblock
"name": "Flight Goldnight Angel (PSI)"
"size": "Medium"
"type": "celestial"
"alignment": "Lawful Good"
"ac": !!int "17"
"ac_class": "natural armor"
"hp": !!int "136"
"hit_dice": "16d8 + 64"
"stats":
- !!int "18"
- !!int "18"
- !!int "18"
- !!int "17"
- !!int "20"
- !!int "20"
"speed": "30 ft., fly 90 ft."
"saves":
  "Charisma": !!int "9"
  "Wisdom": !!int "9"
"skillsaves":
  "Insight": !!int "9"
  "Perception": !!int "9"
"damage_resistances": "radiant; bludgeoning, piercing, slashing from nonmagical attacks"
"condition_immunities": "[charmed](Mechanics/Rules/conditions.md#Charmed), [exhaustion](Mechanics/Rules/conditions.md#Exhaustion),\
  \ [frightened](Mechanics/Rules/conditions.md#Frightened)"
"senses": "darkvision 120 ft., passive Perception 19"
"languages": "all, telepathy 120 ft."
"cr": "11"
"traits":
- "desc": "The angel's spellcasting ability is Charisma (spell save DC 17). The angel\
    \ can innately cast the following spells, requiring only verbal components:\n\n\
    At will: [detect evil and good](Mechanics/spells/detect-evil-and-good.md)\n\
    \n1/day each: [commune](Mechanics/spells/commune.md), [raise dead](Mechanics/spells/raise-dead.md)"
  "name": "Innate Spellcasting"
- "desc": "The angel's weapon attacks are magical. When the angel hits with any weapon,\
    \ the weapon deals an extra 4d8 radiant damage (included in the attack)."
  "name": "Angelic Weapons"
- "desc": "The angel has advantage on saving throws against spells and other magical\
    \ effects."
  "name": "Magic Resistance"
- "desc": "As an action, an angel of Flight Goldnight can strike fear into the hearts\
    \ of its enemies. Each creature of the angel's choice that is within 120 feet\
    \ of it and is aware of it must succeed on a Wisdom saving throw or become [frightened](Mechanics/Rules/conditions.md#Frightened)\
    \ for 1 minute. The DC for this saving throw is the same as for the angel's Innate\
    \ Spellcasting trait. A creature can repeat the saving throw at the end of each\
    \ of its turns, ending the effect on itself on a success. If a creature's saving\
    \ throw is successful or the effect ends for it, the creature is immune to that\
    \ angel's Goldnight Menace for the next 24 hours."
  "name": "Goldnight Menace"
"actions":
- "desc": "The angel makes two melee attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +8 to hit, reach 5 ft., one target. Hit: 7 (1d6\
    \ + 4) bludgeoning damage plus 18 (4d8) radiant damage."
  "name": "Mace"
- "desc": "The angel touches another creature. The target magically regains 20 (4d8\
    \ + 2) hit points and is freed from any curse, disease, poison, blindness, or\
    \ deafness."
  "name": "Healing Touch (3/Day)"
- "desc": "The angel magically polymorphs into a humanoid or beast that has a challenge\
    \ rating equal to or less than its own, or back into its true form. It reverts\
    \ to its true form if it dies. Any equipment it is wearing or carrying is absorbed\
    \ or borne by the new form (the angel's choice).\n\nIn a new form, the angel retains\
    \ its game statistics and ability to speak, but its AC, movement modes, Strength,\
    \ Dexterity, and special senses are replaced by those of the new form, and it\
    \ gains any statistics and capabilities (except class features, legendary actions,\
    \ and lair actions) that the new form has but that it lacks."
  "name": "Change Shape"
"source":
- "PSI"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/PSI/Flight%20Goldnight%20Angel.webp"
```
^statblock