CamelCase: The time complexity of the CamelCase code is O(n). This is simple, but because we use one for loop to iterate over an array of characters the time is only dependent on the length of the array
being n. So because of this we can say that the time complexoty is O(n). The space complexity of the program is also O(n). This is because the space complexity is dependent on the size of the character array.
We know that the size of the array is n, so the only thing that the space is dependent on is the integer n. So we can say that the space complexity is also O(n).


Correctness and the loop invariant: The bugs in this program are found in the while loop of the code. To fix the code, we simply change the comparisons from > to >=. The time complexity of the program is is O(n^2).
This is because we have 2 nested for loops that are dependent on the size of the input, which is n. n * n = n^2, so therefore we can say that the time complexity is O(n^2). The space complexity, on the other hand, is
O(n). This is because the space is dependent on storing the values in the integer array arr. The size of this array is n, so because of this we can say that the space complexity is O(n).
