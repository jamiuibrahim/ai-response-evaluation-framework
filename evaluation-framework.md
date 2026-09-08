# AI Response Evaluation Framework

## 1. Purpose

This framework defines a structured method for evaluating and comparing AI-generated responses.

The objective is to assess response quality using consistent criteria rather than relying only on whether an answer appears correct.

---

## 2. Evaluation Criteria

Each AI response is evaluated using six criteria.

### 2.1 Accuracy

Measures whether the response contains a correct answer based on the available facts, evidence, or logical constraints.

**Scoring:**

- **5** — Fully correct
- **4** — Mostly correct with a minor issue
- **3** — Partially correct
- **2** — Significant errors
- **1** — Fundamentally incorrect

---

### 2.2 Relevance

Measures whether the response directly addresses the user's request without unnecessary or unrelated information.

**Scoring:**

- **5** — Directly relevant
- **4** — Mostly relevant
- **3** — Some unnecessary information
- **2** — Frequently off-topic
- **1** — Does not address the task

---

### 2.3 Completeness

Measures whether the response addresses all required components of the prompt.

**Scoring:**

- **5** — Fully addresses all requirements
- **4** — Minor omission
- **3** — Some requirements addressed
- **2** — Major requirements missing
- **1** — Requirements largely ignored

---

### 2.4 Clarity

Measures how clearly and understandably the response communicates its answer.

Factors include:

- Organization
- Readability
- Explanation quality
- Appropriate language
- Logical presentation

**Scoring:**

- **5** — Extremely clear
- **4** — Clear with minor issues
- **3** — Understandable but could be improved
- **2** — Difficult to follow
- **1** — Very unclear

---

### 2.5 Logical Reasoning

Measures whether the reasoning correctly connects the available information to the conclusion.

This criterion is especially important for reasoning, constraint, mathematical, and analytical tasks.

**Scoring:**

- **5** — Reasoning is logically sound
- **4** — Mostly sound with a minor weakness
- **3** — Mixed reasoning quality
- **2** — Significant reasoning errors
- **1** — Fundamentally invalid reasoning

---

### 2.6 Instruction Following

Measures whether the response follows the explicit requirements provided in the prompt.

Examples include:

- Word limits
- Required structure
- Number of examples
- Requested format
- Specific output requirements

**Scoring:**

- **5** — Follows all instructions
- **4** — Minor deviation
- **3** — Several deviations
- **2** — Major instructions ignored
- **1** — Does not follow the task requirements

---

# 3. Scoring System

Each criterion receives a score from **1 to 5**.

There are six evaluation criteria:

```text
6 criteria × 5 maximum points = 30 points
