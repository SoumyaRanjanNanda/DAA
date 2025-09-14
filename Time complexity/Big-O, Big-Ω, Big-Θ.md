# 🍎 Imagine You Are Searching for a Candy 🍬 in a Jar

There are **n candies** inside a jar. One candy is special (red).

---

### 🔴 **Big-O (O)** = Worst Case

👉 *What if you are very unlucky?*

* You check from the first candy… but the red one is at the **last position**.
* You had to check **all n candies**.
* That’s **O(n)** (worst case steps).

---

### 🟢 **Big-Ω (Ω)** = Best Case

👉 *What if you are super lucky?*

* You check the first candy, and boom! it’s the red one.
* Only **1 step** needed.
* That’s **Ω(1)** (best case steps).

---

### 🟡 **Big-Θ (Θ)** = Average Case

👉 *What if luck is normal?*

* Sometimes candy is at the start, sometimes at the end, but **on average** it’s somewhere in the middle.
* You check about **n/2 candies**.
* We call that **Θ(n)** (average steps).

---

# 📌 Super Simple Summary

* **O (Big-O)** → Worst case (how slow it can get).
* **Ω (Big-Omega)** → Best case (how fast it can be).
* **Θ (Big-Theta)** → Average case (usually happens).

---

Example: **Linear Search** in an array of size n

* Best case (Ω) → 1 step (element at start)
* Worst case (O) → n steps (element at end or not present)
* Average case (Θ) → about n/2 steps
---
