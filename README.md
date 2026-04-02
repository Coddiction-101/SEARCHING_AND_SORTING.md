# 🔍 Searching & Sorting (Core Fundamentals)

This section covers all important **searching and sorting techniques** used in DSA along with their applications and practice problems.

---

# 🔎 Searching Techniques

### 🟥 Linear Search
<details>
<summary>Concept + Problems</summary>

### 📌 Concept
- Traverse the array one by one
- Compare each element

### ⏱ Complexity
- Time: O(n)
- Space: O(1)

### 💡 Use Case
- Small datasets
- Unsorted arrays

### 🧪 Problems
- Find element in array
- First Occurrence of Element
- Count occurrences

</details>

---

## 🟥 Binary Search ⭐
<details>
<summary>Concept + Problems</summary>

### 📌 Concept
- Works on **sorted arrays**
- Divide and conquer

### ⏱ Complexity
- Time: O(log n)

### 🧠 Key Idea
- Mid = (low + high) / 2

### 🔥 Problems
- Binary Search
- Search Insert Position
- First Bad Version
- Find First and Last Position ⭐
- Search in Rotated Sorted Array ⭐⭐
- Find Peak Element

</details>

---

# 🔃 Sorting Techniques

## 🟨 Bubble Sort
<details>
<summary>Concept + Problems</summary>

### 📌 Concept
- Repeatedly swap adjacent elements

### ⏱ Complexity
- O(n²)

### 🧪 Problems
- Basic sorting practice

</details>

---

## 🔹 Selection Sort
<details>
<summary>Concept + Problems</summary>

### 📌 Concept
- Select minimum and swap

### ⏱ Complexity
- O(n²)

</details>

---

## 🔹 Insertion Sort
<details>
<summary>Concept + Problems</summary>

### 📌 Concept
- Insert element in correct position

### ⏱ Complexity
- O(n²)

</details>

---

## 🔹 Merge Sort ⭐
<details>
<summary>Concept + Problems</summary>

### 📌 Concept
- Divide and merge

### ⏱ Complexity
- O(n log n)

### 🧪 Problems
- Merge Sort Implementation
- Count Inversions ⭐

</details>

---

## 🔹 Quick Sort ⭐⭐
<details>
<summary>Concept + Problems</summary>

### 📌 Concept
- Pivot-based partitioning

### ⏱ Complexity
- Avg: O(n log n)
- Worst: O(n²)

</details>

---

## 🔹 Built-in Sorting (Important 🔥)
<details>
<summary>Usage</summary>

### C++:
```cpp
sort(arr.begin(), arr.end());
