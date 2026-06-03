# 🏥 Smart Hospital Management System

A Smart Hospital Management System modeled as a **Weighted Directed Graph** to simulate hospital workflow management between multiple departments.

This project demonstrates the practical application of:

- DFS Cycle Detection
- DFS-Based Topological Sort
- Huffman Coding
- Graph Theory
- Adjacency List Representation
- Greedy Algorithms

The system contains 8 hospital departments and 17 weighted directed connections representing workflow dependencies.

---

## 📄 Project Report

<div align="center">

### 📘 Detailed Project Documentation

<a href="./Smart Hospital Management System Using Graph Algorithms and Huffman Coding.pdf>
    <img src="https://img.shields.io/badge/📄-View%20Full%20Report-red?style=for-the-badge">
</a>

</div>

---

## 🎯 Project Objectives

- Detect workflow deadlocks using DFS Cycle Detection
- Generate a valid task execution order using Topological Sort
- Create an operational log from traversal results
- Compress operational logs using Huffman Coding
- Analyze algorithm correctness and efficiency

---

## 🏥 Hospital Departments

| Node | Department |
|------|------------|
| A | Emergency & Trauma |
| B | Radiology & Imaging |
| C | Pathology / Laboratory |
| D | Cardiology |
| E | Pharmacy |
| F | ICU / Critical Care |
| G | Surgery & Operation Theatre |
| H | Administration & Records |

---

## 🔗 Graph Information

| Property | Value |
|-----------|---------|
| Graph Type | Weighted Directed Graph |
| Nodes | 8 |
| Edges | 17 |
| Structure | Directed Acyclic Graph (DAG) |

---

## 🧠 Algorithms Implemented

### 1️⃣ DFS Cycle Detection

Detects circular dependencies and workflow deadlocks.

**Time Complexity:** O(V + E)

### 2️⃣ DFS Topological Sort

Generates a valid execution sequence for hospital operations.

**Topological Order**

```text
A → B → C → E → D → F → G → H
```

### 3️⃣ Huffman Coding

Compresses operational logs using an optimal prefix-free encoding scheme.

**Operational Log**

```text
ABCEDFGH
```

**Encoded Bitstream**

```text
000001010011100101110111
```

---

## 📊 Results

### Cycle Detection

✅ No cycle found

✅ Deadlock-free workflow

### Topological Sort

✅ Valid execution order generated

### Huffman Compression

| Metric | Value |
|---------|---------|
| Original Size | 64 bits |
| Compressed Size | 24 bits |
| Compression Ratio | 62.5% |
| Data Saved | 40 bits |

---

## 📂 Repository Structure

```text
smart-hospital-management-system/
│
├── README.md
├── emon_sir_assignment.pdf
├── graph-diagram.png
├── topological-order.png
├── huffman-tree.png
└── source-code/
```

---

## 🚀 Project Highlights

- Weighted Directed Graph Modeling
- DFS-Based Cycle Detection
- Topological Sorting
- Huffman Compression
- Complexity Analysis
- Real-World Healthcare Workflow Simulation
- Deadlock Prevention Mechanism
- Efficient Data Compression

---

## ⚙️ Technologies & Concepts

- Algorithms
- Data Structures
- Graph Theory
- Depth First Search (DFS)
- Topological Sorting
- Huffman Coding
- Greedy Algorithms
- Adjacency Lists
- Complexity Analysis

---

## 📈 Complexity Analysis

| Algorithm | Time Complexity | Space Complexity |
|------------|----------------|------------------|
| DFS Cycle Detection | O(V + E) | O(V) |
| DFS Topological Sort | O(V + E) | O(V) |
| Huffman Encoding | O(n log n) | O(n) |
| Huffman Decoding | O(n × depth) | O(n) |

---

## 🎓 Learning Outcomes

This project demonstrates how graph algorithms and data compression techniques can be applied to real-world healthcare workflow systems for dependency management, scheduling, deadlock prevention, and efficient operational log storage.

---

## 👨‍💻 Author

**Ifty Anwar**

Computer Science & Engineering Student  
Web Developer | Problem Solver | Technology Enthusiast

---

## 📜 License

This project is created for academic and educational purposes.
