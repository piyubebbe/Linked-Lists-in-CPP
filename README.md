# Linked List in C++

**Aim:** Implementation of linked list in C++  
**Software:** Mingw C++ compiler, VS Code, Online C/C++ compiler  

---

## Program 1

### Explanation with Theory
This program demonstrates the creation of a basic linked structure using a `Node` class. Each node holds an integer value and a pointer to the next node. Two nodes are dynamically allocated and linked to form a simple chain. The `display()` method prints the node’s data and checks whether it points to another node or marks the end of the list.  

This approach introduces the concept of pointer-based connectivity, which is foundational in linked lists. It also emphasizes memory allocation and object-oriented design, making it ideal for beginners exploring dynamic data structures in C++.

### Algorithm
1. Define `Node` class with value and `next` pointer  
2. Create two nodes using `new`  
3. Link first node to second  
4. Use `display()` to show each node’s data and linkage  
5. End  

---

## Program 2

### Explanation with Theory
This program builds a singly linked list using dynamic memory allocation and head insertion. The `Node` class encapsulates each element with a value and a pointer to the next node.  

The `addToFront()` function inserts new nodes at the beginning by updating the head pointer. The `printList()` function traverses the list and prints each node’s value, ending with `NULL`.  

This structure supports efficient insertion in **O(1)** time and is ideal for stack-like behavior. It also reinforces key concepts like pointer manipulation, memory management, and traversal logic in object-oriented programming.

### Algorithm
1. Define `Node` class with value and `next` pointer  
2. Initialize `head` as `nullptr`  
3. For each new value:  
   - Create a new node  
   - Point its `next` to current `head`  
   - Update `head` to new node  
4. Traverse and print list using `printList()`  
5. End  

---

## Conclusion
Both programs exemplify the foundational principles of singly linked lists in C++, showcasing dynamic memory allocation, pointer-based node linking, and modular function design.  

- Program 1 shows the creation of a simple two-node chain.  
- Program 2 demonstrates inserting multiple nodes at the head efficiently.  

These implementations reinforce how data structures can be built and traversed. The use of classes encapsulates node behavior, while functions like `display()` and `addToFront()` promote clarity and reusability.  

Together, they offer a strong starting point for mastering linked list operations and pave the way for more advanced features like deletion, tail insertion, or full list encapsulation in object-oriented programming.  
