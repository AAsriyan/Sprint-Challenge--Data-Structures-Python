Add your answers to the questions below.

1. What is the runtime complexity of your ring buffer's `append` method? O(1) because accessing is O(1) and all I'm doing is swapping values since we initialized the length of our array already.

2. What is the space complexity of your ring buffer's `append` function? This is also constant O(1) since no new space in the array is ever created

3. What is the runtime complexity of your ring buffer's `get` method? O(n) since we are looping through each element to check if it is not None.

4. What is the space complexity of your ring buffer's `get` method? O(1) constant since I'm just altering the already created array, not creating a new array


5. What is the runtime complexity of the provided code in `names.py`? O(n^2) since it's a nested loop

6. What is the space complexity of the provided code in `names.py`? O(n) simplified, but technically 3n since we have two lists of names with an n size and we are creating a duplicates list which could be n as the worst case.

7. What is the runtime complexity of your optimized code in `names.py`? O(n) linear simplified, O(2n) since I am running two loops separately.

8. What is the space complexity of your optimized code in `names.py`? O(n) linear simplified, O(4n) since we have the two two lists of names, a duplicates list and now a names hash table which could all be n at worst case.
