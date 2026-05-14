# Algorithms — Sorting, Searching & Complexity

## 📐 Sorting Algorithms (Must Know!)

### Comparison of Sorting Algorithms

| Algorithm | Best Case | Average Case | Worst Case | Stable? | In-place? |
|-----------|-----------|--------------|------------|---------|-----------|
| **Bubble Sort** | O(n) | O(n²) | O(n²) | Yes | Yes |
| **Selection Sort** | O(n²) | O(n²) | O(n²) | No | Yes |
| **Insertion Sort** | O(n) | O(n²) | O(n²) | Yes | Yes |
| **Merge Sort** | O(n log n) | O(n log n) | O(n log n) | Yes | No |
| **Quick Sort** | O(n log n) | O(n log n) | O(n²) | No | Yes |
| **Heap Sort** | O(n log n) | O(n log n) | O(n log n) | No | Yes |
| **Counting Sort** | O(n+k) | O(n+k) | O(n+k) | Yes | No |

**Stable sort** = equal elements maintain their original relative order
**In-place** = sorts without needing extra memory (O(1) extra space)

---

## 📐 Bubble Sort — How It Works

**Idea:** Compare adjacent elements, swap if wrong order. Repeat.

**Example:** Sort [64, 34, 25, 12, 22]

**Pass 1:**
- Compare 64,34 → swap → [34, 64, 25, 12, 22]
- Compare 64,25 → swap → [34, 25, 64, 12, 22]
- Compare 64,12 → swap → [34, 25, 12, 64, 22]
- Compare 64,22 → swap → [34, 25, 12, 22, **64**] ← largest settled

**After n−1 passes, array is sorted.**

---

## 📐 Selection Sort — How It Works

**Idea:** Find minimum element, place it at front. Repeat.

**Example:** Sort [64, 25, 12, 22, 11]

- Pass 1: Min = 11. Swap with first → [**11**, 25, 12, 22, 64]
- Pass 2: Min of rest = 12. Swap → [11, **12**, 25, 22, 64]
- Pass 3: Min = 22. Swap → [11, 12, **22**, 25, 64]
- Sorted!

---

## 📐 Insertion Sort — How It Works

**Idea:** Build sorted part one element at a time (like sorting playing cards).

**Example:** Sort [5, 2, 4, 6, 1]
- [5] | 2 → insert 2 before 5 → [2, 5]
- [2,5] | 4 → insert 4 → [2, 4, 5]
- [2,4,5] | 6 → stays → [2, 4, 5, 6]
- [2,4,5,6] | 1 → insert 1 at start → [1, 2, 4, 5, 6] ✅

---

## 📐 Merge Sort — How It Works

**Idea:** Divide array in half, sort each half, then merge.

**Divide:** [38, 27, 43, 3, 9, 82, 10]
→ [38, 27, 43] | [3, 9, 82, 10]
→ [38] [27,43] | [3,9] [82,10]
→ [38] [27] [43] | [3] [9] [82] [10]

**Merge back (sorted):**
→ [27,38,43] | [3,9,10,82]
→ **[3, 9, 10, 27, 38, 43, 82]** ✅

---

## 📐 Searching Algorithms

### Linear Search
- Check each element one by one
- Time: **O(n)** — worst case is n comparisons
- Works on **unsorted** arrays

### Binary Search
- Only works on **sorted** arrays
- Compare with middle element, eliminate half
- Time: **O(log n)**

**Example:** Find 23 in [1, 5, 10, 15, 23, 30, 40]

```
Low=0, High=6, Mid=3 → arr[3]=15 < 23 → search right
Low=4, High=6, Mid=5 → arr[5]=30 > 23 → search left
Low=4, High=4, Mid=4 → arr[4]=23 = 23 FOUND!
```

---

## 📐 Algorithm Complexity

### Big-O Notation — measures how time grows with input size n

| O(1) | Array access: `arr[5]` |
|------|----------------------|
| O(log n) | Binary search |
| O(n) | Linear search |
| O(n log n) | Merge sort, Heap sort |
| O(n²) | Bubble, Selection, Insertion sort |
| O(2ⁿ) | Power set generation |

### Space Complexity:
| Algorithm | Space |
|-----------|-------|
| Merge Sort | O(n) — needs extra array |
| Quick Sort | O(log n) — recursion stack |
| Bubble/Insertion/Selection | O(1) — in-place |

---

## ⚡ Key Points to Remember

1. **Merge Sort** — best for large data, guaranteed O(n log n)
2. **Quick Sort** — fastest in practice, but O(n²) worst case
3. **Insertion Sort** — best for nearly sorted data (O(n) best case)
4. **Bubble Sort** — simplest but slowest; good for teaching only
5. **Binary Search** — MUST be sorted; O(log n)

---

## 📝 Practice Problems

1. What is the worst-case time complexity of Quick Sort?
   (A) O(n)  (B) O(n log n)  (C) O(n²)  (D) O(log n)

2. Which sorting algorithm has guaranteed O(n log n) in ALL cases?
   (A) Quick Sort  (B) Bubble Sort  (C) Merge Sort  (D) Insertion Sort

3. Binary search requires the array to be:
   (A) Sorted  (B) Unsorted  (C) Reversed  (D) Linked

4. How many comparisons does binary search need for n=128?
   (A) 128  (B) 64  (C) 7  (D) 8

5. Which sort is best for nearly-sorted data?
   (A) Merge Sort  (B) Quick Sort  (C) Insertion Sort  (D) Heap Sort

6. What is the space complexity of Merge Sort?
   (A) O(1)  (B) O(n)  (C) O(n²)  (D) O(log n)

7. Selection sort's time complexity in all cases is:
   (A) O(n)  (B) O(n log n)  (C) O(n²)  (D) O(1)

8. In bubble sort, after k passes, how many elements are in their final position?
   (A) k  (B) k-1  (C) 2k  (D) n-k

---


> 📖 **[See detailed step-by-step solutions →](./04-Algorithms-Answers.md)**

---

## 📅 Previous Year Appearance (PGCET)

- **2025:** ❌ Not appeared
- **2024:** ❌ Not appeared
- **2023:** ❌ Not appeared

> Links open the exact question in the respective year's paper for cross-reference.
