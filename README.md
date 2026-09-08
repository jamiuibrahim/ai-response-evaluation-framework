# AI Response Evaluation Framework

A structured framework for evaluating and comparing AI-generated responses using consistent, evidence-based criteria.

## Overview

This project demonstrates a practical approach to evaluating Large Language Model (LLM) responses across different task types.

The framework focuses on assessing not only whether an AI response is correct, but also how well it satisfies the task requirements, explains its reasoning, and communicates the result.

Four AI models were evaluated using the same prompts and a standardized evaluation rubric.

### Models Evaluated

- ChatGPT
- Claude
- DeepSeek
- Google Gemini

---

## Evaluation Criteria

Each response is evaluated across six dimensions:

| Criterion | Description |
|---|---|
| **Accuracy** | Whether the response is factually or logically correct |
| **Relevance** | Whether the response directly addresses the task |
| **Completeness** | Whether all required parts of the task are addressed |
| **Clarity** | Whether the response is understandable and well presented |
| **Logical Reasoning** | Whether conclusions follow correctly from the available information |
| **Instruction Following** | Whether the response follows the explicit requirements of the prompt |

Each criterion is scored from **1–5**.

**Maximum score per model: 30 points.**

---

## Evaluation Methodology

The evaluation process follows a consistent workflow:

1. Define the evaluation task.
2. Establish the expected answer or ground truth.
3. Submit the same prompt to each model.
4. Preserve the original model responses.
5. Evaluate each response independently.
6. Score each evaluation criterion from 1–5.
7. Calculate total and average scores.
8. Document strengths, weaknesses, and failure patterns.
9. Compare results across models.
10. Identify broader evaluation insights.

The goal is to make the evaluation process **structured, reproducible, and evidence-based**.

---

## Test Cases

### Test Case 01 — Factual Explanation

**Task:** Explain the difference between supervised and unsupervised learning.

The task required the models to:

- Clearly define both concepts
- Provide one practical example of each
- Stay under 200 words
- Use beginner-friendly language

**Result:** All four models achieved **30/30 (5.0/5.0)**.

The main differences were qualitative rather than score-based:

- ChatGPT provided a balanced explanation and concise summary.
- DeepSeek used an effective simple analogy.
- Claude provided explanatory depth while remaining beginner-friendly.
- Gemini presented the information in a structured and concise format.

[View Test Case 01 →](test-cases/test-case-01.md)

---

### Test Case 02 — Logical Reasoning

**Task:** Determine which pet belongs to each of three people based on a set of constraints.

The prompt intentionally contained a contradiction.

Amina was explicitly prohibited from owning:

- The cat
- The dog
- The rabbit

Therefore, no valid assignment could satisfy all constraints.

**Result:**

| Model | Score | Average |
|---|---:|---:|
| ChatGPT | 30/30 | 5.0/5.0 |
| Claude | 30/30 | 5.0/5.0 |
| DeepSeek | 30/30 | 5.0/5.0 |
| Google Gemini | 15/30 | 2.5/5.0 |

Three models correctly identified the contradiction.

Google Gemini incorrectly assigned the cat to Amina, directly violating one of the stated constraints.

This test demonstrates an important evaluation principle:

> Clear and confident reasoning does not necessarily mean correct reasoning.

[View Test Case 02 →](test-cases/test-case-02.md)

---

## Key Findings

### 1. Correctness requires constraint verification

A response can appear logically convincing while failing to check its conclusion against every constraint.

### 2. Clear writing is not sufficient

A response may be well structured and easy to understand while still producing an incorrect conclusion.

### 3. Ground-truth validation is important

Before scoring a model, the expected answer or logical constraints should be independently validated.

### 4. Standardized rubrics improve consistency

Using the same evaluation dimensions across models makes qualitative comparison more systematic.

### 5. Different tasks expose different model behaviors

A model that performs well on factual explanation may behave differently on tasks requiring multi-step logical reasoning.

---

## Repository Structure

```text
ai-response-evaluation-framework/
│
├── README.md
├── evaluation-framework.md
│
├── test-cases/
│   ├── test-case-01.md
│   └── test-case-02.md
│
├── responses/
│   ├── test-case-01-responses.md
│   └── test-case-02-responses.md
│
├── evaluation-results/
│   ├── test-case-01-evaluation.md
│   └── test-case-02-evaluation.md
│
└── findings.md
