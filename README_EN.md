# Hons Algos

[English](README_EN.md) | [中文](README.md)

## Introduction

NYU CSCI-GA.3520-001 Honors Analysis of Algorithms is the only required course for CS PhD students at Courant Institute of Mathematical Sciences, and is part of the Qualifying Exam (QE). This repository contains exam questions from Honors Algorithms spanning 20 years (2005-2024), along with a one-month study plan designed for exam preparation.

## Repository Contents

This repository contains study materials and organized content for Honors Analysis of Algorithms:
- Past exam papers (PDFs and extracted text) are located in `resources/exams/`
- Topic-categorized question bank index: `resources/exams/exam_topic_catalog.md`
- Full study plan: See "One-Month Study and Practice Plan" below or the file `resources/exams/study_plan_4weeks.md`

---

## One-Month Study and Practice Plan (Progressive Learning, Final Week Full Mock Exams)

> Note: The first three weeks progress from "foundation → advanced → comprehensive": recurrence/divide-and-conquer → dynamic programming → linear → hashing/trees/amortized → graphs → randomization → NP; Week 4 is dedicated to full mock exams and gap-filling.

### Overall Strategy
- Cover all question types from the exam syllabus; practice questions are unified from `resources/exams/exam_topic_catalog.md`
- Daily review of mistakes and approaches; weekly light review and template consolidation
- Same-day practice from easy to hard: warm-up → main focus → wrap-up; avoid just stacking quantity

### Week 1: Recurrence/Divide-and-Conquer / Dynamic Programming / Linear Algorithms Foundation
| Day | Focus Topic | Specific Tasks | Practice Problems (ID) | Notes | Status |
| --- | --- | --- | --- | --- | --- |
| Day 1 | Recurrence Relations & Master Theorem | Master Master Theorem/recursion tree; write rigorous asymptotic proofs | 2023_P6, 2022_P3, 2016_P4, 2005_P1 | Start with 2023_P6 as warm-up, then cover the rest |  |
| Day 2 | Recursion & Complexity Reinforcement | Merge-style counting/divide-and-conquer statistics; expected recursion | 2021_P4, 2010_P1 | Write complete proofs and complexity derivations |  |
| Day 3 | Sequence/Tree DP | Sequence DP (edit distance/LCS/LIS) and tree DP templates | 2021_P1, 2013_P1 | Record subproblem design and transition invariants |  |
| Day 4 | DAG/Path DP | Path DP on DAGs with capacity/constraint modeling | 2020_P3, 2015_P4, 2009_P1, 2020_P1 | Summarize "graph → DP" patterns |  |
| Day 5 | Linear-Time Algorithms I | Stack/scan/selection algorithms; flowchart implementation | 2016_P1, 2019_P2, 2013_P2 | Focus on boundaries and stability |  |
| Day 6 | Linear-Time Algorithms II | Reinforcement practice and error review | Self-selected consolidation problems | Use 1-2 problems to maintain momentum |  |
| Day 7 | Weekly Summary & Light Review | Consolidate notes; review mistakes; template consolidation | Any unfinished problems | Keep within 2 hours |  |

### Week 2: Hashing / Balanced Trees & Heaps / Amortized Analysis
| Day | Focus Topic | Specific Tasks | Practice Problems (ID) | Notes | Status |
| --- | --- | --- | --- | --- | --- |
| Day 8 | Hashing Basics | Universal hashing, collision probability, rolling hash principles | 2015_P2, 2006_Q5 | Write error/failure probability bounds |  |
| Day 9 | Hashing Applications | Sparse structures/matrix storage, hash+list hybrid structures | 2023_P5 | Design operation interfaces and complexity proofs |  |
| Day10 | Balanced Trees/Heaps I | BST basics, priority queue operations and complexity | 2008_P1, 2006_Q2 | Focus on rotation/merge semantics |  |
| Day11 | Balanced Trees/Heaps II | Augmentation and amortized perspective; batch tree maintenance | 2020_P2, 2019_P1, 2010_P4 | Compare trade-offs of different structures |  |
| Day12 | Amortized Analysis I | Two-stack queue, redundant binary counter; derive potential function | 2017_P1, 2015_P1 | Write clear potential function and invariants |  |
| Day13 | Amortized Analysis II + Union-Find | Dynamic connectivity & tree structure split/merge | 2014_P2, 2009_P4 | Practice maintaining potential/rank rules |  |
| Day14 | Data Structures Comprehensive | Check this week's mastery; supplement heap/hash problems | Self-selected consolidation problems | Fill gaps |  |

### Week 3: Graph Algorithms / Randomization / NP-Completeness
| Day | Focus Topic | Specific Tasks | Practice Problems (ID) | Notes | Status |
| --- | --- | --- | --- | --- | --- |
| Day15 | Single-Source/Staged Shortest Paths | Color/required-point/multi-stage modeling with single Dijkstra | 2021_P2, 2016_P3, 2015_P5, 2014_P4 | Draw expansion graphs and analyze complexity |  |
| Day16 | Multi-Stage/Round-Trip Paths | Reduction patterns for "go to A, then B, then return" | 2022_P4, 2013_P4, 2020_P4 | Summarize reverse graph + staged templates |  |
| Day17 | MST/Difference Constraints/Root | MST updates, difference constraints, graph root determination | 2011_P2, 2019_P4, 2018_P1, 2013_P3 | Write correctness proof points |  |
| Day18 | Graph Structure & Properties | Alternating walks/expansion/tree centroid/cut vertices | 2018_P2, 2018_P4, 2009_P3, 2008_P3 | Organize common lemmas and bounds |  |
| Day19 | Randomization Basics | Expectation/large number bounds/derandomization ideas | 2014_P5, 2017_P4, 2007_P1, 2010_P1 | Derive key probability inequalities |  |
| Day20 | Random Graphs & Algorithms | Probabilistic method and random construction/coloring/hashing | 2020_P5, 2019_P5, 2018_P5, 2022_P5, 2016_P2 | Provide existence → construction ideas |  |
| Day21 | NP-Completeness Reductions | Classic and variant 3SAT, graph problem reductions | 2023_P1, 2022_P6, 2019_P3, 2018_P6 | Draw reduction flowcharts and bidirectional proofs |  |

### Week 4: Full Mock Exams & Gap-Filling
| Day | Mock Schedule | Practice Papers & Review | Key Points | Status |
| --- | --- | --- | --- | --- |
| Day22 | Mock 1 (Recent Exams) | 2023 full exam | Strict 4-hour timing, answer by booklet; 2-hour post-exam review |  |
| Day23 | Mock 1 Review | Write complete solutions for each problem; check against syllabus | Organize mistakes by topic, re-categorize |  |
| Day24 | Mock 2 (Similar Difficulty) | 2022 full exam | Control pace, try 3-problem high-quality strategy |  |
| Day25 | Mock 2 Review + Targeted Reinforcement | Practice 2-3 problems from matching weak topics (from question bank) | Focus on time management and writing standards |  |
| Day26 | Mock 3 (Medium Comprehensive) | 2020 full exam | Practice handling graph+NP mixed problem order |  |
| Day27 | Mock 3 Review + Quick Consolidation | Output summary notes (problem type → solution → key points) | Complete final quick reference, confirm formulas/lemmas |  |
| Day28 | Light Review & State Adjustment | Browse all mistake summaries; moderate 1-2 leftover problems | Maintain momentum, no heavy cramming the night before |  |

---

For more questions organized by topic with summaries, see: `resources/exams/exam_topic_catalog.md`

