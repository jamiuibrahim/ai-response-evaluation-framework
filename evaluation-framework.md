# AI Response Evaluation Framework

## 1. Purpose

This framework provides a structured and repeatable method for evaluating the quality of AI-generated responses.

The objective is to ensure that evaluations are consistent, transparent, and supported by clear reasoning rather than subjective preference.

---

## 2. Evaluation Principles

Each response should be evaluated independently based on the requirements of the original prompt.

Evaluators should:

- Focus on the content rather than personal preference.
- Apply the same standards to every response.
- Verify factual claims when necessary.
- Consider both strengths and weaknesses.
- Provide clear justification for assigned scores.
- Avoid allowing writing style alone to influence the overall evaluation.

---

## 3. Evaluation Criteria

### 3.1 Accuracy

**Definition:**  
Measures whether the response contains factually correct information and avoids unsupported or misleading claims.

**Questions to Consider:**

- Are the facts correct?
- Are important claims supported?
- Does the response contain misinformation?
- Are there unsupported assumptions?

**Scoring Guide:**

| Score | Description |
|---|---|
| 5 | Fully accurate with no significant factual errors |
| 4 | Mostly accurate with minor issues |
| 3 | Generally acceptable but contains some questionable information |
| 2 | Contains significant inaccuracies |
| 1 | Contains major factual errors or misinformation |

---

### 3.2 Relevance

**Definition:**  
Measures how directly the response addresses the user's request.

**Questions to Consider:**

- Does the response answer the actual question?
- Does it include unnecessary information?
- Does it remain focused on the requested task?

**Scoring Guide:**

| Score | Description |
|---|---|
| 5 | Directly and completely addresses the request |
| 4 | Mostly relevant with minor unnecessary information |
| 3 | Partially relevant |
| 2 | Frequently unfocused or includes excessive irrelevant information |
| 1 | Does not adequately address the request |

---

### 3.3 Completeness

**Definition:**  
Measures whether the response provides sufficient information to fully address the task.

**Questions to Consider:**

- Are important parts of the question answered?
- Is critical information missing?
- Does the response require unnecessary follow-up questions?

**Scoring Guide:**

| Score | Description |
|---|---|
| 5 | Fully addresses all important aspects of the task |
| 4 | Addresses most aspects with minor omissions |
| 3 | Addresses the basic request but lacks important details |
| 2 | Significant information is missing |
| 1 | Fails to provide sufficient information |

---

### 3.4 Clarity

**Definition:**  
Measures how easy the response is to understand.

**Questions to Consider:**

- Is the language understandable?
- Is the response well-organized?
- Are explanations clear?
- Is unnecessary complexity avoided?

**Scoring Guide:**

| Score | Description |
|---|---|
| 5 | Exceptionally clear and well-structured |
| 4 | Clear with minor organizational issues |
| 3 | Understandable but could be clearer |
| 2 | Difficult to follow |
| 1 | Extremely unclear or poorly structured |

---

### 3.5 Logical Reasoning

**Definition:**  
Measures whether the response demonstrates coherent reasoning and logical consistency.

**Questions to Consider:**

- Do conclusions follow from the information provided?
- Are there contradictions?
- Are explanations logically structured?
- Does the response make unsupported logical jumps?

**Scoring Guide:**

| Score | Description |
|---|---|
| 5 | Highly logical and internally consistent |
| 4 | Mostly logical with minor reasoning gaps |
| 3 | Acceptable reasoning but noticeable gaps exist |
| 2 | Significant reasoning problems |
| 1 | Illogical, contradictory, or unsupported reasoning |

---

### 3.6 Instruction Following

**Definition:**  
Measures whether the AI follows explicit instructions and constraints in the original prompt.

**Questions to Consider:**

- Did the response follow all instructions?
- Did it respect formatting requirements?
- Did it follow length constraints?
- Did it complete the requested task?

**Scoring Guide:**

| Score | Description |
|---|---|
| 5 | Follows all instructions precisely |
| 4 | Follows most instructions with minor deviations |
| 3 | Follows basic instructions but misses some requirements |
| 2 | Fails to follow important instructions |
| 1 | Ignores major instructions or fails the task |

---

## 4. Evaluation Process

Each AI response will be evaluated using the following process:

1. Read and understand the original prompt.
2. Identify explicit instructions and constraints.
3. Review the AI-generated response independently.
4. Evaluate the response against each criterion.
5. Assign a score from 1 to 5.
6. Document evidence supporting each score.
7. Identify critical errors or weaknesses.
8. Calculate the overall score.
9. Compare responses when multiple models are tested.
10. Produce a final ranking with justification.

---

## 5. Overall Scoring

The baseline overall score is calculated by averaging the six evaluation criteria:

**Overall Score = (Accuracy + Relevance + Completeness + Clarity + Logical Reasoning + Instruction Following) / 6**

However, the numerical score should not replace human judgment.

A response containing a major factual error, harmful misinformation, or serious instruction violation should be flagged even if its average score is high.

---

## 6. Evaluation Output Template

Each evaluation should contain:

### Prompt

[Original test prompt]

### Model

[Name of AI model]

### Response

[AI-generated response]

### Evaluation

| Criteria | Score (1–5) | Justification |
|---|---|---|
| Accuracy | | |
| Relevance | | |
| Completeness | | |
| Clarity | | |
| Logical Reasoning | | |
| Instruction Following | | |

### Overall Score

[Score]

### Key Strengths

- 
- 
- 

### Key Weaknesses

- 
- 
- 

### Final Assessment

[Brief overall evaluation and ranking decision]

---

## 7. Limitations

This framework includes subjective judgment. Different evaluators may assign slightly different scores depending on interpretation.

To improve consistency:

- Evaluation guidelines should be clearly defined.
- Evaluators should document evidence for scores.
- Multiple evaluators can be used for comparison.
- Calibration exercises can help align scoring standards.

---

## Author

**Jamiu Ibrahim Adejumobi**

AI Generalist | AI Evaluation & Research | Prompt Engineering
