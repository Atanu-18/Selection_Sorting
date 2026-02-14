# Selection Sort (Java)

A clean and beginner-friendly explanation of the **Selection Sort** algorithm implemented in Java.  
This project is meant for learning core sorting concepts and time complexity analysis.

---

## ✨ Overview

Selection Sort is a simple comparison-based sorting technique.  
It works by repeatedly selecting the largest element from the unsorted portion of the array and placing it at the end.  
The process continues until the entire array is sorted in ascending order.

---

## 🧠 How the Algorithm Works

- Divide the array into two parts:  
  - Sorted part (initially empty)  
  - Unsorted part (initially the whole array)
- In each pass:
  - Find the maximum element in the unsorted part  
  - Place it at the correct position (end of the unsorted range)
- Reduce the unsorted range by one
- Repeat until the array becomes fully sorted

---

## ⏱️ Time & Space Complexity

| Case        | Time Complexity |
|-------------|------------------|
| Best Case   | O(n²)            |
| Average     | O(n²)            |
| Worst Case  | O(n²)            |

**Space Complexity:** O(1) (In-place algorithm)

---

## ⚠️ Stability

- Selection Sort is **not a stable sorting algorithm**  
- If there are equal elements, their original order **may change** after sorting

---

## 👍 Pros & 👎 Cons

### ✅ Advantages
- Very easy to understand and implement  
- Works in-place (no extra memory needed)  
- Number of swaps is minimal compared to some other algorithms

### ❌ Disadvantages
- Inefficient for large datasets  
- Always takes O(n²) time, even if the array is already sorted  
- Not stable by default

---

## 🎯 When to Use

- Learning and practicing sorting algorithms  
- Understanding how comparison-based sorting works  
- Small datasets where performance is not critical

---

## 📚 Concepts Covered

- Array traversal  
- Selection technique  
- Swapping elements  
- Time complexity (Big O)  
- Stable vs Unstable sorting concept

---

## 🚀 Future Improvements

- Add comparison with other sorting algorithms (Bubble Sort, Insertion Sort, Merge Sort)  
- Visualize the sorting process step-by-step  
- Make a stable version of Selection Sort

---

## 🙌 Author

Made for practicing **Data Structures & Algorithms in Java**.  
Feel free to fork and improve!
