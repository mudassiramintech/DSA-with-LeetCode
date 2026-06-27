# Two Sum

## Difficulty
Easy

## Topic
Array, Hash Map

## Approach Used
Hashing (unordered_map)

### Algorithm
1. Traverse the array.
2. Calculate:
   second = target - first
3. Check whether second already exists in the hash map.
4. If yes, return both indices.
5. Otherwise store the current element and its index.

## Time Complexity
O(n)

## Space Complexity
O(n)

## What I Learned
- Using unordered_map for fast lookup.
- Complement technique.
- Solving the problem in one traversal.