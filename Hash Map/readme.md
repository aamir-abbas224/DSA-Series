# Hashmap Implementation in Python

This repository contains a custom hashmap (hash table) implementation in Python using separate chaining with lists to handle collisions. It supports basic operations like insertion, deletion, retrieval, and iteration over keys and values.

---

## 📌 Overview

A hashmap is a data structure that maps keys to values using a hash function to determine the index in an underlying array (bucket list).  

- Average case operations: O(1) – constant time  
- Worst case operations: O(n) – linear time (all keys collide in one bucket)

---

## 🔹 Core Concepts

### 1. Buckets

- A list of lists used to store key-value pairs.  
- Each bucket handles collisions using a separate list.  

### 2. Hash Function

- Converts a key into a numerical index: _hash_function(key)  
- Uses a polynomial rolling hash formula:  
  hash_result = (hash_result * 31 + ord(char)) % capacity
- Ensures keys are evenly distributed across buckets.  

---

## 🔹 Operations Implemented

| Operation | Description | Complexity |
|-----------|-------------|------------|
| put(key, value) | Inserts or updates a key-value pair | Avg: O(1), Worst: O(n) |
| get(key) | Retrieves the value associated with a key | Avg: O(1), Worst: O(n) |
| remove(key) | Deletes a key-value pair | Avg: O(1), Worst: O(n) |
| keys() | Returns a list of all keys | O(n) |
| values() | Returns a list of all values | O(n) |
| items() | Returns a list of all key-value pairs | O(n) |
| __contains__(key) | Checks if key exists | Avg: O(1), Worst: O(n) |
| __length__() | Returns the total number of key-value pairs | O(1) |

---
