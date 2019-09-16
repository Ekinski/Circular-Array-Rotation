# Circular-Array-Rotation
Rotation on an array of integers which returns the integer at the rotated position without rotating the original array.

An operation called a right circular rotation on an array of integers. One rotation operation moves the last array element to the first position and shifts all remaining elements right one. For each array, perform a number of right circular rotations and return the value of the element at a given index.

Function Description

Complete the circularArrayRotation function in the editor below. It should return an array of integers representing the values at the specified indices.

circularArrayRotation has the following parameter(s):

a: an array of integers to rotate
k: an integer, the rotation count
queries: an array of integers, the indices to report

Sample Input 0

3 2 3     
1 2 3
0
1
2
Sample Output 0

2
3
1

Input (int[] a, int k, int[] queries)

3 <- Length of A, 2 <- number of rotation, 3 <- Length of queries     
1 2 3 <- a[] 
0  <- q[] what integer at give postion 0 should return new integer after rotation.
1  <- q[] what integer at give postion 1 should return new integer after rotation.
2  <- q[] what integer at give postion 2 should return new integer after rotation.
