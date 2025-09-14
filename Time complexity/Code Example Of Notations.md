## 🍬 Example: Linear Search

We want to find a number in an array.

### Code (C++ / Java style):

```cpp
int linearSearch(int arr[], int n, int key) {
    for (int i = 0; i < n; i++) {
        if (arr[i] == key) {
            return i;   // Found!
        }
    }
    return -1;  // Not found
}
```

---

## 🔍 Step-by-Step Analysis

### 1. **Best Case → Big-Ω (Ω)**

👉 If the key is at the **first position** (arr\[0]).

* The loop checks only **once**.
* **Steps = 1** → **Ω(1)**

---

### 2. **Worst Case → Big-O (O)**

👉 If the key is at the **last position** OR **not present**.

* The loop checks **all n elements**.
* **Steps = n** → **O(n)**

---

### 3. **Average Case → Big-Θ (Θ)**

👉 On average, the key may be found around the **middle**.

* The loop checks about **n/2 elements**.
* But in Big-Θ we ignore constants → **Θ(n)**

---

## 🎯 Final Answer for Linear Search:

* **Best Case (Ω)** = Ω(1)
* **Worst Case (O)** = O(n)
* **Average Case (Θ)** = Θ(n)

---

## 🍕 Another Quick Example: Binary Search

### Code:

```cpp
int binarySearch(int arr[], int n, int key) {
    int low = 0, high = n-1;
    while (low <= high) {
        int mid = (low + high) / 2;
        if (arr[mid] == key) return mid;
        else if (arr[mid] < key) low = mid + 1;
        else high = mid - 1;
    }
    return -1;
}
```

* **Best Case (Ω)** → Key is exactly at mid in 1st check → Ω(1)
* **Worst Case (O)** → We keep dividing until 1 element left → O(log n)
* **Average Case (Θ)** → Generally takes log n steps → Θ(log n)

---

✨ So notations always mean:

* **O = maximum time needed**
* **Ω = minimum time needed**
* **Θ = typical/average time**

---

