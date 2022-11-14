# Simple-Battle-Damage-5e
This is a damage calculator for managing rolls for large-scale encounters in D&D 5e.

I made this program in response to an excess of player-controlled NPC's during a battle. Treating them as a single unit would have removed the entire reason for having them, but using them separately meant they were rolling over 70 attacks their turn. My solution was to roll for each target rather than each attack. Obviously, this solution only works when there is a significant discrepancy between the number of units on each side.

## How To Use

Select a target and decide how many identical attacks will be made against it, then plug these numbers into the program.

Roll the attack, with any neccesary modifers such as advantage or crit damage, and plug those in.

That's it. 

"ACT DMG" should change to the correct number. If you have on-hit effects "Good ATKs' should tell you how many times to proc them.

## Additional Information

Damage starts at 50% and changes in increments of 5 based off the difference between ATK and AC. On a crit you add or subtract 50% to this.
Advantage/Disadvantage modifies the ATK used in calculations by 4. If you don't like this just dont mark it. 

Alternatively, heres the formula: TOTAL = DMG * (ATK + (4 * Advantage Status) - AC + 10 * (0, 1, 2 Crit Status)) * 5 / 100

Every number used is based off my understanding of averages, and the intended balance of D&D 5e.
