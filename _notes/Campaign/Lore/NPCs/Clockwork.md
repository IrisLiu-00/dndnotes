---
tags:
  - NPC
Location:
  - Kevara-Arda
Last Edited: 2023-10-14T17:14
---
chain (range 10ft slashing)

abilities: plant time bomb (time stop), rewind (reaction to reroll, have to take the new result)

protection from energy?, dispel magic, summon construct

# Notes

- Tiefling bounty hunter. Reddish skin, lanky, black reflective sunglasses, black leather jacket. One horn cleanly sheared off. Spiked cuffs connect to pocket watch + chain.
- James (team rocket) voice, over the top, unhinged, anime villain
- Chasing rumors of a tiefling caster Indira who brought infernal secrets beyond Apostasy
    - Indira Ashoor: lawyer specializing in contract law magic. Working w Konrad Luca / Avizallo to develop logic trees + moral contracts in automata OR (then?) working w the rebel elves to litigate covenants
    - she helped Coriolis, so is being pursued?
- Was an excellent watchmaker who turned to explosives + murder
- Has a younger sister

- probably increase dmg the next time they meet him, inc ac?
  
```
{
	"name": "Clockwork (Bounty Hunter)",
	"size": [
		"M"
	],
	"type": "humanoid",
	"source": "Huskies",
	"alignment": [
		"C",
		"N"
	],
	"ac": [
		{
			"ac": 14,
			"from": [
				"Leather armor"
			]
		}
	],
	"hp": {
		"special": "120"
	},
	"speed": {
		"walk": 30
	},
	"str": 12,
	"dex": 16,
	"con": 14,
	"int": 10,
	"wis": 8,
	"cha": 14,
	"passive": 9,
	"cr": "4",
	"level": 7,
	"save": {
		"dex": "+6",
		"cha": "+5"
	},
	"skill": {
		"deception": "+5",
		"athletics": "+4"
	},
	"resist": [
		"fire"
	],
	"senses": [
		"darkvision 30 ft."
	],
	"senseTags": [
		"D"
	],
	"spellcasting": [
		{
			"name": "Spellcasting",
			"headerEntries": [
				"Attack +5, Save {@dc 13}"
			],
			"spells": {
				"3": {
					"spells": [
						"{@spell dispel magic}"
					],
					"slots": 3
				},
				"4": {
					"spells": [
						"{@spell summon construct|TCE}"
					],
					"slots": 1
				}
			},
			"type": "spellcasting"
		}
	],
	"spellcastingTags": [
		"O"
	],
	"action": [
		{
			"name": "Chain",
			"entries": [
				"2 attacks with chain. {@atk mw} {@hit 6} to hit, reach 10 ft., one target. {@h}15 ({@damage 2d6 + 9}) slashing damage. Bonus action STR contest to be pulled 20ft. "
			]
		},
		{
			"name": "Stasis Charge",
			"entries": [
				"(3/day) Throw a bomb with 20ft radius, center within 30ft of you. All targets within must make a WIS save {@dc 13} or be frozen in time ({@condition paralyzed}) until the end of Clockwork's next turn. "
			]
		}
	],
	"miscTags": [
		"MW",
		"RCH"
	],
	"reaction": [
		{
			"name": "Chronal Shift",
			"entries": [
				"(2/day) After you or a creature you can see within 30 feet of you makes an attack roll, an ability check, or a saving throw, you can force the creature to reroll. You make this decision after you see whether the roll succeeds or fails. The target must use the result of the second roll."
			]
		}
	],
	"bonus": [
		{
			"name": "Time Bomb",
			"entries": [
				"(4/day) Throw a detonator with range 30ft, radius 10ft. At the end of Clockwork's next turn, the bomb goes off for {@dice 2d6} fire dmg (DEX save 13 for half)."
			]
		}
	],
	"damageTags": [
		"S"
	]
}
```