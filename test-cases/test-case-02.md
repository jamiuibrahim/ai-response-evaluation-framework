## Ground Truth / Evaluator Validation

Before evaluating model responses, the logical constraints were manually reviewed.

The constraints create a contradiction:

- Amina does not own the cat.
- Amina does not own the dog.
- Amina does not own the rabbit.

Because the task states that each person owns one different pet, Amina must own one of the three pets. However, all three possibilities are explicitly eliminated.

Therefore, the problem is logically inconsistent and does not have a valid solution as written.

A high-quality AI response should identify the contradiction rather than inventing an unsupported assignment of pets.

### Expected Evaluator Behavior

A strong response should:

- Detect that Amina has no possible pet.
- Explain the contradiction clearly.
- Avoid inventing a solution.
- State that the problem requires correction or additional clarification.
