# BINARY-SEARCH-in-python and c

The idea of binary search is to use the information that the array is sorted and reduce the time complexity to O(Log n).


Search a sorted array by repeatedly dividing the search interval in half. Begin with an interval covering the whole array. If the value of the search key is less than the item in the middle of the interval, narrow the interval to the lower half. Otherwise narrow it to the upper half. Repeatedly check until the value is found or the interval is empty.

# APPROACH


We basically ignore half of the elements just after one comparison.

Compare x with the middle element.
If x matches with middle element, we return the mid index.
Else If x is greater than the mid element, then x can only lie in right half subarray after the mid element. So we recur for right half.
Else (x is smaller) recur for the left half.

# LINK FOR REFERENCE
# 1st
JENNY'S LECTURE
https://www.youtube.com/watch?v=V_T5NuccwRA
# 2nd
EDUCATION 4U
https://www.youtube.com/watch?v=81QLBCW94Oo

# Time Complexities

Best case complexity: O(1)
Average case complexity: O(log n)
Worst case complexity: O(log n)
# Space Complexity

The space complexity of the binary search is O(n).

# Binary Search Applications
In libraries of Java, .Net, C++ STL
While debugging, the binary search is used to pinpoint the place where the error happens.
