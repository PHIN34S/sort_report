# 🫧 sort_report: Sorting Algorithms Visualizer

[![GitHub Repo](https://img.shields.io/badge/GitHub-Repository-blue?logo=github)](https://github.com/PHIN34S/sort_report)
[![Language](https://img.shields.io/badge/Language-Vanilla%20JS-yellow)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)

> **"Abstract logic made visible."** > `sort_report` is a lightweight, high-performance web tool designed to demystify classic computer science algorithms through real-time, interactive animations.

---

## 🕹️ Interactive Playground
Experience the algorithms directly by launching these modules:

| Algorithm | Mechanism | Key Focus |
| :--- | :--- | :--- |
| **[Bubble Sort](bubble-sort.html)** | Swapping | Adjacent comparison & "Floating" logic |
| **[Selection Sort](selection-sort.html)** | Scanning | Minimum value extraction & Index tracking |
| **[Insertion Sort](insertion-sort.html)** | Shifting | Sorted sub-list expansion & Key placement |

---

## 🧠 Core Algorithm Deep-Dive

### 1. Bubble Sort (The Optimized Approach)
Bubble Sort repeatedly steps through the list, compares adjacent elements, and swaps them if they are in the wrong order. 

* **Optimization Strategy**: Includes a `swapped` flag to terminate the process early if the array becomes sorted before the final pass.
* **Best For**: Detecting an already sorted list in $O(n)$ time.

### 2. Selection Sort (The Memory Efficient)
Selection sort finds the smallest element in the unsorted portion and swaps it into its final position.

* **Stability Note**: This is an **Unstable** sort; equal elements may jump over each other during the swap.
* **Efficiency**: It performs at most $n-1$ swaps, making it ideal when memory writes are expensive.

### 3. Insertion Sort (The Real-World Hybrid)
Insertion sort builds a final sorted array one item at a time. It is much more efficient than the others for small data sets.

* **Adaptive Nature**: It is highly efficient for data sets that are already substantially sorted.
* **Online Capability**: Can sort a list as it receives it.

---

## 📊 Performance Matrix

| Algorithm | Best | Average | Worst | Space | Stable |
| :--- | :---: | :---: | :---: | :---: | :---: |
| **Bubble** | $O(n)$ | $O(n^2)$ | $O(n^2)$ | $O(1)$ | ✅ |
| **Selection** | $O(n^2)$ | $O(n^2)$ | $O(n^2)$ | $O(1)$ | ❌ |
| **Insertion** | $O(n)$ | $O(n^2)$ | $O(n^2)$ | $O(1)$ | ✅ |

---

## 🎨 Visual Language System
To help users track the state of the data, the system uses a consistent color-coded feedback loop:

* **🔵 Neutral**: Unsorted data waiting to be processed.
* **🟡 Comparison**: Elements currently being evaluated by the pointer.
* **🔴 Action**: Elements undergoing a swap or a position shift.
* **🟢 Finality**: Elements locked in their mathematically correct position.

---

## 🛠️ Developer & User Tools
* **Speed Control**: Granular slider ranging from **100ms** (Lightning Fast) to **1900ms** (Slow-Motion Analysis).
* **Data Flexibility**: Toggle between **Randomized Arrays** or **Custom CSV Inputs** to test edge cases.
* **Code Sync**: A built-in code box highlights the specific line of pseudocode being executed in the animation.

---

## 🚀 Getting Started

1. **Clone the repo**
   ```bash
   git clone [https://github.com/PHIN34S/sort_report.git](https://github.com/PHIN34S/sort_report.git)
