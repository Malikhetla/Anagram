# Anagram

1. Correctness

The code does what it is intended to do and generates anagrams as per expected output. It generates groups lists from strings where "bat" does not have an anagram from the list provided and is grouped into its own list,  "ate", "eat" and "tea" are anagrams of each other so belong to their own list while "nat" and "tan" are also anagrams of each other therefore belong to a separate list. However, there is an error on line 3 where "sorted()" expects an argument to iterate over and is not provided with one. There are also indentation issues with the code from line 3 to line 10. For example, the return statement on line 10 must be inside the function declaration on line 2 and not outside. 

2. Efficiency 

The code is efficient for the given example because a dictionary is used which has a consistent time complexity O(n) . Since the for-loop on line 4 iterates depending on the number of items looked up in the dictionary , larger dictionariess may make the code less efficient and a different data structure such as tuple which is much more memory efficient can be used. 

3. Style 

The code is clear and easy to follow. It provides a logical understanding of the solution to the problem. There are also clear variable, class and function names with the exception of "ob1" on lines 11 and 12 which does not convey much meaning. 

4. Documentation 

There is not sufficient documentation in the code to fully understand what the purpose of the code is if a description is not provided. 


General Comments 

This is a good solution that adequately address the problem. The student demostrates good understanding logical thinking and good use various concepts such as data structures, loops and conditional statements. Only a few syntax issues such as indentation and variable naming need to be improved on.
