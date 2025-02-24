---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/mabjov
- monster/cr/8
- monster/size/medium
- monster/type/humanoid/human
aliases: ["Imoen"]
---
# Imoen
*Source: Minsc and Boo's Journal of Villainy p. 88*  

> [!quote] A quote from MINSC  
> 
> Boo has always liked Imoen. She's like his big sister. Though not as furry and a lot smaller.

Imoen is a Bhaalspawn and the half-sister of Abdel Adrian. She was his first companion when he set out from Candlekeep after witnessing the murder of his mentor. Imoen is naturally inquisitive and her expertise in lockpicking and stealth ensures that no secret is ever safe from her.

During her adventures with Abdel, Imoen was captured by the wizard Jon Irenicus who experimented on her, hoping to unlock the powers she unknowingly had as a Bhaalspawn. Irenicus managed to extract Imoen's divine blood and transfuse it with his sibling Bodhi. While Imoen escaped her brush with death, she no longer had the powers of a Bhaalspawn and her blood was contaminated with a vampire's.

This contamination made several changes in Imoen. She has elongated incisors that she takes pains to conceal. Her aging process has slowed down, extending her life by centuries. Despite learning of her heritage and becoming infected with the blood of a vampire, Imoen has managed to retain a sunny outlook. However, her reputation in Baldur's Gate as the child of a god of murder eventually forced her to relocate south to the city of Athkatla, where she joined the Shadow Thieves.

In her new home city Imoen has embraced the fact that she is a fusion of god, human and vampire. She has become an expert in all of those who struggle with their identity. Imoen is friendly and easygoing but has no patience for wickedness—and she's not afraid to show it.

## Imoen as a Contact

Imoen becomes available as a contact for members of the Shadow Thieves at 7th level. Imoen has uncovered secrets of transformation that she is willing to share if asked. Imoen does require a donation for the poor and downtrodden of Athkatla and Baldur's Gate. She will cure someone already infected with lycanthropy for free, but this is not the same as showing them how to better control their changes.

**Transformation Secrets from Imoen**

| Transformation | Required Level | Prerequisites | Cost |
|----------------|----------------|---------------|------|
| Blessing of Corellon (gender change) | 1 | – | 25 gp |
| Druidic reincarnation (race change) | 1 | – | 100 gp |
| Controlled lycanthropy—werewolf | 7 | Infected by a werewolf | 1000 gp |
| Controlled lycanthropy—weretiger | 9 | Infected by a weretiger | 2000 gp |
| Controlled lycanthropy—werebear | 9 | Infected by a werebear | 2000 gp |
^transformation-secrets-from-imoen

## Statblock

```ad-statblock
title: Imoen
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/MaBJoV/Imoen.webp#token)
*Medium humanoid (human), Neutral Good*

- **Armor Class** 16 ([studded leather](2-Mechanics/CLI/items/studded-leather-armor.md))
- **Hit Points** 156 (`24d8 + 48`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|11 (+0)|18 (+4)|14 (+2)|14 (+2)|10 (+0)|14 (+2)|

- **Proficiency Bonus** +3
- **Saving Throws** Dexterity +7, Intelligence +5
- **Skills** Acrobatics +7, Deception +5, Perception +3, Stealth +10
- **Senses** darkvision 60 ft., passive Perception 13
- **Damage Resistances** necrotic, poison
- **Languages** Common, Thieves' cant, Undercommon
- **Challenge** 8

## Traits

***Evasion.*** If Imoen is subjected to an effect that allows her to make a Dexterity saving throw to take only half damage, Imoen instead takes no damage if she succeeds on the saving throw, and only half damage if she fails.

***Sneak Attack (1/Turn).*** Imoen deals an extra `dice:4d6|noform|avg|text(14)` (`4d6`) damage when she hits a target with a weapon attack and has advantage on the attack roll, or when the target is within 5 feet of an ally of Imoen that isn't incapacitated and Imoen doesn't have disadvantage on the attack roll.

***Spider Climb.*** Imoen can climb difficult surfaces, including upside down on ceilings, without needing to make an ability check.

***Sunlight Sensitivity.*** While in sunlight, Imoen has disadvantage on attack rolls, as well as on Wisdom ([Perception](2-Mechanics/CLI/rules/skills.md#Perception)) checks that rely on sight.

## Actions

***Multiattack.*** Imoen makes two Shortsword attacks and one Hand Crossbow attack.

***Shortsword.*** *Melee Weapon Attack:* `dice:1d20+7|noform|text(+7)` to hit, reach 5 ft., one target. *Hit:* `dice:1d6+4|noform|avg|text(7)` (`1d6 + 4`) piercing damage plus `dice:1d6|noform|avg|text(3)` (`1d6`) poison damage.

***Hand Crossbow.*** *Ranged Weapon Attack:* `dice:1d20+7|noform|text(+7)` to hit, range 30/210 ft., one target. *Hit:* `dice:1d6+4|noform|avg|text(7)` (`1d6 + 4`) piercing damage plus `dice:3d6|noform|avg|text(10)` (`3d6`) poison damage.

## Bonus Actions

***Cunning Action.*** Imoen takes the Dash, Disengage, or Hide action.
```
^statblock