# CI2024_lab3

## N-Puzzle problem
The n puzzle is a classical problem for modeling algorithms involving heuristics. Commonly used heuristics for this problem include counting the number of misplaced tiles and finding the sum of the taxicab distances between each block and its position in the goal configuration. Note that both are admissible.
- (https://en.wikipedia.org/wiki/15_puzzle#:~:text=The%20n%20puzzle%20is%20a,Note%20that%20both%20are%20admissible.)

### Expected output for the 8-Puzzle problem:
|1|2|3|
|:---:|:---:|:---:| 
|4|5|6|
|7|8|0|

## Depth-First approach
Memory consumption is high, we can't always find a solution even for the 8-Puzzle problem if the number of iterations is too low

## Breadth-First approach
Memory consumption is a little lower than the depth-first approach but still too high, we can't always find a solution even for the 8-Puzzle problem if the number of iterations is too low

## A*

