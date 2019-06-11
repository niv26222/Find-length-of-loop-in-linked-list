# Find-length-of-loop-in-linked-list
Java program to count number of nodes in loop in a linked list if loop is present  




Write a function detectAndCountLoop() that checks whether a given Linked List contains loop and if loop is present then returns count of nodes in loop. For example, loop is present in below linked list and length of loop is 4. If loop is not present, then function should return 0.

We know that Floyd’s Cycle detection algorithm terminates when fast and slow pointers meet at a common point. We also know that this common point is one of the loop nodes (2 or 3 or 4 or 5 in the above diagram). We store the address of this common point in a pointer variable say ptr. Then we initialize a counter with 1 and start from the common point and keeps on visiting next node and increasing the counter till we again reach the common point(ptr). At that point, the value of the counter will be equal to the length of the loop.
