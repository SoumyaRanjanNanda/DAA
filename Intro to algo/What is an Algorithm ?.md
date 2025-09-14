# 📌 **Step 1: What is an Algorithm?**

👉 An **Algorithm** is a **finite set of steps** that solves a problem.
It’s like a recipe in cooking—clear instructions that lead to the final dish.

### Example:

Problem → Find the largest of 3 numbers.

Algorithm (step by step):

1. Take three numbers `a, b, c`.
2. Compare `a` with `b`.
3. If `a > b`, then compare `a` with `c`.

   * If `a > c`, largest = `a`
   * Else, largest = `c`
4. Else compare `b` with `c`.

   * If `b > c`, largest = `b`
   * Else, largest = `c`.
5. Print the largest number.

👉 That’s an algorithm.

---

# 📌 **Step 2: Difference between Algorithm & Program**

* **Algorithm** → Language independent (just steps).
* **Program** → Implementation of algorithm in a programming language (like C++, Java, Python).

Example (same problem in Python):

```python
a, b, c = 10, 25, 15

if a > b and a > c:
    print("Largest:", a)
elif b > c:
    print("Largest:", b)
else:
    print("Largest:", c)
```

---

# 📌 **Step 3: Why Analyze Algorithms?**

* Suppose you have **two algorithms** for the same problem. Which one is better?
* To decide, we measure:

  1. **Time Complexity** → How fast it runs (execution time).
  2. **Space Complexity** → How much memory it needs.

Example:

* Linear Search → O(n)
* Binary Search → O(log n) (much faster for large n).

---
