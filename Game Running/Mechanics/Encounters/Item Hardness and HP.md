---
dg-publish: true
---
- All items have a hardness and HP. The hardness is effectively DR, in the manner that it gets subtracted from the incoming damage before it is applied to the HP. 
	- For instance if an item with a hardness of 10 is hit with an attack dealing 14 damage, it’s hardness of 10 will be subtracted from the 14 damage, and the item would loose a total of 4 HP
- If an item looses more than half of its hit points it is rendered broken
	- The broken condition has a variety of effects based on what exactly is broken, these can be seen in the section below
[source](https://www.d20pfsrd.com/EQUIPMENT/DAMAGING-OBJECTS/#Table_Substance_Hardness_and_HP) (and conditions page for broken)
### Common Armor, Weapon, and Shield Hardness and HP

| Weapons                        | Hardness | HP (medium) |
| ------------------------------ | -------- | ----------- |
| Light blade                    | 10       | 2           |
| One-handed blade               | 10       | 5           |
| Two-handed blade               | 10       | 10          |
| Light metal-hafted weapon      | 10       | 10          |
| One-handed metal-hafted weapon | 10       | 20          |
| Light hafted weapon            | 5        | 2           |
| One-handed hafted weapon       | 5        | 5           |
| Two-handed hafted weapon       | 5        | 10          |
| Projectile weapon              | 5        | 5           |

| Shield              | Hardness | HP (medium) |
| ------------------- | -------- | ----------- |
| Buckler             | 10       | 5           |
| Light wooden shield | 5        | 7           |
| Heavy wooden shield | 5        | 15          |
| Light steel shield  | 10       | 10          |
| Heavy steel shield  | 10       | 20          |
| Tower shield        | 5        | 20          |
For each +1 enhancement bonus a magic item has its *Hardness* increases by 2 and its *HP* is increased by 10
The HP amounts are given for medium size, halve the hp for each size smaller or double the HP for each size larger
#### Armor
The Hardness of armor depends on the substance it is made out of, and the HP is equal to the armor bonus x 5
### Examples of substance Hardness and HP

| Substance       | Hardness | HP <br>per inch of thickness |
| --------------- | -------- | ---------------------------- |
| Glass           | 1        | 1                            |
| Paper or cloth  | 0        | 2                            |
| Rope            | 0        | 2                            |
| Ice             | 0        | 3                            |
| Leather or hide | 2        | 5                            |
| Wood            | 5        | 10                           |
| Stone           | 8        | 15                           |
| Iron or steel   | 10       | 30                           |
| Mithral         | 15       | 30                           |
| Adamantine      | 20       | 40                           |
### Examples of Object Hardness and HP

| Object                   | Hardness | HP  | Break or burst DC<br>(Str check) |
| ------------------------ | -------- | --- | -------------------------------- |
| Rope bonds               | 0        | 2   | 23                               |
| Simple wooden door       | 5        | 10  | 13                               |
| Small chest              | 5        | 1   | 17                               |
| Good wooden door         | 5        | 15  | 18                               |
| Treasure chest           | 5        | 15  | 23                               |
| Strong wooden door       | 5        | 20  | 23                               |
| Masonry wall (1ft thick) | 8        | 90  | 35                               |
| Hewn stone (3 ft thick)  | 8        | 540 | 50                               |
| Chain                    | 10       | 5   | 26                               |
| Manacles                 | 10       | 10  | 26                               |
| Masterwork manacles      | 10       | 10  | 28                               |
| Iron door (2 in thick)   | 10       | 60  | 28                               |
Breaking items such as busting down a door or bursting out of bindings is mostly DM discretion but there are examples listed above
The size bonus to breaking items in this way is shown in the table below

| Creature Size | Bonus |
| ------------- | ----- |
| Colossal      | +16   |
| Gargantuan    | +12   |
| Huge          | +8    |
| Large         | +4    |
| Medium        | 0     |
| Small         | -4    |
| Tiny          | -8    |
| Diminutive    | -12   |
| Fine          | -16   |
### Hitting Objects not on a person
Objects still do have an Armor class its equal to 10 + its size modifier + its dex mod (inanimate objects get a -7).
for attacking an inanimate object you can also take a full round attack to get an automatic melee hit or a +5 bonus to hit with a ranged weapon

| Object Size | AC Mod |
| ----------- | ------ |
| Colossal    | -8     |
| Gargantuan  | -4     |
| Huge        | -2     |
| Large       | -1     |
| Medium      | 0      |
| Small       | +1     |
| Tiny        | +2     |
| Diminutive  | +4     |
| Fine        | +8     |
- Energy attacks deal half damage to most objects (halved before hardness) 
	- some objects may be more weak to types of energy like cloth being weak to fire this is DM discretion
- Ranged weapons deal half damage to most objects 
- Objects are immune to nonlethal damage and critical hits
### Condition: Broken

| Item              | Effects                                                                               |
| ----------------- | ------------------------------------------------------------------------------------- |
| Weapons           | -2 on attack and damage rolls<br>Only crits on a nat 20 and only deals 2x on crit     |
| Armors or Shields | AC is halved, rounding down<br>Broken armor doubles its armor check penalty on skills |
| Tools             | Any skill check made using the tool takes a -2 penalty                                |
| Wand or Staff     | uses twice as many charges when used                                                  |
- When an item is broken it is worth 75% its normal value
- Fixing broken gear
	- If it is magical it needs a mending or make whole spell from a caster of equal or higher level
	- Non magical items can be repaired with magic or through the corresponding craft skill
		- Generally it takes a DC 20 craft check and 1 hour per point of damage to repair an item
	- The starting price for a repair is typically ⅒th of the item’s original cost. This of course goes up if it is significantly damaged or ruined