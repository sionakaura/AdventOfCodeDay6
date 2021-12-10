# Advent Of Code Day 1 - Sonar Sweep

For the main, I had to import a file of the data values and convert them into an ArrayList. 

Part 1:
The goal of this part was to count the number of times the depth of the ocean increased. My method for this was *sonarSweep1*, where I checked the values of an ArrayList of data values to see if a value was greater than the one before it. If this was true, I added it to my count of increases. At the end, I returned the number of increases. 

Part 2:
This part was similar to part 1, except it counted the increases in windows of 3. It compared one group of three to another group of three and determined if there was an increase. My method for this was *sonarSweep2*, which was similar to the first but checked it through the windows of three. At the end, I returned the number of increaases. 

# Advent Of Code Day 2 - Dive!

In the main, I had to import a file of all of the positions and convert them to an ArrayList. 

Part 1: 
The goal of this part was to find the horizontal distance traveled multiplied by the depth of the submarine. My method for this was *part1*, where I checked the substrings of each String in the ArrayList to determine if it was forward, up, or down. After that, I used parseInt to find X, the amount that the horizontal distance or the depth changed by. At the end, I returned the depth * the horizontal distance traveled.

Part 2: The next part was similar to the first part, but this time there was a new variable "aim", which helped calculate the depth. My method for this was *part2*, which was similar to the first method; but when checking if the command was forward, it also increased the depth by the aim * X.  At the end, I returned the depth * the horizontal distance traveled. 

# Advent Of Code Day 6 - Lanternfish
Part 1:
The goal of this part was to count the amount of lanternfish in an increasing school of these fish, where a new fish was added every single time the internal timer of another went off. My method for this was *countfish*, where I decreased the internal timer for the fish and if it reached zero, replaced it with 6 and added an 8 to the end. I used a for loop to repeat this as many times as needed. At the end, I returned the size of the ArrayList that I was counting the fish in. 


