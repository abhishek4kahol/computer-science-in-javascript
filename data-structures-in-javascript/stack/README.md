# STACK DATA STRUCTURE

* Stack is a linear data structure which follows a particular order in which the operations are performed. The order may be LIFO(Last In First Out) or FILO(First In Last Out).

* Mainly the following three basic operations are performed in the stack:
1. Push: Adds an item in the stack. If the stack is full, then it is said to be an Overflow condition.
2. Pop: Removes an item from the stack. The items are popped in the reversed order in which they are pushed. If the stack is empty, then it is said to be an Underflow condition.
3. Peek or Top: Returns top element of stack.


* There are two ways to implement a stack:
1. Using array
2. Using linked list

## Stack implementation using Arrays

* Pros: Easy to implement. Memory is saved as pointers are not involved.
* Cons: It is not dynamic. It doesn’t grow and shrink depending on needs at runtime.


## Stack implementation using Linked List

* Pros: The linked list implementation of stack can grow and shrink according to the needs at runtime.
* Cons: Requires extra memory due to involvement of pointers.
