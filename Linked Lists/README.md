# Data Structures and Algorithms – Linked Lists

This repository covers fundamental **linked list** implementations in Python, including singly, doubly, and circular linked lists. Each implementation comes with common operations like insertion, deletion, search, and traversal.

---

## 📌 Data Structures Covered

### 1. Node

A **Node** is the building block of linked lists.  
It contains:

- **Data**: the stored value  
- **Pointer(s)**: reference(s) to other node(s)  

Types of nodes:

- **Singly**: one pointer → next node  
- **Doubly**: two pointers → next and previous nodes  

---

### 2. Singly Linked List

A **Singly Linked List** is a sequence of nodes where each node points to the **next** node.  

- Traversal: **Forward only** (head → tail)  
- Memory efficient compared to arrays  

**Features implemented:**

- Prepend (insert at head)  
- Append (insert at tail)  
- Delete (by value or position)  
- Size (count number of nodes)  
- Iterate (loop through nodes)  
- Search (find element)  
- Clear (remove all nodes)  

---

### 3. Doubly Linked List

A **Doubly Linked List** has nodes that point to both the **next** and **previous** nodes.  

- Traversal: **Forward and backward**  
- Easier to delete or insert nodes as both neighbours are known  

**Features implemented:**

- Prepend  
- Append  
- Delete  
- Size  
- Iterate (forward/backward)  
- Search  
- Clear  

---

### 4. Circular Linked List

A **Circular Linked List** connects the last node back to the **head**.  

- Can be implemented as **singly** or **doubly**  
- Commonly used in **round-robin scheduling** and **buffered systems**  

**Features implemented:**

- Prepend  
- Append  
- Delete  
- Size  
- Iterate (circular traversal)  
- Search  
- Clear  

---

## Why Linked Lists?

- **Dynamic memory allocation** – no need for contiguous memory blocks like arrays  
- **Efficient insertion/deletion** – especially in the middle of the list  
- Choice depends on **use case**:  
  - Singly → simple, memory-efficient  
  - Doubly → fast insert/delete both ends, bi-directional traversal  
  - Circular → endless looping structures, scheduling  

---

## Real-World Applications

- **Singly Linked List** → Stack, queue implementations  
- **Doubly Linked List** → Undo/redo functionality, web browser navigation  
- **Circular Linked List** → Music playlists, CPU round-robin scheduling, buffers  

---
> The File contains implementation of the above mentioned topics
