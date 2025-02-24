---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/25
- monster/environment/underdark
- monster/size/gargantuan
- monster/type/dragon
aliases: ["Ancient Cave Dragon"]
---
# Ancient Cave Dragon
*Source: Tome of Beasts 1 (2023 Edition) p. 113*  

*Covered in black spikes, the dragon's eyeless head swings from side to side. Darkness creeps from its strange, eel-like hide, spreading like ink in water.*

Apex predators of the underworld, cave dragons are the stuff of nightmare for creatures with little else to fear. They can speak, but they value silence, speaking rarely except when bargaining for food.

## Born to Darkness

Eyeless, these dragons have long, thin spikes that help them navigate tunnels or seal passages around them, preventing foes from outflanking them. Their stunted wings are little more than feelers, useful in rushing down tunnels. Their narrow snouts poke into tight passages, which their tongues scour free of bats and vermin. Young cave dragons and wyrmlings can fly, poorly, but older specimens lose the gift of flight. Cave dragon hide is more like eel skin than reptilian scales, and it grows mottled with brown and black as it ages.

## Ravenous Marauders

Cave dragons are always hungry and ready to eat everything. They devour undead, plant creatures, or anything organic. When feeding, they treat all nearby creatures as both a threat and the next course. Alliances they make only last so long as their allies make themselves scarce when the dragon feeds. They can be bribed with food as easily as with gold, but other attempts at diplomacy typically fail. Cave dragons do form alliances with peoples of the underworld, joining them in battle against enemies, but there is always a price to be paid in flesh, bone, and marrow. Wise allies keep a cave dragon well fed.

## A Hard Life

Limited food underground makes truly ancient cave dragons almost unheard of. The eldest tend to die of starvation after stripping their territory bare of prey. Their nigh-endless hunger leaves the ancients the most likely of cave dragons to form alliances, especially with allies that promise—and deliver—food. On occasion, cave dragons climb to the surface to feed, but their earthbound, plodding pace leaves them outcompeted by other predators or unable to keep up with swift or flying prey. They prefer tight tunnels where they can ambush and outmaneuver prey.

## Edible Hoards and Vertical Lairs

Due to the scarcity of food in their subterranean world, a cave dragon's hoard may consist largely of food sources: bat colonies, enormous beetles, carcasses in states of decay, a cavern infested with shriekers, and whatever else the dragon doesn't immediately devour. Cave dragons are fond of bones and items with strong taste or smell. Vast collections of bones, teeth, ivory, and the shells of huge insects litter their lairs, arranged like artful ossuaries. Large vertical chimneys serve as nesting sites for eggs and are popular resting places when a cave dragon sleeps within its lair. Chimneys just wide enough to hold young cave dragons make preferred ambush sites, as the dragons' tough spikes help hold them in position until prey passes beneath. The oldest cave dragons also retreat to vertical chimneys near nesting sites or within their lairs to die in peace. Stories claim that enormous treasures are heaped up in these ledges, abysses, and other inaccessible locations.

## A Cave Dragon's Lair

Labyrinthine systems of tunnels, caverns, and chasms make up the world of cave dragons. They claim miles of cave networks as their own. Depending on the depth of their domain, some consider the surface world their territory as well, though they visit only to eliminate potential rivals.

## Statblock

```ad-statblock
title: Ancient Cave Dragon
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Ancient%20Cave%20Dragon.webp#token)
*Gargantuan dragon, Neutral Evil*

- **Armor Class** 20 (natural armor)
- **Hit Points** 507 (`26d20 + 234`)
- **Speed** 40 ft., burrow 40 ft., climb 40 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|30 (+10)|12 (+1)|29 (+9)|14 (+2)|16 (+3)|18 (+4)|

- **Proficiency Bonus** +8
- **Saving Throws** Dexterity +9, Constitution +17, Wisdom +11, Charisma +12
- **Skills** Perception +19, Stealth +9
- **Senses** blindsight 60 ft., tremorsense 120 ft., passive Perception 29
- **Damage Immunities** poison
- **Condition Immunities** [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** Common, Darakhul, Draconic
- **Challenge** 25

## Traits

***Darkness Aura.*** The cave dragon emits magical darkness in a 30- foot radius around it. The darkness moves with the dragon and spreads around corners. Darkvision can't penetrate this darkness, and no natural light can illuminate it. If any of the darkness overlaps with an area of light created by a spell of 4th level or lower, the spell creating the light is dispelled. At the start of each of its turns, the dragon chooses whether this aura is active. A successful [dispel magic](2-Mechanics/CLI/spells/dispel-magic.md) (DC 15) cast on the dragon suppresses this aura for 1 minute.

***Legendary Resistance (3/Day).*** If the dragon fails a saving throw, it can choose to succeed instead.

***Magical Tunneler.*** The cave dragon can burrow through any unworked earth and stone. While doing so, the dragon can choose whether to leave the material it moves through undisturbed or leave a 15-foot diameter tunnel in its wake.

***Spiked Climb.*** The dragon uses its spikes to hold itself in place while climbing, allowing it to climb difficult surfaces, including upside down on ceilings, without needing to make an ability check. If it climbs upside down on a ceiling or suspends itself on a vertical surface while leaving its claws free, it can't use the Ruff Spikes reaction.

## Actions

***Multiattack.*** The dragon uses its Frightful Presence. It then makes three attacks: one with its Bite and two with its Claws.

***Bite.*** *Melee Weapon Attack:* `dice:1d20+18|noform|text(+18)` to hit, reach 15 ft., one target. *Hit:* `dice:2d10+10|noform|avg|text(21)` (`2d10 + 10`) piercing damage plus `dice:4d6|noform|avg|text(14)` (`4d6`) poison damage.

***Claw.*** *Melee Weapon Attack:* `dice:1d20+18|noform|text(+18)` to hit, reach 10 ft., one target. *Hit:* `dice:2d6+10|noform|avg|text(17)` (`2d6 + 10`) slashing damage.

***Tail.*** *Melee Weapon Attack:* `dice:1d20+18|noform|text(+18)` to hit, reach 20 ft., one target. *Hit:* `dice:2d8+10|noform|avg|text(19)` (`2d8 + 10`) bludgeoning damage.

***Frightful Presence.*** Each creature of the dragon's choice that is within 120 feet of the dragon and aware of it must succeed on a DC 20 Wisdom saving throw or become [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened) for 1 minute. A creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success. If a creature's saving throw is successful or the effect ends for it, the creature is immune to the dragon's Frightful Presence for the next 24 hours.

***Poison Breath (Recharge 5-6).*** The dragon exhales a cone of black, poisonous gas in a 90-foot cone. Each target in that area must make a DC 25 Constitution saving throw. On a failure, a creature takes `dice:26d6|noform|avg|text(91)` (`26d6`) poison damage and is [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) until cured by the [greater restoration](2-Mechanics/CLI/spells/greater-restoration.md) spell or similar magic. On a success, a creature takes half the damage and isn't [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned).

## Reactions

***Ruff Spikes.*** When a creature moves to a space within 10 feet of the cave dragon, the dragon flares its many feelers and spikes. The creature must succeed on a DC 25 Dexterity saving throw or take `dice:3d8|noform|avg|text(13)` (`3d8`) piercing damage and be prevented from entering that space.

## Legendary Actions

***Detect.*** The dragon makes a Wisdom ([Perception](2-Mechanics/CLI/rules/skills.md#Perception)) check.

***Tail Attack.*** The dragon makes a Tail attack.

***Limb Sweep (Costs 2 Actions).*** The dragon sweeps its wingless limbs outward. Each creature within 10 feet of the dragon must succeed on a DC 25 Dexterity saving throw or take `dice:2d6+8|noform|avg|text(15)` (`2d6 + 8`) bludgeoning damage and be pushed up to 10 feet away from the dragon and knocked [prone](2-Mechanics/CLI/rules/conditions.md#Prone).

![Cave Dragon](2-Mechanics/CLI/bestiary/legendary-group/cave-dragon-tob1-2023.md)
```
^statblock

## Environment

underdark