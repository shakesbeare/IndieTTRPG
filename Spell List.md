# Spell List
All spells share the same spell list. There are no such lists governing whether a spell is Arcane, Occult, Divine, or Primal, as in `Pathfinder 2e`. Spells which are unique to a given class are given as rewards for Features of that class and are marked as `not learnable`. Otherwise, spellcasters may learn any spell. 
```dataview
TABLE
	name AS "Name",
	class AS "Class", 
	learnable AS "Learnable"
FROM "Spells"
SORT name
```
