---
obsidianUIMode: preview
cssclasses: json5e-item
tags:
- compendium/src/5e/dmg
- item/attunement/required
- item/rarity/legendary
- item/tier/major
- item/weapon/simple
aliases: 
- "Staff of the Magi"
---
# Staff of the Magi
*Staff, weapon, major, legendary (requires attunement by a sorcerer, warlock, or wizard)*  

- **Damage**:
  - One-handed: 1d6 B
  - Two-handed: 1d8 B
- **Properties**: [Versatile](2-Mechanics/CLI/rules/item-properties.md#Versatile)
- **Weight**: 4.0 lbs.

This staff can be wielded as a magic quarterstaff that grants a +2 bonus to attack and damage rolls made with it. While you hold it, you gain a +2 bonus to spell attack rolls.

The staff has 50 charges for the following properties. It regains `dice:4d6+2|noform|avg` (`4d6 + 2`) expended charges daily at dawn. If you expend the last charge, roll a `dice:d20|noform|avg` (`d20`). On a 20, the staff regains `dice:1d12+1|noform|avg` (`1d12 + 1`) charges.

## Spell Absorption

While holding the staff, you have advantage on saving throws against spells. In addition, you can use your reaction when another creature casts a spell that targets only you. If you do, the staff absorbs the magic of the spell, canceling its effect and gaining a number of charges equal to the absorbed spell's level. However, if doing so brings the staff's total number of charges above 50, the staff explodes as if you activated its retributive strike (see below).

## Spells

While holding the staff, you can use an action to expend some of its charges to cast one of the following spells from it, using your spell save DC and spellcasting ability: [conjure elemental](2-Mechanics/CLI/spells/conjure-elemental.md) (7 charges), [dispel magic](2-Mechanics/CLI/spells/dispel-magic.md) (3 charges), [fireball](2-Mechanics/CLI/spells/fireball.md) (7th-level version, 7 charges), [flaming sphere](2-Mechanics/CLI/spells/flaming-sphere.md) (2 charges), [ice storm](2-Mechanics/CLI/spells/ice-storm.md) (4 charges), [invisibility](2-Mechanics/CLI/spells/invisibility.md) (2 charges), [knock](2-Mechanics/CLI/spells/knock.md) (2 charges), [lightning bolt](2-Mechanics/CLI/spells/lightning-bolt.md) (7th-level version, 7 charges), [passwall](2-Mechanics/CLI/spells/passwall.md) (5 charges), [plane shift](2-Mechanics/CLI/spells/plane-shift.md) (7 charges), [telekinesis](2-Mechanics/CLI/spells/telekinesis.md) (5 charges), [wall of fire](2-Mechanics/CLI/spells/wall-of-fire.md) (4 charges), or [web](2-Mechanics/CLI/spells/web.md) (2 charges).

You can also use an action to cast one of the following spells from the staff without using any charges: [arcane lock](2-Mechanics/CLI/spells/arcane-lock.md), [detect magic](2-Mechanics/CLI/spells/detect-magic.md), [enlarge/reduce](2-Mechanics/CLI/spells/enlarge-reduce.md), [light](2-Mechanics/CLI/spells/light.md), [mage hand](2-Mechanics/CLI/spells/mage-hand.md), or [protection from evil and good](2-Mechanics/CLI/spells/protection-from-evil-and-good.md).

## Retributive Strike

You can use an action to break the staff over your knee or against a solid surface, performing a retributive strike. The staff is destroyed and releases its remaining magic in an explosion that expands to fill a 30-foot-radius sphere centered on it.

You have a 50 percent chance to instantly travel to a random plane of existence, avoiding the explosion. If you fail to avoid the effect, you take force damage equal to 16 × the number of charges in the staff. Every other creature in the area must make a DC 17 Dexterity saving throw. On a failed save, a creature takes an amount of damage based on how far away it is from the point of origin, as shown in the following table. On a successful save, a creature takes half as much damage.

| Distance from Origin | Damage |
|----------------------|--------|
| 10 ft. away or closer | 8 × the number of charges in the staff |
| 11 to 20 ft. away | 6 × the number of charges in the staff |
| 21 to 30 ft. away | 4 × the number of charges in the staff |
^distance-from-origin-damage

*Source: Dungeon Master's Guide p. 203. Available in the <span title='Systems Reference Document (5.1)'>SRD</span>*