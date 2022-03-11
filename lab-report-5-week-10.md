# Test # 1

* For this test I searched it manually to find out that this test is different with my implementation compared to the lab given. 
* I basically ran through multiple tests from the markdown file and saw this test different with the two implementations.
* The tests is file 518 or test 518.html

# Lab implementation
![alt text](comp1.png)

# My implementation
![alt text](comp2.png)

# Actual output
![alt text](actualtest1.png)

* Based on the shown outputs, my implementation is shown to be the correct one.
* The problem with the implementation for the Lab is that it had /uri twice instead of once so I think the problem with the code is that a loop happen where it counted too many times and as a result made two copies of the same link. If I were to go and search for a fix I would go through the findCloseParen function as the function might've accidentially counted the parenthesis wrong due to the input having a lot of parenthesis being placed mixed together. And also I would fix the GetLinks function because compared to my code and its code it uses a for loop whenever its checking the file directory and in my code it doesn't so that could cause an error in the output.
