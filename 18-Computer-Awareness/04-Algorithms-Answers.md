# Algorithms — Practice Problem Solutions

---

### Q1

**❓ Question:** What is the worst-case time complexity of Quick Sort?
(A) O(n)  (B) O(n log n)  (C) O(n²)  (D) O(log n)

**🤔 What I understood:** This is asking me to identify Quick Sort's time complexity in the worst-case scenario.

**💡 What I'll use:** My knowledge of Quick Sort's behavior and its pivot selection problem from this chapter.

**✏️ My Thought Process:**
- Option A — O(n): **Wrong** — O(n) would mean sorting in linear time, which is impossible for a comparison-based sort in general.
- Option B — O(n log n): **Wrong** — O(n log n) is Quick Sort's **average case** (and best case), not worst case.
- Option C — O(n²): **Correct** — Worst case occurs when the pivot is always the smallest or largest element (e.g., already sorted array with first-element pivot). Each partition splits into 1 and n-1, giving n recursive calls each doing O(n) work → O(n²).
- Option D — O(log n): **Wrong** — O(log n) is the space used by the call stack in the best case, not the time complexity.

**✅ Answer: (C) O(n²)**

---

### Q2

**❓ Question:** Which sorting algorithm has guaranteed O(n log n) in ALL cases?
(A) Quick Sort  (B) Bubble Sort  (C) Merge Sort  (D) Insertion Sort

**🤔 What I understood:** This is asking me to identify which sort maintains O(n log n) for best, average, AND worst cases.

**💡 What I'll use:** My knowledge of sorting algorithm complexity guarantees from this chapter.

**✏️ My Thought Process:**
- Option A — Quick Sort: **Wrong** — Quick Sort is O(n log n) on average but degrades to O(n²) in the worst case.
- Option B — Bubble Sort: **Wrong** — Bubble Sort is O(n²) in average and worst case; only O(n) in best case (already sorted).
- Option C — Merge Sort: **Correct** — Merge Sort always divides the array into exactly two halves and merges them. This guarantees O(n log n) in all cases — best, average, and worst — because the division and merge steps are deterministic.
- Option D — Insertion Sort: **Wrong** — Insertion Sort is O(n²) in average and worst case; only O(n) for nearly-sorted data.

**✅ Answer: (C) Merge Sort**

---

### Q3

**❓ Question:** Binary search requires the array to be:
(A) Sorted  (B) Unsorted  (C) Reversed  (D) Linked

**🤔 What I understood:** This is asking me to identify the mandatory precondition for binary search to work.

**💡 What I'll use:** My knowledge of binary search prerequisites from this chapter.

**✏️ My Thought Process:**
- Option A — Sorted: **Correct** — Binary search works by comparing the target to the middle element and eliminating half the array. This only works if the array is sorted — otherwise you can't determine which half to discard.
- Option B — Unsorted: **Wrong** — Binary search on an unsorted array would give incorrect results since the halving logic assumes order.
- Option C — Reversed: **Wrong** — A reversed (descending) array is sorted, just in reverse order. You could use a modified binary search, but the standard requirement is "sorted" (ascending).
- Option D — Linked: **Wrong** — Binary search actually performs poorly on linked lists because you can't do O(1) middle-element access. Arrays support random access which is essential.

**✅ Answer: (A) Sorted**

---

### Q4

**❓ Question:** How many comparisons does binary search need for n=128?
(A) 128  (B) 64  (C) 7  (D) 8

**🤔 What I understood:** This is asking me to calculate the maximum number of comparisons in binary search for a 128-element array.

**💡 What I'll use:** Binary search comparison count = log₂(n)

**✏️ My Thought Process:**
- Option A — 128: **Wrong** — That's linear search (O(n)), not binary search.
- Option B — 64: **Wrong** — 64 = n/2 = one step into binary search, not the total count.
- Option C — 7: **Correct** — log₂(128) = log₂(2⁷) = **7**. Binary search halves the search space each time: 128 → 64 → 32 → 16 → 8 → 4 → 2 → 1. That's 7 steps.
- Option D — 8: **Wrong** — 2⁸ = 256, so 8 comparisons would handle up to 256 elements, not 128.

**✅ Answer: (C) 7**

---

### Q5

**❓ Question:** Which sort is best for nearly-sorted data?
(A) Merge Sort  (B) Quick Sort  (C) Insertion Sort  (D) Heap Sort

**🤔 What I understood:** This is asking me to identify which sorting algorithm is most efficient when input data is already almost in order.

**💡 What I'll use:** My knowledge of adaptive sorting algorithms from this chapter.

**✏️ My Thought Process:**
- Option A — Merge Sort: **Wrong** — Merge Sort always does O(n log n) work regardless of input order; it doesn't take advantage of existing sortedness.
- Option B — Quick Sort: **Wrong** — Quick Sort can actually perform worse on nearly-sorted data depending on pivot selection (may approach O(n²)).
- Option C — Insertion Sort: **Correct** — Insertion Sort is **adaptive**. For nearly-sorted data, most elements are already in place, so very few shifts are needed. Best case is O(n) — it only does one comparison per element when data is already sorted.
- Option D — Heap Sort: **Wrong** — Heap Sort is always O(n log n) and doesn't benefit from pre-sorted input.

**✅ Answer: (C) Insertion Sort**

---

### Q6

**❓ Question:** What is the space complexity of Merge Sort?
(A) O(1)  (B) O(n)  (C) O(n²)  (D) O(log n)

**🤔 What I understood:** This is asking me about the extra memory Merge Sort needs beyond the input array.

**💡 What I'll use:** My knowledge of Merge Sort's implementation and its temporary array requirement from this chapter.

**✏️ My Thought Process:**
- Option A — O(1): **Wrong** — O(1) (in-place) algorithms don't need extra memory. Merge Sort requires a temporary array for merging, so it's not O(1).
- Option B — O(n): **Correct** — Merge Sort needs an auxiliary array of size n to merge the two halves. This is the dominant space cost, making it O(n) space complexity.
- Option C — O(n²): **Wrong** — O(n²) space would be extremely wasteful; no standard sort requires this much extra space.
- Option D — O(log n): **Wrong** — O(log n) is the space for the recursive call stack (depth of recursion), but the auxiliary merge array (O(n)) dominates, so overall space is O(n).

**✅ Answer: (B) O(n)**

---

### Q7

**❓ Question:** Selection sort's time complexity in all cases is:
(A) O(n)  (B) O(n log n)  (C) O(n²)  (D) O(1)

**🤔 What I understood:** This is asking me about Selection Sort's time complexity — and notably that it's the same for all cases.

**💡 What I'll use:** My knowledge of Selection Sort's mechanism from this chapter.

**✏️ My Thought Process:**
- Option A — O(n): **Wrong** — Selection Sort always scans the remaining unsorted portion to find the minimum, never achieving linear time.
- Option B — O(n log n): **Wrong** — Selection Sort does not use divide-and-conquer or any logarithmic structure.
- Option C — O(n²): **Correct** — Selection Sort always performs n + (n-1) + (n-2) + ... + 1 = n(n-1)/2 comparisons regardless of input order. Even for a sorted array, it still scans all elements to "confirm" the minimum. So best = average = worst = **O(n²)**.
- Option D — O(1): **Wrong** — O(1) would mean no work at all, which is impossible for sorting.

**✅ Answer: (C) O(n²)**

---

### Q8

**❓ Question:** In bubble sort, after k passes, how many elements are in their final position?
(A) k  (B) k-1  (C) 2k  (D) n-k

**🤔 What I understood:** This is asking me about the effect of k passes in Bubble Sort — specifically how many elements are guaranteed to be sorted.

**💡 What I'll use:** My knowledge of Bubble Sort's behavior — largest elements "bubble" to the end.

**✏️ My Thought Process:**
- Option A — k: **Correct** — After each pass, the largest unsorted element bubbles to its correct position at the end. After pass 1: 1 element in place. After pass 2: 2 elements in place. After k passes: **k elements** are in their final sorted positions (at the right end of the array).
- Option B — k-1: **Wrong** — k-1 would mean pass 1 places 0 elements, which is wrong — each pass always places at least one element.
- Option C — 2k: **Wrong** — Elements don't get placed in pairs per pass in standard bubble sort.
- Option D — n-k: **Wrong** — n-k would mean the remaining unsorted portion, not the sorted portion.

**✅ Answer: (A) k**

---

[← Back to Practice Problems](./04-Algorithms.md)
