# Valid Anagram

## Difficulty
Easy

## Topic
String, Hashing

## Approach
- First check whether both strings have the same length.
- Store the frequency of each character from the first string in an unordered_map.
- Traverse the second string and decrease the frequency.
- If any frequency becomes negative, the strings are not anagrams.
- Otherwise, they are anagrams.

## Time Complexity
O(n)

## Space Complexity
O(1)