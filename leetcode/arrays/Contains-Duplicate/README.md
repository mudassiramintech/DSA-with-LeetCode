# Contains Duplicate

## Difficulty
Easy

## Topic
Array, Hashing

## Approach
Traverse the array and store each element in an unordered_map.
Before inserting an element, check whether it already exists in the map.
If it exists, return true.
Otherwise, insert it and continue.

## Time Complexity
O(n)

## Space Complexity
O(n)