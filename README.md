## Quiz Practice

The github for this file is:

https://github.com/itamames/Quiz1Practice

Answers will be posted in less than 24 hours.

## Question 1: 
Strings d1 and d2 have n characters each and n ≥ 0.

For the following operations:

a) Define the worst-case runtime complexity in big-O notation in terms of n? Explain your answer.
```java
 System.out.println(s1.indexOf('a'));
```
Answer:
```text
...
```

b) Define the best-case runtime complexity in big-O notation in terms of n? Explain your answer.

```java
 System.out.println(s1.equals(s2));
```
Answer:
```text
...
```

## Question 2: 

Define the runtime complexity of the following code fragments in big-O notation as functions of m and/or n? Explain each answer. (Your answers should represent the tightest/closest function for the code given.)

a)
```java
int sum = 0;
for (int i = 1; i <= n; i++)
        for (int j = 1; j <= n; j+=2)
                sum += (i+j);
```

Answer:
```text
...
```

b)
```java
int sum = 0;
for (int i = 1; i <= 50; i+=2)
        for (int j = 1; j <= n; j+=3)
                sum += (i+j);
```
Answer:
```text
...
```

c)
```java
int sum = 0;
for (int i = 1; i <= m; i++)
	for (int j = 1; j <= n; j*=2)
		sum += (i+j);
```
Answer:
```text
...
```

d)
```java       
int sum1 = 0;
for (int i = 1; i <= m*m; i++)
     sum1 += i;
int sum2 = 0;
for (int j = 1; j <= m; j++)
     sum2 += j;
```
Answer:
```text
...
```

## Question 3: (15%) 

Consider the following Java method that returns true if an array of n integers has two adjacent values that are the same, false otherwise:

```java
public static boolean adjacentDuplicates(int[] a) {
	for (int i = 0; i < a.length-1; i++)
		if (a[i] == a[i+1])
			return true;
	return false;
}
```
a) What is the runtime complexity of this method using big-O notation in the worst case? Explain your answer.

Answer:
```text
...
```

b) What is the runtime complexity of this method using big-O notation in the best case? Explain your answer.

Answer:
```text
...
```

## Question 4:

a) Suppose an algorithm processes n data elements using exactly n<sup>2</sup> operations, where n = 8. If we double the number data elements, how many additional operations will the algorithm perform? Show your work.


Answer:
```text
...
```

b) Suppose an algorithm processes n data elements using exactly log<sub>2</sub>n operations, where n = 8. If we double the number data elements, how many additional operations will the algorithm perform? Show your work.


Answer:
```text
...
```

c) Suppose an algorithm processes n data elements using exactly 2<sup>n</sup> operations, where n = 8. If we double the number data elements, how many additional operations will the algorithm perform? Show your work.


Answer:
```text
...
```


## Question 5: 

Given an array of integers in increasing order, and given a target sum, we wish to determine if the array contains two integers that can be added together to make that sum.

a) What is the worst-case runtime complexity (in big-O notation) of the following solution if the length of the array is n? Briefly explain your answer.

```java
public static boolean sumInArray(int[] a, int sum) {
	//finds sum of all pairs in the array
	for (int i = 1; i < a.length; i++)
	        for (int j = 0; j < i; j++)
	                if (a[i] + a[j] == sum)
	                        return true;
	return false;
}
```

Answer:
```text
...
```

b) Create an algorithm that performs better asymptotically than the algorithm above. Determine the worst-case runtime complexity of your algorithm.


Answer in Java:
```java
public static boolean sumInArray(int[] a, int sum) {
...
}
```

Answer:
```text
...
```

## Question 6: 
Given n data values, an algorithm processes these n data values with a running time given by the equation T(n) = 6n<sup>2</sup> + 15n + 75.

a) Show that T(n) = O(n<sup>2</sup>) by using the formal definition of the big O function.

b) Is T(n) = O(n<sup>3</sup>)? Explain.

Answer:
```text
...
```
c) Is T(n) = O(n)? Explain.

Answer:
```text
...
```
