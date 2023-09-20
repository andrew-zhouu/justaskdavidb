# Introduction to Singly Linked Lists and Doubly Linked Lists
Singly linked lists and doubly linked lists are special types of lists, or collections of data, that contain slightly different information than other types of lists or arrays. 
There are two fields of data in linked lists: the data elements themselves and a node, which is a pointer to the position of element(s) immediately next to it. 
Singly linked lists’ nodes can only access the next node, while doubly linked lists’ nodes can access both the previous and next node. 
Singly linked lists and doubly linked lists have both many advantages and many disadvantages, as well as some differing uses.

### Singly Linked Lists
Singly linked lists’ nodes are connected only to the next node, and many potential problems or benefits can arise from this distinction. 
Some advantages of singly linked lists would be the ease of accessing data in the forward direction, the insertion and deletion of nodes are easy and don’t require the movement of all elements, and the easy implementation of its data structure. 
Additionally, singly linked lists require less memory than other linked lists, such as doubly linked lists. 
However, the main problem with singly linked lists is that directly accessing the previous node is impossible because of the lack of data in the current node. Also, the access of a node is time consuming because of the lack of easy indexing. 

### Doubly Linked Lists
In contrast, doubly linked lists’ nodes are connected to both the previous and next node, so this difference impacts its potential, in both positive and negative ways. 
For example, the main advantage of a doubly linked list over a singly linked list is its ability to traverse easily both in a forward and backward directions. 
If pointers are given on a specific node’s position, then its deletion would be much more efficient as opposed to singly linked lists because a previous node is needed to delete a node; however, singly linked lists’ nodes do not have data on the previous node, so the list needs to be traversed again sometimes in order to delete the node. But doubly linked lists can be disadvantageous compared to singly linked lists as well. 
For instance, extra space is needed to store the previous pointer in a doubly linked list. 
Additionally, the extra pointer can be burdensome, as all operations such as insertion would require more pointers to be modified than if the insertion occurred in a singly linked list.

### Comparing Uses
Because of the many differences between singly linked lists and doubly linked lists, their uses are completely different. Doubly linked lists are used mostly when handling recent data and the order that the data is in. 
For example, the forward and backward navigation on web browsers and data involving a user’s history, such as MRU (Most Recently Used) and LRU (Least Recently Used), both use doubly linked lists to maintain order. 
Doubly linked lists are also used to undo operations because it involves a user’s history and can be used to track or determine the executions of multiple processes. 
Similar to the doubly linked list, singly linked lists can also be used to undo functions. Singly linked lists are implemented in stacks and queues, which are the foundation of computer science. 
Singly linked lists can also be used to represent polynomials and graphs because of the links between different values in polynomials.

### Conclusion
Ultimately, both singly linked lists and doubly linked lists can be problematic or beneficial depending on the circumstance and each have their own unique uses. 
Linked lists are very important to computer science, and many commonly used features use linked lists. 
With different types of linked lists, numerous more possibilities still exist, and more functions can be created with the fundamental and simplistic yet important roles of linked lists.

### Works Cited
Wikimedia Foundation. (2023, September 20). Linked List. Wikipedia. https://en.wikipedia.org/wiki/Linked_list  

Garwal, P. (2023, February 15). Advantages and Disadvantages of Linked List. GeeksforGeeks. https://www.geeksforgeeks.org/advantages-and-disadvantages-of-linked-list/  

Mittal, D. (2023, February 23). Applications of linked list data structure. GeeksforGeeks. https://www.geeksforgeeks.org/applications-of-linked-list-data-structure/  

GeeksforGeeks. (2023, April 19). Introduction to Doubly Linked List – Data Structure and Algorithm Tutorials. GeeksforGeeks. https://www.geeksforgeeks.org/data-structures/linked-list/doubly-linked-list/ 