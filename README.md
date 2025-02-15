**Advent of Code - Day 19 (2024) - Part 1 - Approach**

For part 1, the goal was to determine how many designs could be made using the available towel patterns. I started coding by reading the input file to get all the patterns and designs. For each design, I checked if it could be formed by matching the patterns at different positions. I compared parts of the design with the patterns and if a match was found, I made sure that the position before the pattern was also reachable. I kept track of all the reachable positions, and by the end of the loop, I counted how many designs could be fully formed. 

**Advent of Code - Day 19 (2024) - Part 2 - Approach**

Part 2 was a bit trickier, the challenge was to count how many different ways a design can be made from the same patterns. Since I need to explore all possible combinations of patterns that can form a design, I chose to use memoization. It stores the no. of ways each design can be formed and directly retrieve the result when the same sub-design is encountered again and saves the code to run for too long. In the end, I calculated how many ways each design could be formed and added them all up, using memoization to speed up the process.
