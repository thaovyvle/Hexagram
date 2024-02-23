# Hexagram
Programming Language: Java

A Hexagram is a 6-pointed star, sometimes called the Star of David. Given these numbers:
```text
3 17 15 18 11 22 12 23 21 7 9 13
```
There are four unique ways of assigning the numbers to vertices of the hexagram such that all of the sets of four numbers along the lines have the same sum (57 in this case). All other ways may be obtained from these by rotation and/or reflection.

<img width="439" alt="Screenshot 2024-02-22 at 7 29 00 PM" src="https://github.com/thaovyvle/Hexagram/assets/122627050/6d193326-6dc4-4254-a77b-5c97987da7d8">

Given 12 distinct numbers, in how many ways, disregarding rotations and reflections, can you assign the numbers to the vertices such that the sum of the numbers along each of 6 straight lines passing through 4 vertices is the same?

# Input
There will be several test cases in the input. Each test case will consist of twelve unique positive integers on a single line, with single spaces separating them. All of the numbers will be less than 1,000,000. The input will end with a line with twelve 0s.

# Output
For each test case, output the number of ways the numbers can be assigned to vertices such that the sum along each line of the hexagram is the same. Put each answer on its own line. Output no extra spaces, and do not separate answers with blank lines.

## Sample Input
```text
3 17 15 18 11 22 12 23 21 7 9 13
1 2 3 4 5 6 7 8 9 10 11 13
0 0 0 0 0 0 0 0 0 0 0 0
```

## Sample Output
```text
4
0
```
