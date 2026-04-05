# sort_report

## 📚 Sorting Algorithms Visualization System
**Repository:** [https://github.com/PHIN34S/sort_report](https://github.com/PHIN34S/sort_report)

An integrated, interactive web-based tool featuring classic sorting algorithms. This project aims to help students and developers visualize algorithmic logic, step-by-step execution, and complexity characteristics through high-fidelity animations and real-time pseudocode tracking.

---

## 🔗 Project Navigation
Access the interactive modules directly through these files:

* **[Bubble Sort](bubble-sort.html)**: Adjacent swapping logic where larger values "bubble" to the top.
* **[Selection Sort](selection-sort.html)**: Systematic scanning to find minimum values and place them in order.
* **[Insertion Sort](insertion-sort.html)**: Building a sorted sub-list one element at a time, similar to sorting playing cards.

---

## 🧪 Algorithm Principles & Details

### 1. Bubble Sort
The algorithm repeatedly steps through the list, compares adjacent elements, and swaps them if they are in the wrong order. 

* **Key Feature**: Includes an optimization where the process terminates early if a full pass occurs without any swaps.
* **Time Complexity**: Best $O(n)$, Average $O(n^2)$, Worst $O(n^2)$.
* **Stability**: **Stable ✓**

### 2. Selection Sort
Selection sort divides the input list into two parts: a sorted sub-list of items built up from left to right and a remaining unsorted sub-list. It finds the smallest element in the unsorted sub-list and swaps it with the leftmost unsorted element.

* **Key Feature**: Minimizes the number of swaps ($n-1$ max), making it useful when memory write-cycles are costly.
* **Time Complexity**: $O(n^2)$ for all cases.
* **Stability**: **Unstable ✗**

### 3. Insertion Sort
Insertion sort iterates through an input list and removes one element per iteration, finding the place it belongs in the sorted list and inserting it there.

* **Key Feature**: Highly efficient for small data sets and "nearly sorted" arrays.
* **Time Complexity**: Best $O(n)$, Average $O(n^2)$, Worst $O(n^2)$.
* **Stability**: **Stable ✓**

---

## 📊 Complexity Comparison Table

| Algorithm | Best Time | Average Time | Worst Time | Space | Stable |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **Bubble Sort** | $O(n)$ | $O(n^2)$ | $O(n^2)$ | $O(1)$ | Yes |
| **Selection Sort** | $O(n^2)$ | $O(n^2)$ | $O(n^2)$ | $O(1)$ | No |
| **Insertion Sort** | $O(n)$ | $O(n^2)$ | $O(n^2)$ | $O(1)$ | Yes |

---

## 🛠️ Technical Implementation

### Visualization Design
* **Tech Stack**: HTML5, CSS3 (Flexbox for responsive charts), and Vanilla JavaScript.
* **Color System**:
    * 🔵 **Blue**: Unsorted elements.
    * 🟡 **Yellow**: Currently being compared.
    * 🔴 **Red**: Currently swapping/moving.
    * 🟢 **Green**: Sorted and locked in position.

### Interactive Features
* **Playback Control**: Auto-Play, Pause, and Step-by-Step execution.
* **Custom Data**: Manual input (comma-separated) or Random Generation.
* **Dynamic Parameters**: Adjustable animation speed (100ms - 1900ms) and array size (3 - 15 elements).

---

## 🚀 How to Run Locally

1.  **Clone the repository:**
    ```bash
    git clone
