# SEARCHING & SORTING PLAYBOOK

Core searching and sorting techniques with concepts, complexity, and key problems.

---

## SEARCHING

<details>
<summary>Linear Search</summary>

Concept  
- Traverse elements one by one  
- Compare each value  

Complexity  
- Time: O(n)  
- Space: O(1)  

Use Case  
- Small or unsorted data  

Problems  
- Find element in array  
- First occurrence  
- Count occurrences  

</details>

---

<details>
<summary>Binary Search</summary>

Concept  
- Works on sorted arrays  
- Divide search space into halves  

Key Idea  
- mid = low + (high - low) / 2  

Complexity  
- Time: O(log n)  

Problems  
- Binary Search  
- Search Insert Position  
- First Bad Version  
- First and Last Position  
- Search in Rotated Sorted Array  
- Find Peak Element  

</details>

---

## SORTING

<details>
<summary>Bubble Sort</summary>

Concept  
- Swap adjacent elements repeatedly  

Complexity  
- Time: O(n²)  

Use Case  
- Learning / small datasets  

</details>

---

<details>
<summary>Selection Sort</summary>

Concept  
- Select minimum and place correctly  

Complexity  
- Time: O(n²)  

</details>

---

<details>
<summary>Insertion Sort</summary>

Concept  
- Insert element into sorted portion  

Complexity  
- Time: O(n²)  

Use Case  
- Nearly sorted arrays  

</details>

---

<details>
<summary>Merge Sort</summary>

Concept  
- Divide and merge  

Complexity  
- Time: O(n log n)  
- Space: O(n)  

Problems  
- Merge Sort  
- Count Inversions  

</details>

---

<details>
<summary>Quick Sort</summary>

Concept  
- Pivot-based partitioning  

Complexity  
- Avg: O(n log n)  
- Worst: O(n²)  

Key Learning  
- Partition logic  

</details>

---

<details>
<summary>Built-in Sorting</summary>

C++  
```cpp
sort(arr.begin(), arr.end());
