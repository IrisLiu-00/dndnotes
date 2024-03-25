---
tags:
  - NPC
Location:
  - Candlekeep
  - Traveller
Last Edited: 2022-11-17T22:30
---
- Human bard
- Travels with Lyell to help with his research
- Personality - drunkard, frat bro
- Voice - deep, booming
- Good friends with the party
- Eternally gets no bitches
- Went to state school uni 


```
{
	"name": "Ringley",
	"source": "Huskies",
	"page": 59,
	"size": [
		"M"
	],
	"type": "humanoid",
	"alignment": [
		"A"
	],
	"ac": [
		{
			"ac": 15,
			"from": [
				"{@item chain shirt|phb}"
			]
		}
	],
	"hp": {
		"formula": "7d8 + 7",
		"average": 38
	},
	"speed": {
		"walk": 30
	},
	"str": 11,
	"dex": 14,
	"con": 12,
	"int": 10,
	"wis": 13,
	"cha": 14,
	"save": {
		"dex": "+4",
		"wis": "+3"
	},
	"skill": {
		"acrobatics": "+4",
		"perception": "+5",
		"performance": "+6"
	},
	"passive": 15,
	"languages": [
		"any two languages"
	],
	"cr": "2",
	"spellcasting": [
		{
			"name": "Spellcasting",
			"headerEntries": [
				"The bard casts one of the following spells, using Charisma as the spellcasting ability (spell save {@dc 12}):"
			],
			"will": [
				"{@spell dancing lights}",
				"{@spell mage hand}",
				"{@spell prestidigitation}"
			],
			"daily": {
				"1e": [
					"{@spell charm person}",
					"{@spell invisibility}",
					"{@spell sleep}"
				]
			},
			"ability": "cha",
			"displayAs": "action",
			"type": "spellcasting"
		}
	],
	"action": [
		{
			"name": "Multiattack",
			"entries": [
				"The bard makes two Shortsword or Shortbow attacks. It can replace one attack with a use of Spellcasting."
			]
		},
		{
			"name": "Shortsword",
			"entries": [
				"{@atk mw} {@hit 4} to hit, reach 5 ft., one target. {@h}5 ({@damage 1d6 + 2}) piercing damage."
			]
		},
		{
			"name": "Shortbow",
			"entries": [
				"{@atk rw} {@hit 4} to hit, range 80/320 ft., one target. {@h}5 ({@damage 1d6 + 2}) piercing damage."
			]
		}
	],
	"bonus": [
		{
			"name": "Taunt (2/Day)",
			"entries": [
				"The bard targets one creature within 30 feet of it. If the target can hear the bard, the target must succeed on a {@dc 12} Charisma saving throw or have disadvantage on ability checks, attack rolls, and saving throws until the start of the bard's next turn."
			]
		},
		{
			"name": "Bardic Inspiration (3/Day)",
			"entries": [
				"Give a {@dice 1d8}"
			]
		}
	],
	"environment": [
		"urban"
	],
	"soundClip": {
		"type": "external",
		"url": "https://5e.tools/audio/bestiary/bard.mp3"
	},
	"attachedItems": [
		"shortbow|phb",
		"shortsword|phb"
	],
	"actionTags": [
		"Multiattack"
	],
	"languageTags": [
		"X"
	],
	"spellcastingTags": [
		"CB"
	],
	"miscTags": [
		"MW",
		"MLW",
		"RW"
	],
	"conditionInflictSpell": [
		"charmed",
		"invisible",
		"unconscious"
	],
	"hasFluff": true,
	"hasFluffImages": true,
	"tokenUrl": "https://5e.tools/img/MPMM/Bard.png",
	"fluff": {
		"name": "Bard",
		"source": "MPMM",
		"entries": [
			"Bards are gifted poets, storytellers, and entertainers who travel far and wide. They're commonly found in taverns or in the company of jolly bands of adventurers, rough-and-tumble mercenaries, and wealthy patrons.",
			"Each bard is a master of at least one type of performance. You may choose a bard's main type, or you may roll on the Bard {@skill Performance} Types table to determine it.",
			{
				"type": "table",
				"caption": "Bard Performance Types",
				"colLabels": [
					"d10",
					"Performance Type"
				],
				"colStyles": [
					"col-1 text-center",
					"col-11"
				],
				"rows": [
					[
						"1",
						"Poetry"
					],
					[
						"2",
						"Singing"
					],
					[
						"3",
						"Bagpipe"
					],
					[
						"4",
						"Flute"
					],
					[
						"5",
						"Dancing"
					],
					[
						"6",
						"Drum"
					],
					[
						"7",
						"Lute"
					],
					[
						"8",
						"Puppetry"
					],
					[
						"9",
						"Mime"
					],
					[
						"10",
						"Acting"
					]
				]
			}
		],
		"images": [
			{
				"type": "image",
				"href": {
					"type": "internal",
					"path": "bestiary/MPMM/Bard.webp"
				},
				"credit": "Rudy Siswanto"
			}
		]
	},
	"damageTags": [
		"P"
	],
	"savingThrowForced": [
		"charisma"
	],
	"savingThrowForcedSpell": [
		"wisdom"
	]
}
```