# MAS Score & Grading Guide

> **Simple explanation of how we measure diagram quality**

---

## What is MAS Score?

MAS Score is a number from **0 to 100** that tells you how good your generated diagram is.

- **100** = Perfect diagram
- **80+** = Good quality, ready to use
- **60-79** = Acceptable, may need small fixes
- **Below 60** = Needs improvement

---

## How Do We Calculate the Score?

We check **4 things** about every diagram:

### 1. Semantic Quality (40% of score)
**"Does the diagram contain the right information?"**

- Did we extract all the important items (people, systems, steps)?
- Did we show the correct connections between items?

Example: If you asked for a diagram with "Customer, Sales, Warehouse" and we only found "Customer, Sales", we lose points.

### 2. Structural Quality (30% of score)
**"Is the diagram properly built?"**

- Is the Mermaid code valid (no syntax errors)?
- Does it have all required parts for that diagram type?
  - Swimlane: Has lanes for each role
  - User Journey: Has sections and actions
  - Value Stream: Has process steps with times

Example: A swimlane without any lanes = low structural score.

### 3. Cognitive Quality (20% of score)
**"Is the diagram easy to read?"**

- Is it the right size? (not too simple, not too complex)
- Are labels short and clear? (not cut off or too long)

Example: A diagram with 50 nodes is too complex. A diagram with 1 node is too simple.

### 4. Pragmatic Quality (10% of score)
**"Does it match what you asked for?"**

- Does the diagram contain words from your request?
- Does it fit the business context?

Example: You asked for "order processing" but the diagram shows "user login" = low pragmatic score.

---

## Grade Meanings

| Grade | Score Range | What It Means |
|-------|-------------|---------------|
| **A+** | 95-100 | Excellent! Production ready, no changes needed |
| **A** | 90-94 | Great quality, very minor improvements possible |
| **A-** | 85-89 | Good quality, small tweaks would help |
| **B+** | 80-84 | Above average, usable but could be better |
| **B** | 75-79 | Average quality, review before using |
| **B-** | 70-74 | Below average, needs some fixes |
| **C+** | 65-69 | Fair, noticeable issues to fix |
| **C** | 60-64 | Passing, but significant improvements needed |
| **C-** | 55-59 | Poor, major issues present |
| **D** | 50-54 | Very poor, consider regenerating |
| **F** | Below 50 | Failed, regenerate with clearer input |

---

## What Each Diagram Type Needs

### Swimlane Diagram
- ✅ Multiple lanes (one per role/team)
- ✅ Tasks in each lane
- ✅ Arrows showing flow between tasks
- ✅ MVP groupings (if requested)

### User Journey
- ✅ Sections (phases of the journey)
- ✅ Actions with emotion scores (1-5)
- ✅ Actor labels (who does each action)

### Business Process
- ✅ Start and end nodes
- ✅ Task boxes with owner and SLA
- ✅ Decision gateways (diamond shapes)
- ✅ Flow arrows between steps

### Decision Tree
- ✅ Root decision node
- ✅ Yes/No branches
- ✅ Outcome nodes at the end
- ✅ Priority labels (Critical, High, Medium, Low)

### Value Stream
- ✅ Process steps in order
- ✅ Process Time (PT) for each step
- ✅ Wait Time (WT) for each step
- ✅ Metrics summary (Lead Time, Efficiency)

---

## Tips to Get Higher Scores

1. **Be specific in your request**
   - Bad: "Show me a diagram"
   - Good: "Swimlane diagram for Customer places order, Sales validates, Warehouse ships"

2. **Include role/actor names**
   - Mention who does what: "Customer", "Admin", "System"

3. **Describe the flow clearly**
   - Use action words: "submits", "reviews", "approves", "sends"

4. **Mention connections**
   - Say how things relate: "User sends to API, API calls Database"

---

## Example Score Breakdown

For a Business Process diagram that scores **98.2**:

| Dimension | Weight | Score | Contribution |
|-----------|--------|-------|--------------|
| Semantic | 40% | 100 | 40.0 |
| Structural | 30% | 95 | 28.5 |
| Cognitive | 20% | 96 | 19.2 |
| Pragmatic | 10% | 95 | 9.5 |
| **Total** | 100% | - | **97.2** |

The small deductions (5 points from Structural, 4 from Cognitive, 5 from Pragmatic) might be from:
- A label that's slightly too long (Readability)
- Missing one expected connection (Relationship)
- Slight mismatch with request wording (Faithfulness)

---

## Quick Reference

| If Score Is... | Grade | Action |
|----------------|-------|--------|
| 95+ | A+ | Use as-is ✅ |
| 80-94 | A/B+ | Review quickly, likely fine |
| 60-79 | B/C | Check for issues, may need edits |
| Below 60 | D/F | Regenerate with clearer input |

---

*Document Version: 1.0.0 | Last Updated: 2025-12-10*
