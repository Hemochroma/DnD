```statblock
layout: Basic 5e Layout
name: "Aberrant Spirit"
image: [[Aberrant Spirit.jpg]]
size: "Medium"
type: "aberration"
subtype: ""
alignment: "unaligned"
ac: 11
hp: 40
hit_dice: ""
speed: "30 ft., fly 30 ft. (beholderkin only; hover) (hover)"
stats: [16, 10, 15, 16, 10, 6]
saves: []
skillsaves: []
senses: "darkvision 60 ft., passive Perception 10"
languages: "Deep Speech, understands the languages you speak"
damage_resistances: ""
damage_immunities: "psychic"
condition_immunities: ""
cr: ""
traits:
  - name: "Regeneration (Slaad Only)"
    desc: |-
      The aberration regains 5 hit points at the start of its turn if it has at least 1 hit point.
  - name: "Whispering Aura (Star Spawn Only)"
    desc: |-
      At the start of each of the aberration's turns, each creature within 5 feet of the aberration must succeed on a Wisdom saving throw against your spell save DC or take 2d6 psychic damage, provided that the aberration isn't incapacitated.
actions:
  - name: "Multiattack"
    desc: |-
      The aberration makes a number of attacks equal to half this spell's level (rounded down).
  - name: "Eye Ray (Beholderkin Only)"
    desc: |-
      *Ranged Spell Attack:* your spell attack modifier to hit, range 150 ft., one creature. *Hit:* 1d8 + 3 + summonSpellLevel psychic damage.
  - name: "Claws (Slaad Only)"
    desc: |-
      *Melee Weapon Attack:* your spell attack modifier to hit, reach 5 ft., one target. *Hit:* 1d10 + 3 + summonSpellLevel slashing damage. If the target is a creature, it can't regain hit points until the start of the aberration's next turn.
  - name: "Psychic Slam (Star Spawn Only)"
    desc: |-
      *Melee Spell Attack:* your spell attack modifier to hit, reach 5 ft., one creature. *Hit:* 1d8 + 3 + summonSpellLevel psychic damage.
reactions: []
legendary_actions: []
mythic_actions: []
lair_actions: []
spells: []
source: "TCE"
page: 109
```