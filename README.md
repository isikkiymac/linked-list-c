# Linked List Library in C

A generic, void-pointer-based linked list library in C with full memory management.

## Overview
Built as part of Columbia University's Computer Systems course (COMS 3157). Implements a reusable linked list that stores void pointers, allowing it to hold any data type.

## Tech Stack
- **Language:** C
- **Concepts:** void pointers, function pointers, manual memory management

## Functions Implemented
- `initList` — initialize empty list
- `addFront` — O(1) insertion at head
- `addBack` — O(n) insertion at tail
- `addAfter` — insert after a given node
- `traverseList` — apply a function to each element
- `findNode` — search with custom comparator
- `popFront` — remove and return head data
- `removeAllNodes` — free all nodes
- `reverseList` — pointer manipulation, no allocation

## Key Features
- **Generic design** — stores `void *`, works with any type
- **Custom comparators** — function pointer for flexible equality
- **Custom callbacks** — function pointer for traversal operations
- **Zero memory leaks** — verified with Valgrind
- **O(1) reverse** — pointer-only reversal without malloc

## What I Learned
- Generic programming in C with void pointers
- Function pointers and callbacks
- Manual memory management and leak prevention
- Pointer manipulation for list reversal

## Note
This project was completed for a course. Source code is available upon request due to course policy restrictions. I'm happy to discuss the design and implementation in an interview.
