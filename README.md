# Light-Out-Puzzle

## Authors
- [Devicez](https://github.com/Devicez)
- [SHihozs](https://github.com/SHihozs)

## FILE IN /SRC FOLDER
- LightOutPuzzle.java

## CLASS IN /OUT FOLDER
- LightOutPuzzle.class

## INTRODUCTION
  - Lights are placed in N x N grid. Each of them can be ON (1) or OFF (0). When a light is toggled, from ON to OFF or OFF to ON, so are its horizontal and vertical neighbors 
  – if any of them exists. Find a way to switch off all lights and print one possible sequence.

## REQUIREMENTS

# 1. The progam must at least
  - Get grid size (N must be at least 3) and initial states of N x N lights from user
  - Find at least 1 sequence to turn off all the light. You’ll get extra point if the number of moves in this sequence is minimum. Display the light states in each move, until all lights are OFF.

# 2. Design a better user interface
  - Good user interface doesn’t mean fancy output, but rather how your program is easy to understand & to use even without user manual.

# 3. Data Structure 
  - There are many approaches to solving this problem. Using brute force (i.e. trying all possible states of all lights) is one of them. But you should research and implement a better solution.
  - In my solution solving it with graphs and using proper Java collection & JGraphT (version 1.5.0) APIs

# 4. Algorithm
  - How do you find a sequence of moves to switch off all the lights ? If you use well-known
algorithms (e.g. Dijkstra, Bellman-Ford, etc.), explain reasons for using them
  - Demonstrate how your algorithm works step-by-step until all lights are off, using the example
of 3 x 3 grid and initial states 000110101.
  - How do you know whether the number of moves in this sequence is minimum ?

# 5. Exception handling
  - For example, don’t give a limitation that your program will crash if N is negative just because you are too lazy to check for valid input


