# LeetCode Solutions

My personal collection of LeetCode problems, solved while learning data structures and algorithms. Each solution includes my approach, complexity analysis, and notes on what tripped me up. The goal is to make the *reasoning* easy to follow, not just the code, so I can review it later or walk someone else through it.

## About

- **Language(s):** Python, C++, Go, Swift, RUst
- **Started:** [August 2025]
- **Goal:** Build a solid foundation in DSA for classes and technical interviews
- **Level:** Still learning! Some early solutions aren't optimal; I note that where I know it.

## How This Repo Is Organized

Problems are grouped by topic, and each problem gets its own folder:

```
leetcode/
├── arrays-and-hashing/
│   ├── 0001-two-sum/
│   │   ├── solution.py
│   │   └── NOTES.md
│   └── 0217-contains-duplicate/
├── two-pointers/
├── sliding-window/
├── stack/
├── binary-search/
├── linked-list/
├── trees/
├── graphs/
└── dynamic-programming/
```

Problem numbers are zero-padded (`0001`, not `1`) so folders sort in order.

## Problem Index

| #   | Problem | Difficulty | Topic | Solution | Key Idea |
|-----|---------|------------|-------|----------|----------|
| 1   | [Two Sum](https://leetcode.com/problems/two-sum/) | Easy | Hash Map | [Python](arrays-and-hashing/0001-two-sum/solution.py) | Store each number's index in a hash map; check if `target - num` is already there |
| 217 | [Contains Duplicate](https://leetcode.com/problems/contains-duplicate/) | Easy | Hash Set | [Python](arrays-and-hashing/0217-contains-duplicate/solution.py) | A set gives O(1) lookups, so one pass is enough |

<!-- Add a row each time you solve a problem -->

## What Each Problem's Notes Include

Every problem folder has a `NOTES.md` that follows this template:

```markdown
# [Problem #] — [Problem Name]
Link: [LeetCode URL]
Difficulty: Easy / Medium / Hard
Topics: Array, Hash Map, ...
Date solved: YYYY-MM-DD

## The Problem (in my own words)
One or two sentences describing what's being asked.

## First Thoughts / Brute Force
What I tried first and why it was too slow (or why it worked).

## Optimized Approach
Step-by-step explanation of the better solution.
Why does it work? What's the key insight?

## Complexity
- Time: O(?) — why
- Space: O(?) — why

## Edge Cases
- Empty input, single element, duplicates, negatives, etc.

## Mistakes I Made
Bugs, wrong assumptions, things I misread.

## Related Problems
Other problems that use the same pattern.
```

## Patterns I've Learned

A running cheat sheet of techniques and when to reach for them:

- **Hash map / set:** fast lookups; "have I seen this before?"
- **Two pointers:** sorted arrays, pairs, palindromes
- **Sliding window:** contiguous subarrays/substrings with a condition
- **Binary search:** sorted data, or "find the smallest X that works"
- **BFS / DFS:** trees, graphs, grids
- **Dynamic programming:** overlapping subproblems; "how many ways" or "min/max cost"

<!-- Add a short example problem next to each pattern as you learn it -->

## Running the Code

```bash
# Python example
python arrays-and-hashing/0001-two-sum/solution.py
```

Some solutions include simple test cases at the bottom of the file so they can be run directly.

## Progress

| Easy | Medium | Hard | Total |
|------|--------|------|-------|
| 0    | 0      | 0    | 0     |

## Resources

Courses, books, videos, or roadmaps I've found helpful:

- [Resource name](link) — what it helped with

## Note

These are my own solutions, written for learning. If you're working through these problems too, try them yourself first. You'll learn way more from struggling with them than from reading someone else's answer.
