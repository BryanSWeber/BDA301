# BDA301 Lesson Reordering Proposal

## Standardized Structure (per lesson)
Every lesson notebook should follow this format:

```markdown
# Day X: [Topic Title]

## Learning Objectives
- Specific, measurable objectives

## Prerequisites
- Previous lesson reference

## Content Sections
- Section 1: [Topic]
- Section 2: [Topic]

## Key Takeaways
- 3-5 bullet points summarizing main concepts

## Exercises
- Practice problems

## Next Lesson Preview
- Brief teaser for next topic
```

---

## Recommended Lesson Order

| Order | Lesson | Topic | Notes |
|-------|--------|-------|-------|
| 1 | Introduction | Course intro, Python basics (print, loops, conditionals) | Current: Introduction.ipynb + Day 01 (Part 1 content) |
| 2 | Data Types & Structures | Variables, lists, dictionaries, data frames | Currently missing as standalone |
| 3 | Data Distributions | Random numbers, distributions, probability | Current: Day 05 |
| 4 | Descriptive Statistics | Mean, median, mode, std, IQR, variance | Current: Day 03 |
| 5 | Data Visualization I | Histograms, bar charts, pie charts | Current: Day 04 |
| 6 | Data Visualization II | Scatter plots, heatmaps, advanced plots | Merge with Day 04 |
| 7 | Data Loading & Exploration | Reading CSVs, .head(), .describe() | Current: Day 01 + Day 02 (partial) |
| 8 | Data Cleaning & Manipulation | Missing values, outliers, type conversion | Current: Day 02 |
| 9 | Confidence Intervals & Hypothesis Testing | Statistical testing, p-values | Current: Day 06 |
| 10 | Introduction to Regression | Linear regression basics | Currently: Day 07-09 area |
| 11 | Multiple Regression & Diagnostics | F-tests, multicollinearity, VIF | Current: Day 10 |
| 12 | Classification Basics | Logistic regression, decision trees | Currently: Day 11-13 area |
| 13 | Random Forests & Ensembles | Decision trees, RF, model evaluation | Current: Day 16 |
| 14 | [Optional Advanced Topic] | Clustering, PCA, or time series | Currently: Day 14-15 area |
| 15 | Final Project Workshop | Applied analysis project | |
| 16 | Course Review & Wrap-up | Key concepts review, exam prep | |

---

## Changes Required

### Move Introduction Content
- **From**: Introduction.ipynb scattered across days
- **To**: Day 1 (rename/move Python basics from Introduction.ipynb to "Day 01 Lesson.ipynb")

### Fix Day Mismatches
- `Day 06 Lesson.ipynb`: Header says "Day 5" → should be "Day 9"
- `Day 10 Lesson.ipynb`: Header says "Day 8 Lesson" → should be "Day 11"

### Consolidate Duplicate Topics
- Day 01 + Day 02 (partial): Both cover data loading → merge into Day 7
- Day 04 + Day 05: Both cover visualization basics → merge into Days 5-6

### Add Missing Content
- Data Types & Structures: Create new lesson (currently only in Introduction.ipynb partially)
- Exercises section: Add to all lessons
- Key Takeaways: Add to all lessons
- Next Lesson Preview: Add to all lessons

---

## Implementation Priority

1. **High Priority** (errors/outdated):
   - Fix Day 06 header ("Day 5" → "Day 9")
   - Fix Day 10 header ("Day 8" → "Day 11")
   - Add consistent structure to Day 16 (currently missing intro)

2. **Medium Priority** (content organization):
   - Add Learning Objectives to all lessons
   - Add Key Takeaways to all lessons
   - Add Next Lesson Preview to all lessons

3. **Low Priority** (curriculum redesign):
   - Reorder lessons 1-16 as proposed
   - Consolidate duplicate content
   - Create missing lessons (Data Types & Structures)
