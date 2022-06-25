# Design Philosophy 
- Reduce complexity where possible – all rules should be
    explainable in a few, simple sentences.
 - Where complexity must remain or increase, it should do so in an intuitive 
    way which is easily understandable or lines up well with how the real 
    world works. 
- Every level-up should have a meaningful, impactful choice. 
- Every player turn in combat should have a meaningful, impactful choice. 
- Player fun is more important than game balance, except where the lack of 
    balance interferes with player fun.

# Building a character

## Ability Scores

Ability scores, as opposed to other systems, do not exist. By `Dungeons &
Dragons 5e` and `Pathfinder 2e`, ability scores are purely useful for determining
how well you roll for skill checks and attack roles, with maybe the occasional
rule here or there that directly interacts with it such as multiclass or feat
prerequisites. Thus, with some careful planning, ability scores can be safely
excised from the game while still maintaining a cohesive feel. 

Beyond that, the very idea of ability scores is somewhat contrary to our
experience in real life. We do not imagine that our strength can only increase
so much through extensive training, for example. There are many degrees of
success in these traits and the system in place in current popular system
fails to create an effective abstraction of real life. In this system, your
ability to perform a skill is directly associated with that skill. Athletics,
for example, is a perfectly fine abstraction of all activities of running,
lifting, climbing, etc, without needing the intermediary of the `Strength`
score in the middle of it all.

## Improving Skills

In this system, skills are improved by skill points. Each skill point placed
into a skill represents an additional `+1` bonus to performing associated actions.
The number of skill points you receive per level is based on your class and other
skills. Your starting skill points are also determined by your chosen class.

# Combat

## Combat Procedure

Upon entering combat, all involved creatures roll initiative and play proceeds
in a turn-based fashion. Initiative represents how fast a creature acts and
reacts in combat and is governed by the agility ability. A critical success on
initiative results in the creature being placed at the top of initiative order
and a critical failure results in being placed at the bottom. If two creatures
tie, their agility modifiers should be compared and the higher result goes
first. If there is still a tie, both creatures should reroll until there is no
tie and that result determines the order which those creatures take their
turns.

Each creature involved in the combat gets three `actions` to take their part in
the battle. They are also allowed a single `reaction` to use during another
creature's turn, provided the trigger is fulfilled. `Saving Throws` are not
considered reactions. 

## Making an Attack

In contrast to other systems, attacks have a very high likelihood of
succeeding. If you are proficient in the use of a weapon, attacks with that
weapon need only meet a `DC11` ability check in order for the attack to hit. 
 
In combat, a creature’s armor class is subtracted from all damage dealt to
them before it is applied to their health. For example, if Lothric has an AC
of `5` and he is hit with a `15` damage attack, Lothric only takes `10` damage. A
creature can also attempt to dodge an attack swung at them to nullify all
damage they take, assuming they succeed in an `agility saving throw` which is
compared to the attacker’s attack roll. If the attacker rolls a critical
success, you take half damage on a successful dodge unless you also critically
succeed. Generally, wearing armor decreases your ability to succeed in `agility
saving throws` related to dodging attacks.

## Casting Spells

In this system, spells are cast using mana. At the beginning of each turn, a
player roles to determine the number of mana points they are able to spend for
that round. For most spellcasters, this starts as `1d4` mana points. Depending
on your class, feats, and skills, you might be able to gain more mana than
that. You may spend as many mana points as you have available to cast whatever
spells you have at your disposal. However, some spells might require more mana
than you could possibly generate in a turn.

For these spells, you can take the `Conserve Mana` action to instantly end your
turn. When you `Conserve Mana`, any mana point remaining unspent will be
available to you at the beginning of your next turn. Be warned, this action is
visible to enemies and requires a great deal of concentration. DM's may opt to
have more intelligent creatures deliberately target mages who are `Conserving
Mana` in order to weaken your party.

### Differences from other Systems

The idea of spell slots has been done away with. You can learn any spell at any time, but
know that you may not be able to generate the mana in time to cast it reasonably, yet. 
There is also no longer a distinction made between spells and cantrips. You may consider
a cantrip a spell which you simply always generate enough mana to cast each turn.