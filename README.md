# Advent Of Code Day 6 - Lanternfish
Part 1:
The goal of this part was to count the amount of lanternfish in an increasing school of these fish, where a new fish was added every single time the internal timer of another went off. My method for this was *countfish*, where I decreased the internal timer for the fish and if it reached zero, replaced it with 6 and added an 8 to the end. At the end, I returned the size of the ArrayList that I was counting the fish in. 


