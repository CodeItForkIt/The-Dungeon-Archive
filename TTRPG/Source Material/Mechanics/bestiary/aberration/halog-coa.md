---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/coa
- monster/cr/7
- monster/size/small
- monster/type/aberration
statblock: inline
aliases: ["Halog"]
---
# [Halog](Mechanics\bestiary\aberration/halog-coa.md)
*Source: Chains of Asmodeus p. 242*  

There are few places more inhospitable than the Nine Hells, yet denizens from other places make a home even here. Not only the evil whose philosophy aligns with the devils, but simple creatures whose endurance and appetites permit them to survive the infernal realms. Often this means huge monsters strong enough to fight the native denizens, but some intruders pose a different kind of problem to the devils. Halogs seem small and weak compared to almost everything in the Nine Hells, yet they're becoming a serious nuisance across all the lower planes.

## Swarming Vermin

Halogs are around the size of a dog, and somewhere between a rat and a dog in appearance. Individually they're unprepossessing, often bearing burns, festering pustules, scars and other marks of a harsh environment that never seems able to quite kill them. They breed with formidable speed. Pairs of halogs raise litters of twenty which can mature in just a handful of days if sufficient food is on hand. And halogs eat anything. Their digestive juices alter in composition to permit them to devour infernal flesh as easily as that of mortal creatures, along with any kind of plant matter and even minerals. Only regions that are nothing but barren rock and dust offer nothing to them.

## Extraplanar Adaptations

Individually, halogs are weak, but as a species they're fearsomely hardy. Halogs seldom thrive in regions not requiring their unique adaptability, because of greater competition from other creatures. The hostile conditions of the lower planes mean that regular vermin and predators are lacking, leaving them their niche. The secret of the halogs' success is that the harsher their environment, the more they prosper. Whether heat, cold, acid, poison, or even pure necrotic energy—if it doesn't kill them outright then they swiftly adapt to feed off it. Halogs live among the flames of Phlegethos, the icy wastes of Stygia and the swamps of Minauros equally, and no devil city is free of their swarming presence no matter how the Fiends try to exterminate them. They even swim rat-like in the waters of the Styx. The vermin have a powerful defense mechanism. Their saliva and blood adapts swiftly in response to the vulnerabilities of their antagonists so that their bites inflict the worst harm, and anything trying to eat their flesh suffers for it. The remarkable upshot of this is that the halogs of the Nine Hells most often have teeth blazing with radiant divine energy, enough to make short work of unwary minor devils.

## Unexpected Allies

Despite their remarkable abilities and most common habitats, halogs are basically just animals. They're smart, but in the same way as a bright dog or a monkey. Druids, rangers, and other guardians of nature luckless enough to find themselves in the Nine Hells have been able to forge bonds with the creatures, and even muster them as impromptu scouts and sentries when travelling in the lower planes.

```statblock
"name": "Halog (CoA)"
"size": "Small"
"type": "aberration"
"alignment": "Unaligned"
"ac": !!int "14"
"ac_class": "natural armor"
"hp": !!int "150"
"hit_dice": "20d6 + 80"
"stats":
- !!int "13"
- !!int "14"
- !!int "18"
- !!int "4"
- !!int "8"
- !!int "8"
"speed": "40 ft."
"saves":
  "Dexterity": !!int "5"
  "Constitution": !!int "7"
"skillsaves":
  "Athletics": !!int "4"
  "Perception": !!int "2"
  "Survival": !!int "5"
"condition_immunities": "[poisoned](Mechanics/Rules/conditions.md#Poisoned)"
"senses": "darkvision 120 ft., passive Perception 12"
"languages": ""
"cr": "7"
"traits":
- "desc": "The halog magically alters its fangs to inflict more damage on the creatures\
    \ it hits (included in the attack)."
  "name": "Adaptive Fangs"
- "desc": "The halog has advantage on saving throws against spells and other magical\
    \ effects."
  "name": "Magic Resistance"
- "desc": "The halog gains advantage on attacks targeting creatures adjacent to one\
    \ or more of the halog's conscious allies."
  "name": "Pack Tactics"
"actions":
- "desc": "The halog makes two Bite attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 12\
    \ (3d6 + 2) piercing damage plus 10 (3d6) damage of a type that the target\
    \ is most vulnerable to."
  "name": "Bite"
"reactions":
- "desc": "After taking damage, the halog is now invulnerable to the damage type of\
    \ the damage it just took, and any future damage of that type instead heals the\
    \ halog by the damage amount. These benefits last until the halog uses this reaction\
    \ again."
  "name": "Adaptive Hide"
"source":
- "CoA"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/CoA/Halog.webp"
```
^statblock