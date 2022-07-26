# Stack And Queues

## difference between Stack and Queue

The stack is based on LIFO(Last In First Out) principle The queue is based on FIFO(First In First Out) principle Insertion Operation is called Push Operation Insertion Operation is called Enqueue Operation Deletion Operation is called Pop Operation Deletion Operation is called Dequeue Operation Push and Pop Operation takes place from one end of the stack Enqueue and Dequeue Operation takes place from a different end of the queue The most accessible element is called Top and the least accessible is called the Bottom of the stack The insertion end is called Rear End and the deletion end is called the Front End Simple Implementation Complex implementation in comparison to stack Only one pointer is used for performing operations Two pointers are used to perform operations Empty condition is checked using Top==-1 Empty condition is checked using Front==-1 or Front==Rear+1 Full condition is checked using Top==Max-1 Full condition is checked using Rear==Max-1 There are no variants available for stack There are three types of variants i.e circular queue, double-ended queue and priority queue Can be considered as a vertical collection visual Can be considered as a horizontal collection visual Used to solve the recursive type problems Used to solve the problem having sequential processing

## What is Stacks and how to use it?

Stack is a linear data structure that follows the specific order to perform the operations. Pushing an element into the stack from one end and popping an element out of the same end are two operations we do on the stack. The term "top of the stack" refers to the point at which all operations are carried out. Since a stack adheres to the Last In First Out (LIFO) principle, it is crucial to keep in mind that it only holds pieces of the same data type.

Basic operations

Stack supports two basic operations which are;

- push — inserts into the stack.
- pop — deletes from the stack.

Other operations are also available but their functionality is to check the status of the Stack, unlike the insertion and deletion operations. And they are;

- isFull — checks if the stack is full.

- isEmpty — checks if the stack is empty.

- peek — gets the element at the top of the Stack.

## What is Queue?

Queue : a linear data structure in which we can insert the element from one side of the list and delete the element from the other side of the list. The end of the list from where the elements are inserted is called the rear end and the end from where the elements are deleted is called the front end. Therefore, the queue data structure follows the FIFO(First In First Out) principle, which means the element inserted first from the rear end will be the first element to be deleted from the front end. The insertion technique in the queue data structure is called enqueue operation and the deletion technique in the queue data structure is called dequeue operation.


