# Initiative Tracker
- Making Creatures
	- When creating creatures you can define a basic creature with the syntax: "name, hp, ac, initiative modifier, xp" all of these but the name is optional.
	- you can add a number : before the creature to make multiple ex: "3: goblin" would make 3 goblins this can also be done with 1d3 or similar dice rolls
	- you can also add additional lines to make unique creatures
	- to change the display name of a creature put it in double **brackets** and do ((monster, name) stats go here) If the monster name has a comma in it surround it with quotes like (("Rat, Giant", Carl)stats) to make a Rat, Giant named Carl
	- To mark a creature as an ally add the tag , ally after the individual or group this can also be done with , friendly
	- you can mark a creature as hidden with ,  hidden
	- **The fast and easy way to make creatures is to use the add button that’s in the initiative tracker pane, but there are less customization options**
- Making an encounter
	- mark the code block as encounter
	- you can then define name: party: and creatures:
	- you can also mark the code block as an encounter table and separate encounters in the table with ---
---
# Dice Roller
### Formula Examples
Drop Highest: add dh at the end you can add numbers after to drop the 2 highest or more
Drop Lowest add dl at the end
### Inline Rolling
inline rolling has be be surrounded by backticks ”` `”  and then use the formatting of dice: Thing with thing either being a dice equation or even a table using a double bracket link and a ^ to indicate the table
Example:
`dice: 1d4`
or
`dice: [[Races#^e0ae2c]]`