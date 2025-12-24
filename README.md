# 🔁 push_swap — Sorting with Two Stacks

A fast and optimized algorithmic sorting project using only two stacks and a limited set of operations. The goal is to sort numbers using the fewest possible moves, focusing on complexity, algorithm design, and optimization.

---

## 🎯 Objective
Sort a list of integers using:
```bash
sa sb ss
pa pb
ra rb rr
rra rrb rrr
```

---

## 🧠 Concepts & Skills Learned
- Complexity & Time Optimization (O(n log n), O(n²))
- Chunking strategies / Greedy approaches (Turk algorithm)
- Stack manipulation & linked list data structures
- Command-based algorithm execution
- Input validation & error handling

---

## 🛠 Tech Stack
| Language | Build |
|----------|--------|
| C        | Makefile |

---

## 📦 Usage
```sh
git clone https://github.com/Jnba23/push_swap.git
cd push_swap
make
```
### Usage example :
  Run:
```bash
./push_swap "3 2 1"
```
  To test the checker run:
```bash
ARG="4 67 3 87 23"; ./push_swap $ARG | ./checker_Mac $ARG
```
