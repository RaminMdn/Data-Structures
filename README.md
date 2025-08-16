# 📚 Data Structures Practice in Python

This repository contains implementations of fundamental data structures in Python. It's created for personal learning and hands-on practice, with a focus on writing clean, testable code. Each data structure is implemented in its own file with methods, example usages, and unit testing.

---

## File Structure

data-structures-python/
│
├── linked_list.py # Singly linked list implementation
├── stack.py # Stack implementation
├── queue.py # Queue implementation
├── tree.py # Binary tree implementation
├── graph.py # Graph using adjacency list
├── README.md # Project documentation (this file)

<pre> <code>data-structures-python/ 
│ 
├── linked_list.py # Singly linked list implementation
├── stack.py # Stack implementation 
├── queue.py # Queue implementation 
├── tree.py # Binary tree implementation 
├── graph.py # Graph using adjacency list 
├── README.md # Project documentation (this file) </code> 
</pre>


## Typical File Content

Each file includes:

- A class defining the data structure
- Methods for performing standard operations
- Simple usage examples for quick verification
- A `run_unit_tests()` function using Python's `unittest` module

### Implemented Data Structures

| Data Structure  | File             | Description                                                            |
|-----------------|------------------|------------------------------------------------------------------------|
| **Linked List** | `linked_list.py` | Singly linked list with `append`, `delete`, `search`, etc.             |
| **Stack**       | `stack.py`       | Stack using list with `push`, `pop`, `peek`, `is_empty`                |
| **Queue**       | `queue.py`       | Queue using list or `deque`, with enqueue/dequeue methods              |
| **Tree**        | `tree.py`        | Binary tree with insertion, traversal, search                          |
| **Graph**       | `graph.py`       | Graph using adjacency list, with methods to add/remove nodes and edges |

---

## How to Use

You can run each file directly to see basic examples and unit test output:

```bash
python linked_list.py
