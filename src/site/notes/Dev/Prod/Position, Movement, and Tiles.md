---
{"dg-publish":true,"permalink":"/dev/prod/position-movement-and-tiles/"}
---

## Tiles
Battle maps, top-down depictions of environments to represent physical interactions, are mainly made up of tiles, aka Hexes. A hex, or hexagon, is a type of battle map that more accurately and quickly represents distance.

To accurately determine the limits of a character, the system assumes 1 tile = 1 meter.
## Position
When in a battle or any situation where every edge matters, characters must keep in mind where they are in relation to everyone else.
### Cover
Characters can take cover behind objects to protect themselves. The cover itself though can take the damage and once the cover is destroyed the protection is gone.

Full Cover:
- You are unseen and sufficiently covered to not be targeted.
- Area of Effect attacks that do not move around corners cannot hit you.

Partial Cover:
- At least half of you are sufficiently covered.
- Characters targeting you suffer a disadvantage.

### Elevation
Being higher or lower than your target affects what you might do in a situation. Effectively, being higher than your target in ranged combat is a good thing, and being higher than your opponent in melee combat is a bad thing.

- Ranged
	- Higher Elevation
		- You gain an advantage against the target.
	- Same Elevation
		- No advantage or disadvantage.
	- Lower Elevation
		- You suffer a disadvantage against the target.

- Melee
	- Higher Elevation
		- You suffer a disadvantage against the target.
	- Same Elevation
		- No advantage or disadvantage.
	- Lower Elevation
		- You gain an advantage against the target.


## Speed
Just about every character has a speed stat. This speed determines the amount it can move and how.

A character's speed is determined by adding together their rank in Agility twice and their rank in Might twice. For example, if a character has Rank 2 in Agility and Rank 3 in Might, the character has 2+2=4 and 3+3=6 then 4+6=10 speed.

Whenever a character wants to move through a more difficult environment such as swimming, climbing, or moving through bramble. That character suffers 1 stack of slowed, halfing their movment or more if they already have stacks of slowed.
