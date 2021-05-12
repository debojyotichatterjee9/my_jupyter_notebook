### Problem Statement

The absolute difference between two integers, a and b, is written as |a-b|. The maximum absolute difference between two integers in a set of positive integers, ***elements***, is the largest absolute difference between any two integers in ***__elements***.

The Difference class is started for you in the editor. It has a private integer array ***(elements)*** for storing ***N*** non-negative integers, and a public integer ***(maximumDifference)*** for storing the maximum absolute difference.

Task
Complete the Difference class by writing the following:

* A class constructor that takes an array of integers as a parameter and saves it to the ***__elements*** instance variable.
* A *computeDifference* method that finds the maximum absolute difference between any **2** numbers in ***__elements*** and stores it in the ***maximumDifference*** instance variable.

#### Input Format

##### Constraints
* 1<= N <= 10
1 <= ***__elements[i]*** <= 100, where 0 <= i <= N - 1

#### Output Format

The Solution class will print the value of the ***maximumDifference*** instance variable.

##### Sample Input

```bash
STDIN   Function
-----   --------
3       __elements[] size N = 3
1 2 5   __elements = [1, 2, 5]
```
##### Sample Output

4

Explanation

The scope of the ***__elements*** array and ***maximumDifference*** integer is the entire class instance. The class constructor saves the argument passed to the constructor as the ***__elements*** instance variable (where the *computeDifference* method can access it).

To find the maximum difference, computeDifference checks each element in the array and finds the maximum difference between any **2** elements: 

|1 - 2| = 1

|1 - 5| = 4

|2 - 5| = 3

The maximum of these differences is **4**, so it saves the value **4** as the ***maximumDifference*** instance variable,then prints the value stored as ***maximumDIfference***, which is **4**.