# Full Folder + Pattern + PYQ Audit Report

Date: 2026-05-12
Repository: `/home/runner/work/pgcet/pgcet`

## 1) What was checked

I checked the repository structure and the training-vs-PYQ mapping across all topic folders and old papers mapping files.

- Total topic folders checked: **33** (`01` to `33`)
- Topic markdown files checked: **265**
- Total markdown files in repo checked: **294**
- `papers-qp` years checked: **2023, 2024, 2025**
- Validation done: folder inventory, pattern file availability, answer-file availability, question-to-topic link integrity, source completeness flags

## 2) Core findings (important)

### A. Structure and content health

- All **33 topic folders exist**.
- All **33 topic folders have README.md**.
- Pattern coverage per folder exists throughout; most folders have pattern + answer files.

### B. Old-paper mapping health

- In `papers-qp` Questions files:
  - 2023 exact topic-pattern links: **80/80 valid**
  - 2024 exact topic-pattern links: **100/100 valid**
  - 2025 exact topic-pattern links: **100/100 valid**
- So mapped link integrity is **280/280 valid (100%)**.

### C. Data-quality gap found

- `papers-qp/2024` contains **9 SOURCE MISSING placeholders** in `Questions.md`.
- `papers-qp/2024/Answers-Detailed.md` also has **9 SOURCE MISSING placeholders**.
- This is the main reason scoring confidence for 2024 trend is slightly reduced.

### D. Pattern-vs-PYQ difference (what is different from how we are doing)

1. **Repo training is topic-wise** (good for learning), while paper questions are **mixed and speed-driven** (54 sec/question).
2. Some folders are strong in pattern depth but have low mapped PYQ recurrence (still useful, but lower immediate return).
3. A few areas are highly repeated in mapped PYQs and should get highest revision priority.

## 3) Folder-by-folder matrix (pattern depth vs PYQ references)

| Folder | Pattern files | Answer files | PYQ refs (2023+2024+2025) | 2023 | 2024 | 2025 |
|---|---:|---:|---:|---:|---:|---:|
| 01-Time-and-Work | 10 | 5 | 2 | 0 | 1 | 1 |
| 02-Time-Speed-Distance | 10 | 5 | 5 | 1 | 3 | 1 |
| 03-Profit-and-Loss | 10 | 5 | 2 | 0 | 1 | 1 |
| 04-Percentages | 8 | 4 | 1 | 1 | 0 | 0 |
| 05-Ratio-and-Proportion | 8 | 4 | 5 | 1 | 3 | 1 |
| 06-Simple-Compound-Interest | 8 | 4 | 2 | 0 | 1 | 1 |
| 07-Averages | 8 | 4 | 0 | 0 | 0 | 0 |
| 08-Number-System | 6 | 3 | 0 | 0 | 0 | 0 |
| 09-Permutation-Combination | 6 | 3 | 2 | 1 | 0 | 1 |
| 10-Probability | 7 | 3 | 8 | 1 | 4 | 3 |
| 11-Blood-Relations | 6 | 3 | 2 | 1 | 0 | 1 |
| 12-Coding-Decoding | 8 | 4 | 3 | 1 | 1 | 1 |
| 13-Series | 4 | 2 | 13 | 9 | 1 | 3 |
| 14-Syllogisms | 4 | 2 | 3 | 0 | 2 | 1 |
| 15-Seating-Arrangement | 6 | 3 | 1 | 0 | 1 | 0 |
| 16-Direction-Sense | 4 | 2 | 3 | 3 | 0 | 0 |
| 17-Data-Interpretation | 6 | 3 | 10 | 5 | 3 | 2 |
| 18-Computer-Awareness | 17 | 8 | 62 | 20 | 21 | 21 |
| 19-Statistics | 9 | 3 | 7 | 3 | 1 | 3 |
| 20-Sets-and-Relations | 4 | 2 | 3 | 2 | 0 | 1 |
| 21-Matrices-and-Determinants | 4 | 2 | 4 | 3 | 0 | 1 |
| 22-Mathematical-Logic | 5 | 2 | 3 | 1 | 1 | 1 |
| 23-General-English | 6 | 3 | 36 | 6 | 15 | 15 |
| 24-Algebra-Basics | 11 | 5 | 7 | 2 | 1 | 4 |
| 25-Quadratic-Equations | 5 | 2 | 1 | 0 | 0 | 1 |
| 26-Coordinate-Geometry | 7 | 3 | 18 | 3 | 9 | 6 |
| 27-Trigonometry | 9 | 4 | 16 | 5 | 6 | 5 |
| 28-Boolean-Algebra | 5 | 2 | 11 | 2 | 5 | 4 |
| 29-General-Awareness | 12 | 6 | 45 | 7 | 19 | 19 |
| 30-Counting-Figures | 6 | 0 | 0 | 0 | 0 | 0 |
| 31-Dice | 4 | 2 | 1 | 0 | 0 | 1 |
| 32-Clocks | 5 | 2 | 2 | 1 | 0 | 1 |
| 33-Calendar | 4 | 2 | 2 | 1 | 1 | 0 |

## 4) Priority interpretation from audit

### Highest immediate return (based on mapped recurrence)

- **18-Computer-Awareness**
- **29-General-Awareness**
- **23-General-English**
- **26-Coordinate-Geometry**
- **27-Trigonometry**
- **13-Series**
- **17-Data-Interpretation**
- **28-Boolean-Algebra**

### Useful but lower observed recurrence in mapped set

- 07-Averages, 08-Number-System, 30-Counting-Figures (not mapped in current 2023–2025 files)
- 31-Dice, 32-Clocks, 33-Calendar (present, lower count)

## 5) Scoring

## A) Repository quality score (content + mapping)

- Structure completeness: **33/33 folders with README** → strong
- Link integrity: **280/280 valid topic links** → strong
- Data completeness penalty: **9 source-missing in 2024** → medium issue
- Pattern-to-answer consistency: generally strong; note `30-Counting-Figures` has no separate answer files

**Overall repository audit score: 90/100**

## B) Exam readiness score if studied in the same current way

Because study material is mostly topic-wise (not fully mixed timed simulation), readiness depends on execution style:

- If only reading + little timed practice: **52–62/100**
- If full topic practice + revision sheets + PYQ solve twice: **63–76/100**
- If mixed mocks + strict 90-min simulation + weak-topic correction loop: **77–88/100**

## 6) Exact “difference” summary requested

- **Current approach in repo:** pattern-wise learning by topic (excellent for concept building).
- **Actual paper behavior:** mixed-topic jumps + speed pressure + option traps.
- **Gap to close for score jump:** add more mixed-paper simulation rounds using already mapped PYQs and revision sheets.

## 7) Action list (from this audit)

1. Restore 2024 SOURCE MISSING entries first (high impact on confidence).
2. Keep topic study, but shift last phase to mixed timed sets.
3. Put more revision time into high-recurrence folders listed above.
4. For low-recurrence folders, do maintenance revision (don’t over-invest time).

---

This file is the requested full report based on folder/pattern/PYQ audit of the current repository content.
