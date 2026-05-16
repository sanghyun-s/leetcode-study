# 📚 LeetCode Study Log — 2026

**Goal:** Build pattern recognition through systematic practice  
**Study Pace:** 3-7 problems/day  
**Mentor Review:** Weekly  
**Focus:** Python3 only

---

## 📊 Progress Dashboard

| Week | Easy | Medium | Hard | Topic | Status |
|------|------|--------|------|-------|--------|
| W1 | 13 | 7 | 0 | Arrays, Sort, Hashing & DFS | ✅ Complete |
| W2 | 0 | 0 | 0 | Sliding Window & Stack | ⬜ Upcoming |
| W3 | — | — | — | Linked Lists | ⬜ Upcoming |

---

## 🔢 Total Solved

- 🟢 Easy: 13
- 🟡 Medium: 7
- 🔴 Hard: 0
- **Total: 20**

---

## 🔥 Current Stats

- **Study streak:** Day 3 🔥
- **Patterns learned:** Arrays, Hash Map, Two Pointers, Binary Search, Backtracking, Sorting, DP, Depth-First Search (DFS)
- **Focus:** Tree traversal & manipulation
- **Last session:** W1-Day2 (6 sorting problems)

---

## 📋 Problem Log

### Easy (11)

| # | Title | Pattern | Date | Link |
|---|-------|---------|------|------|
| 1 | Two Sum | Hash Map | 2026-05-15 | [View](problems/easy/0001-two-sum.md) ✅ |
| 14 | Longest Common Prefix | String | 2026-05-15 | [View](problems/easy/0014-longest-common-prefix.md) ✅ |
| 26 | Remove Duplicates | Two Pointers | 2026-05-15 | [View](problems/easy/0026-remove-duplicates-sorted-array.md) ✅ |
| 27 | Remove Element | Two Pointers | 2026-05-15 | [View](problems/easy/0027-remove-element.md) ✅ |
| 35 | Search Insert Position | Binary Search | 2026-05-15 | [View](problems/easy/0035-search-insert-position.md) ✅ |
| 66 | Plus One | Array/Math | 2026-05-15 | [View](problems/easy/0066-plus-one.md) ✅ |
| 88 | Merge Sorted Array | Two Pointers | 2026-05-15 | [View](problems/easy/0088-merge-sorted-array.md) ✅ |
| 905 | Transform Array by Parity | Sorting | 2026-05-15 | [View](problems/easy/0905-transform-array-by-parity.md) ✅ |
| 1679 | Count Pairs Sum < Target | Sorting | 2026-05-15 | [View](problems/easy/1679-count-pairs-sum-less-than-target.md) ✅ |
| 2050 | Count Numbers Unique Digits | Brute Force | 2026-05-15 | [View](problems/easy/2050-count-numbers-with-unique-digits.md) ✅ |
| 2418 | Sort the People | Sorting/Hash Map | 2026-05-15 | [View](problems/easy/2418-sort-the-people.md) ✅ |
| 938 | Range Sum of BST | Trees/DFS | 2026-05-15 | [View](0938-range-sum-of-bst.md) ✅ |
| 1379 | Find Corresponding Node in Clone | Trees/DFS | 2026-05-15 | [View](1379-find-corresponding-node-of-binary-tree-in-clone.md) ✅ |

### Medium (5)

| # | Title | Pattern | Date | Link |
|---|-------|---------|------|------|
| 11 | Container with Most Water | Greedy/TP | 2026-05-15 | [View](problems/medium/0011-container-with-most-water.md) ✅ |
| 15 | Three Sum | Two Pointers | 2026-05-15 | [View](problems/medium/0015-three-sum.md) ✅ |
| 39 | Combination Sum | Backtracking | 2026-05-15 | [View](problems/medium/0039-combination-sum.md) ✅ |
| 46 | Permutations | Backtracking | 2026-05-15 | [View](problems/medium/0046-permutations.md) ✅ |
| 2541 | Min Cost Split into Ones | DP | 2026-05-15 | [View](problems/medium/2541-minimum-cost-to-split-into-ones.md) ✅ |
| 2545 | Sort Students by Kth Score | Sorting | 2026-05-15 | [View](problems/medium/2545-sort-students-by-kth-score.md) ✅ |
| 1038 | BST to Greater Sum Tree | Trees/DFS | 2026-05-15 | [View](1038-bst-to-greater-sum-tree.md) ✅ |
| 2265 | Count Nodes Equal to Average | Trees/DFS | 2026-05-15 | [View](2265-count-nodes-equal-to-average-of-subtree.md) ✅ |
---

## 🧩 Pattern Summary

| Pattern | Easy | Medium | Hard | Total |
|---------|------|--------|------|-------|
| Hash Map | 1 | 0 | 0 | 1 |
| Two Pointers | 3 | 2 | 0 | 5 |
| Binary Search | 1 | 0 | 0 | 1 |
| Backtracking | 0 | 2 | 0 | 2 |
| Sorting | 4 | 2 | 0 | 6 |
| DP | 1 | 1 | 0 | 2 |
| Greedy | 0 | 1 | 0 | 1 |
| Brute Force | 1 | 0 | 0 | 1 |
| Trees/DFS | 2 | 2 | 0 | 4 |

---

## 📚 Key Learnings

### Problem-Solving Strategy
- **Editorial + Review:** Solved first 2 problems with editorial, then solved last 2 independently
- **Post-order traversal:** Essential for combining subtree results
- **BST properties:** Can prune branches for optimization

### Code Patterns
- Tuple returns: `(sum, count)` for accumulating subtree info
- Parallel traversal: Navigate both original and cloned trees
- Nonlocal variables: Accessing outer scope in nested functions

---

## 📚 Notes

- **Patterns Cheat Sheet:** See `notes/patterns.md`
- **Problem Details:** See individual files in `problems/easy/` and `problems/medium/`
- **Editorial + Review:** Solved first 2 problems with editorial, then solved last 2 independently
- **Post-order traversal:** Essential for combining subtree results
- **BST properties:** Can prune branches for optimization

### What Worked
- Editorial for understanding baseline approach
- Independent coding for double coding problem
- Tracing through examples step-by-step

### Challenges
- Indentation issues (Python sensitivity)
- Post-order vs pre-order traversal logic
- Tuple unpacking in recursive calls


Each problem file includes:
- ✅ Understanding the Goal
- ✅ LAYER 1: Line-by-line code explanation
- ✅ LAYER 2: Worked examples with traces
- ✅ LAYER 3: Key insights & complexity
- ✅ LAYER 4: Interview variations
- ✅ LAYER 5: Cheat sheet entry

---

**Last Updated:** May 15, 2026 | W1 Complete ✅
