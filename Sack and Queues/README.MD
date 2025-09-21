# Data Structures and Algorithms – Stacks and Queues

This repository covers fundamental **stack** and **queue** implementations in Python.  
Each implementation comes with common operations like **insertion, deletion, search, and traversal** where applicable.

---

## 📌 Data Structures Covered

### **Pointer Structures**  

Pointer-based structures store elements that are **not required** to be in sequential memory.  
Each element (node) contains one or more **links** (pointers) to other elements in the structure.  

**Advantages:**  

- Do not require contiguous memory allocation  
- Can start small and grow dynamically as nodes are added  

---

### **Stacks**  

A **stack** is a linear data structure that follows the **LIFO (Last In, First Out)** principle.  
The most recently inserted element is the first one to be removed.  

**Implemented functionality:**  

- **Push** → Insert an element onto the stack  
- **Pop** → Remove the top element from the stack  
- **Peek** → View the top element without removing it  
- **Size** → Get the number of elements in the stack  
- **IsEmpty** → Check if the stack is empty  
- **Clear** → Remove all elements from the stack  

**Why use stacks:**  

- Track history (e.g., undo/redo operations)  
- Function call management in programming (call stack)  
- Expression evaluation and syntax parsing  

---

### **Queues**  

A **queue** is a linear data structure that follows the **FIFO (First In, First Out)** principle.  
The element inserted first is the first one to be removed.  

**Implemented functionality:**  

- **Enqueue** → Insert an element at the rear of the queue  
- **Dequeue** → Remove an element from the front of the queue  
- **Peek/Front** → View the element at the front without removing it  
- **Size** → Get the number of elements in the queue  
- **IsEmpty** → Check if the queue is empty  
- **Clear** → Remove all elements from the queue  

**Why use queues:**  

- Task scheduling (CPU scheduling, print queues)  
- Handling asynchronous data (e.g., messaging systems)  
- Breadth-first search (BFS) in graphs and trees  
