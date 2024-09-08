```
{
	"siteVersion": "1.210.0",
	"_meta": {
		"sources": [
			{
				"json": "Huskies",
				"abbreviation": "Hsk",
				"full": "Huskies",
				"url": "",
				"authors": [],
				"convertedBy": []
			}
		],
		"dateAdded": 1724608201,
		"dateLastModified": 1724608201
	},
	"monster": [
		{
			"name": "Avizallo Cleric",
			"shortName": "cleric",
			"source": "Huskies",
			"page": 201,
			"size": [
				"S"
			],
			"type": {
				"type": "humanoid",
				"tags": [
					"luma"
				]
			},
			"alignment": [
				"L",
				"NX",
				"C",
				"G"
			],
			"ac": [
				{
					"ac": 14,
					"from": [
						"{@item chain shirt|phb}"
					]
				}
			],
			"hp": {
				"formula": "6d6 + 6",
				"average": 40
			},
			"speed": {
				"walk": 25
			},
			"str": 10,
			"dex": 13,
			"con": 12,
			"int": 10,
			"wis": 16,
			"cha": 14,
			"skill": {
				"medicine": "+7",
				"persuasion": "+4",
				"religion": "+2"
			},
			"passive": 13,
			"cr": "2",
			"spellcasting": [
				{
					"name": "Spellcasting",
					"type": "spellcasting",
					"headerEntries": [
						"The cleric is a 5th-level spellcaster. Their spellcasting ability is Wisdom (spell save {@dc 13}, +5 to hit with spell attacks). The cleric has the following cleric spells prepared:"
					],
					"spells": {
						"0": {
							"spells": [
								"{@spell sacred flame|PHB}"
							]
						},
						"1": {
							"spells": [
								"{@spell bless|PHB}(c)",
								"{@spell cure wounds|PHB}",
								"{@spell guiding bolt|PHB}"
							],
							"slots": 4
						},
						"2": {
							"spells": [
								"{@spell hold person}",
								"{@spell spiritual weapon|PHB}"
							],
							"slots": 3
						},
						"3": {
							"spells": [
								"{@spell dispel magic|PHB}"
							],
							"slots": 2
						}
					},
					"ability": "wis"
				}
			],
			"trait": [
				{
					"name": "Glide",
					"entries": [
						"When falling at least 10 feet, the cleric can spend a reaction to fly up to their speed in one direction as they descend. They land in an unoccupied space at the end of their movement, and take no falling damage. They cannot glide while carrying heavy objects, or heavy weapons, or shields (though they can drop any held items as part of their reaction)."
					]
				},
				{
					"name": "Fated (Recharges after a Long Rest)",
					"entries": [
						"The luma cleric can choose to reroll any attack roll, skill check, or saving throw."
					]
				}
			],
			"action": [
				{
					"name": "Staff",
					"entries": [
						"{@atk mw} {@hit 5} to hit, reach 5 ft., one target. {@h}6 ({@damage 2d6}) bludgeoning damage, and every foot of movement the target makes towards the cleric costs 2 feet until the end of the priest's next turn."
					]
				},
				{
					"name": "Vigor (1/Day)",
					"entries": [
						"The cleric imbues their allies with her protective life force. The luma cleric and up to 3 allies within 30 feet gain 5 ({@dice 2d4}) temporary hit points. For one minute, anyone under this effect gains 5 temporary hit points at the start of each of their turns."
					]
				}
			],
			"bonus": [
				{
					"name": "Wing Flap",
					"entries": [
						"As a bonus action, the cleric can use their powerful feathered arms to propel themselves upward up to half their movement speed. The cleric can use this in conjunction with a regular jump, but not while gliding."
					]
				}
			],
			"token": {
				"name": "",
				"source": ""
			},
			"damageTags": [
				"B"
			],
			"damageTagsSpell": [
				"O",
				"R"
			],
			"spellcastingTags": [
				"CC"
			],
			"miscTags": [
				"MW"
			],
			"savingThrowForcedSpell": [
				"dexterity",
				"wisdom"
			],
			"hasFluff": true,
			"hasFluffImages": true
		},
		{
			"name": "Avizallo Feather Scout",
			"source": "Huskies",
			"size": [
				"M"
			],
			"type": "humanoid",
			"alignment": [
				"N"
			],
			"ac": [
				15
			],
			"hp": {
				"special": "38"
			},
			"speed": {
				"walk": 30
			},
			"str": 14,
			"dex": 10,
			"con": 12,
			"int": 10,
			"wis": 12,
			"cha": 13,
			"passive": 11,
			"cr": "1",
			"action": [
				{
					"name": "Multiattack",
					"entries": [
						"Make 2 melee attacks"
					]
				},
				{
					"name": "Longsword",
					"entries": [
						"{@atk mw} {@hit +4} to hit, reach 5 ft., one target. {@h}7 ({@damage 1d10 + 2}) slashing damage."
					]
				},
				{
					"name": "Cookies",
					"entries": [
						"All creatures in a 15ft cone must make a DC12 Dex save or take {@damage 2d6} bludgeoning damage. The scout flings cookies in a wide arc. "
					]
				}
			],
			"attachedItems": [
				"longsword|phb"
			],
			"actionTags": [
				"Multiattack"
			],
			"damageTags": [
				"S"
			],
			"miscTags": [
				"MLW",
				"MW"
			]
		},
		{
			"name": "Avizallo Guard",
			"source": "Huskies",
			"page": 226,
			"size": [
				"M"
			],
			"type": {
				"type": "humanoid",
				"tags": [
					"any race"
				]
			},
			"alignment": [
				"A"
			],
			"ac": [
				{
					"ac": 18,
					"from": [
						"{@item chain mail|phb}",
						"{@item shield|phb}"
					]
				}
			],
			"hp": {
				"average": 16,
				"formula": "3d8 + 3"
			},
			"speed": {
				"walk": 30
			},
			"str": 13,
			"dex": 12,
			"con": 12,
			"int": 10,
			"wis": 11,
			"cha": 11,
			"skill": {
				"perception": "+2",
				"athletics": "+3"
			},
			"passive": 12,
			"languages": [
				"any one language (usually Common)"
			],
			"cr": "1/2",
			"trait": [
				{
					"name": "Formation Tactics",
					"entries": [
						"The soldier has advantage on saving throws against being {@condition charmed}, {@condition frightened}, {@condition grappled}, or {@condition restrained} while it is within 5 feet of at least one ally."
					]
				}
			],
			"action": [
				{
					"name": "Multiattack",
					"entries": [
						"The soldier makes two melee attacks."
					]
				},
				{
					"name": "Longsword",
					"entries": [
						"{@atk mw} {@hit 3} to hit, reach 5 ft., one target. {@h}6 ({@damage 1d8 + 2}) slashing damage, or 7 ({@damage 1d10 + 2}) slashing damage if used with two hands."
					]
				}
			],
			"bonus": [
				{
					"name": "Glide",
					"entries": [
						"Use winged cloak to glide 30 feet, without provoking opportunity attacks. "
					]
				}
			],
			"token": {
				"name": "Soldier",
				"source": "GGR"
			},
			"attachedItems": [
				"longsword|phb"
			],
			"actionTags": [
				"Multiattack"
			],
			"languageTags": [
				"C",
				"X"
			],
			"damageTags": [
				"S"
			],
			"miscTags": [
				"MLW",
				"MW"
			],
			"hasFluff": true,
			"fluff": {
				"name": "Soldier",
				"source": "GGR",
				"entries": [
					{
						"type": "entries",
						"entries": [
							{
								"type": "entries",
								"entries": [
									{
										"type": "entries",
										"entries": [
											"Soldiers are found in many of Ravnica's guilds. The soldier stat block represents a typical member of the rank and file, though weaponry and armor can vary."
										]
									}
								]
							}
						]
					}
				]
			}
		},
		{
			"name": "Butcher Balladeer",
			"source": "Huskies",
			"page": 23,
			"basicRules": true,
			"size": [
				"M"
			],
			"type": "undead",
			"alignment": [
				"C",
				"E"
			],
			"ac": [
				13
			],
			"hp": {
				"average": 58,
				"formula": "13d8"
			},
			"speed": {
				"walk": 0,
				"fly": {
					"number": 40,
					"condition": "(hover)"
				},
				"canHover": true
			},
			"str": 1,
			"dex": 14,
			"con": 10,
			"int": 12,
			"wis": 11,
			"cha": 17,
			"save": {
				"wis": "+2",
				"cha": "+5"
			},
			"senses": [
				"darkvision 60 ft."
			],
			"passive": 10,
			"resist": [
				"acid",
				"fire",
				"lightning",
				"thunder",
				{
					"resist": [
						"bludgeoning",
						"piercing",
						"slashing"
					],
					"note": "from nonmagical attacks",
					"cond": true
				}
			],
			"immune": [
				"cold",
				"necrotic",
				"poison"
			],
			"conditionImmune": [
				"charmed",
				"exhaustion",
				"frightened",
				"grappled",
				"paralyzed",
				"petrified",
				"poisoned",
				"prone",
				"restrained"
			],
			"languages": [
				"Common",
				"Elvish"
			],
			"cr": "4",
			"trait": [
				{
					"name": "Incorporeal Movement",
					"entries": [
						"The Butcher can move through other creatures and objects as if they were {@quickref difficult terrain||3}. He takes 5 ({@damage 1d10}) force damage if he ends his turn inside an object."
					]
				}
			],
			"action": [
				{
					"name": "Corrupting Touch",
					"entries": [
						"{@atk ms} {@hit 4} to hit, reach 5 ft., one target. {@h}12 ({@damage 3d6 + 2}) necrotic damage."
					]
				},
				{
					"name": "Horrifying Visage",
					"entries": [
						"Each non-undead creature within 60 feet of the butcher that can him her must succeed on a {@dc 13} Wisdom saving throw or be {@condition frightened} for 1 minute. A {@condition frightened} target can repeat the saving throw at the end of each of its turns, with disadvantage if the banshee is within line of sight, ending the effect on itself on a success. If a target's saving throw is successful or the effect ends for it, the target is immune to the banshee's Horrifying Visage for the next 24 hours."
					]
				},
				{
					"name": "Shriek {@recharge 5}",
					"entries": [
						"The butcher plays a horrifying shriek. All other creatures within 30 feet of her that can hear her must make a {@dc 13} Constitution saving throw, taking 10 ({@damage 3d6}) psychic damage on a failure or half as much on a success. "
					]
				}
			],
			"environment": [
				"coastal",
				"forest"
			],
			"token": {
				"name": "Banshee",
				"source": "MM"
			},
			"soundClip": {
				"type": "external",
				"url": "https://5e.tools/audio/bestiary/banshee.mp3"
			},
			"traitTags": [
				"Incorporeal Movement"
			],
			"senseTags": [
				"D"
			],
			"languageTags": [
				"C",
				"E"
			],
			"damageTags": [
				"N",
				"O",
				"Y"
			],
			"conditionInflict": [
				"frightened"
			],
			"savingThrowForced": [
				"constitution",
				"wisdom"
			],
			"hasFluff": true,
			"hasFluffImages": true,
			"fluff": {
				"name": "Banshee",
				"source": "MM",
				"entries": [
					{
						"type": "entries",
						"entries": [
							{
								"type": "entries",
								"entries": [
									"When night falls, unlucky travelers hear the faint cries of the forlorn dead. This woeful spirit is a banshee, a spiteful creature formed from the spirit of a female elf. Banshees appear as luminous, wispy forms that vaguely recall their mortal features. A banshee's face is wreathed in a wild tangle of hair, its body clad in wispy rags that flutter and stream around it.",
									{
										"name": "Divine Wrath",
										"type": "entries",
										"entries": [
											"Banshees are the undead remnants of elves who, blessed with great beauty, failed to use their gift to bring joy to the world. Instead, they used their beauty to corrupt and control others. Elves afflicted by the banshee's curse experience no gladness, feeling only distress in the presence of the living. As the curse takes its toll, their minds and bodies decay, until death completes their transformation into undead monsters."
										]
									},
									{
										"name": "Sorrow Bound",
										"type": "entries",
										"entries": [
											"A banshee becomes forever bound to the place of its demise, unable to venture more than five miles from there. It is forced to relive every moment of its life with perfect recall, yet always refuses to accept responsibility for its doom."
										]
									},
									{
										"name": "Beauty Hoarders",
										"type": "entries",
										"entries": [
											"The vanity that inspired the banshee's cursed creation persists in undeath. These creatures covet beautiful objects: fine jewelery, paintings, statues, and other objects of art. At the same time, a banshee abhors any mirrored surface, for it can't bear to see the horror of its own existence. A single glimpse of itself is enough to send a banshee into a rage."
										]
									},
									{
										"name": "Undead Nature",
										"type": "entries",
										"entries": [
											"A banshee doesn't require air, food, drink, or sleep."
										]
									}
								]
							}
						]
					}
				],
				"images": [
					{
						"type": "image",
						"href": {
							"type": "internal",
							"path": "bestiary/MM/Banshee.webp"
						},
						"credit": "Tomas Giorello"
					}
				]
			}
		},
		{
			"name": "Clockwork (Bounty Hunter)",
			"source": "Huskies",
			"level": 7,
			"size": [
				"M"
			],
			"type": "humanoid",
			"alignment": [
				"C",
				"N"
			],
			"ac": [
				{
					"ac": 16,
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
			"wis": 10,
			"cha": 14,
			"save": {
				"dex": "+6",
				"cha": "+5"
			},
			"skill": {
				"deception": "+5",
				"athletics": "+4"
			},
			"senses": [
				"darkvision 30 ft."
			],
			"passive": 10,
			"resist": [
				"fire"
			],
			"cr": "4",
			"spellcasting": [
				{
					"name": "Spellcasting",
					"type": "spellcasting",
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
					}
				}
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
			"bonus": [
				{
					"name": "Time Bomb",
					"entries": [
						"(4/day) Throw a detonator with range 30ft, radius 10ft. At the end of Clockwork's next turn, the bomb goes off for {@dice 2d6} fire dmg (DEX save 13 for half)."
					]
				}
			],
			"reaction": [
				{
					"name": "Chronal Shift",
					"entries": [
						"(2/day) After you or a creature you can see within 30 feet of you makes an attack roll, an ability check, or a saving throw, you can force the creature to reroll. You make this decision after you see whether the roll succeeds or fails. The target must use the result of the second roll."
					]
				}
			],
			"senseTags": [
				"D"
			],
			"damageTags": [
				"S"
			],
			"spellcastingTags": [
				"O"
			],
			"miscTags": [
				"MW",
				"RCH"
			]
		},
		{
			"name": "Cultist of Song",
			"source": "Huskies",
			"size": [
				"M"
			],
			"type": "humanoid",
			"alignment": [
				"N"
			],
			"ac": [
				15
			],
			"hp": {
				"formula": "8d8 + 8",
				"average": 44
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
				"perception": "+3",
				"performance": "+6"
			},
			"passive": 15,
			"conditionImmune": [
				{
					"conditionImmune": [
						"charmed"
					]
				},
				{
					"conditionImmune": [
						"frightened"
					]
				}
			],
			"cr": "2",
			"spellcasting": [
				{
					"name": "Spellcasting",
					"type": "spellcasting",
					"daily": {
						"1e": [
							"{@spell charm person}",
							"{@spell invisibility}",
							"{@spell sleep}"
						]
					}
				}
			],
			"trait": [
				{
					"name": "Concentration Save",
					"entries": [
						"Each time the cultist takes damage, it must make a WIS save to maintain possession."
					]
				}
			],
			"action": [
				{
					"name": "Multiattack",
					"entries": [
						"The cultist makes two weapon attacks. It can replace one attack with a use of Spellcasting."
					]
				},
				{
					"name": "Shortsword",
					"entries": [
						"{@atk mw} {@hit 4} to hit, reach 5 ft., one target. {@h}5 ({@damage 1d6 + 2}) piercing damage. ",
						"Once per turn when the cultist hits a creature with an attack using this weapon, it can wound its target. At the start of each of the wounded creature's turns, it takes 2 ({@damage 1d4}) necrotic damage for each time it's been wounded by this weapon. It can then make a {@dc 15} Constitution saving throw, ending the effect of all such wounds on itself on a success. Alternatively, the wounded creature, or a creature within 5 feet of it, can use an action to make a {@dc 15} Wisdom (Medicine) check, ending the effect of such wounds on it on a success."
					]
				},
				{
					"name": "Shortbow",
					"entries": [
						"{@atk rw} {@hit 4} to hit, range 80/320 ft., one target. {@h}5 ({@damage 1d6 + 2}) piercing damage."
					]
				},
				{
					"name": "Cacophony {@recharge 4}",
					"entries": [
						"Each creature in a 15-foot cube originating from the bard must make a {@dc 12} Constitution saving throw. On a failed save, a creature takes 9 ({@damage 2d8}) thunder damage and is pushed up to 10 feet away from the bard. On a successful save, a creature takes half as much damage and isn't pushed."
					]
				}
			],
			"attachedItems": [
				"shortbow|phb",
				"shortsword|phb"
			],
			"actionTags": [
				"Breath Weapon",
				"Multiattack"
			],
			"damageTags": [
				"N",
				"P",
				"T"
			],
			"spellcastingTags": [
				"O"
			],
			"miscTags": [
				"AOE",
				"MLW",
				"MW",
				"RW"
			],
			"savingThrowForced": [
				"constitution"
			],
			"savingThrowForcedSpell": [
				"wisdom"
			]
		},
		{
			"name": "Dance Ghoul",
			"source": "Huskies",
			"page": 148,
			"basicRules": true,
			"size": [
				"M"
			],
			"type": "undead",
			"alignment": [
				"C",
				"E"
			],
			"ac": [
				13
			],
			"hp": {
				"formula": "5d8",
				"average": 33
			},
			"speed": {
				"walk": 40
			},
			"str": 13,
			"dex": 15,
			"con": 10,
			"int": 7,
			"wis": 10,
			"cha": 6,
			"senses": [
				"darkvision 60 ft."
			],
			"passive": 10,
			"immune": [
				"poison"
			],
			"conditionImmune": [
				"charmed",
				"exhaustion",
				"poisoned"
			],
			"languages": [
				"Common"
			],
			"cr": "1",
			"trait": [
				{
					"name": "Kinetic Jaunt",
					"entries": [
						"A Dance Ghoul does not provoke opportunity attacks, and can move through other creatures without difficult terrain. It cannot end its turn in another creature's space. "
					]
				}
			],
			"action": [
				{
					"name": "Claws",
					"entries": [
						"{@atk mw} {@hit 4} to hit, reach 5 ft., one target. {@h}7 ({@damage 2d4 + 2}) slashing damage. If the target is a creature other than an elf or undead, it must succeed on a {@dc 10} Constitution saving throw or be {@condition paralyzed} for 1 minute. The target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success."
					]
				},
				{
					"name": "Pas de Deux (Suella)",
					"entries": [
						"If Suella succeeds on an attack, she can twirl with the target up to her movement. "
					]
				},
				{
					"name": "Irresistible Dance (Glenda, 1/day)",
					"entries": [
						"Cast {@spell Otto's Irresistible Dance} on one target. {@dc 13} WIS save on target's turn."
					]
				},
				{
					"name": "Step in Time (Andrei, 1/day)",
					"entries": [
						"All enemies make a {@dc 13} DEX save, {@status concentration}. A failed target fails to move to the beat and sticks out like a sore thumb. Any attack roll against it has advantage if the attacker can see it, and the affected creature can't benefit from being {@condition invisible}."
					]
				},
				{
					"name": "Break-dance (Malachite)",
					"entries": [
						"{@atk rw} {@hit 4} to hit, range 20/60 ft., one target. {@h}11 ({@damage 2d6 + 4}) bludgeoning damage. Attacks via a mirror have advantage. Parts of Malachite's disintegrating body go flying as he dances. "
					]
				}
			],
			"environment": [
				"swamp",
				"underdark",
				"urban"
			],
			"token": {
				"name": "Ghoul",
				"source": "MM"
			},
			"soundClip": {
				"type": "external",
				"url": "https://5e.tools/audio/bestiary/ghoul.mp3"
			},
			"senseTags": [
				"D"
			],
			"languageTags": [
				"C"
			],
			"damageTags": [
				"B",
				"S"
			],
			"miscTags": [
				"MW",
				"RW"
			],
			"conditionInflict": [
				"paralyzed"
			],
			"savingThrowForced": [
				"constitution"
			],
			"hasFluff": true,
			"hasFluffImages": true,
			"fluff": {
				"name": "Ghoul",
				"source": "MM",
				"entries": [
					{
						"type": "entries",
						"entries": [
							{
								"type": "entries",
								"entries": [
									"Ghouls roam the night in packs, driven by an insatiable hunger for humanoid flesh.",
									{
										"name": "Devourers of Flesh",
										"type": "entries",
										"entries": [
											"Like maggots or carrion beetles, ghouls thrive in places rank with decay and death. A ghoul haunts a place where it can gorge on dead flesh and decomposing organs. When it can't feed on the dead, it pursues living creatures and attempts to make corpses of them. Though they gain no nourishment from the corpses they devour, ghouls are driven by an unending hunger that compels them to consume. A ghoul's undead flesh never rots, and this monster can persist in a crypt or tomb for untold ages without feeding."
										]
									},
									{
										"name": "Abyssal Origins",
										"type": "entries",
										"entries": [
											"Ghouls trace their origins to the Abyss. Doresain, the first of their kind, was an elf worshiper of Orcus. Turning against his own people, he feasted on humanoid flesh to honor the Demon Prince of Undeath. As a reward for his service, Orcus transformed Doresain into the first ghoul. Doresain served Orcus faithfully in the Abyss, creating ghouls from the demon lord's other servants until an incursion by Yeenoghu, the demonic Gnoll Lord, robbed Doresain of his abyssal domain. When Orcus would not intervene on his behalf, Doresain turned to the elf gods for salvation, and they took pity on him and helped him escape certain destruction. Since then, elves have been immune to the ghouls' paralytic touch."
										]
									},
									{
										"name": "Ghasts",
										"type": "entries",
										"entries": [
											"Orcus sometimes infuses a ghoul with a stronger dose of abyssal energy, making a ghast. Whereas ghouls are little more than savage beasts, a ghast is cunning and can inspire a pack of ghouls to follow its commands."
										]
									}
								]
							}
						]
					}
				],
				"images": [
					{
						"type": "image",
						"href": {
							"type": "internal",
							"path": "bestiary/MM/Ghoul.webp"
						}
					}
				]
			}
		},
		{
			"name": "Duke Vasilev",
			"shortName": "Vasilev",
			"source": "Huskies",
			"level": 8,
			"size": [
				"M"
			],
			"type": {
				"type": "humanoid",
				"tags": [
					{
						"tag": "elf",
						"prefix": "Drow"
					}
				]
			},
			"alignment": [
				"N"
			],
			"ac": [
				10
			],
			"hp": {
				"formula": "1d8 + 1",
				"average": 5
			},
			"speed": {
				"walk": 30
			},
			"str": 10,
			"dex": 16,
			"con": 12,
			"int": 16,
			"wis": 10,
			"cha": 14,
			"save": {
				"dex": "+6",
				"int": "+6",
				"wis": "+3"
			},
			"skill": {
				"perception": "+9",
				"investigation": "+6",
				"persuasion": "+5",
				"deception": "+8",
				"intimidation": "+5"
			},
			"senses": [
				"Darkvision 120ft"
			],
			"passive": 10,
			"conditionImmune": [
				{
					"conditionImmune": [
						"charmed"
					],
					"note": "or magically put to sleep"
				}
			],
			"cr": "4",
			"spellcasting": [
				{
					"name": "Spellcasting",
					"type": "spellcasting",
					"spells": {
						"0": {
							"spells": [
								"{@spell mage hand}",
								"{@spell message}"
							]
						}
					}
				}
			],
			"senseTags": [
				"D"
			],
			"spellcastingTags": [
				"O"
			]
		},
		{
			"name": "Ghost (Reduced Threat)",
			"source": "Huskies",
			"page": 147,
			"basicRules": true,
			"size": [
				"M"
			],
			"type": "undead",
			"alignment": [
				"A"
			],
			"ac": [
				11
			],
			"hp": {
				"average": 45,
				"formula": "10d8"
			},
			"speed": {
				"walk": 0,
				"fly": {
					"number": 40,
					"condition": "(hover)"
				},
				"canHover": true
			},
			"str": 7,
			"dex": 13,
			"con": 10,
			"int": 10,
			"wis": 12,
			"cha": 17,
			"senses": [
				"darkvision 60 ft."
			],
			"passive": 11,
			"resist": [
				"acid",
				"fire",
				"lightning",
				"thunder",
				{
					"resist": [
						"bludgeoning",
						"piercing",
						"slashing"
					],
					"note": "from nonmagical attacks",
					"cond": true
				}
			],
			"immune": [
				"cold",
				"necrotic",
				"poison"
			],
			"conditionImmune": [
				"charmed",
				"exhaustion",
				"frightened",
				"grappled",
				"paralyzed",
				"petrified",
				"poisoned",
				"prone",
				"restrained"
			],
			"languages": [
				"any languages it knew in life"
			],
			"cr": "2",
			"trait": [
				{
					"name": "Ethereal Sight",
					"entries": [
						"The ghost can see 60 feet into the Ethereal Plane when it is on the Material Plane, and vice versa."
					]
				},
				{
					"name": "Incorporeal Movement",
					"entries": [
						"The ghost can move through other creatures and objects as if they were {@quickref difficult terrain||3}. It takes 5 ({@damage 1d10}) force damage if it ends its turn inside an object."
					]
				}
			],
			"action": [
				{
					"name": "Withering Touch",
					"entries": [
						"{@atk mw} {@hit 5} to hit, reach 5 ft., one target. {@h}9 ({@damage 2d6 + 3}) necrotic damage."
					]
				},
				{
					"name": "Etherealness",
					"entries": [
						"The ghost enters the Ethereal Plane from the Material Plane, or vice versa. It is visible on the Material Plane while it is in the Border Ethereal, and vice versa, yet it can't affect or be affected by anything on the other plane."
					]
				},
				{
					"name": "Horrifying Visage",
					"entries": [
						"Each non-undead creature within 60 feet of the ghost that can see it must succeed on a {@dc 13} Wisdom saving throw or be {@condition frightened} for 1 minute.  A {@condition frightened} target can repeat the saving throw at the end of each of its turns, ending the {@condition frightened} condition on itself on a success. If a target's saving throw is successful or the effect ends for it, the target is immune to this ghost's Horrifying Visage for the next 24 hours."
					]
				},
				{
					"name": "Possession {@recharge}",
					"entries": [
						"One humanoid that the ghost can see within 5 feet of it must succeed on a {@dc 13} Charisma saving throw or be possessed by the ghost; the ghost then disappears, and the target is {@condition incapacitated} and loses control of its body. The ghost now controls the body but doesn't deprive the target of awareness. The ghost can't be targeted by any attack, spell, or other effect, except ones that turn undead, and it retains its alignment, Intelligence, Wisdom, Charisma, and immunity to being {@condition charmed} and {@condition frightened}. It otherwise uses the possessed target's statistics, but doesn't gain access to the target's knowledge, class features, or proficiencies.",
						"The possession lasts until the body drops to 0 hit points, the ghost ends it as a bonus action, or the ghost is turned or forced out by an effect like the {@spell dispel evil and good} spell. When the possession ends, the ghost reappears in an unoccupied space within 5 feet of the body. The target is immune to this ghost's Possession for 24 hours after succeeding on the saving throw or after the possession ends."
					]
				}
			],
			"environment": [
				"underdark",
				"urban"
			],
			"token": {
				"name": "Ghost",
				"source": "MM"
			},
			"soundClip": {
				"type": "external",
				"url": "https://5e.tools/audio/bestiary/ghost.mp3"
			},
			"traitTags": [
				"Incorporeal Movement"
			],
			"senseTags": [
				"D"
			],
			"languageTags": [
				"LF"
			],
			"damageTags": [
				"N",
				"O"
			],
			"miscTags": [
				"MW"
			],
			"conditionInflict": [
				"frightened",
				"incapacitated"
			],
			"savingThrowForced": [
				"charisma",
				"wisdom"
			],
			"hasFluff": true,
			"hasFluffImages": true,
			"fluff": {
				"name": "Ghost",
				"source": "MM",
				"entries": [
					{
						"type": "entries",
						"entries": [
							{
								"type": "entries",
								"entries": [
									"A ghost is the soul of a once-living creature, bound to haunt a specific location, creature, or object that held significance to it in its life.",
									{
										"name": "Unfinished Business",
										"type": "entries",
										"entries": [
											"A ghost yearns to complete some unresolved task from its life. It might seek to avenge its own death, fulfill an oath, or relay a message to a loved one. A ghost might not realize that it has died and continue the everyday routine of its life. Others are driven by wickedness or spite, as with a ghost that refuses to rest until every member of a certain family or organization is dead.",
											"The surest way to rid an area of a ghost is to resolve its unfinished business. A ghost can be destroyed more easily by invoking a weakness tied to its former life. The ghost of a person tortured to death might be killed again by the implements of that torture. The ghost of a gardener might become more vulnerable when exposed to a potent floral fragrance."
										]
									},
									{
										"name": "Ghostly Manifestations",
										"type": "entries",
										"entries": [
											"Sensations of profound sadness, loneliness, and unfulfilled yearning emanate from places where ghostly hauntings occur. Strange sounds or unnatural silences create an unsettling atmosphere. Cold spots settle in rooms that have roaring fires. A choking stench might seep into the area, inanimate objects might move of their own accord, and corpses might rise from the grave. The ghost has no control over these manifestations; they simply occur."
										]
									},
									{
										"name": "Undead Nature",
										"type": "entries",
										"entries": [
											"A ghost doesn't require air, food, drink, or sleep."
										]
									}
								]
							}
						]
					}
				],
				"images": [
					{
						"type": "image",
						"href": {
							"type": "internal",
							"path": "bestiary/MM/Ghost.webp"
						}
					}
				]
			}
		},
		{
			"name": "Gyrfalcon",
			"source": "Huskies",
			"level": 7,
			"size": [
				"M"
			],
			"type": {
				"type": "humanoid",
				"sidekickType": "warrior",
				"sidekickHidden": true
			},
			"ac": [
				{
					"ac": 20,
					"from": [
						"{@item plate armor|phb}",
						"{@item shield|phb}"
					]
				},
				15
			],
			"hp": {
				"average": 52,
				"formula": "8d8 + 16"
			},
			"speed": {
				"walk": 30
			},
			"str": 16,
			"dex": 14,
			"con": 14,
			"int": 10,
			"wis": 12,
			"cha": 10,
			"save": {
				"con": "+5"
			},
			"skill": {
				"athletics": "+6",
				"perception": "+4",
				"survival": "+4"
			},
			"passive": 14,
			"languages": [
				"Common",
				"plus one of your choice"
			],
			"trait": [
				{
					"name": "Battle Readiness",
					"entries": [
						"The warrior has advantage on initiative rolls."
					]
				},
				{
					"name": "Improved Critical",
					"entries": [
						"The warrior's attack rolls score a critical hit on a roll of 19 or 20 on the {@dice d20}."
					]
				}
			],
			"action": [
				{
					"name": "Extra Attack",
					"entries": [
						"The warrior can attack twice, instead of once, whenever it takes the {@action Attack} action on its turn."
					]
				},
				{
					"name": "Longsword",
					"entries": [
						"{@atk mw} {@hit 6} to hit, reach 5 ft., one target. {@h}7 ({@damage 1d8 + 3}) slashing damage, or 8 ({@damage 1d10 + 3}) slashing damage if used with two hands."
					]
				},
				{
					"name": "Longbow",
					"entries": [
						"{@atk rw} {@hit 5} to hit, range 150/600 ft., one target. {@h}6 ({@damage 1d8 + 2}) piercing damage."
					]
				}
			],
			"reaction": [
				{
					"name": "Protection (Defender Only)",
					"entries": [
						"The warrior imposes disadvantage on the attack roll of a creature within 5 feet of it whose target isn't the warrior. The warrior must be able to see the attacker."
					]
				}
			],
			"tokenUrl": "https://5e.tools/img/SLW/Warrior.png",
			"languageTags": [
				"C"
			],
			"damageTags": [
				"P",
				"S"
			],
			"miscTags": [
				"MW",
				"RNG",
				"RW"
			]
		},
		{
			"name": "Isaiah Giltstern",
			"source": "Huskies",
			"size": [
				"M"
			],
			"type": "humanoid",
			"alignment": [
				"N"
			],
			"ac": [
				14
			],
			"hp": {
				"formula": "1d8 + 1",
				"average": 45
			},
			"speed": {
				"walk": 30
			},
			"str": 12,
			"dex": 10,
			"con": 12,
			"int": 16,
			"wis": 14,
			"cha": 20,
			"save": {
				"cha": "+8",
				"int": "+6"
			},
			"skill": {
				"deception": "+8",
				"history": "+6",
				"insight": "+5",
				"intimidation": "+8",
				"persuasion": "+8"
			},
			"passive": 12,
			"cr": "2",
			"trait": [
				{
					"name": "Political Savvy",
					"entries": [
						"Advantage on saves to avoid or end the {@condition charmed} condition or resist magical suggestion. "
					]
				}
			],
			"action": [
				{
					"name": "Musket",
					"entries": [
						"Ranged, 40/120ft. {@hit 3} to hit, 11 ({@damage 2d8 + 3}) piercing damage."
					]
				},
				{
					"name": "Inspire",
					"entries": [
						"Target up to 5 allies within 60 feet. Each ally can take a movement and an attack immediately. "
					]
				},
				{
					"name": "Choose Champion",
					"entries": [
						"Target an ally within 30ft. Until the start of Isaiah's next turn, the ally has resistance to bludgeoning, piercing, slashing damage, and does an extra 3 ({@dice 1d6}) dmg when it hits. "
					]
				}
			],
			"attachedItems": [
				"musket|dmg"
			],
			"damageTags": [
				"P"
			]
		},
		{
			"name": "Kareem",
			"source": "Huskies",
			"page": 187,
			"size": [
				"M"
			],
			"type": {
				"type": "humanoid",
				"tags": [
					"goblinoid"
				]
			},
			"alignment": [
				"N",
				"G"
			],
			"ac": [
				{
					"ac": 20,
					"from": [
						"{@item plate armor|phb}",
						"{@item shield|phb}"
					]
				}
			],
			"hp": {
				"average": 97,
				"formula": "13d8 + 39"
			},
			"speed": {
				"walk": 30
			},
			"str": 16,
			"dex": 14,
			"con": 16,
			"int": 14,
			"wis": 11,
			"cha": 15,
			"save": {
				"int": "+5",
				"wis": "+3",
				"cha": "+5"
			},
			"senses": [
				"darkvision 60 ft."
			],
			"passive": 10,
			"languages": [
				"Common",
				"Goblin"
			],
			"cr": "6",
			"action": [
				{
					"name": "Multiattack",
					"entries": [
						"Kareem makes two attacks."
					]
				},
				{
					"name": "Longsword",
					"entries": [
						"{@atk mw} {@hit 9} to hit, reach 5 ft., one target. {@h}7 ({@damage 1d8 + 3}) (rage, {@damage 1d8 + 6}) slashing damage, or 8 ({@damage 1d10 + 3}) slashing damage if used with two hands."
					]
				},
				{
					"name": "Shield Bash",
					"entries": [
						"{@atk mw} {@hit 9} to hit, reach 5 ft., one creature. {@h}5 ({@damage 1d4 + 3}) (rage, {@damage 1d4 + 6}) bludgeoning damage. If the target is Large or smaller, it must succeed on a {@dc 14} Strength saving throw or be knocked {@condition prone}."
					]
				},
				{
					"name": "Javelin",
					"entries": [
						"{@atk mw,rw} {@hit 9} to hit, reach 5 ft. or range 30/120 ft., one target. {@h}6 ({@dice 1d6 + 3}), (rage, {@dice 1d6 + 6}) piercing damage."
					]
				}
			],
			"bonus": [
				{
					"name": "Rage",
					"entries": [
						"Advantage on STR checks and saves. +3 to melee attacks. Resistance to bludgeoning, piercing, and slashing damage."
					]
				}
			],
			"reaction": [
				{
					"name": "Parry",
					"entries": [
						"Kareem adds 3 to its AC against one melee attack that would hit it. To do so, Kareem must see the attacker and be wielding a melee weapon."
					]
				}
			],
			"environment": [
				"desert",
				"forest",
				"grassland",
				"hill",
				"underdark"
			],
			"token": {
				"name": "Hobgoblin Warlord",
				"source": "MM"
			},
			"soundClip": {
				"type": "external",
				"url": "https://5e.tools/audio/bestiary/hobgoblin-warlord.mp3"
			},
			"attachedItems": [
				"javelin|phb",
				"longsword|phb"
			],
			"senseTags": [
				"D"
			],
			"actionTags": [
				"Multiattack",
				"Parry"
			],
			"languageTags": [
				"C",
				"GO"
			],
			"damageTags": [
				"S"
			],
			"miscTags": [
				"MLW",
				"MW",
				"RW",
				"THW"
			],
			"conditionInflict": [
				"prone"
			],
			"savingThrowForced": [
				"strength"
			],
			"hasFluff": true,
			"hasFluffImages": true
		},
		{
			"name": "Kingfisher (Court of Birds)",
			"source": "Huskies",
			"page": 264,
			"size": [
				"M"
			],
			"type": {
				"type": "humanoid"
			},
			"alignment": [
				"A"
			],
			"ac": [
				12,
				{
					"ac": 15,
					"condition": "with {@spell mage armor}",
					"braces": true
				}
			],
			"hp": {
				"special": "33"
			},
			"speed": {
				"walk": 30
			},
			"str": 10,
			"dex": 10,
			"con": 10,
			"int": 15,
			"wis": 12,
			"cha": 14,
			"save": {
				"int": "+4",
				"wis": "+5"
			},
			"skill": {
				"arcana": "+7",
				"history": "+7"
			},
			"passive": 11,
			"resist": [
				"necrotic"
			],
			"languages": [
				"any four languages"
			],
			"cr": "3",
			"spellcasting": [
				{
					"name": "Spellcasting",
					"type": "spellcasting",
					"headerEntries": [
						"The necromancer casts one of the following spells, using Intelligence as the spellcasting ability (spell save {@dc 15}):"
					],
					"will": [
						"{@spell dancing lights}",
						"{@spell mage hand}",
						"{@spell prestidigitation}"
					],
					"daily": {
						"1e": [
							"{@spell bestow curse}",
							"{@spell dimension door}",
							"{@spell mage armor}",
							"{@spell web}"
						]
					},
					"ability": "int"
				}
			],
			"action": [
				{
					"name": "Arcane Burst",
					"entries": [
						"{@atk ms,rs} {@hit 5} to hit, reach 5 ft. or range 120 ft., one target. {@h}8 ({@damage 1d10 + 3}) necrotic damage."
					]
				},
				{
					"name": "Scimitar",
					"entries": [
						"{@atk mw} {@hit +2} to hit, reach 5 ft., one target. {@h}3 ({@damage 1d6}) slashing damage."
					]
				}
			],
			"environment": [
				"desert",
				"urban"
			],
			"token": {
				"name": "Necromancer Wizard",
				"source": "MPMM"
			},
			"soundClip": {
				"type": "external",
				"url": "https://5e.tools/audio/bestiary/necromancer.mp3"
			},
			"attachedItems": [
				"scimitar|phb"
			],
			"actionTags": [
				"Multiattack"
			],
			"languageTags": [
				"X"
			],
			"damageTags": [
				"N",
				"S"
			],
			"damageTagsSpell": [
				"F",
				"N",
				"O"
			],
			"spellcastingTags": [
				"O"
			],
			"miscTags": [
				"MLW",
				"MW"
			],
			"conditionInflictSpell": [
				"restrained"
			],
			"savingThrowForcedSpell": [
				"dexterity",
				"wisdom"
			],
			"hasFluff": true,
			"hasFluffImages": true,
			"fluff": {
				"name": "Necromancer Wizard",
				"source": "MPMM",
				"images": [
					{
						"type": "image",
						"href": {
							"type": "internal",
							"path": "bestiary/MPMM/Necromancer Wizard.webp"
						},
						"credit": "Randy Vargas"
					}
				],
				"entries": [
					{
						"type": "entries",
						"entries": [
							"Necromancers study the interaction of life, death, and undeath. Some necromancers dig up or purchase corpses to create Undead servitors. A few instead use their powers for good, hunting Undead."
						]
					},
					{
						"type": "section",
						"name": "Wizards",
						"entries": [
							"Wizards pursue magical power through the study of arcane texts. Some travel the world searching for esoteric tomes while others train lesser wizards or collaborate with colleagues to create new spells."
						]
					}
				]
			}
		},
		{
			"name": "Leanna (mage)",
			"source": "Huskies",
			"page": 129,
			"size": [
				"M"
			],
			"type": {
				"type": "humanoid",
				"tags": [
					"elf"
				]
			},
			"alignment": [
				"N",
				"E"
			],
			"ac": [
				12,
				{
					"ac": 15,
					"condition": "with {@spell mage armor}",
					"braces": true
				}
			],
			"hp": {
				"formula": "10d8",
				"average": 30
			},
			"speed": {
				"walk": 30
			},
			"str": 9,
			"dex": 14,
			"con": 10,
			"int": 17,
			"wis": 13,
			"cha": 12,
			"skill": {
				"arcana": "+6",
				"deception": "+4",
				"perception": "+5",
				"stealth": "+5"
			},
			"senses": [
				"darkvision 120 ft."
			],
			"passive": 15,
			"languages": [
				"Elvish"
			],
			"cr": "3",
			"spellcasting": [
				{
					"name": "Innate Spellcasting",
					"type": "spellcasting",
					"headerEntries": [
						"The drow's spellcasting ability is Charisma (spell save {@dc 12}). It can innately cast the following spells, requiring no material components:"
					],
					"daily": {
						"1e": [
							"{@spell darkness}"
						]
					},
					"ability": "cha"
				},
				{
					"name": "Spellcasting",
					"type": "spellcasting",
					"headerEntries": [
						"Its spellcasting ability is Intelligence (spell save {@dc 14}, {@hit 6} to hit with spell attacks). The drow has the following wizard spells prepared:"
					],
					"spells": {
						"0": {
							"spells": [
								"{@spell mage hand}",
								"{@spell minor illusion}",
								"{@spell poison spray}",
								"{@spell ray of frost}"
							]
						},
						"1": {
							"spells": [
								"{@spell mage armor}",
								"{@spell magic missile}",
								"{@spell shield}",
								"{@spell witch bolt}"
							],
							"slots": 4
						},
						"2": {
							"spells": [
								"{@spell misty step}",
								"{@spell web}"
							],
							"slots": 3
						},
						"3": {
							"spells": [
								"{@spell fly}",
								"{@spell lightning bolt}"
							],
							"slots": 3
						},
						"4": {
							"spells": [
								"{@spell Evard's black tentacles}",
								"{@spell greater invisibility}"
							],
							"slots": 1
						}
					},
					"ability": "int"
				}
			],
			"trait": [
				{
					"name": "Fey Ancestry",
					"entries": [
						"The drow has advantage on saving throws against being {@condition charmed}, and magic can't put the drow to sleep."
					]
				}
			],
			"action": [
				{
					"name": "Staff",
					"entries": [
						"{@atk mw} {@hit 2} to hit, reach 5 ft., one target. {@h} 3 ({@damage 1d8 - 1}) bludgeoning damage if used with two hands, plus 3 ({@damage 1d6}) poison damage."
					]
				}
			],
			"environment": [
				"underdark"
			],
			"token": {
				"name": "Drow Mage",
				"source": "MM"
			},
			"soundClip": {
				"type": "external",
				"url": "https://5e.tools/audio/bestiary/drow-mage.mp3"
			},
			"traitTags": [
				"Fey Ancestry",
				"Sunlight Sensitivity"
			],
			"senseTags": [
				"SD"
			],
			"languageTags": [
				"E"
			],
			"damageTags": [
				"B",
				"I"
			],
			"damageTagsSpell": [
				"B",
				"C",
				"F",
				"I",
				"L",
				"O"
			],
			"spellcastingTags": [
				"CW",
				"I"
			],
			"miscTags": [
				"MW"
			],
			"conditionInflictSpell": [
				"invisible",
				"restrained"
			],
			"savingThrowForcedSpell": [
				"constitution",
				"dexterity"
			],
			"hasFluff": true,
			"hasFluffImages": true,
			"fluff": {
				"name": "Drow Mage",
				"source": "MM",
				"images": [
					{
						"type": "image",
						"href": {
							"type": "internal",
							"path": "bestiary/MM/Drow Mage.webp"
						}
					}
				],
				"entries": [
					{
						"name": "Drow",
						"type": "section",
						"entries": [
							{
								"type": "entries",
								"entries": [
									{
										"type": "entries",
										"entries": [
											"Tens of thousands of years ago, the elves were divided, with those of benevolent disposition battling those that were selfish and cruel. The war among elvenkind ended when the good elves banished their malevolent kin to the subterranean depths. Here, in the lightless caverns and endless warrens of twisting passages, the dark elves-the drow-found refuge. They also found leadership in the only elven deity who had not forsaken them. At her command, the dark elves built an empire in the underworld.",
											{
												"type": "entries",
												"entries": [
													{
														"type": "entries",
														"entries": [
															{
																"type": "entries",
																"name": "Children of Lolth",
																"entries": [
																	"The drow worship Lolth, a deity who resides in the Abyss. Known as the Spider Queen or the Demon Queen of Spiders, she is the figure around which the dark elves have built their subterranean civilization. Whatever she demands, the drow do. The wickedest of elves, drow are seldom seen by the surface world. Though they plot to destroy the elves that banished them, they no longer see themselves as exiles. They are the destined rulers of the darkness, and when Lolth commands them to rise up and destroy their surface-dwelling kin, they will."
																]
															},
															{
																"type": "entries",
																"name": "Creatures of Darkness",
																"entries": [
																	"The drow have lived underground for so long that they have evolved to their surroundings and can see in the dark. However, they can no longer stand sunlight. When slaves are in short supply in the Underdark, the drow send raiding parties to the surface to capture humanoids under cover of darkness, bringing them back to their cities to be tortured into submission. Beyond those occasional excursions, the drow are content to remain in their subterranean realm, where they feel secure and in control."
																]
															},
															{
																"type": "entries",
																"name": "Underdark Cities",
																"entries": [
																	"The dark elves build fantastic cities in enormous caverns where food and water are abundant. Their ability to sculpt stone rivals that of the greatest dwarf artisans, yet their structures retain a decidedly elven aesthetic. Though appearing delicate, drow settlements are structurally sound and remarkably resilient. The drow like to hollow out enormous stalagmites and stalactites, creating populated spires that rise from the floors and ceilings. A drow city is a sprawling metropolis enclosed by high walls. Non-drow visitors must conduct their business outside the walls under watchful eyes. The drow raise and keep giant spiders to help protect their cities against intruders, even as they drape those cities in beautiful webbing, creating a gossamer snare to catch flying enemies that would otherwise soar over the walls."
																]
															},
															{
																"type": "entries",
																"name": "Drow Magic",
																"entries": [
																	"Just as the drow have adapted to underground life, so too has their magic. In addition to using that magic to carve their cities from stone, they empower their weapons, create dangerous new magic items, and summon demons from the Abyss. Drow spellcasters are supremely arrogant and never hesitate to use their magic in the most abhorrent ways."
																]
															},
															{
																"type": "entries",
																"name": "Arms and Armor",
																"entries": [
																	"Drow craft weapons made of adamantine, a dark and supernaturally hard metal. Drow artisans adorn their weapons and armor with web-like filigree and spider motifs, and mages sometimes imbue items with magic to enhance their effectiveness. However, such magic fades when exposed to sunlight, so that magical drow weapons and armor rarely retain their enhancement bonuses and magical properties when brought to the surface."
																]
															},
															{
																"type": "entries",
																"name": "Cutthroat Politics",
																"entries": [
																	"Drow politics are cutthroat and rife with intrigue. When drow work together, it is typically to destroy a common foe and ensure their own survival, and such alliances are short lived and fraught with peril.",
																	"Drow society is divided into noble houses, each ruled by a matron who seeks to raise the prestige and power of her house above all others. Other high-ranking members of the house are blood relatives, while the middling ranks are flush with drow from weaker families that have sworn fealty to the greater house. Clinging precariously to the bottom rung of a house's social ladder are the house slaves, made up of drow of low birth and the occasional non-drow captive."
																]
															},
															{
																"type": "entries",
																"name": "Matriarchal Rule",
																"entries": [
																	"Lolth, through her faithful priestesses, dictates the rules of drow society, ensuring that her orders and plots are carried out. Since Lolth is prone to manifesting on the Material Plane and directly punishing those that disobey her, the drow have learned to heed what she says and do as her priestesses command.",
																	"In drow society, males are subservient to females. A male drow might lead an Underdark patrol or a raiding party to the surface, but he reports to a female drow-either the matron of his house or one of her hand-picked female subordinates. Although male drow can fill almost any function in drow society, they can't be priests, nor can they rule a house."
																]
															},
															{
																"type": "entries",
																"name": "Poison Predilection",
																"entries": [
																	"Distilled from spider venom and the flora of the Underdark, poison can be found in abundance among the drow, and it plays an important part in their culture and politics. Drow mages concoct a viscid toxin that leaves enemies {@condition unconscious}. Drow warriors coat their blades and crossbow bolts with this venom, looking forward to the interrogation and torture that follows combat."
																]
															},
															{
																"type": "inset",
																"name": "Variant: Drow Magic Armor and Weapons",
																"entries": [
																	"Drow often wear magic armor and carry magic weapons that lose their enhancement bonuses permanently if they are exposed to sunlight for 1 hour or longer.",
																	{
																		"type": "list",
																		"items": [
																			"A drow wearing a +1 chain shirt and carrying a +1 shortsword has AC 16 and a +1 bonus on attack and damage rolls with shortsword attacks.",
																			"A drow elite warrior wearing +2 studded leather and carrying a +2 shortsword has AC 20 and a +2 bonus on attack and damage rolls with shortsword attacks.",
																			"A drow priestess of Lolth wearing +3 scale mail has AC 19."
																		]
																	}
																]
															}
														]
													}
												]
											}
										]
									},
									{
										"type": "insetReadaloud",
										"entries": [
											{
												"type": "quote",
												"entries": [
													"Such depravity. Such terrifying cruelty. They are the vile poison that plagues all elvenkind."
												],
												"by": "Nelar Autumnwell, elf cleric of Corellon Larethian"
											}
										]
									}
								]
							}
						]
					}
				]
			}
		},
		{
			"name": "Luca Industries Automata",
			"source": "Huskies",
			"size": [
				"M"
			],
			"type": "construct",
			"alignment": [
				"N"
			],
			"ac": [
				{
					"ac": 16,
					"from": [
						"natural armor"
					]
				}
			],
			"hp": {
				"formula": "5d10 + 5",
				"average": 30
			},
			"speed": {
				"walk": 30
			},
			"str": 15,
			"dex": 14,
			"con": 12,
			"int": 10,
			"wis": 10,
			"cha": 12,
			"passive": 14,
			"resist": [
				{
					"resist": [
						"bludgeoning",
						"piercing",
						"slashing"
					],
					"note": "(not adamantine)"
				},
				{
					"resist": [
						"poison"
					]
				}
			],
			"vulnerable": [
				{
					"vulnerable": [
						"lightning"
					]
				},
				{
					"vulnerable": [],
					"preNote": "water"
				}
			],
			"conditionImmune": [
				"charmed"
			],
			"cr": "2",
			"action": [
				{
					"name": "Multiattack",
					"entries": [
						"make 2 attacks"
					]
				},
				{
					"name": "Arm Prong",
					"entries": [
						"{@atk mw} {@hit 4} to hit, reach 5 ft., one target. {@h}6 ({@damage 1d8 + 2}) piercing damage."
					]
				},
				{
					"name": "Electric Crossbow",
					"entries": [
						"{@atk rw} {@hit +4} to hit, range 40/160 ft., one target. {@h}6 ({@damage 1d8 + 2}) lightning damage."
					]
				},
				{
					"name": "Shockwave",
					"entries": [
						"1/day. CON save {@dc 13} within a 15 ft radius. On a failed save, creatures take {@damage 3d8} lightning damage and are {@condition stunned}. On a successful save, creatures take half damage and no effects. "
					]
				}
			],
			"reaction": [
				{
					"name": "Shockback",
					"entries": [
						"When the automata takes damage, it can roll a {@dice d10}. If the result is greater than its percentage of remaining health (rounded down), the automata can use its reaction to deal {@damage 1d8 + 2} lightning damage in a 15 foot radius (CON save {@dc 13} to evade). On a failure, the target is also {@condition stunned} until the start of the automata's next turn. "
					]
				}
			],
			"actionTags": [
				"Multiattack"
			],
			"damageTags": [
				"L",
				"P"
			],
			"miscTags": [
				"MW",
				"RW"
			],
			"conditionInflict": [
				"stunned"
			]
		},
		{
			"name": "Merrow Shallowpriest (nerfed)",
			"source": "Huskies",
			"page": 294,
			"size": [
				"L"
			],
			"type": "monstrosity",
			"alignment": [
				"C",
				"E"
			],
			"ac": [
				{
					"ac": 14,
					"from": [
						"natural armor"
					]
				}
			],
			"hp": {
				"formula": "8d10 + 16",
				"average": 60
			},
			"speed": {
				"walk": 10,
				"swim": 40
			},
			"str": 18,
			"dex": 14,
			"con": 15,
			"int": 11,
			"wis": 16,
			"cha": 9,
			"senses": [
				"darkvision 60 ft."
			],
			"passive": 13,
			"languages": [
				"Abyssal",
				"Aquan"
			],
			"cr": "3",
			"spellcasting": [
				{
					"name": "Spellcasting",
					"type": "spellcasting",
					"headerEntries": [
						"The merrow is a 6th-level spellcaster. Its spellcasting ability is Wisdom (spell save {@dc 13}, {@hit 5} to hit with spell attacks). The merrow has the following druid spells prepared:"
					],
					"spells": {
						"0": {
							"spells": [
								"{@spell druidcraft}",
								"{@spell minor illusion}",
								"{@spell shocking grasp}"
							]
						},
						"1": {
							"spells": [
								"{@spell cure wounds}",
								"{@spell fog cloud}",
								"{@spell thunderwave}"
							],
							"slots": 4
						},
						"2": {
							"spells": [
								"{@spell hold person}",
								"{@spell mirror image}",
								"{@spell misty step}"
							],
							"slots": 3
						},
						"3": {
							"spells": [
								"{@spell dispel magic}",
								"{@spell lightning bolt} (see \"Actions\" below)",
								"{@spell sleet storm}"
							],
							"slots": 1
						}
					},
					"ability": "wis"
				}
			],
			"trait": [
				{
					"name": "Amphibious",
					"entries": [
						"The merrow can breathe air and water."
					]
				}
			],
			"action": [
				{
					"name": "Harpoon",
					"entries": [
						"{@atk mw,rw} {@hit 6} to hit, reach 5 ft. or range 20/60 ft., one target. {@h}11 ({@damage 2d6 + 4}) piercing damage. If the target is a Medium or smaller creature, the merrow can pull it 10 feet closer."
					]
				},
				{
					"name": "Lightning Bolt (3rd-Level Spell; Requires a Spell Slot)",
					"entries": [
						"The merrow unleashes a stroke of lightning in a line 100 feet long and 5 feet wide. Each creature in the line must make a {@dc 13} Dexterity saving throw, taking 28 ({@damage 8d6}) lightning damage on a failed save, or half as much damage on a successful one."
					]
				}
			],
			"tokenUrl": "https://5e.tools/img/EGW/Merrow Shallowpriest.png",
			"traitTags": [
				"Amphibious"
			],
			"senseTags": [
				"D"
			],
			"languageTags": [
				"AB",
				"AQ"
			],
			"damageTags": [
				"L",
				"P"
			],
			"damageTagsSpell": [
				"L",
				"T"
			],
			"spellcastingTags": [
				"CD"
			],
			"miscTags": [
				"MW",
				"RW"
			],
			"savingThrowForced": [
				"dexterity"
			],
			"savingThrowForcedSpell": [
				"constitution",
				"dexterity",
				"wisdom"
			],
			"hasFluff": true,
			"hasFluffImages": true,
			"fluff": {
				"name": "Merrow Shallowpriest",
				"source": "EGW",
				"entries": [
					{
						"type": "entries",
						"entries": [
							"Some of the many merrow that dwell in the watery shadows of the Menagerie Coast learn to harness the magical aspects of the elements. Often working as guides leading merrow hunting parties, some of these shallowpriests rise to become powerful leaders, inspiring their clans to terrorize coastal communities and passing ships.",
							"Rumors speak of underground waterways and lakes carved into the rock beneath Wildemount, where shallowpriests hold court over huge subterranean communities of merrow. These evil creatures are thought to seek the means of flooding the surface world, allowing them to steal away who and what they will to the dark waters below.",
							"While most shallowpriests do not bind themselves in the service of a specific deity, some are drawn to the worship of entities that reign over regions of the Elemental Plane of Water, hoping to find means of expanding their dominion into the seas of Exandria. These merrow often spearhead the construction of intricate shrines and temples along the bottom of the ocean, preparing a sacred space for planar doorways to their master's realm to be opened and maintained."
						]
					}
				],
				"images": [
					{
						"type": "image",
						"href": {
							"type": "internal",
							"path": "bestiary/EGW/Merrow Shallowpriest.webp"
						},
						"credit": "Andrew Mar"
					}
				]
			}
		},
		{
			"name": "Mettlewise",
			"source": "Huskies",
			"size": [
				"M"
			],
			"type": "humanoid",
			"alignment": [
				"N"
			],
			"ac": [
				17
			],
			"hp": {
				"special": "91"
			},
			"speed": {
				"walk": 30
			},
			"str": 16,
			"dex": 10,
			"con": 14,
			"int": 10,
			"wis": 12,
			"cha": 13,
			"save": {
				"wis": "+4",
				"cha": "+4"
			},
			"skill": {
				"athletics": "+6",
				"insight": "+4",
				"religion": "+3"
			},
			"passive": 11,
			"cr": "5",
			"spellcasting": [
				{
					"name": "Spellcasting",
					"type": "spellcasting",
					"headerEntries": [
						"Charisma as ability (save {@dc 12})"
					],
					"daily": {
						"1": [
							"{@spell command}",
							"{@spell detect evil and good}",
							"{@spell revivify}",
							"{@spell zone of truth}"
						]
					},
					"ability": "cha"
				}
			],
			"trait": [
				{
					"name": "Blessed Aura",
					"entries": [
						"When Mettlewise or one of her allies within 10 ft makes a saving throw, they add {@dice 1d4} to the roll"
					]
				}
			],
			"action": [
				{
					"name": "Multiattack",
					"entries": [
						"Make 2 greatsword attacks"
					]
				},
				{
					"name": "Greatsword",
					"entries": [
						"{@atk mw} {@hit 6} to hit, reach 5 ft., one target. {@h}13 ({@damage 2d6 + 3}) slashing damage, plus 9 ({@damage 2d8}) radiant damage."
					]
				},
				{
					"name": "Purifying Touch (1/day)",
					"entries": [
						"Mettlewise or one creature of her choice within 5ft regains 55 hp. Additionally, all curses, diseases, and poisons are removed. "
					]
				}
			],
			"bonus": [
				{
					"name": "Smite",
					"entries": [
						"Immediately after hitting a target with an attack, force target to make a DC12 CHA save. On a failure, suffer one of the following effects:",
						"- Radiance: shed dim light in a 5ft radius until the end of Mettlewise's next turn. Creatures that can see the radiance have advantage on attack rolls.",
						"- Punishment: abjuration lasting one minute. Target takes {@damage 1d10} radiant damage when it deals damage to another for the first time on each turn. The target can repeat the save at the end of each of its turns. "
					]
				}
			],
			"attachedItems": [
				"greatsword|phb"
			],
			"actionTags": [
				"Multiattack"
			],
			"damageTags": [
				"R",
				"S"
			],
			"spellcastingTags": [
				"O"
			],
			"miscTags": [
				"MLW",
				"MW"
			],
			"savingThrowForcedSpell": [
				"charisma",
				"wisdom"
			]
		},
		{
			"name": "Mushika",
			"group": [
				"Lycanthropes"
			],
			"source": "Huskies",
			"page": 209,
			"size": [
				"M"
			],
			"type": {
				"type": "humanoid",
				"tags": [
					"human",
					"shapechanger"
				]
			},
			"alignment": [
				"L",
				"E"
			],
			"ac": [
				12
			],
			"hp": {
				"average": 33,
				"formula": "6d8 + 6"
			},
			"speed": {
				"walk": 30
			},
			"str": 10,
			"dex": 15,
			"con": 12,
			"int": 11,
			"wis": 10,
			"cha": 8,
			"skill": {
				"perception": "+2",
				"stealth": "+4"
			},
			"senses": [
				"darkvision 60 ft. (rat form only)"
			],
			"passive": 12,
			"immune": [
				{
					"immune": [
						"bludgeoning",
						"piercing",
						"slashing"
					],
					"note": "from nonmagical attacks that aren't silvered",
					"cond": true
				}
			],
			"languages": [
				"Common (can't speak in rat form)"
			],
			"cr": "2",
			"trait": [
				{
					"name": "Shapechanger",
					"entries": [
						"The wererat can use its action to polymorph into a rat-humanoid hybrid or into a giant rat, or back into its true form, which is humanoid. Its statistics, other than its size, are the same in each form. Any equipment it is wearing or carrying isn't transformed. It reverts to its true form if it dies."
					]
				},
				{
					"name": "Keen Smell",
					"entries": [
						"The wererat has advantage on Wisdom ({@skill Perception}) checks that rely on smell."
					]
				}
			],
			"action": [
				{
					"name": "Multiattack (Humanoid or Hybrid Form Only)",
					"entries": [
						"The wererat makes two attacks, only one of which can be a bite."
					]
				},
				{
					"name": "Bite (Rat or Hybrid Form Only)",
					"entries": [
						"{@atk mw} {@hit 4} to hit, reach 5 ft., one target. {@h}4 ({@damage 1d4 + 2}) piercing damage. If the target is a humanoid, it must succeed on a {@dc 11} Constitution saving throw or be cursed with wererat lycanthropy."
					]
				},
				{
					"name": "Shortsword (Humanoid or Hybrid Form Only)",
					"entries": [
						"{@atk mw} {@hit 4} to hit, reach 5 ft., one target. {@h}5 ({@damage 1d6 + 2}) piercing damage."
					]
				},
				{
					"name": "Hand Crossbow (Humanoid or Hybrid Form Only)",
					"entries": [
						"{@atk rw} {@hit 4} to hit, range 30/120 ft., one target. {@h}5 ({@damage 1d6 + 2}) piercing damage."
					]
				},
				{
					"name": "Detonator",
					"entries": [
						"1/day. Range 30 ft. {@dc 14} DEX save in 10 ft radius for {@dice 2d6} fire dmg."
					]
				}
			],
			"variant": [
				{
					"type": "variant",
					"name": "Nonhuman Lycanthropes",
					"entries": [
						"The statistics presented in this section assume a base creature of human. However, you can also use the statistics to represent nonhuman lycanthropes, adding verisimilitude by allowing a nonhuman lycanthrope to retain one or more of its humanoid racial traits. For example, an elf werewolf might have the Fey Ancestry trait."
					]
				}
			],
			"environment": [
				"forest",
				"urban"
			],
			"tokenUrl": "https://5e.tools/img/MM/Wererat.png",
			"soundClip": {
				"type": "external",
				"url": "https://5e.tools/audio/bestiary/wererat.mp3"
			},
			"attachedItems": [
				"hand crossbow|phb",
				"shortsword|phb"
			],
			"traitTags": [
				"Keen Senses",
				"Shapechanger"
			],
			"senseTags": [
				"D"
			],
			"actionTags": [
				"Multiattack"
			],
			"languageTags": [
				"C",
				"CS"
			],
			"damageTags": [
				"P"
			],
			"miscTags": [
				"MLW",
				"MW",
				"RW"
			],
			"savingThrowForced": [
				"constitution"
			],
			"hasFluff": true,
			"hasFluffImages": true,
			"fluff": {
				"name": "Wererat",
				"source": "MM",
				"entries": [
					{
						"type": "entries",
						"entries": [
							{
								"type": "entries",
								"entries": [
									"Wererats are cunning lycanthropes with sly, avaricious personalities. They are wiry and twitchy in humanoid form, with thin hair and darting eyes. In their humanoid and hybrid forms, wererats prefer light weapons and use ambush tactics rather than fighting as a pack. Although a wererat can deliver a nasty bite in its rat form, it favors that form for stealthy infiltration and escape rather than combat.",
									"A wererat clan operates much like a thieves' guild, with wererats transmitting their curse only to creatures they want to induct into the clan. Wererats that are accidentally cursed or break loose from the clan's control are quickly hunted down and killed.",
									"Wererat clans are found throughout urban civilization, often dwelling in cellars and catacombs. These creatures are common in the sewers beneath major cities, viewing those subterranean areas as their hunting grounds. Rats and giant rats are commonly found living among wererats."
								]
							}
						]
					},
					{
						"type": "section",
						"name": "Lycanthropes",
						"entries": [
							"One of the most ancient and feared of all curses, lycanthropy can transform the most civilized humanoid into a ravening beast. In its natural humanoid form, a creature cursed by lycanthropy appears as its normal self. Over time, however, many lycanthropes acquire features suggestive of their animal form. In that animal form, a lycanthrope resembles a powerful version of a normal animal. On close inspection, its eyes show a faint spark of unnatural intelligence and might glow red in the dark.",
							"Evil lycanthropes hide among normal folk, emerging in animal form at night to spread terror and bloodshed, especially under a full moon. Good lycanthropes are reclusive and uncomfortable around other civilized creatures, often living alone in wilderness areas far from villages and towns.",
							{
								"type": "entries",
								"entries": [
									{
										"type": "entries",
										"name": "Curse of Lycanthropy",
										"entries": [
											"A humanoid creature can be afflicted with the curse of lycanthropy after being wounded by a lycanthrope, or if one or both of its parents are lycanthropes. A {@spell remove curse} spell can rid an afflicted lycanthrope of the curse, but a natural born lycanthrope can be freed of the curse only with a wish.",
											"A lycanthrope can either resist its curse or embrace it. By resisting the curse, a lycanthrope retains its normal alignment and personality while in humanoid form. It lives its life as it always has, burying deep the bestial urges raging inside it. However, when the full moon rises, the curse becomes too strong to resist, transforming the individual into its beast form-or into a horrible hybrid form that combines animal and humanoid traits. When the moon wanes, the beast within can be controlled once again. Especially if the cursed creature is unaware of its condition, it might not remember the events of its transformation, though those memories often haunt a lycanthrope as bloody dreams.",
											"Some individuals see little point in fighting the curse and accept what they are. With time and experience, they learn to master their shapechanging ability and can assume beast form or hybrid form at will. Most lycanthropes that embrace their bestial natures succumb to bloodlust, becoming evil, opportunistic creatures that prey on the weak."
										]
									}
								]
							},
							{
								"type": "inset",
								"name": "Player Characters as Lycanthropes",
								"entries": [
									"A character who becomes a lycanthrope retains his or her statistics except as specified by lycanthrope type. The character gains the lycanthrope's speeds in non-humanoid form, damage immunities, traits, and actions that don't involve equipment. The character is proficient with the lycanthrope's natural attacks, such as its bite or claws, which deal damage as shown in the lycanthrope's statistics. The character can't speak while in animal form.",
									"A non-lycanthrope humanoid hit by an attack that carries the curse of lycanthropy must succeed on a Constitution saving throw (DC 8 + the lycanthrope's proficiency bonus + the lycanthrope's Constitution modifier) or be cursed. If the character embraces the curse, his or her alignment becomes the one defined for the lycanthrope. The DM is free to decide that a change in alignment places the character under DM control until the curse of lycanthropy is removed.",
									"The following information applies to specific lycanthropes.",
									{
										"type": "entries",
										"entries": [
											{
												"type": "entries",
												"name": "{@creature Werebear}",
												"entries": [
													"The character gains a Strength of 19 if his or her score isn't already higher, and a +1 bonus to AC while in bear or hybrid form (from natural armor). Attack and damage rolls for the natural weapons are based on Strength."
												]
											},
											{
												"type": "entries",
												"name": "{@creature Wereboar}",
												"entries": [
													"The character gains a Strength of 17 if his or her score isn't already higher, and a +1 bonus to AC while in boar or hybrid form (from natural armor). Attack and damage rolls for the tusks are based on Strength. For the Charge trait, the DC is 8 + the character's proficiency bonus + Strength modifier."
												]
											},
											{
												"type": "entries",
												"name": "{@creature Wererat}",
												"entries": [
													"The character gains a Dexterity of 15 if his or her score isn't already higher. Attack and damage rolls for the bite are based on whichever is higher of the character's Strength and Dexterity."
												]
											},
											{
												"type": "entries",
												"name": "{@creature Weretiger}",
												"entries": [
													"The character gains a Strength of 17 if his or her score isn't already higher. Attack and damage rolls for the natural weapons are based on Strength. For the Pounce trait, the DC is 8 + the character's proficiency bonus + Strength modifier."
												]
											},
											{
												"type": "entries",
												"name": "{@creature Werewolf}",
												"entries": [
													"The character gains a Strength of 15 if his or her score isn't already higher, and a +1 bonus to AC while in wolf or hybrid form (from natural armor). Attack and damage rolls for the natural weapons are based on Strength."
												]
											}
										]
									}
								]
							}
						]
					}
				],
				"images": [
					{
						"type": "image",
						"href": {
							"type": "internal",
							"path": "bestiary/MM/Wererat.webp"
						},
						"credit": "Conceptopolis"
					}
				]
			}
		},
		{
			"name": "Nameless Assassin (Corinsson)",
			"source": "Huskies",
			"size": [
				"M"
			],
			"type": "undead",
			"alignment": [
				"N"
			],
			"ac": [
				15
			],
			"hp": {
				"special": "108"
			},
			"speed": {
				"walk": 30,
				"climb": 30
			},
			"str": 12,
			"dex": 18,
			"con": 10,
			"int": 12,
			"wis": 14,
			"cha": 10,
			"save": {
				"dex": "+7",
				"str": "+4",
				"wis": "+5"
			},
			"skill": {
				"acrobatics": "+7",
				"athletics": "+4",
				"stealth": "+10",
				"perception": "+8",
				"investigation": "+7"
			},
			"passive": 18,
			"immune": [
				"poison"
			],
			"conditionImmune": [
				"poisoned"
			],
			"cr": "8",
			"trait": [
				{
					"name": "Dread Ambush",
					"entries": [
						"Get +6 to initiative rolls. In the first round of combat, get an extra attack."
					]
				},
				{
					"name": "Assassinate",
					"entries": [
						"Advantage on attacks against anyone who has not taken a turn. Hits on {@status surprised} creatures are critical."
					]
				},
				{
					"name": "Sharpshooter",
					"entries": [
						"Ignore long range, half cover, three quarters cover. Can choose a -5 penalty on attack roll for a +10 to damage."
					]
				},
				{
					"name": "Unending Breath",
					"entries": [
						"Hold breath indefinitely"
					]
				}
			],
			"action": [
				{
					"name": "Multiattack",
					"entries": [
						"Make 2 attacks (longbow or knife), or 3 on the first round. "
					]
				},
				{
					"name": "Hunting Knife",
					"entries": [
						"{@atk mw} {@hit +7} to hit, reach 5 ft., one target. {@h}7 ({@damage 1d6 + 4}) piercing damage."
					]
				},
				{
					"name": "Longbow",
					"entries": [
						"{@atk rw} {@hit +9} to hit, range 150/600 ft., one target. {@h}8 ({@damage 1d8 + 4}) piercing damage. If the arrow does not hit, all creatures within 10ft of the target must make a DC12 Dex save or take {@damage 1d4} piercing damage."
					]
				},
				{
					"name": "Missilebolt {@recharge 5}",
					"entries": [
						"3 glowing darts of magical force, range 600ft. Each dart automatically deals {@damage 1d10 + 4} force damage."
					]
				},
				{
					"name": "Spell Arrow",
					"entries": [
						"1/day each. Spell effects happen where the arrow lands. ",
						"- {@spell grasping vine} (c): Vine in unoccupied spot. Grab a creature within 30ft, Dex save {@dc 13} (adv if caster can't see). Pull 20 ft towards vine. Bonus action to lash again.",
						"- {@spell spike growth} (c): 20ft radius difficult terrain. {@dice 2d4} piercing for every 5ft of movement."
					]
				},
				{
					"name": "Levitate (1/day)",
					"entries": [
						"{@spell levitate}. DC12 CON save. Use to stop targets from running."
					]
				}
			],
			"bonus": [
				{
					"name": "Cunning Action",
					"entries": [
						"Dash, Disengage, Hide"
					]
				}
			],
			"reaction": [
				{
					"name": "Uncanny Dodge",
					"entries": [
						"Halve damage from an attack you can see"
					]
				}
			],
			"legendaryHeader": [
				"Take one on each round, on initiative 20."
			],
			"legendary": [
				{
					"name": "Assassinate (round 1)",
					"entries": [
						"+6 initiative. Advantage attacks, crit on {@status surprised} creatures, 3 attacks. Take -5 penalty to hit for +10 damage."
					]
				},
				{
					"name": "Spike Growth (round 2)",
					"entries": [
						"Cast spike growth spell arrow. "
					]
				},
				{
					"name": "Missilebolt (round 3)",
					"entries": [
						"Free casting of missilebolt."
					]
				}
			],
			"attachedItems": [
				"longbow|phb"
			],
			"actionTags": [
				"Multiattack"
			],
			"damageTags": [
				"P"
			],
			"miscTags": [
				"MW",
				"RW"
			]
		},
		{
			"name": "Raven (Court of Birds)",
			"source": "Huskies",
			"size": [
				"M"
			],
			"type": "humanoid",
			"alignment": [
				"N"
			],
			"ac": [
				15
			],
			"hp": {
				"formula": "1d8 + 1",
				"average": 88
			},
			"speed": {
				"walk": 30
			},
			"str": 15,
			"dex": 12,
			"con": 12,
			"int": 15,
			"wis": 14,
			"cha": 10,
			"save": {
				"con": "+4",
				"wis": "+5"
			},
			"skill": {
				"insight": "+5",
				"intimidation": "+3",
				"investigation": "+5",
				"perception": "+5"
			},
			"passive": 13,
			"cr": "5",
			"spellcasting": [
				{
					"name": "Spellcasting",
					"type": "spellcasting",
					"headerEntries": [
						"INT (+5) as spellcasting ability, save {@dc 13}"
					],
					"daily": {
						"2e": [
							"{@spell alarm}",
							"{@spell arcane lock}",
							"{@spell detect thoughts}",
							"{@spell zone of truth}"
						],
						"1e": [
							"{@spell silence} c",
							"{@spell slow} c"
						]
					}
				}
			],
			"trait": [
				{
					"name": "Investigative Arcana",
					"entries": [
						"Sense whether magic has been present within 30 in the past 24 hours. Can spend an action to discern the location, effect, types of creature that caused it. "
					]
				}
			],
			"action": [
				{
					"name": "Multiattack",
					"entries": [
						"2 dagger attacks."
					]
				},
				{
					"name": "Dagger",
					"entries": [
						"Melee, reach 5ft. {@hit 5} to hit, 6 ({@dice 1d8 + 2}) slashing plus 7 ({@damage 2d6}) force damage. "
					]
				},
				{
					"name": "Forcebolt Crossbow",
					"entries": [
						"Ranged 100/400 ft. {@hit 3} to hit, 5 ({@dice 1d10}) piercing plus 7 ({@damage 2d6}) force damage. "
					]
				},
				{
					"name": "Detain {@recharge 4}",
					"entries": [
						"Magically bind one creature it can see wihin 30 ft. Target makes DC13 STR save, or be {@condition restrained} and {@condition incapacitated} for 1 minute or until Raven loses {@status concentration}. Target can save at the end of each of its turns. "
					]
				},
				{
					"name": "Cloak of Invisiblity",
					"entries": [
						"Pull the hood up to become {@condition invisible}. Max usage 2 hrs per day."
					]
				},
				{
					"name": "Summon Shadows (1/day)",
					"entries": [
						"Open a cigarette case to summon (how many?) shadows"
					]
				}
			],
			"reaction": [
				{
					"name": "Disrupt Spell (2/day)",
					"entries": [
						"When Raven sees a creature within 60ft casting a spell, it can make the creature do a {@dc 13} INT save, or the spell fails."
					]
				}
			],
			"attachedItems": [
				"dagger|phb"
			],
			"actionTags": [
				"Multiattack"
			],
			"damageTags": [
				"O"
			],
			"spellcastingTags": [
				"O"
			],
			"miscTags": [
				"MLW"
			],
			"savingThrowForcedSpell": [
				"charisma",
				"wisdom"
			]
		},
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
					"type": "spellcasting",
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
					"displayAs": "action"
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
			"tokenUrl": "https://5e.tools/img/MPMM/Bard.png",
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
			"damageTags": [
				"P"
			],
			"spellcastingTags": [
				"CB"
			],
			"miscTags": [
				"MLW",
				"MW",
				"RW"
			],
			"conditionInflictSpell": [
				"charmed",
				"invisible",
				"unconscious"
			],
			"savingThrowForced": [
				"charisma"
			],
			"savingThrowForcedSpell": [
				"wisdom"
			],
			"hasFluff": true,
			"hasFluffImages": true,
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
			}
		},
		{
			"name": "Sahuagin Wraith",
			"group": [
				"Beholders"
			],
			"source": "Huskies",
			"page": 30,
			"basicRules": true,
			"size": [
				"M"
			],
			"type": "aberration",
			"alignment": [
				"L",
				"N"
			],
			"ac": [
				{
					"ac": 16,
					"from": [
						"natural armor"
					]
				}
			],
			"hp": {
				"formula": "6d8 + 12",
				"average": 50
			},
			"speed": {
				"walk": 30,
				"swim": 50
			},
			"str": 8,
			"dex": 14,
			"con": 14,
			"int": 13,
			"wis": 14,
			"cha": 11,
			"skill": {
				"perception": "+6"
			},
			"senses": [
				"darkvision 120 ft."
			],
			"passive": 16,
			"conditionImmune": [
				"prone"
			],
			"languages": [
				"Deep Speech",
				"Undercommon",
				"telepathy 120 ft."
			],
			"cr": "3",
			"trait": [
				{
					"name": "Blood Frenzy",
					"entries": [
						"Advantage on melee attack rolls against any creature that doesn't have all its hit points."
					]
				}
			],
			"action": [
				{
					"name": "Bite/Claws",
					"entries": [
						"{@atk mw} Attacks twice, {@hit 5} to hit, reach 5 ft., one target. {@h}2 ({@damage 1d6 + 3}) piercing damage."
					]
				},
				{
					"name": "Aberrant Breath",
					"entries": [
						"The spectator makes up to two noxious sprays at one or two creatures it can see within 90 feet of it. It can use each ray only once on a turn.",
						{
							"type": "list",
							"style": "list-hang-notitle",
							"items": [
								{
									"type": "item",
									"name": "1. Confusion Ray",
									"style": "italic",
									"entry": "The target must succeed on a {@dc 13} Wisdom saving throw, or it can't take reactions until the end of its next turn. On its turn, the target can't move, and it uses its action to make a melee or ranged attack against a randomly determined creature within range. If the target can't attack, it does nothing on its turn."
								},
								{
									"type": "item",
									"name": "2. Wounding Ray",
									"style": "italic",
									"entry": "The target must make a {@dc 13} Constitution saving throw, taking 16 ({@damage 3d10}) necrotic damage on a failed save, or half as much damage on a successful one."
								}
							]
						}
					]
				}
			],
			"reaction": [
				{
					"name": "Spell Reflection",
					"entries": [
						"If the spectator makes a successful saving throw against a spell, or a spell attack misses it, the spectator can choose another creature (including the spellcaster) it can see within 30 feet of it. The spell targets the chosen creature instead of the spectator. If the spell forced a saving throw, the chosen creature makes its own save. If the spell was an attack, the attack roll is rerolled against the chosen creature."
					]
				}
			],
			"environment": [
				"underdark"
			],
			"token": {
				"name": "Spectator",
				"source": "MM"
			},
			"soundClip": {
				"type": "external",
				"url": "https://5e.tools/audio/bestiary/spectator.mp3"
			},
			"senseTags": [
				"SD"
			],
			"actionTags": [
				"Breath Weapon"
			],
			"languageTags": [
				"DS",
				"TP",
				"U"
			],
			"damageTags": [
				"N",
				"P"
			],
			"miscTags": [
				"MW"
			],
			"savingThrowForced": [
				"constitution",
				"wisdom"
			],
			"hasFluff": true,
			"hasFluffImages": true,
			"fluff": {
				"name": "Spectator",
				"source": "MM",
				"entries": [
					{
						"type": "entries",
						"entries": [
							{
								"type": "entries",
								"entries": [
									"A spectator is a lesser beholder that is summoned from another plane of existence by a magical ritual, the components of which include four beholder eyestalks that are consumed by the ritual's magic. Appropriately, a spectator has four eyestalks, two on each side of the wide eye at the center of its four-foot diameter body.",
									{
										"name": "Magical Guardians",
										"type": "entries",
										"entries": [
											"A summoned spectator guards a location or a treasure of its summoner's choice for 101 years, allowing no creature but its summoner to enter the area or access the item, unless the summoner instructed otherwise. If the item is stolen or destroyed before the years have all passed, a summoned spectator vanishes. It otherwise never abandons its post."
										]
									},
									{
										"name": "Glimmers of Madness",
										"type": "entries",
										"entries": [
											"Though it can speak, a spectator communicates primarily by way of telepathy. It is civil while on guard, openly discussing its orders and its summoner. However, even a brief conversation with a spectator is enough to reveal quirks in its personality brought on by its years of isolation. It might invent imaginary enemies, refer to itself in the third person, or try to adopt the voice of its summoner.",
											"Like any beholder, a spectator views itself as the epitome of its kind, and it has an intense hatred of other spectators. If two spectators encounter one another, they almost always fight to the death."
										]
									},
									{
										"type": "entries",
										"name": "Freed from Service",
										"entries": [
											"When a spectator has fulfilled its service, it is free to do as it pleases. Many take up residence in the places they previously guarded, especially if their summoners have died. With the spectator's loss of purpose, the flickers of madness it displayed during its servitude flourish."
										]
									}
								]
							}
						]
					}
				],
				"images": [
					{
						"type": "image",
						"href": {
							"type": "internal",
							"path": "bestiary/MM/Spectator.webp"
						},
						"credit": "Kieran Yanner"
					}
				]
			}
		},
		{
			"name": "Shrewseer",
			"isNpc": true,
			"isNamedCreature": true,
			"source": "Huskies",
			"page": 159,
			"size": [
				"M"
			],
			"type": {
				"type": "humanoid",
				"tags": [
					{
						"tag": "elf",
						"prefix": "Wood"
					}
				]
			},
			"alignment": [
				"A"
			],
			"ac": [
				11,
				{
					"ac": 16,
					"condition": "with {@spell barkskin}",
					"braces": true
				}
			],
			"hp": {
				"average": 27,
				"formula": "5d8 + 5"
			},
			"speed": {
				"walk": 35
			},
			"str": 10,
			"dex": 12,
			"con": 13,
			"int": 12,
			"wis": 15,
			"cha": 11,
			"skill": {
				"nature": "+3",
				"perception": "+4",
				"deception": "+2"
			},
			"senses": [
				"darkvision 60 ft."
			],
			"passive": 14,
			"languages": [
				"Druidic plus any two languages",
				"Elvish"
			],
			"cr": "2",
			"spellcasting": [
				{
					"name": "Spellcasting",
					"type": "spellcasting",
					"headerEntries": [
						"Shrewseer is a 4th-level spellcaster. Its spellcasting ability is Wisdom (spell save {@dc 12}, {@hit 4} to hit with spell attacks). It has the following druid spells prepared:"
					],
					"spells": {
						"0": {
							"spells": [
								"{@spell druidcraft}",
								"{@spell produce flame}",
								"{@spell shillelagh}"
							]
						},
						"1": {
							"spells": [
								"{@spell entangle}",
								"{@spell longstrider}",
								"{@spell speak with animals}",
								"{@spell thunderwave}"
							],
							"slots": 4
						},
						"2": {
							"spells": [
								"{@spell animal messenger}",
								"{@spell barkskin}"
							],
							"slots": 3
						}
					},
					"ability": "wis"
				}
			],
			"trait": [
				{
					"name": "Fey Ancestry",
					"entries": [
						"Shrewseer has advantage on saving throws against being {@condition charmed}, and magic can't put Eira to sleep."
					]
				},
				{
					"name": "Mask of the Wild",
					"entries": [
						"Shrewseer can attempt to {@action hide} even when they are only lightly obscured by foliage, heavy rain, falling snow, mist, and other natural phenomena."
					]
				}
			],
			"action": [
				{
					"name": "Quarterstaff",
					"entries": [
						"{@atk mw} {@hit 2} to hit ({@hit 4} to hit with shillelagh), reach 5 ft., one target. {@h}3 ({@damage 1d6}) bludgeoning damage, 4 ({@damage 1d8}) bludgeoning damage if wielded with two hands, or 6 ({@damage 1d8 + 2}) bludgeoning damage with {@spell shillelagh}."
					]
				}
			],
			"tokenUrl": "https://5e.tools/img/TftYP/Eira.png",
			"traitTags": [
				"Fey Ancestry"
			],
			"senseTags": [
				"D"
			],
			"languageTags": [
				"DU",
				"E",
				"X"
			],
			"damageTags": [
				"B"
			],
			"damageTagsSpell": [
				"F",
				"T"
			],
			"spellcastingTags": [
				"CD"
			],
			"miscTags": [
				"MW"
			]
		},
		{
			"name": "Vulture (Court of Birds)",
			"source": "Huskies",
			"size": [
				"M"
			],
			"type": "humanoid",
			"alignment": [
				"N"
			],
			"ac": [
				10
			],
			"hp": {
				"formula": "1d8",
				"average": 27
			},
			"speed": {
				"walk": 30
			},
			"str": 10,
			"dex": 12,
			"con": 10,
			"int": 14,
			"wis": 14,
			"cha": 10,
			"save": {
				"wis": "+4"
			},
			"skill": {
				"deception": "+2",
				"history": "+4",
				"insight": "+4",
				"persuasion": "+2"
			},
			"passive": 12,
			"cr": "0",
			"trait": [
				{
					"name": "Political SAvvy",
					"entries": [
						"Advantage on saves to avoid or end the {@condition charmed} condition, and resist magical suggestion."
					]
				}
			],
			"action": [
				{
					"name": "Poison Dagger",
					"entries": [
						"Melee, range 5ft. {@hit 3} to hit, 4 ({@dice 1d4 + 1}) piercing, and the target must make a DC12 CON save or take 5 ({@dice 1d10}) poison dmg. "
					]
				},
				{
					"name": "Beguiling Whisper (1/day)",
					"entries": [
						"One creature within 30ft who can hear Vulture must make a DC14 WIS save. The creature has disadvantage if it was targeted within the last 24hrs. On a fail, the target is {@condition charmed} and considers Vulture a trustworthy source of advice for 1hr, or until the noble attacks the target or allies. "
					]
				}
			],
			"miscTags": [
				"MLW"
			],
			"conditionInflict": [
				"charmed"
			]
		}
	]
}
```