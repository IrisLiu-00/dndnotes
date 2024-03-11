```
{
   "_meta":{
      "sources":[
         {
            "json":"Huskies",
            "abbreviation":"Hsk",
            "full":"Huskies",
            "url":"",
            "authors":[
               
            ],
            "convertedBy":[
               
            ]
         }
      ]
   },
   "monster":[
      {
         "name":"Shrewseer",
         "isNpc":true,
         "isNamedCreature":true,
         "source":"Huskies",
         "page":159,
         "traitTags":[
            "Fey Ancestry"
         ],
         "size":[
            "M"
         ],
         "type":{
            "type":"humanoid",
            "tags":[
               {
                  "tag":"elf",
                  "prefix":"Wood"
               }
            ]
         },
         "alignment":[
            "A"
         ],
         "ac":[
            11,
            {
               "ac":16,
               "condition":"with {@spell barkskin}",
               "braces":true
            }
         ],
         "hp":{
            "average":27,
            "formula":"5d8 + 5"
         },
         "speed":{
            "walk":35
         },
         "str":10,
         "dex":12,
         "con":13,
         "int":12,
         "wis":15,
         "cha":11,
         "skill":{
            "nature":"+3",
            "perception":"+4",
            "deception":"+2"
         },
         "passive":14,
         "languages":[
            "Druidic plus any two languages",
            "Elvish"
         ],
         "cr":"2",
         "spellcasting":[
            {
               "name":"Spellcasting",
               "headerEntries":[
                  "Shrewseer is a 4th-level spellcaster. Its spellcasting ability is Wisdom (spell save {@dc 12}, {@hit 4} to hit with spell attacks). It has the following druid spells prepared:"
               ],
               "spells":{
                  "0":{
                     "spells":[
                        "{@spell druidcraft}",
                        "{@spell produce flame}",
                        "{@spell shillelagh}"
                     ]
                  },
                  "1":{
                     "spells":[
                        "{@spell entangle}",
                        "{@spell longstrider}",
                        "{@spell speak with animals}",
                        "{@spell thunderwave}"
                     ],
                     "slots":4
                  },
                  "2":{
                     "spells":[
                        "{@spell animal messenger}",
                        "{@spell barkskin}"
                     ],
                     "slots":3
                  }
               },
               "ability":"wis",
               "type":"spellcasting"
            }
         ],
         "action":[
            {
               "name":"Quarterstaff",
               "entries":[
                  "{@atk mw} {@hit 2} to hit ({@hit 4} to hit with shillelagh), reach 5 ft., one target. {@h}3 ({@damage 1d6}) bludgeoning damage, 4 ({@damage 1d8}) bludgeoning damage if wielded with two hands, or 6 ({@damage 1d8 + 2}) bludgeoning damage with {@spell shillelagh}."
               ]
            }
         ],
         "languageTags":[
            "DU",
            "X",
            "E"
         ],
         "damageTags":[
            "B"
         ],
         "damageTagsSpell":[
            "F",
            "T"
         ],
         "spellcastingTags":[
            "CD"
         ],
         "miscTags":[
            "MW"
         ],
         "senses":[
            "darkvision 60 ft."
         ],
         "trait":[
            {
               "name":"Fey Ancestry",
               "entries":[
                  "Shrewseer has advantage on saving throws against being {@condition charmed}, and magic can't put Eira to sleep."
               ]
            },
            {
               "name":"Mask of the Wild",
               "entries":[
                  "Shrewseer can attempt to {@action hide} even when they are only lightly obscured by foliage, heavy rain, falling snow, mist, and other natural phenomena."
               ]
            }
         ],
         "tokenUrl":"https://5e.tools/img/TftYP/Eira.png",
         "senseTags":[
            "D"
         ]
      },
      {
         "name":"Basta",
         "source":"Huskies",
         "page":165,
         "size":[
            "M"
         ],
         "type":{
            "type":"humanoid",
            "note":"Dwarf"
         },
         "ac":[
            {
               "ac":15,
               "from":[
                  "Unarmored Defense"
               ]
            }
         ],
         "hp":{
            "formula":"10d8 + 10",
            "average":55
         },
         "speed":{
            "walk":40
         },
         "str":12,
         "dex":16,
         "con":12,
         "int":10,
         "wis":14,
         "cha":10,
         "skill":{
            "perception":"+4",
            "acrobatics":"+5",
            "stealth":"+5"
         },
         "passive":14,
         "languages":[
            "Common"
         ],
         "cr":"3",
         "action":[
            {
               "name":"Multiattack",
               "entries":[
                  "The monk makes two attacks."
               ]
            },
            {
               "name":"Mace",
               "entries":[
                  "{@atk mw} {@hit 6} to hit, reach 5 ft., one target. {@h}7 ({@damage 1d8 + 3}) bludgeoning damage. When you hit another creature, you can spend 1 ki point to attempt a stunning strike. The target must succeed on a Constitution saving throw ({@dc 13}) or be {@condition stunned} until the end of your next turn."
               ]
            }
         ],
         "attachedItems":[
            "mace|phb"
         ],
         "actionTags":[
            "Multiattack"
         ],
         "languageTags":[
            "C"
         ],
         "miscTags":[
            "MW",
            "MLW"
         ],
         "tokenUrl":"https://5e.tools/img/CM/Immortal Lotus Monk.png",
         "senses":[
            "darkvision 60 ft."
         ],
         "senseTags":[
            "D"
         ],
         "resist":[
            "poison"
         ],
         "bonusHeader":[
            "6 ki points"
         ],
         "bonus":[
            {
               "name":"Flurry of blows",
               "entries":[
                  "Immediately after you take the Attack action on your turn, you can spend 1 ki point to make two unarmed strikes: {@hit 6} to hit, {@damage 1d6 + 3} damage. You gain the benefit of the Disengage action, and your walking speed increases by 10 feet until the end of the current turn"
               ]
            }
         ],
         "conditionInflict":[
            "stunned"
         ],
         "reaction":[
            {
               "name":"Tipsy Sway",
               "entries":[
                  "When a creature misses you with a melee attack roll, you can spend 1 ki point as a reaction to cause that attack to hit one creature of your choice, other than the attacker, that you can see within 5 feet of you."
               ]
            }
         ],
         "damageTags":[
            "B"
         ]
      },
      {
         "name":"Mushika",
         "group":[
            "Lycanthropes"
         ],
         "source":"Huskies",
         "page":209,
         "size":[
            "M"
         ],
         "type":{
            "type":"humanoid",
            "tags":[
               "human",
               "shapechanger"
            ]
         },
         "alignment":[
            "L",
            "E"
         ],
         "ac":[
            12
         ],
         "hp":{
            "average":33,
            "formula":"6d8 + 6"
         },
         "speed":{
            "walk":30
         },
         "str":10,
         "dex":15,
         "con":12,
         "int":11,
         "wis":10,
         "cha":8,
         "skill":{
            "perception":"+2",
            "stealth":"+4"
         },
         "senses":[
            "darkvision 60 ft. (rat form only)"
         ],
         "passive":12,
         "immune":[
            {
               "immune":[
                  "bludgeoning",
                  "piercing",
                  "slashing"
               ],
               "note":"from nonmagical attacks that aren't silvered",
               "cond":true
            }
         ],
         "languages":[
            "Common (can't speak in rat form)"
         ],
         "cr":"2",
         "trait":[
            {
               "name":"Shapechanger",
               "entries":[
                  "The wererat can use its action to polymorph into a rat-humanoid hybrid or into a giant rat, or back into its true form, which is humanoid. Its statistics, other than its size, are the same in each form. Any equipment it is wearing or carrying isn't transformed. It reverts to its true form if it dies."
               ]
            },
            {
               "name":"Keen Smell",
               "entries":[
                  "The wererat has advantage on Wisdom ({@skill Perception}) checks that rely on smell."
               ]
            }
         ],
         "action":[
            {
               "name":"Multiattack (Humanoid or Hybrid Form Only)",
               "entries":[
                  "The wererat makes two attacks, only one of which can be a bite."
               ]
            },
            {
               "name":"Bite (Rat or Hybrid Form Only)",
               "entries":[
                  "{@atk mw} {@hit 4} to hit, reach 5 ft., one target. {@h}4 ({@damage 1d4 + 2}) piercing damage. If the target is a humanoid, it must succeed on a {@dc 11} Constitution saving throw or be cursed with wererat lycanthropy."
               ]
            },
            {
               "name":"Shortsword (Humanoid or Hybrid Form Only)",
               "entries":[
                  "{@atk mw} {@hit 4} to hit, reach 5 ft., one target. {@h}5 ({@damage 1d6 + 2}) piercing damage."
               ]
            },
            {
               "name":"Hand Crossbow (Humanoid or Hybrid Form Only)",
               "entries":[
                  "{@atk rw} {@hit 4} to hit, range 30/120 ft., one target. {@h}5 ({@damage 1d6 + 2}) piercing damage."
               ]
            },
            {
               "name":"Detonator",
               "entries":[
                  "1/day. Range 30 ft. {@dc 14} DEX save in 10 ft radius for {@dice 2d6} fire dmg."
               ]
            }
         ],
         "variant":[
            {
               "type":"variant",
               "name":"Nonhuman Lycanthropes",
               "entries":[
                  "The statistics presented in this section assume a base creature of human. However, you can also use the statistics to represent nonhuman lycanthropes, adding verisimilitude by allowing a nonhuman lycanthrope to retain one or more of its humanoid racial traits. For example, an elf werewolf might have the Fey Ancestry trait."
               ]
            }
         ],
         "environment":[
            "forest",
            "urban"
         ],
         "soundClip":{
            "type":"external",
            "url":"https://5e.tools/audio/bestiary/wererat.mp3"
         },
         "attachedItems":[
            "hand crossbow|phb",
            "shortsword|phb"
         ],
         "traitTags":[
            "Keen Senses",
            "Shapechanger"
         ],
         "senseTags":[
            "D"
         ],
         "actionTags":[
            "Multiattack"
         ],
         "languageTags":[
            "C",
            "CS"
         ],
         "miscTags":[
            "MW",
            "MLW",
            "RW"
         ],
         "hasFluff":true,
         "hasFluffImages":true,
         "tokenUrl":"https://5e.tools/img/MM/Wererat.png",
         "fluff":{
            "name":"Wererat",
            "source":"MM",
            "entries":[
               {
                  "type":"entries",
                  "entries":[
                     {
                        "type":"entries",
                        "entries":[
                           "Wererats are cunning lycanthropes with sly, avaricious personalities. They are wiry and twitchy in humanoid form, with thin hair and darting eyes. In their humanoid and hybrid forms, wererats prefer light weapons and use ambush tactics rather than fighting as a pack. Although a wererat can deliver a nasty bite in its rat form, it favors that form for stealthy infiltration and escape rather than combat.",
                           "A wererat clan operates much like a thieves' guild, with wererats transmitting their curse only to creatures they want to induct into the clan. Wererats that are accidentally cursed or break loose from the clan's control are quickly hunted down and killed.",
                           "Wererat clans are found throughout urban civilization, often dwelling in cellars and catacombs. These creatures are common in the sewers beneath major cities, viewing those subterranean areas as their hunting grounds. Rats and giant rats are commonly found living among wererats."
                        ]
                     }
                  ]
               },
               {
                  "type":"section",
                  "name":"Lycanthropes",
                  "entries":[
                     "One of the most ancient and feared of all curses, lycanthropy can transform the most civilized humanoid into a ravening beast. In its natural humanoid form, a creature cursed by lycanthropy appears as its normal self. Over time, however, many lycanthropes acquire features suggestive of their animal form. In that animal form, a lycanthrope resembles a powerful version of a normal animal. On close inspection, its eyes show a faint spark of unnatural intelligence and might glow red in the dark.",
                     "Evil lycanthropes hide among normal folk, emerging in animal form at night to spread terror and bloodshed, especially under a full moon. Good lycanthropes are reclusive and uncomfortable around other civilized creatures, often living alone in wilderness areas far from villages and towns.",
                     {
                        "type":"entries",
                        "entries":[
                           {
                              "type":"entries",
                              "name":"Curse of Lycanthropy",
                              "entries":[
                                 "A humanoid creature can be afflicted with the curse of lycanthropy after being wounded by a lycanthrope, or if one or both of its parents are lycanthropes. A {@spell remove curse} spell can rid an afflicted lycanthrope of the curse, but a natural born lycanthrope can be freed of the curse only with a wish.",
                                 "A lycanthrope can either resist its curse or embrace it. By resisting the curse, a lycanthrope retains its normal alignment and personality while in humanoid form. It lives its life as it always has, burying deep the bestial urges raging inside it. However, when the full moon rises, the curse becomes too strong to resist, transforming the individual into its beast form-or into a horrible hybrid form that combines animal and humanoid traits. When the moon wanes, the beast within can be controlled once again. Especially if the cursed creature is unaware of its condition, it might not remember the events of its transformation, though those memories often haunt a lycanthrope as bloody dreams.",
                                 "Some individuals see little point in fighting the curse and accept what they are. With time and experience, they learn to master their shapechanging ability and can assume beast form or hybrid form at will. Most lycanthropes that embrace their bestial natures succumb to bloodlust, becoming evil, opportunistic creatures that prey on the weak."
                              ]
                           }
                        ]
                     },
                     {
                        "type":"inset",
                        "name":"Player Characters as Lycanthropes",
                        "entries":[
                           "A character who becomes a lycanthrope retains his or her statistics except as specified by lycanthrope type. The character gains the lycanthrope's speeds in non-humanoid form, damage immunities, traits, and actions that don't involve equipment. The character is proficient with the lycanthrope's natural attacks, such as its bite or claws, which deal damage as shown in the lycanthrope's statistics. The character can't speak while in animal form.",
                           "A non-lycanthrope humanoid hit by an attack that carries the curse of lycanthropy must succeed on a Constitution saving throw (DC 8 + the lycanthrope's proficiency bonus + the lycanthrope's Constitution modifier) or be cursed. If the character embraces the curse, his or her alignment becomes the one defined for the lycanthrope. The DM is free to decide that a change in alignment places the character under DM control until the curse of lycanthropy is removed.",
                           "The following information applies to specific lycanthropes.",
                           {
                              "type":"entries",
                              "entries":[
                                 {
                                    "type":"entries",
                                    "name":"{@creature Werebear}",
                                    "entries":[
                                       "The character gains a Strength of 19 if his or her score isn't already higher, and a +1 bonus to AC while in bear or hybrid form (from natural armor). Attack and damage rolls for the natural weapons are based on Strength."
                                    ]
                                 },
                                 {
                                    "type":"entries",
                                    "name":"{@creature Wereboar}",
                                    "entries":[
                                       "The character gains a Strength of 17 if his or her score isn't already higher, and a +1 bonus to AC while in boar or hybrid form (from natural armor). Attack and damage rolls for the tusks are based on Strength. For the Charge trait, the DC is 8 + the character's proficiency bonus + Strength modifier."
                                    ]
                                 },
                                 {
                                    "type":"entries",
                                    "name":"{@creature Wererat}",
                                    "entries":[
                                       "The character gains a Dexterity of 15 if his or her score isn't already higher. Attack and damage rolls for the bite are based on whichever is higher of the character's Strength and Dexterity."
                                    ]
                                 },
                                 {
                                    "type":"entries",
                                    "name":"{@creature Weretiger}",
                                    "entries":[
                                       "The character gains a Strength of 17 if his or her score isn't already higher. Attack and damage rolls for the natural weapons are based on Strength. For the Pounce trait, the DC is 8 + the character's proficiency bonus + Strength modifier."
                                    ]
                                 },
                                 {
                                    "type":"entries",
                                    "name":"{@creature Werewolf}",
                                    "entries":[
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
            "images":[
               {
                  "type":"image",
                  "href":{
                     "type":"internal",
                     "path":"bestiary/MM/Wererat.webp"
                  },
                  "credit":"Conceptopolis"
               }
            ]
         },
         "damageTags":[
            "P"
         ],
         "savingThrowForced":[
            "constitution"
         ]
      },
      {
         "name":"Ringley",
         "source":"Huskies",
         "page":59,
         "size":[
            "M"
         ],
         "type":"humanoid",
         "alignment":[
            "A"
         ],
         "ac":[
            {
               "ac":15,
               "from":[
                  "{@item chain shirt|phb}"
               ]
            }
         ],
         "hp":{
            "formula":"7d8 + 7",
            "average":38
         },
         "speed":{
            "walk":30
         },
         "str":11,
         "dex":14,
         "con":12,
         "int":10,
         "wis":13,
         "cha":14,
         "save":{
            "dex":"+4",
            "wis":"+3"
         },
         "skill":{
            "acrobatics":"+4",
            "perception":"+5",
            "performance":"+6"
         },
         "passive":15,
         "languages":[
            "any two languages"
         ],
         "cr":"2",
         "spellcasting":[
            {
               "name":"Spellcasting",
               "headerEntries":[
                  "The bard casts one of the following spells, using Charisma as the spellcasting ability (spell save {@dc 12}):"
               ],
               "will":[
                  "{@spell dancing lights}",
                  "{@spell mage hand}",
                  "{@spell prestidigitation}"
               ],
               "daily":{
                  "1e":[
                     "{@spell charm person}",
                     "{@spell invisibility}",
                     "{@spell sleep}"
                  ]
               },
               "ability":"cha",
               "displayAs":"action",
               "type":"spellcasting"
            }
         ],
         "action":[
            {
               "name":"Multiattack",
               "entries":[
                  "The bard makes two Shortsword or Shortbow attacks. It can replace one attack with a use of Spellcasting."
               ]
            },
            {
               "name":"Shortsword",
               "entries":[
                  "{@atk mw} {@hit 4} to hit, reach 5 ft., one target. {@h}5 ({@damage 1d6 + 2}) piercing damage."
               ]
            },
            {
               "name":"Shortbow",
               "entries":[
                  "{@atk rw} {@hit 4} to hit, range 80/320 ft., one target. {@h}5 ({@damage 1d6 + 2}) piercing damage."
               ]
            }
         ],
         "bonus":[
            {
               "name":"Taunt (2/Day)",
               "entries":[
                  "The bard targets one creature within 30 feet of it. If the target can hear the bard, the target must succeed on a {@dc 12} Charisma saving throw or have disadvantage on ability checks, attack rolls, and saving throws until the start of the bard's next turn."
               ]
            },
            {
               "name":"Bardic Inspiration (3/Day)",
               "entries":[
                  "Give a {@dice 1d8}"
               ]
            }
         ],
         "environment":[
            "urban"
         ],
         "soundClip":{
            "type":"external",
            "url":"https://5e.tools/audio/bestiary/bard.mp3"
         },
         "attachedItems":[
            "shortbow|phb",
            "shortsword|phb"
         ],
         "actionTags":[
            "Multiattack"
         ],
         "languageTags":[
            "X"
         ],
         "spellcastingTags":[
            "CB"
         ],
         "miscTags":[
            "MW",
            "MLW",
            "RW"
         ],
         "conditionInflictSpell":[
            "charmed",
            "invisible",
            "unconscious"
         ],
         "hasFluff":true,
         "hasFluffImages":true,
         "tokenUrl":"https://5e.tools/img/MPMM/Bard.png",
         "fluff":{
            "name":"Bard",
            "source":"MPMM",
            "entries":[
               "Bards are gifted poets, storytellers, and entertainers who travel far and wide. They're commonly found in taverns or in the company of jolly bands of adventurers, rough-and-tumble mercenaries, and wealthy patrons.",
               "Each bard is a master of at least one type of performance. You may choose a bard's main type, or you may roll on the Bard {@skill Performance} Types table to determine it.",
               {
                  "type":"table",
                  "caption":"Bard Performance Types",
                  "colLabels":[
                     "d10",
                     "Performance Type"
                  ],
                  "colStyles":[
                     "col-1 text-center",
                     "col-11"
                  ],
                  "rows":[
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
            "images":[
               {
                  "type":"image",
                  "href":{
                     "type":"internal",
                     "path":"bestiary/MPMM/Bard.webp"
                  },
                  "credit":"Rudy Siswanto"
               }
            ]
         },
         "damageTags":[
            "P"
         ],
         "savingThrowForced":[
            "charisma"
         ],
         "savingThrowForcedSpell":[
            "wisdom"
         ]
      },
      {
         "name":"Gyrfalcon",
         "source":"Huskies",
         "level":7,
         "size":[
            "M"
         ],
         "type":{
            "type":"humanoid",
            "sidekickType":"warrior",
            "sidekickHidden":true
         },
         "ac":[
            {
               "ac":20,
               "from":[
                  "{@item plate armor|phb}",
                  "{@item shield|phb}"
               ]
            },
            15
         ],
         "hp":{
            "average":52,
            "formula":"8d8 + 16"
         },
         "speed":{
            "walk":30
         },
         "str":16,
         "dex":14,
         "con":14,
         "int":10,
         "wis":12,
         "cha":10,
         "save":{
            "con":"+5"
         },
         "skill":{
            "athletics":"+6",
            "perception":"+4",
            "survival":"+4"
         },
         "passive":14,
         "languages":[
            "Common",
            "plus one of your choice"
         ],
         "trait":[
            {
               "name":"Battle Readiness",
               "entries":[
                  "The warrior has advantage on initiative rolls."
               ]
            },
            {
               "name":"Improved Critical",
               "entries":[
                  "The warrior's attack rolls score a critical hit on a roll of 19 or 20 on the {@dice d20}."
               ]
            }
         ],
         "action":[
            {
               "name":"Extra Attack",
               "entries":[
                  "The warrior can attack twice, instead of once, whenever it takes the {@action Attack} action on its turn."
               ]
            },
            {
               "name":"Longsword",
               "entries":[
                  "{@atk mw} {@hit 6} to hit, reach 5 ft., one target. {@h}7 ({@damage 1d8 + 3}) slashing damage, or 8 ({@damage 1d10 + 3}) slashing damage if used with two hands."
               ]
            },
            {
               "name":"Longbow",
               "entries":[
                  "{@atk rw} {@hit 5} to hit, range 150/600 ft., one target. {@h}6 ({@damage 1d8 + 2}) piercing damage."
               ]
            }
         ],
         "reaction":[
            {
               "name":"Protection (Defender Only)",
               "entries":[
                  "The warrior imposes disadvantage on the attack roll of a creature within 5 feet of it whose target isn't the warrior. The warrior must be able to see the attacker."
               ]
            }
         ],
         "languageTags":[
            "C"
         ],
         "damageTags":[
            "P",
            "S"
         ],
         "miscTags":[
            "MW",
            "RW",
            "RNG"
         ],
         "tokenUrl":"https://5e.tools/img/SLW/Warrior.png"
      },
      {
         "name":"Clockwork (Bounty Hunter)",
         "size":[
            "M"
         ],
         "type":"humanoid",
         "source":"Huskies",
         "alignment":[
            "C",
            "N"
         ],
         "ac":[
            {
               "ac":14,
               "from":[
                  "Leather armor"
               ]
            }
         ],
         "hp":{
            "special":"120"
         },
         "speed":{
            "walk":30
         },
         "str":12,
         "dex":16,
         "con":14,
         "int":10,
         "wis":8,
         "cha":14,
         "passive":9,
         "cr":"4",
         "level":7,
         "save":{
            "dex":"+6",
            "cha":"+5"
         },
         "skill":{
            "deception":"+5",
            "athletics":"+4"
         },
         "resist":[
            "fire"
         ],
         "senses":[
            "darkvision 30 ft."
         ],
         "senseTags":[
            "D"
         ],
         "spellcasting":[
            {
               "name":"Spellcasting",
               "headerEntries":[
                  "Attack +5, Save {@dc 13}"
               ],
               "spells":{
                  "3":{
                     "spells":[
                        "{@spell dispel magic}"
                     ],
                     "slots":3
                  },
                  "4":{
                     "spells":[
                        "{@spell summon construct|TCE}"
                     ],
                     "slots":1
                  }
               },
               "type":"spellcasting"
            }
         ],
         "spellcastingTags":[
            "O"
         ],
         "action":[
            {
               "name":"Chain",
               "entries":[
                  "2 attacks with chain. {@atk mw} {@hit 6} to hit, reach 10 ft., one target. {@h}15 ({@damage 2d6 + 9}) slashing damage. Bonus action STR contest to be pulled 20ft. "
               ]
            },
            {
               "name":"Stasis Charge",
               "entries":[
                  "(3/day) Throw a bomb with 20ft radius, center within 30ft of you. All targets within must make a WIS save {@dc 13} or be frozen in time ({@condition paralyzed}) until the end of Clockwork's next turn. "
               ]
            }
         ],
         "miscTags":[
            "MW",
            "RCH"
         ],
         "reaction":[
            {
               "name":"Chronal Shift",
               "entries":[
                  "(2/day) After you or a creature you can see within 30 feet of you makes an attack roll, an ability check, or a saving throw, you can force the creature to reroll. You make this decision after you see whether the roll succeeds or fails. The target must use the result of the second roll."
               ]
            }
         ],
         "bonus":[
            {
               "name":"Time Bomb",
               "entries":[
                  "(4/day) Throw a detonator with range 30ft, radius 10ft. At the end of Clockwork's next turn, the bomb goes off for {@dice 2d6} fire dmg (DEX save 13 for half)."
               ]
            }
         ],
         "damageTags":[
            "S"
         ]
      },
      {
         "name":"Captain Stevian",
         "source":"Huskies",
         "size":[
            "M"
         ],
         "type":{
            "type":"humanoid",
            "tags":[
               "any race"
            ]
         },
         "alignment":[
            "NX",
            "C",
            "G",
            "NY",
            "E"
         ],
         "ac":[
            {
               "ac":15,
               "from":[
                  "{@item studded leather armor|phb|studded leather}"
               ]
            }
         ],
         "hp":{
            "average":65,
            "formula":"10d8 + 20"
         },
         "speed":{
            "walk":30
         },
         "str":15,
         "dex":16,
         "con":14,
         "int":14,
         "wis":11,
         "cha":14,
         "save":{
            "str":"+4",
            "dex":"+5",
            "wis":"+2"
         },
         "skill":{
            "athletics":"+4",
            "perception":"+2"
         },
         "passive":12,
         "languages":[
            "any two languages"
         ],
         "cr":"2",
         "action":[
            {
               "name":"Multiattack",
               "entries":[
                  "The captain makes 2 melee attacks with the longsword or 2 ranged attacks with the crossbow. "
               ]
            },
            {
               "name":"Longsword",
               "entries":[
                  "{@atk mw} {@hit 5} to hit, reach 5 ft., one target. {@h}8 ({@damage 1d10 + 3}) slashing damage."
               ]
            },
            {
               "name":"Crossbow",
               "entries":[
                  "{@atk rw} {@hit 5} to hit, reach 5 ft. or range 20/60 ft., one target. {@h}6 ({@damage 1d6 + 3}) piercing damage."
               ]
            }
         ],
         "reaction":[
            {
               "name":"Parry",
               "entries":[
                  "The captain adds 2 to its AC against one melee attack that would hit it. To do so, the captain must see the attacker and be wielding a melee weapon."
               ]
            }
         ],
         "environment":[
            "arctic",
            "coastal",
            "desert",
            "forest",
            "hill",
            "urban"
         ],
         "soundClip":{
            "type":"external",
            "url":"https://5e.tools/audio/bestiary/bandit-captain.mp3"
         },
         "actionTags":[
            "Multiattack",
            "Parry"
         ],
         "languageTags":[
            "X"
         ],
         "damageTags":[
            "P",
            "S"
         ],
         "miscTags":[
            "MW",
            "RW"
         ],
         "hasFluff":true,
         "hasFluffImages":true,
         "tokenUrl":"https://5e.tools/img/MM/Bandit Captain.png",
         "fluff":{
            "name":"Bandit Captain",
            "source":"MM",
            "entries":[
               {
                  "type":"entries",
                  "entries":[
                     {
                        "type":"entries",
                        "entries":[
                           "It takes a strong personality, ruthless cunning, and a silver tongue to keep a gang of bandits in line. The bandit captain has these qualities in spades.",
                           "In addition to managing a crew of selfish malcontents, the pirate captain is a variation of the bandit captain, with a ship to protect and command. To keep the crew in line, the captain must mete out rewards and punishment on a regular basis.",
                           "More than treasure, a bandit captain or pirate captain craves infamy. A prisoner who appeals to the captain's vanity or ego is more likely to be treated fairly than a prisoner who does not or claims not to know anything of the captain's colorful reputation."
                        ]
                     }
                  ]
               }
            ],
            "images":[
               {
                  "type":"image",
                  "href":{
                     "type":"internal",
                     "path":"bestiary/MM/Bandit Captain.jpg"
                  }
               }
            ]
         },
         "shortName":"Stevian"
      },
      {
         "name":"Duke Vasilev",
         "size":[
            "M"
         ],
         "type":{
            "type":"humanoid",
            "tags":[
               {
                  "tag":"elf",
                  "prefix":"Drow"
               }
            ]
         },
         "source":"Huskies",
         "alignment":[
            "N"
         ],
         "ac":[
            10
         ],
         "hp":{
            "formula":"1d8 + 1",
            "average":5
         },
         "speed":{
            "walk":30
         },
         "str":10,
         "dex":16,
         "con":12,
         "int":16,
         "wis":10,
         "cha":14,
         "passive":10,
         "cr":"4",
         "shortName":"Vasilev",
         "level":8,
         "senses":[
            "Darkvision 120ft"
         ],
         "senseTags":[
            "D"
         ],
         "save":{
            "dex":"+6",
            "int":"+6",
            "wis":"+3"
         },
         "skill":{
            "perception":"+9",
            "investigation":"+6",
            "persuasion":"+5",
            "deception":"+8",
            "intimidation":"+5"
         },
         "conditionImmune":[
            {
               "conditionImmune":[
                  "charmed"
               ],
               "note":"or magically put to sleep"
            }
         ],
         "spellcasting":[
            {
               "name":"Spellcasting",
               "spells":{
                  "0":{
                     "spells":[
                        "{@spell mage hand}",
                        "{@spell message}"
                     ]
                  }
               },
               "type":"spellcasting"
            }
         ],
         "spellcastingTags":[
            "O"
         ]
      },
      {
         "name":"Luca Industries Automata",
         "size":[
            "M"
         ],
         "type":"construct",
         "source":"Huskies",
         "alignment":[
            "N"
         ],
         "ac":[
            {
               "ac":16,
               "from":[
                  "natural armor"
               ]
            }
         ],
         "hp":{
            "formula":"5d10 + 5",
            "average":30
         },
         "speed":{
            "walk":30
         },
         "str":15,
         "dex":14,
         "con":12,
         "int":10,
         "wis":10,
         "cha":12,
         "passive":14,
         "cr":"2",
         "vulnerable":[
            {
               "vulnerable":[
                  "lightning"
               ]
            },
            {
               "vulnerable":[
                  
               ],
               "preNote":"water"
            }
         ],
         "resist":[
            {
               "resist":[
                  "bludgeoning",
                  "piercing",
                  "slashing"
               ],
               "note":"(not adamantine)"
            },
            {
               "resist":[
                  "poison"
               ]
            }
         ],
         "conditionImmune":[
            "charmed"
         ],
         "action":[
            {
               "name":"Multiattack",
               "entries":[
                  "make 2 attacks"
               ]
            },
            {
               "name":"Arm Prong",
               "entries":[
                  "{@atk mw} {@hit 4} to hit, reach 5 ft., one target. {@h}6 ({@damage 1d8 + 2}) piercing damage."
               ]
            },
            {
               "name":"Electric Crossbow",
               "entries":[
                  "{@atk rw} {@hit +4} to hit, range 40/160 ft., one target. {@h}6 ({@damage 1d8 + 2}) lightning damage."
               ]
            },
            {
               "name":"Shockwave",
               "entries":[
                  "1/day. CON save {@dc 13} within a 15 ft radius. On a failed save, creatures take {@damage 3d8} lightning damage and are {@condition stunned}. On a successful save, creatures take half damage and no effects. "
               ]
            }
         ],
         "actionTags":[
            "Multiattack"
         ],
         "miscTags":[
            "MW",
            "RW"
         ],
         "reaction":[
            {
               "name":"Shockback",
               "entries":[
                  "When the automata takes damage, it can roll a {@dice d10}. If the result is greater than its percentage of remaining health (rounded down), the automata can use its reaction to deal {@damage 1d8 + 2} lightning damage in a 15 foot radius (CON save {@dc 13} to evade). On a failure, the target is also {@condition stunned} until the start of the automata's next turn. "
               ]
            }
         ],
         "conditionInflict":[
            "stunned"
         ],
         "damageTags":[
            "L",
            "P"
         ]
      },
      {
         "name":"Merrow Shallowpriest (nerfed)",
         "source":"Huskies",
         "page":294,
         "size":[
            "L"
         ],
         "type":"monstrosity",
         "alignment":[
            "C",
            "E"
         ],
         "ac":[
            {
               "ac":14,
               "from":[
                  "natural armor"
               ]
            }
         ],
         "hp":{
            "formula":"8d10 + 16",
            "average":60
         },
         "speed":{
            "walk":10,
            "swim":40
         },
         "str":18,
         "dex":14,
         "con":15,
         "int":11,
         "wis":16,
         "cha":9,
         "senses":[
            "darkvision 60 ft."
         ],
         "passive":13,
         "languages":[
            "Abyssal",
            "Aquan"
         ],
         "cr":"3",
         "spellcasting":[
            {
               "name":"Spellcasting",
               "headerEntries":[
                  "The merrow is a 6th-level spellcaster. Its spellcasting ability is Wisdom (spell save {@dc 13}, {@hit 5} to hit with spell attacks). The merrow has the following druid spells prepared:"
               ],
               "spells":{
                  "0":{
                     "spells":[
                        "{@spell druidcraft}",
                        "{@spell minor illusion}",
                        "{@spell shocking grasp}"
                     ]
                  },
                  "1":{
                     "spells":[
                        "{@spell cure wounds}",
                        "{@spell fog cloud}",
                        "{@spell thunderwave}"
                     ],
                     "slots":4
                  },
                  "2":{
                     "spells":[
                        "{@spell hold person}",
                        "{@spell mirror image}",
                        "{@spell misty step}"
                     ],
                     "slots":3
                  },
                  "3":{
                     "spells":[
                        "{@spell dispel magic}",
                        "{@spell lightning bolt} (see \"Actions\" below)",
                        "{@spell sleet storm}"
                     ],
                     "slots":1
                  }
               },
               "ability":"wis",
               "type":"spellcasting"
            }
         ],
         "trait":[
            {
               "name":"Amphibious",
               "entries":[
                  "The merrow can breathe air and water."
               ]
            }
         ],
         "action":[
            {
               "name":"Harpoon",
               "entries":[
                  "{@atk mw,rw} {@hit 6} to hit, reach 5 ft. or range 20/60 ft., one target. {@h}11 ({@damage 2d6 + 4}) piercing damage. If the target is a Medium or smaller creature, the merrow can pull it 10 feet closer."
               ]
            },
            {
               "name":"Lightning Bolt (3rd-Level Spell; Requires a Spell Slot)",
               "entries":[
                  "The merrow unleashes a stroke of lightning in a line 100 feet long and 5 feet wide. Each creature in the line must make a {@dc 13} Dexterity saving throw, taking 28 ({@damage 8d6}) lightning damage on a failed save, or half as much damage on a successful one."
               ]
            }
         ],
         "traitTags":[
            "Amphibious"
         ],
         "senseTags":[
            "D"
         ],
         "languageTags":[
            "AB",
            "AQ"
         ],
         "spellcastingTags":[
            "CD"
         ],
         "miscTags":[
            "RW",
            "MW"
         ],
         "hasFluff":true,
         "hasFluffImages":true,
         "tokenUrl":"https://5e.tools/img/EGW/Merrow Shallowpriest.png",
         "fluff":{
            "name":"Merrow Shallowpriest",
            "source":"EGW",
            "entries":[
               {
                  "type":"entries",
                  "entries":[
                     "Some of the many merrow that dwell in the watery shadows of the Menagerie Coast learn to harness the magical aspects of the elements. Often working as guides leading merrow hunting parties, some of these shallowpriests rise to become powerful leaders, inspiring their clans to terrorize coastal communities and passing ships.",
                     "Rumors speak of underground waterways and lakes carved into the rock beneath Wildemount, where shallowpriests hold court over huge subterranean communities of merrow. These evil creatures are thought to seek the means of flooding the surface world, allowing them to steal away who and what they will to the dark waters below.",
                     "While most shallowpriests do not bind themselves in the service of a specific deity, some are drawn to the worship of entities that reign over regions of the Elemental Plane of Water, hoping to find means of expanding their dominion into the seas of Exandria. These merrow often spearhead the construction of intricate shrines and temples along the bottom of the ocean, preparing a sacred space for planar doorways to their master's realm to be opened and maintained."
                  ]
               }
            ],
            "images":[
               {
                  "type":"image",
                  "href":{
                     "type":"internal",
                     "path":"bestiary/EGW/Merrow Shallowpriest.webp"
                  },
                  "credit":"Andrew Mar"
               }
            ]
         },
         "damageTags":[
            "L",
            "P"
         ],
         "damageTagsSpell":[
            "L",
            "T"
         ],
         "savingThrowForced":[
            "dexterity"
         ],
         "savingThrowForcedSpell":[
            "constitution",
            "dexterity",
            "wisdom"
         ]
      },
      {
         "name":"Cultist of Song",
         "size":[
            "M"
         ],
         "type":"humanoid",
         "source":"Huskies",
         "alignment":[
            "N"
         ],
         "ac":[
            15
         ],
         "hp":{
            "formula":"8d8 + 8",
            "average":44
         },
         "speed":{
            "walk":30
         },
         "str":11,
         "dex":14,
         "con":12,
         "int":10,
         "wis":13,
         "cha":14,
         "passive":15,
         "cr":"2",
         "save":{
            "dex":"+4",
            "wis":"+3"
         },
         "skill":{
            "acrobatics":"+4",
            "perception":"+3",
            "performance":"+6"
         },
         "conditionImmune":[
            {
               "conditionImmune":[
                  "charmed"
               ]
            },
            {
               "conditionImmune":[
                  "frightened"
               ]
            }
         ],
         "action":[
            {
               "name":"Multiattack",
               "entries":[
                  "The cultist makes two weapon attacks. It can replace one attack with a use of Spellcasting."
               ]
            },
            {
               "name":"Shortsword",
               "entries":[
                  "{@atk mw} {@hit 4} to hit, reach 5 ft., one target. {@h}5 ({@damage 1d6 + 2}) piercing damage. ",
                  "Once per turn when the cultist hits a creature with an attack using this weapon, it can wound its target. At the start of each of the wounded creature's turns, it takes 2 ({@damage 1d4}) necrotic damage for each time it's been wounded by this weapon. It can then make a {@dc 15} Constitution saving throw, ending the effect of all such wounds on itself on a success. Alternatively, the wounded creature, or a creature within 5 feet of it, can use an action to make a {@dc 15} Wisdom (Medicine) check, ending the effect of such wounds on it on a success."
               ]
            },
            {
               "name":"Shortbow",
               "entries":[
                  "{@atk rw} {@hit 4} to hit, range 80/320 ft., one target. {@h}5 ({@damage 1d6 + 2}) piercing damage."
               ]
            },
            {
               "name":"Cacophony {@recharge 4}",
               "entries":[
                  "Each creature in a 15-foot cube originating from the bard must make a {@dc 12} Constitution saving throw. On a failed save, a creature takes 9 ({@damage 2d8}) thunder damage and is pushed up to 10 feet away from the bard. On a successful save, a creature takes half as much damage and isn't pushed."
               ]
            }
         ],
         "actionTags":[
            "Breath Weapon",
            "Multiattack"
         ],
         "miscTags":[
            "MW",
            "MLW",
            "RW",
            "AOE"
         ],
         "attachedItems":[
            "shortbow|phb",
            "shortsword|phb"
         ],
         "spellcasting":[
            {
               "name":"Spellcasting",
               "daily":{
                  "1e":[
                     "{@spell charm person}",
                     "{@spell invisibility}",
                     "{@spell sleep}"
                  ]
               },
               "type":"spellcasting"
            }
         ],
         "spellcastingTags":[
            "O"
         ],
         "trait":[
            {
               "name":"Concentration Save",
               "entries":[
                  "Each time the cultist takes damage, it must make a WIS save to maintain possession."
               ]
            }
         ],
         "damageTags":[
            "N",
            "P",
            "T"
         ],
         "savingThrowForced":[
            "constitution"
         ],
         "savingThrowForcedSpell":[
            "wisdom"
         ]
      },
      {
         "name":"Butcher Balladeer",
         "source":"Huskies",
         "page":23,
         "basicRules":true,
         "size":[
            "M"
         ],
         "type":"undead",
         "alignment":[
            "C",
            "E"
         ],
         "ac":[
            13
         ],
         "hp":{
            "average":58,
            "formula":"13d8"
         },
         "speed":{
            "walk":0,
            "fly":{
               "number":40,
               "condition":"(hover)"
            },
            "canHover":true
         },
         "str":1,
         "dex":14,
         "con":10,
         "int":12,
         "wis":11,
         "cha":17,
         "save":{
            "wis":"+2",
            "cha":"+5"
         },
         "senses":[
            "darkvision 60 ft."
         ],
         "passive":10,
         "resist":[
            "acid",
            "fire",
            "lightning",
            "thunder",
            {
               "resist":[
                  "bludgeoning",
                  "piercing",
                  "slashing"
               ],
               "note":"from nonmagical attacks",
               "cond":true
            }
         ],
         "immune":[
            "cold",
            "necrotic",
            "poison"
         ],
         "conditionImmune":[
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
         "languages":[
            "Common",
            "Elvish"
         ],
         "cr":"4",
         "trait":[
            {
               "name":"Incorporeal Movement",
               "entries":[
                  "The Butcher can move through other creatures and objects as if they were {@quickref difficult terrain||3}. He takes 5 ({@damage 1d10}) force damage if he ends his turn inside an object."
               ]
            }
         ],
         "action":[
            {
               "name":"Corrupting Touch",
               "entries":[
                  "{@atk ms} {@hit 4} to hit, reach 5 ft., one target. {@h}12 ({@damage 3d6 + 2}) necrotic damage."
               ]
            },
            {
               "name":"Horrifying Visage",
               "entries":[
                  "Each non-undead creature within 60 feet of the butcher that can him her must succeed on a {@dc 13} Wisdom saving throw or be {@condition frightened} for 1 minute. A {@condition frightened} target can repeat the saving throw at the end of each of its turns, with disadvantage if the banshee is within line of sight, ending the effect on itself on a success. If a target's saving throw is successful or the effect ends for it, the target is immune to the banshee's Horrifying Visage for the next 24 hours."
               ]
            },
            {
               "name":"Shriek {@recharge 5}",
               "entries":[
                  "The butcher plays a horrifying shriek. All other creatures within 30 feet of her that can hear her must make a {@dc 13} Constitution saving throw, taking 10 ({@damage 3d6}) psychic damage on a failure or half as much on a success. "
               ]
            }
         ],
         "environment":[
            "coastal",
            "forest"
         ],
         "soundClip":{
            "type":"external",
            "url":"https://5e.tools/audio/bestiary/banshee.mp3"
         },
         "traitTags":[
            "Incorporeal Movement"
         ],
         "senseTags":[
            "D"
         ],
         "languageTags":[
            "C",
            "E"
         ],
         "conditionInflict":[
            "frightened"
         ],
         "hasFluff":true,
         "hasFluffImages":true,
         "token":{
            "name":"Banshee",
            "source":"MM"
         },
         "fluff":{
            "name":"Banshee",
            "source":"MM",
            "entries":[
               {
                  "type":"entries",
                  "entries":[
                     {
                        "type":"entries",
                        "entries":[
                           "When night falls, unlucky travelers hear the faint cries of the forlorn dead. This woeful spirit is a banshee, a spiteful creature formed from the spirit of a female elf. Banshees appear as luminous, wispy forms that vaguely recall their mortal features. A banshee's face is wreathed in a wild tangle of hair, its body clad in wispy rags that flutter and stream around it.",
                           {
                              "name":"Divine Wrath",
                              "type":"entries",
                              "entries":[
                                 "Banshees are the undead remnants of elves who, blessed with great beauty, failed to use their gift to bring joy to the world. Instead, they used their beauty to corrupt and control others. Elves afflicted by the banshee's curse experience no gladness, feeling only distress in the presence of the living. As the curse takes its toll, their minds and bodies decay, until death completes their transformation into undead monsters."
                              ]
                           },
                           {
                              "name":"Sorrow Bound",
                              "type":"entries",
                              "entries":[
                                 "A banshee becomes forever bound to the place of its demise, unable to venture more than five miles from there. It is forced to relive every moment of its life with perfect recall, yet always refuses to accept responsibility for its doom."
                              ]
                           },
                           {
                              "name":"Beauty Hoarders",
                              "type":"entries",
                              "entries":[
                                 "The vanity that inspired the banshee's cursed creation persists in undeath. These creatures covet beautiful objects: fine jewelery, paintings, statues, and other objects of art. At the same time, a banshee abhors any mirrored surface, for it can't bear to see the horror of its own existence. A single glimpse of itself is enough to send a banshee into a rage."
                              ]
                           },
                           {
                              "name":"Undead Nature",
                              "type":"entries",
                              "entries":[
                                 "A banshee doesn't require air, food, drink, or sleep."
                              ]
                           }
                        ]
                     }
                  ]
               }
            ],
            "images":[
               {
                  "type":"image",
                  "href":{
                     "type":"internal",
                     "path":"bestiary/MM/Banshee.webp"
                  },
                  "credit":"Tomas Giorello"
               }
            ]
         },
         "damageTags":[
            "N",
            "O",
            "Y"
         ],
         "savingThrowForced":[
            "constitution",
            "wisdom"
         ]
      },
      {
         "name":"Leanna (mage)",
         "source":"Huskies",
         "page":129,
         "size":[
            "M"
         ],
         "type":{
            "type":"humanoid",
            "tags":[
               "elf"
            ]
         },
         "alignment":[
            "N",
            "E"
         ],
         "ac":[
            12,
            {
               "ac":15,
               "condition":"with {@spell mage armor}",
               "braces":true
            }
         ],
         "hp":{
            "formula":"10d8",
            "average":30
         },
         "speed":{
            "walk":30
         },
         "str":9,
         "dex":14,
         "con":10,
         "int":17,
         "wis":13,
         "cha":12,
         "skill":{
            "arcana":"+6",
            "deception":"+4",
            "perception":"+5",
            "stealth":"+5"
         },
         "senses":[
            "darkvision 120 ft."
         ],
         "passive":15,
         "languages":[
            "Elvish"
         ],
         "cr":"3",
         "spellcasting":[
            {
               "name":"Innate Spellcasting",
               "headerEntries":[
                  "The drow's spellcasting ability is Charisma (spell save {@dc 12}). It can innately cast the following spells, requiring no material components:"
               ],
               "daily":{
                  "1e":[
                     "{@spell darkness}"
                  ]
               },
               "ability":"cha",
               "type":"spellcasting"
            },
            {
               "name":"Spellcasting",
               "headerEntries":[
                  "Its spellcasting ability is Intelligence (spell save {@dc 14}, {@hit 6} to hit with spell attacks). The drow has the following wizard spells prepared:"
               ],
               "spells":{
                  "0":{
                     "spells":[
                        "{@spell mage hand}",
                        "{@spell minor illusion}",
                        "{@spell poison spray}",
                        "{@spell ray of frost}"
                     ]
                  },
                  "1":{
                     "spells":[
                        "{@spell mage armor}",
                        "{@spell magic missile}",
                        "{@spell shield}",
                        "{@spell witch bolt}"
                     ],
                     "slots":4
                  },
                  "2":{
                     "spells":[
                        "{@spell misty step}",
                        "{@spell web}"
                     ],
                     "slots":3
                  },
                  "3":{
                     "spells":[
                        "{@spell fly}",
                        "{@spell lightning bolt}"
                     ],
                     "slots":3
                  },
                  "4":{
                     "spells":[
                        "{@spell Evard's black tentacles}",
                        "{@spell greater invisibility}"
                     ],
                     "slots":1
                  }
               },
               "ability":"int",
               "type":"spellcasting"
            }
         ],
         "trait":[
            {
               "name":"Fey Ancestry",
               "entries":[
                  "The drow has advantage on saving throws against being {@condition charmed}, and magic can't put the drow to sleep."
               ]
            }
         ],
         "action":[
            {
               "name":"Staff",
               "entries":[
                  "{@atk mw} {@hit 2} to hit, reach 5 ft., one target. {@h} 3 ({@damage 1d8 - 1}) bludgeoning damage if used with two hands, plus 3 ({@damage 1d6}) poison damage."
               ]
            }
         ],
         "environment":[
            "underdark"
         ],
         "soundClip":{
            "type":"external",
            "url":"https://5e.tools/audio/bestiary/drow-mage.mp3"
         },
         "traitTags":[
            "Fey Ancestry",
            "Sunlight Sensitivity"
         ],
         "senseTags":[
            "SD"
         ],
         "languageTags":[
            "E"
         ],
         "spellcastingTags":[
            "I",
            "CW"
         ],
         "miscTags":[
            "MW"
         ],
         "conditionInflictSpell":[
            "invisible",
            "restrained"
         ],
         "hasFluff":true,
         "hasFluffImages":true,
         "token":{
            "name":"Drow Mage",
            "source":"MM"
         },
         "fluff":{
            "name":"Drow Mage",
            "source":"MM",
            "images":[
               {
                  "type":"image",
                  "href":{
                     "type":"internal",
                     "path":"bestiary/MM/Drow Mage.webp"
                  }
               }
            ],
            "entries":[
               {
                  "name":"Drow",
                  "type":"section",
                  "entries":[
                     {
                        "type":"entries",
                        "entries":[
                           {
                              "type":"entries",
                              "entries":[
                                 "Tens of thousands of years ago, the elves were divided, with those of benevolent disposition battling those that were selfish and cruel. The war among elvenkind ended when the good elves banished their malevolent kin to the subterranean depths. Here, in the lightless caverns and endless warrens of twisting passages, the dark elves-the drow-found refuge. They also found leadership in the only elven deity who had not forsaken them. At her command, the dark elves built an empire in the underworld.",
                                 {
                                    "type":"entries",
                                    "entries":[
                                       {
                                          "type":"entries",
                                          "entries":[
                                             {
                                                "type":"entries",
                                                "name":"Children of Lolth",
                                                "entries":[
                                                   "The drow worship Lolth, a deity who resides in the Abyss. Known as the Spider Queen or the Demon Queen of Spiders, she is the figure around which the dark elves have built their subterranean civilization. Whatever she demands, the drow do. The wickedest of elves, drow are seldom seen by the surface world. Though they plot to destroy the elves that banished them, they no longer see themselves as exiles. They are the destined rulers of the darkness, and when Lolth commands them to rise up and destroy their surface-dwelling kin, they will."
                                                ]
                                             },
                                             {
                                                "type":"entries",
                                                "name":"Creatures of Darkness",
                                                "entries":[
                                                   "The drow have lived underground for so long that they have evolved to their surroundings and can see in the dark. However, they can no longer stand sunlight. When slaves are in short supply in the Underdark, the drow send raiding parties to the surface to capture humanoids under cover of darkness, bringing them back to their cities to be tortured into submission. Beyond those occasional excursions, the drow are content to remain in their subterranean realm, where they feel secure and in control."
                                                ]
                                             },
                                             {
                                                "type":"entries",
                                                "name":"Underdark Cities",
                                                "entries":[
                                                   "The dark elves build fantastic cities in enormous caverns where food and water are abundant. Their ability to sculpt stone rivals that of the greatest dwarf artisans, yet their structures retain a decidedly elven aesthetic. Though appearing delicate, drow settlements are structurally sound and remarkably resilient. The drow like to hollow out enormous stalagmites and stalactites, creating populated spires that rise from the floors and ceilings. A drow city is a sprawling metropolis enclosed by high walls. Non-drow visitors must conduct their business outside the walls under watchful eyes. The drow raise and keep giant spiders to help protect their cities against intruders, even as they drape those cities in beautiful webbing, creating a gossamer snare to catch flying enemies that would otherwise soar over the walls."
                                                ]
                                             },
                                             {
                                                "type":"entries",
                                                "name":"Drow Magic",
                                                "entries":[
                                                   "Just as the drow have adapted to underground life, so too has their magic. In addition to using that magic to carve their cities from stone, they empower their weapons, create dangerous new magic items, and summon demons from the Abyss. Drow spellcasters are supremely arrogant and never hesitate to use their magic in the most abhorrent ways."
                                                ]
                                             },
                                             {
                                                "type":"entries",
                                                "name":"Arms and Armor",
                                                "entries":[
                                                   "Drow craft weapons made of adamantine, a dark and supernaturally hard metal. Drow artisans adorn their weapons and armor with web-like filigree and spider motifs, and mages sometimes imbue items with magic to enhance their effectiveness. However, such magic fades when exposed to sunlight, so that magical drow weapons and armor rarely retain their enhancement bonuses and magical properties when brought to the surface."
                                                ]
                                             },
                                             {
                                                "type":"entries",
                                                "name":"Cutthroat Politics",
                                                "entries":[
                                                   "Drow politics are cutthroat and rife with intrigue. When drow work together, it is typically to destroy a common foe and ensure their own survival, and such alliances are short lived and fraught with peril.",
                                                   "Drow society is divided into noble houses, each ruled by a matron who seeks to raise the prestige and power of her house above all others. Other high-ranking members of the house are blood relatives, while the middling ranks are flush with drow from weaker families that have sworn fealty to the greater house. Clinging precariously to the bottom rung of a house's social ladder are the house slaves, made up of drow of low birth and the occasional non-drow captive."
                                                ]
                                             },
                                             {
                                                "type":"entries",
                                                "name":"Matriarchal Rule",
                                                "entries":[
                                                   "Lolth, through her faithful priestesses, dictates the rules of drow society, ensuring that her orders and plots are carried out. Since Lolth is prone to manifesting on the Material Plane and directly punishing those that disobey her, the drow have learned to heed what she says and do as her priestesses command.",
                                                   "In drow society, males are subservient to females. A male drow might lead an Underdark patrol or a raiding party to the surface, but he reports to a female drow-either the matron of his house or one of her hand-picked female subordinates. Although male drow can fill almost any function in drow society, they can't be priests, nor can they rule a house."
                                                ]
                                             },
                                             {
                                                "type":"entries",
                                                "name":"Poison Predilection",
                                                "entries":[
                                                   "Distilled from spider venom and the flora of the Underdark, poison can be found in abundance among the drow, and it plays an important part in their culture and politics. Drow mages concoct a viscid toxin that leaves enemies {@condition unconscious}. Drow warriors coat their blades and crossbow bolts with this venom, looking forward to the interrogation and torture that follows combat."
                                                ]
                                             },
                                             {
                                                "type":"inset",
                                                "name":"Variant: Drow Magic Armor and Weapons",
                                                "entries":[
                                                   "Drow often wear magic armor and carry magic weapons that lose their enhancement bonuses permanently if they are exposed to sunlight for 1 hour or longer.",
                                                   {
                                                      "type":"list",
                                                      "items":[
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
                              "type":"insetReadaloud",
                              "entries":[
                                 {
                                    "type":"quote",
                                    "entries":[
                                       "Such depravity. Such terrifying cruelty. They are the vile poison that plagues all elvenkind."
                                    ],
                                    "by":"Nelar Autumnwell, elf cleric of Corellon Larethian"
                                 }
                              ]
                           }
                        ]
                     }
                  ]
               }
            ]
         },
         "damageTags":[
            "B",
            "I"
         ],
         "damageTagsSpell":[
            "B",
            "C",
            "F",
            "I",
            "L",
            "O"
         ],
         "savingThrowForcedSpell":[
            "constitution",
            "dexterity"
         ]
      }
   ]
}
```