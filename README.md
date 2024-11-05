# Extra Exercises (No Scores)

## Q: Sum of Diagonal Elements

Write a program to compute the sum of the diagonal elements of a square matrix.

The program first receives the size of the matrix `n`, which represents both the number of rows and columns, making it a square matrix. Then the user is asked to fill in the values. The program should then compute and print out the sum of the elements on the matrix's main diagonal.

**Case 1**

Sample input:
```
3
1 2 3
4 5 6
7 8 9
```

Sample output:
```
15
```

**Case 2**

Sample input:
```
4
10 0 0 0
0 20 0 0
0 0 30 0
0 0 0 40
```

Sample output:
```
100
```

## Q: Matrix Addition

Write a program to add two matrices provided by the user.

The program first receives the dimensions of the matrices, `n` for the number of rows and `m` for the number of columns. Then it asks the user to fill in the values for both matrices. The program then computes the sum of the two matrices and outputs the resulting matrix.

**Case 1**

Sample input:
```
2 2
1 2
3 4
5 6
7 8
```

Sample output:
```
6 8
10 12
```

**Case 2**

Sample input:
```
3 3
1 1 1
1 1 1
1 1 1
2 2 2
2 2 2
2 2 2
```

Sample output:
```
3 3 3
3 3 3
3 3 3
```

## Q: Element Frequency in 2D Array

Write a program to determine the frequency of a specific element in a 2D array.

The program first receives the dimensions of the matrix, `n` for the number of rows and `m` for the number of columns. Then, it asks the user to fill in the values. Subsequently, it obtains the element for which the frequency needs to be calculated and prints out the frequency count.

**Case 1**

Sample input:
```
3 3
1 2 3
4 5 6
7 8 9
5
```

Sample output:
```
1
```

**Case 2**

Sample input:
```
2 4
9 8 7 6
5 4 3 2
4
```

Sample output:
```
1
```

**Case 3**

Sample input:
```
3 3
2 3 2
4 2 6
2 8 2
2
```

Sample output:
```
4
```

## Q: Reverse Array

Please write a function reverseArray to take in two parameters: an array and its size. The function should reverse the elements of the array in place.

The function prototype will be `void reverseArray(int *arr, int size)`.

The program first receives the size of the array and its elements from the user. Then, the function reverseArray is called from `main()` to reverse the elements of the array. The reversed array is then printed in the `main()` as the final output.

**Case 1**

Sample input:
```
5
1 2 3 4 5
```

Sample output:
```
5 4 3 2 1
```

**Case 2**

Sample input:
```
4
10 20 30 40
```

Sample output:
```
40 30 20 10
```

## Q: Calculate Sum and Product

Please write a function `calculate` to compute the sum and product of two integers using pointers.

The function prototype will be `void calculate(int *num1, int *num2, int *sum, int *product)`.

The program first receives the values of two integers from the user. Then, the function `calculate` is called from main() to compute their sum and product. The results are printed in the main() as a final output.

**Case 1**

Sample input:
```
4 5
```

Sample output:
```
Sum: 9 Product: 20
```

**Case 2**

Sample input:
```
6 3
```

Sample output:
```
Sum: 9 Product: 18
```

## Q: Count Occurrences

Please write a function `countOccurrences` to count the number of occurrences of an integer in an array. The function takes a pointer to the array, the size of the array, the target number to search, and a pointer to store the count result.

The function prototype will be `void countOccurrences(int *arr, int size, int target, int *count)`.

The program receives the number of elements in the array, the integers themselves, and a target number from the user. The function `countOccurrences` is called from main() to determine how many times the target number appears in the array. The count is then printed in the main() as the final output.

**Case 1**

Sample input:
```
6 1 2 3 4 2 2 2
```

Sample output:
```
3
```

**Case 2**

Sample input:
```
4 7 8 9 10 5
```

Sample output:
```
0
```

## Q: Calculate Average

Please write a function `calculateAverage` that takes in the addresses of three integers, `n1`, `n2`, `n3`, and an address of a float `average`.

The function prototype will be `void calculateAverage(int *n1, int *n2, int *n3, float *average)`.

The program first receives the values of `n1`, `n2`, and `n3` from the user. Then, the function `calculateAverage` is called from `main()`. Inside the function, the average of the three integers is calculated and assigned to the float variable pointed by `average`. The result is printed in the `main()` as a final output.

** Case 1 **

Sample input:
```
3
6
9
```

Sample output:
```
6.0
```

** Case 2 **

Sample input:
```
15
25
35
```

Sample output:
```
25.0
```

## Q: Find Minimum and Maximum

Write a function `find_min_max` that takes an array and returns the minimum and maximum elements using pointers.

The function prototype will be `void find_min_max(int *arr, int n, int *min, int *max)`.

The program receives the size of the array `n` and the array elements from the user. The function `find_min_max` assigns the minimum and maximum values to `min` and `max` respectively. These values are printed in `main()` as the final output.

**Case 1**

Sample input:
```
4
5 3 9 1
```

Sample output:
```
Minimum: 1, Maximum: 9
```

**Case 2**

Sample input:
```
6
11 25 3 77 8 5
```

Sample output:
```
Minimum: 3, Maximum: 77
```

## Q: Find the Length of a String Using Pointers

Write a program to find the length of a string using pointers. The program should define a function `strLength` that takes a character pointer as an argument and returns the length of the string.

The function prototype will be `int strLength(char *str)`.

The program first receives a string from the user. The function `strLength` is then called from `main()`, and the length of the string is printed as the final output.

**Case 1**

Sample input:
```
hello
```

Sample output:
```
5
```

**Case 2**

Sample input:
```
C programming
```

Sample output:
```
13
```

## Q: Sort an Array Using Pointers

Write a program to sort an array of integers in ascending order using pointers. The program should define a function `sortArray` that takes an integer pointer and the size of the array.

The function prototype will be `void sortArray(int *arr, int size)`.

The program first receives the size of the array, followed by its elements. The function `sortArray` is then called from `main()`, and the sorted array is printed as the final output.

**Case 1**

Sample input:
```
5
3 1 4 5 2
```

Sample output:
```
1 2 3 4 5
```

**Case 2**

Sample input:
```
3
12 11 13
```

Sample output:
```
11 12 13
```


