# COMP110-Worksheet-5

## Joseph Spaul


## (a)

The task that this algorithm performs is for it to check if there are any duplicated elements in the list. It achieves this by iterating through the list one element at a time using for loops.

## (b)

In the algorithm the second for loop has to be completed in order for the first one to be completed, this is 
becasue they are nested loops. We take the time it takes for the inner loop to run and multiply it by the time 
it takes the outer loop to run. 

## (c)

Using i - 1 instead of n - 1 still lets the algorithm be correct because n is the length of the list and i is 
all of the values in a list. This lets the algorithm run normally. 

## (d)

Because the algorithm will have all of the j values already. So, the time the algorithm takes to work out i and
j will be halved.

## (e) 

Yes, the algorithm would still be called quadratic. This is becasue the two nested loops are still being used.

## (f) 

O(n log n) [1] 

## (g)

I will calculate the time complexity of the algorithm:

	O(1) + O(n log n) + O(n) + O(1) 
This can be boiled down to O(n log n) becasue that is the slowest one
	O(n log n)

## (h)

The algorithm with the complexity O(n log n) will run faster. This is becasue the other algorithm has a complexity
of O(n^2) and O(n log n) is faster than O(n^2).

## (i)

The faster the algorithm, the more likley it is that it would take more time and effort to perfect. So, if the programmer doesnt have much time, or the ability, they can use a slower algorithm.


## References:

[1] "Time Complexity", 2017-06-05,url - https://wiki.python.org/moin/TimeComplexity, 
	accessed on 07-11-2019
