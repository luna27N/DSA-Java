# Java DSA Practice

A structured collection of Data Structures & Algorithms problems in Java, solved as part of placement preparation for Java/Software Developer roles (TCS, Infosys, Cognizant, Wipro, Zoho, Accenture, and Japan-track companies).

## 📂 Repository Structure

Problems are organized by algorithmic pattern rather than difficulty, to reinforce pattern recognition during interviews.

```
src/
├── twopointers/
│   ├── ContainerWithMostWater.java
│   ├── MergeSortedArray.java
│   ├── GroupAnagrams.java
│   ├── RemoveDuplicatesFromSortedArray.java
│   └── TwoSum.java
├── linkedlist/
│   ├── ListNode.java
│   ├── AddTwoNumbers.java
└── README.md
```

## 🧠 Patterns Covered

| Pattern | Key Idea | Problems |
|---|---|---|
| **Two Pointers** | Two indices moving toward/away from each other to avoid nested loops | Container With Most Water, Two Sum, Remove Duplicates |
| **Linked List Traversal** | Slow/fast pointers, dummy head, in-place reversal | Reverse List, Middle of List, Cycle Detection |
| **Hashing** | Grouping/lookup in O(1) | Group Anagrams, Two Sum |

## ▶️ How to Run

Each file contains a `main` method for local testing (LeetCode's runtime environment isn't available locally, so classes like `ListNode` are defined manually where needed).

```bash
javac linkedlist/AddTwoNumbers.java
java linkedlist.AddTwoNumbers
```

Or run directly via IntelliJ IDEA using the green run arrow next to `main`.

## ✅ Progress Tracker

- [x] Two Pointers — 5 problems
- [x] Linked List — in progress
- [ ] Sliding Window
- [ ] Stacks & Queues
- [ ] Trees & BFS/DFS
- [ ] Dynamic Programming

## 📌 Notes

- Each solution includes time & space complexity in comments.
- Solutions prioritize clarity and interview-explainability over micro-optimization.
- `ListNode` and other helper classes are defined locally since LeetCode auto-provides them in its own environment but IntelliJ does not.

## 👩‍💻 Author

**Naviya** — Final-year B.Tech IT student, Dhanalakshmi Srinivasan Engineering College
GitHub: [@luna27N](https://github.com/luna27N)
