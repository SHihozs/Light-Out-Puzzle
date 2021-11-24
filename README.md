# Light-Out-Puzzle

## Authors
- [Devicez](https://github.com/Devicez)
- [SHihozs](https://github.com/SHihozs)

## FILE IN /SRC FOLDER
- LightOutPuzzle.java

## CLASS IN /OUT FOLDER
- LightOutPuzzle.class

## INTRODUCTION
  Lights are placed in the N x N grid. Each of them can be ON (1) or OFF (0). When light is toggled, from ON to OFF or OFF to ON, so are its horizontal and vertical neighbors if any of them exists. Find a way to switch off all lights and print one possible sequence.

## REQUIREMENTS

# 1. The program must at least
     1.1 Get grid size (N must be at least 3) and initial states of N x N lights from the user
     
     1.2 Find at least 1 sequence to turn off all the lights. You’ll get an extra point if the number of moves in this sequence is minimum. 
     Display the light states in each move, until all lights are OFF.

# 2. Design a better user interface
     2.1 Good user interface doesn’t mean fancy output, but rather how your program is easy to understand & to use even without a user manual.

# 3. Data Structure 
     3.1 There are many approaches to solving this problem. Using brute force (i.e. trying all possible states of all lights)
     is one of them. But you should research and implement a better solution.
     
     3.2 In my solution solving it with graphs and using proper Java collection & JGraphT (version 1.5.0) APIs

# 4. Algorithm
     4.1 How do you find a sequence of moves to switch off all the lights? If you use well-known algorithms (e.g. Dijkstra, Bellman-Ford, etc.), explain reasons for using them

     4.2 Demonstrate how your algorithm works step-by-step until all lights are off, using the example of a 3 x 3 grid and initial states 000110101.

     4.3 How do you know whether the number of moves in this sequence is minimum?

# 5. Exception handling
     5.1 For example, don’t give a limitation that your program will crash if N is negative just because you are too lazy to check for valid input


