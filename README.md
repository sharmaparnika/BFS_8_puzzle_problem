# Implementation of BFS for 8-Puzzle problem 

The game is simple yet can be daunting. There is just one rule of the game, as you can see in the video above, you have to slide the tiles in the empty spaces to arrange them in ascending order so that the last space in a 3x3 matrix is blank.

One of the most basic approaches for solving such a problem is to generate a graph map of all possible scenarios from the given initial state and find the goal state (final state) in that map, once found you can backtrack to the initial state to find the path. This approach is called a Brute Force Search or exhaustive search and is generally slower than other search algorithms but serves as a very good learning step.


![image](https://user-images.githubusercontent.com/73773202/156867933-49cbc147-9f70-4418-94fa-63f25321614a.png)


The map generated shows a hierarchy structure which helps in backtracking to find the path and also contains the information of the move by which a child state was created from the parent state.

## Output:

![image](https://user-images.githubusercontent.com/73773202/156867948-e77cff75-f97a-462c-b533-08cf85f27d1b.png)


---
