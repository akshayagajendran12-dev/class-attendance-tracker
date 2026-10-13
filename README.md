# class-attendance-tracker
## Problem Statement
Count the total number of days a student was present and find the longest consecutive streak of present days.

## Algorithm
1. Initialize present, currentStreak, and longestStreak to 0.
2. Traverse the attendance array once.
3. If the current value is 1, increment present and currentStreak.
4. Update longestStreak if currentStreak is greater than it.
5. If the current value is 0, reset currentStreak to 0.
6. Return the total present days and longest streak.

## Example
Input: [1, 1, 0, 1, 1, 1, 0, 1]

Output:
- Present: 6
- Longest streak: 3

## Complexity Analysis
- Time Complexity: O(n), because every day is processed once.
- Auxiliary Space Complexity: O(1), because only a fixed number of variables are used.
- Single Pass: Yes. Both answers are calculated during the same traversal.

## Handling All-Absent Attendance
If every value is 0, the present count and longest streak both remain 0.

