# 60_wrapBinarySearch

0. find the index of a specified value within an ordered list
1. When I am asked to find the index of a value in a list of size n, the recursive abstraction can find the index of a value of a list of size n/2
2.  a. if the lowerBound is greater than the upperBound, return -2. 
b. if the value to find is at the current index, return the index.
c. otherwise ...
i.  if the value to find is greater, increase the lowerBound by 1
ii. if it is smaller, decrease the upperbound by 1.
