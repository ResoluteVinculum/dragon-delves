---
{"dg-publish":true,"permalink":"/rules/source/bestiary/humanoid/archdruid-mpmm/","tags":["ttrpg-cli/compendium/src/5e/mpmm","ttrpg-cli/monster/cr/12","ttrpg-cli/monster/environment/forest","ttrpg-cli/monster/environment/mountain","ttrpg-cli/monster/environment/swamp","ttrpg-cli/monster/environment/underwater","ttrpg-cli/monster/size/medium","ttrpg-cli/monster/type/humanoid/druid"],"dg-note-properties":{"obsidianUIMode":"preview","cssclasses":["json5e-monster"],"tags":["ttrpg-cli/compendium/src/5e/mpmm","ttrpg-cli/monster/cr/12","ttrpg-cli/monster/environment/forest","ttrpg-cli/monster/environment/mountain","ttrpg-cli/monster/environment/swamp","ttrpg-cli/monster/environment/underwater","ttrpg-cli/monster/size/medium","ttrpg-cli/monster/type/humanoid/druid"],"statblock":"inline","statblock-link":"#^statblock","aliases":["Archdruid"]}}
---

# [Archdruid](Rules\Source\bestiary\humanoid/archdruid-mpmm.md)
*Source: Mordenkainen Presents: Monsters of the Multiverse p. 48*  

Archdruids watch over the natural wonders of their domains. They seldom interact with folk away from their druid groves and shrines, unless there is a great threat to the natural order or to a nearby community. An archdruid typically has one or more pupils who are [[Rules/Source/bestiary/humanoid/druid-xmm\|druids]], and the archdruid's lair is usually guarded by loyal Beasts and Fey creatures.

When an archdruid uses their Change Shape action, you may choose the creature they turn into, abiding by the action's restrictions. Or you may roll on the Archdruid Favored Shapes table to determine the form the archdruid adopts.

**Archdruid Favored Shapes**

| dice: d8 | Favored Shape |
|----------|---------------|
| 1 | [[Rules/Source/bestiary/elemental/air-elemental-xmm\|Air elemental]] |
| 2 | [[Rules/Source/bestiary/elemental/earth-elemental-xmm\|Earth elemental]] |
| 3 | [[Rules/Source/bestiary/elemental/fire-elemental-xmm\|Fire elemental]] |
| 4 | [[Rules/Source/bestiary/beast/giant-crocodile-xmm\|Giant crocodile]] |
| 5 | [[Rules/Source/bestiary/beast/mammoth-xmm\|Mammoth]] |
| 6 | [[Rules/Source/bestiary/elemental/flail-snail-mpmm\|Flail snail]] |
| 7 | [[Rules/Source/bestiary/beast/triceratops-xmm\|Triceratops]] |
| 8 | [[Rules/Source/bestiary/elemental/water-elemental-xmm\|Water elemental]] |{ #archdruid-favored-shapes}


```statblock
"name": "Archdruid (MPMM)"
"size": "Medium"
"type": "humanoid"
"subtype": "druid"
"alignment": "Any alignment"
"ac": !!int "14"
"ac_class": "[hide armor](/Rules/Source/items/hide-armor-xphb.md)"
"hp": !!int "154"
"hit_dice": "28d8 + 28"
"modifier": !!int "2"
"stats":
  - !!int "14"
  - !!int "14"
  - !!int "12"
  - !!int "12"
  - !!int "20"
  - !!int "11"
"speed": "30 ft."
"saves":
  - "intelligence": !!int "5"
  - "wisdom": !!int "9"
"skillsaves":
  - "name": "[Medicine](/Rules/Source/skills.md#Medicine)"
    "desc": "+9"
  - "name": "[Nature](/Rules/Source/skills.md#Nature)"
    "desc": "+5"
  - "name": "[Perception](/Rules/Source/skills.md#Perception)"
    "desc": "+9"
"senses": "passive Perception 19"
"languages": "Druidic plus any two languages"
"cr": "12"
"actions":
  - "desc": "The archdruid makes three Staff or Wildfire attacks. It can replace one\
      \ attack with a use of Spellcasting."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +6 to hit, reach 5 ft., one target. *Hit:* 5 (1d6\
      \ + 2) bludgeoning damage plus 21 (6d6) poison damage."
    "name": "Staff"
  - "desc": "*Ranged Spell Attack:* +9 to hit, range 120 ft., one target. *Hit:* 26\
      \ (6d6 + 5) fire damage, and the target is [blinded](/Rules/Source/conditions.md#Blinded)\
      \ until the start of the druid's next turn."
    "name": "Wildfire"
  - "desc": "The archdruid casts one of the following spells, using Wisdom as the\
      \ spellcasting ability (spell save DC 17):\n\n**At will:** [beast sense](/Rules/Source/spells/beast-sense-xphb.md),\
      \ [entangle](/Rules/Source/spells/entangle-xphb.md), [speak with animals](/Rules/Source/spells/speak-with-animals-xphb.md)\n\
      \n**3/day each:** [animal messenger](/Rules/Source/spells/animal-messenger-xphb.md),\
      \ [dominate beast](/Rules/Source/spells/dominate-beast-xphb.md), [faerie fire](/Rules/Source/spells/faerie-fire-xphb.md),\
      \ [tree stride](/Rules/Source/spells/tree-stride-xphb.md)\n\n**1/day each:**\
      \ [commune with nature](/Rules/Source/spells/commune-with-nature-xphb.md) (as\
      \ an action), [mass cure wounds](/Rules/Source/spells/mass-cure-wounds-xphb.md)"
    "name": "Spellcasting"
"bonus_actions":
  - "desc": "The archdruid magically transforms into a Beast or an Elemental with\
      \ a challenge rating of 6 or less and can remain in that form for up to 9 hours.\
      \ The archdruid can choose whether its equipment falls to the ground, melds\
      \ with its new form, or is worn by the new form. The archdruid reverts to its\
      \ true form if it dies or falls [unconscious](/Rules/Source/conditions.md#Unconscious).\
      \ The archdruid can revert to its true form using a bonus action.\n\nWhile in\
      \ a new form, the archdruid's stat block is replaced by the stat block of that\
      \ form, except the archdruid keeps its current hit points, its hit point maximum,\
      \ this bonus action, its languages and ability to speak, and its Spellcasting\
      \ action.\n\nThe new form's attacks count as magical for the purpose of overcoming\
      \ resistances and immunity to nonmagical attacks."
    "name": "Change Shape (2/Day)"
"source":
  - "MPMM"
"image": "/Rules/Source/bestiary/humanoid/token/archdruid-mpmm.webp"
```{ #statblock}


## Environment

forest, mountain, swamp, underwater