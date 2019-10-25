# DFS-3

## Problem1: Number Confused(https://leetcode.com/problems/confusing-number-ii/)

We can rotate digits by 180 degrees to form new digits. When 0, 1, 6, 8, 9 are rotated 180 degrees, they become 0, 1, 9, 8, 6 respectively. When 2, 3, 4, 5 and 7 are rotated 180 degrees, they become invalid.

A confusing number is a number that when rotated 180 degrees becomes a different number with each digit valid.(Note that the rotated number can be greater than the original number.)

Given a positive integer N, return the number of confusing numbers between 1 and N inclusive.

Example 1:

Input: 20

Output: 6

Explanation: 

The confusing numbers are [6,9,10,16,18,19].

6 converts to 9.

9 converts to 6.

10 converts to 01 which is just 1.

16 converts to 91.

18 converts to 81.

19 converts to 61.

Example 2:

Input: 100

Output: 19

Explanation: 

The confusing numbers are [6,9,10,16,18,19,60,61,66,68,80,81,86,89,90,91,98,99,100].

Note:

1 <= N <= 10^9

## Problem2: Matchsticks to Square (https://leetcode.com/problems/matchsticks-to-square/)

Remember the story of Little Match Girl? By now, you know exactly what matchsticks the little match girl has, please find out a way you can make one square by using up all those matchsticks. You should not break any stick, but you can link them up, and each matchstick must be used exactly one time.

Your input will be several matchsticks the girl has, represented with their stick length. Your output will either be true or false, to represent whether you could make one square using all the matchsticks the little match girl has.

Example 1:

Input: [1,1,2,2,2]

Output: true

Explanation: You can form a square with length 2, one side of the square came two sticks with length 1.

Example 2:

Input: [3,3,3,3,4]

Output: false

Explanation: You cannot find a way to form a square with all the matchsticks.

Note:

The length sum of the given matchsticks is in the range of 0 to 10^9.

The length of the given matchstick array will not exceed 15.

