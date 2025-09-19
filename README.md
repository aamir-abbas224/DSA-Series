# DSA-Series
A repository of Data Structures and Algorithms (DSA) concepts implemented in Python.  
This repo serves as a learning and reference resource, covering **definitions, explanations**, and eventually **implementations** of basic to advanced algorithms.

## **Definitions** & **Explanations**:

i. **Data Structures**: They can be defined as a way of formating, storing or structuring data or information effectively and efficiently.

ii. **Algorithms**: An algorithm is a finite sequence of precise instructions for performing a computation or for
solving a problem.
  - **PROPERTIES OF ALGORITHMS**:
  - **Input**. An algorithm has input values from a specified set.
  -  **Output**. From each set of input values an algorithm produces output values from a specified
     set. The output values are the solution to the problem.
  - **Definiteness**. The steps of an algorithm must be defined precisely.
  - **Correctness**. An algorithm should produce the correct output values for each set of input
    values.
  - **Finiteness**. An algorithm should produce the desired output after a finite (but perhaps
    large) number of steps for any input in the set.
  - **Effectiveness**. It must be possible to perform each step of an algorithm exactly and in a
    finite amount of time.
  - **Generality**. The procedure should be applicable for all problems of the desired form, not
    just for a particular set of input values.
    
iii.**Algorithms Design Paradigm**

  i. Divide and Conquer : It involves breaking problems into smaller sub-problems then combining the results to obtain a global solution.
  ii. Greedy Algorithms : It involves optimization and combinatorial problems.
  iii. Dynamic Programming : It is useful when sub-problems overlap.Rather than breaking our problem into independent sub-problems,
                             with dynamic approach, intermediate results are cached and can be used in subsequent operations. 

iv.**Recursion**: It is a method of solving problems where a function calls itself directly or indirectly to break the problem into smaller subproblems until reaching its base case.
                  i.**Base Case**: It is the condition that stops the recursion.
                  ii.**Recursive Case**: It is the part where the function calls itself with simpler input.
                  **Note** :If the memory stack reaches its full capacity, **StackOverflow** error will be indicated.

v.**Backtracking**: It is a form of recursion that is useful where we are presented with a number of options at each node from which we must choose one.
                    Backtracking is a divide and conquer method for exhaustive search. Backtracking prunes branches that cannot give results. 

vi.**Asymptotic analysis**: There are essentially three things that characterize an algorithm's runtime performance.
They are:
        Worst case - Use an input that gives the slowest performance
        Best case - Use an input that give, the best results
        Average case - Assumes the input is random
                    
iv.**Growth Function**
  - **Big-O Notation**

    <img width="936" height="214" alt="_Big O" src="https://github.com/user-attachments/assets/0e20753b-e89b-4e39-8ffa-088655cc3f14" />

    
  - **Big-Omega Notation**

    <img width="931" height="206" alt="_Big Omega" src="https://github.com/user-attachments/assets/78ad71e8-834c-486e-9b57-f436fa0a9659" />

    
  - **Big Theta Notation**

    <img width="742" height="111" alt="_Big Theta" src="https://github.com/user-attachments/assets/2b8499b1-55a7-4da4-bb44-d1ad54877aeb" />

**Time Complexity**:

<img width="1225" height="482" alt="_time complexity" src="https://github.com/user-attachments/assets/3c859e39-0827-43ed-a524-11d43e459d9c" />

## Purpose

This repository is designed to document my DSA journey.  
It will include:
- Core DSA concepts and definitions
- Python implementations (to be added gradually)

The goal is to consolidate learning, track progress, and provide a reference for both myself and others.

## Algorithms and Data Stuctures Covered

- **Merge Sort** – It is a recursive algorithm that uses the divide and conquer approach. It involves breaking problems into sub-problems and then combining the result.
                    The merge sort algorithm consists of three simple steps:
                          1. Recursively sort the left half of the input array.
                          2. Recursively sort the right half of the input array.
                          3. Merge two sorted sub arrays into one.

  - **Arrays** : An array is a sequential list of data. Being sequential means that each element is stored right after the previous one in memory.
                 Arrays are faster since each element follows from previous one in memory.

  - **Pointer Structures**: They are lists of items that can be spread out in memeory.This is because each item contains one or more links to other items in the structure.
                            The benefits with pointer structures is that they dont require sequential storage space and secondly they can start small and can grow arbitrarily as you add more nodes to the structure.

  - **Node**: A node is a container of data,together with one or more links to other nodes. A link is a pointer. A simple type of node is one that only has a link to the next node.

  - **Singly Linked List**: A singly linked list is list with only one pointer between two successive nodes. It can only be traversed in a single direction that is from the first node to the last.
                            -Funtionality included : Prepend, Appending , Deleting , Size , Iterating, Search and Clear methods

  -**Doubly Linked List**: A Doubly Linked List is similar to the Sinly Linked List which uses same fundamentals. A node in doubly linked list has two pointerrs - a pointer to the next node and a pointer to the previous node.
                           Since it has a reference to previous data/node it can be traversed in any direction , deletion operation are much easier to perfrom.
                           -Funtionality included : Prepend, Appending , Deleting , Size , Iterating, Search and Clear methods

  - **Circular Linked List**: It is a type of list where the endpoits are connected. That is the last node points to the head of the list. They can be based on both Singly or Doubly.
                              -Funtionality included : Prepend, Appending , Deleting , Size , Iterating, Search and Clear methods

  - **Stacks**: A stack is a linear data structure that follows LIFO(Last in First Out).the two primary operation that are done on stacks are 'push' & 'pop' and another operation used sometimes is 'peek'.

  - **Queues**:   
      
  




> Each concept will eventually include **Python code implementations** with example problems and complexity analysis.

## Progress Tracker

- [✅] Arrays
- [ ] Strings 
- [ ] Linked Lists  
- [ ] Stacks & Queues  
- [ ] Trees  
- [ ] Graphs  
- [ ] Dynamic Programming  
- [ ] Greedy Algorithms  
- [ ] Sorting & Searching  
- [✅] Recursion & Backtracking

> ✅ Checkboxes indicate concepts with explanations added.  
> 📝 Future updates will include code implementations and examples.
