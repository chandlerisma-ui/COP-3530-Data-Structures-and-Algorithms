# 📚 Data Structures & Algorithms

A collection of data structure implementations in **C** and **C++**, covering core concepts commonly studied in computer science courses.

---

## 📁 Project Structure

```
├── linked-lists/
│   ├── singly_linked_list.c       # Hospital Patient Management System
│   └── doubly_linked_list.c       # Hospital Event Log System
├── queues/
│   └── order_queue.cpp            # Restaurant Order Queue
├── trees/
│   └── binary_search_tree.cpp     # Product Catalog BST
└── README.md
```

---

## 🗂️ Topics Covered

### 1. Singly Linked List — `linked-lists/singly_linked_list.c`
**Context:** Hospital Patient Management System

A singly linked list where each node holds patient information and points to the next node.

**Concepts:**
- Dynamic memory allocation (`malloc`, `free`)
- Traversal and insertion at the end
- Insertion at the middle position (`count / 2`)
- Deletion from the middle position
- Node counting
---

### 2. Doubly Linked List — `linked-lists/doubly_linked_list.c`
**Context:** Hospital Event Log System

A doubly linked list where each node has both a `left` (previous) and `right` (next) pointer.

**Concepts:**
- Bidirectional linking
- Insertion at the beginning
- Deletion from the end (most recent event)
- Memory cleanup on exit
---

### 3. Queue — `queues/order_queue.cpp`
**Context:** Restaurant Order Queue

A queue implemented using `std::vector`, following **FIFO** (First In, First Out) ordering.

**Concepts:**
- Queue data structure (enqueue / dequeue)
- Using `std::vector` as a backing structure (`push_back`, `erase`, `front`)
- Object-Oriented Programming — encapsulation, classes, constructors
- FIFO ordering: orders are processed in the sequence they were received
---

### 4. Binary Search Tree — `trees/binary_search_tree.cpp`
**Context:** Product Catalog sorted by price

A BST where nodes are organized by product price — cheaper items go left, more expensive go right — producing a naturally sorted structure.

**Concepts:**
- Binary Search Tree (BST) structure and properties
- Recursive BST insertion
- In-order traversal (Left → Root → Right) producing ascending sorted output
- Iterative traversal using an explicit `std::stack` (simulates the recursion call stack)
- OOP — two classes, private members, destructor, encapsulation
- Dynamic memory management (`new`, `delete`) with `destroyTree()` to prevent leaks
---

## 🧠 Concept Summary

| Topic | Language | Key Idea |
|-------|----------|----------|
| Singly Linked List | C | One-directional chain, middle insert/delete |
| Doubly Linked List | C | Bidirectional chain, front insert, end delete |
| Queue (FIFO) | C++ | `std::vector`-backed, enqueue/dequeue |
| Binary Search Tree | C++ | Sorted by key, iterative in-order via stack |
---
