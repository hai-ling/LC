# neetcode general study

## General practices:
##### Solving:
- Understand why the problem solution is its designation (greedy, dp, etc)
- Understand brute force sol'n and time/space comp
- Try to find optimal solution
- Consider time/space comp optimizations
- After solving solution, view video for alternative solutions

##### If you can't solve after 15 minutes:
- View solution(s)
- Identify what you missed out on and why you didn't reach the solution
- Come back to this question later

#### Notes
    --> For arrays, don't forget to consider iterating backwards

### Arrays and Hashing
- dict.get(key, default value) is useful when key may not exist yet
### Greedy

### Heap
- Heap is a binary tree, where root is always smaller than its child.
    - given root k, the child is always 2k+[1 or 2]
- Python uses heapq and its functions

### Dynamic Programming
- A good resource/example:
    https://leetcode.com/problems/house-robber/discuss/156523/From-good-to-great.-How-to-approach-most-of-DP-problems.
- https://stackoverflow.com/questions/6164629/what-is-the-difference-between-bottom-up-and-top-down
    -> See notes on tabulation and memoization: memoization is fast but in recursive approaches with large trees, requires a lot of stack space(not using optimal evaluation order). tabulation is choosing the order of your computations to reduce what you are caching. (think fibonnacci starting from both sides)
- 