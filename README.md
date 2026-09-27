# 🚀 DSA Mastery

A structured and comprehensive repository for mastering **Data Structures & Algorithms**. This repository tracks solutions, algorithmic patterns, intuition breakdowns, and complexity analyses across platforms like **LeetCode** and **Striver's A2Z DSA Sheet**.

---

## 📌 Problem Documentation Standard

Every problem directory within this repository **must** include a `README.md` following this exact template:

```markdown
# [Problem Title]

* **Difficulty:** Easy / Medium / Hard
* **Platform:** LeetCode / Striver A2Z Sheet
* **Pattern:** [e.g., Two Pointers, Sliding Window, DP on Grids]

## 1. Problem Statement
Brief summary of the core objective and constraints.

## 2. Approach & Intuition
* **Brute Force:** Explain the naive approach and why it fails constraints.
* **Optimized Approach:** Explain the transition to the optimal pattern.

## 3. Complexity Analysis
* **Time Complexity:** O(...) - Detailed explanation of operations.
* **Space Complexity:** O(...) - Auxiliary memory and call stack analysis.

## 4. Code Implementation
[Link to code file or embedded clean code snippet]
```

---

## 🗂️ Repository Structure

Problems are organized by algorithmic pattern or topic category:

```text
dsa-mastery/
├── 01-Arrays-and-Hashing/
│   └── Two-Sum/
│       ├── README.md              # Detailed documentation using the standard template
│       └── solution.py            # Clean, documented code implementation
├── 02-Two-Pointers/
│   └── 3Sum/
│       ├── README.md
│       └── solution.py
├── 03-Sliding-Window/
├── 04-Stack-and-Queue/
├── 05-Binary-Search/
├── 06-Linked-List/
├── 07-Trees-and-Graphs/
├── 08-Dynamic-Programming/
└── README.md                      # Root repository guidelines
```

---

## 📊 Topic & Pattern Roadmap

| # | Topic / Pattern | Status | Key Problems Covered |
|---|-----------------|:------:|----------------------|
| 01 | **Arrays & Hashing** | 🟡 In Progress | Two Sum, Contains Duplicate, Group Anagrams |
| 02 | **Two Pointers** | ⚪ Planned | Valid Palindrome, Two Sum II, 3Sum, Container With Most Water |
| 03 | **Sliding Window** | ⚪ Planned | Best Time to Buy/Sell Stock, Longest Substring Without Repeating |
| 04 | **Stack & Queue** | ⚪ Planned | Valid Parentheses, Min Stack, Daily Temperatures |
| 05 | **Binary Search** | ⚪ Planned | Binary Search, Search in Rotated Sorted Array |
| 06 | **Linked List** | ⚪ Planned | Reverse Linked List, Merge Two Sorted Lists |
| 07 | **Trees & Graphs** | ⚪ Planned | Invert Tree, Maximum Depth, Level Order Traversal |
| 08 | **Dynamic Programming** | ⚪ Planned | Climbing Stairs, Coin Change, Longest Increasing Subsequence |

---

## 🌿 Git & Pull Request (PR) Workflow

To add a new problem or improvement, follow these steps:

### 1. Create a Topic Branch
```bash
git checkout -b <topic>/<problem-name>
# Example: git checkout -b arrays/two-sum
```

### 2. Implement and Document
- Create the problem directory under its topic.
- Add `solution.py` (or `.cpp` / `.java`).
- Add `README.md` following the template above.

### 3. Stage & Commit
```bash
git add .
git commit -m "feat(arrays): add Two Sum solution and documentation"
```

### 4. Push & Open PR
```bash
git push -u origin <topic>/<problem-name>
```
Visit GitHub and click **Compare & pull request** to submit your work.
