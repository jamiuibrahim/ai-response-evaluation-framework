# Test Case 01: Collected AI Responses

## Test Prompt

Explain the difference between supervised learning and unsupervised learning.

Your response must:

1. Clearly define both concepts.
2. Provide one practical example of each.
3. Keep the explanation under 200 words.
4. Use language understandable to a beginner.

---

## Response Collection Method

The same prompt was submitted to each AI model without modification.

Responses were collected from the first generated output without regeneration or follow-up instructions.

The responses were preserved as generated for independent evaluation.

---

# Model 1: ChatGPT

## Response

Supervised Learning vs. Unsupervised Learning

Supervised Learning is a type of machine learning where the model learns from labeled data. This means the correct answers are already provided, and the model learns to predict outcomes for new data.

Example: Training a model with labeled emails ("spam" or "not spam") so it can identify whether a new email is spam.

Unsupervised Learning is a type of machine learning where the model works with unlabeled data. It tries to discover hidden patterns, relationships, or groups without being told the correct answers.

Example: A business uses customer purchase data to automatically group customers with similar buying habits.

In simple terms:

Supervised Learning = Learning with answers provided.

Unsupervised Learning = Finding patterns without answers provided.

---

# Model 2: DeepSeek

## Response

Supervised learning is like studying with an answer key. You train an algorithm using labeled data—input paired with the correct output. The model learns the pattern to predict outcomes on new, unseen data.

Unsupervised learning has no answer key. You give the algorithm unlabeled data and let it discover hidden structures, groups, or patterns on its own.

Practical examples:

- Supervised: Email spam detection. You feed the model thousands of emails labeled "spam" or "not spam." It learns to classify new emails.
- Unsupervised: Customer segmentation. You give a store's purchase history (no labels) to the algorithm, and it automatically groups customers with similar buying habits for targeted marketing.

In short: Supervised = learning with guidance (predicting outcomes). Unsupervised = finding hidden treasures (discovering structure).

---

# Model 3: Claude

## Response

**Supervised learning** is when a computer learns from labeled examples — data that already has the correct answer attached. The model studies these examples and learns to predict the answer for new, unseen data.

*Example:* Teaching a model to identify spam emails by showing it thousands of emails already labeled "spam" or "not spam."

**Unsupervised learning** is when a computer looks at data with no labels or correct answers given. Instead, it tries to find hidden patterns or groupings on its own.

*Example:* Grouping customers into segments based on shopping habits, without telling the model in advance what those groups should be.

**Key difference:** Supervised learning learns from answers you already know (like studying with a teacher and an answer key). Unsupervised learning explores data to discover structure you didn't know existed (like sorting a pile of mixed objects into groups just by noticing similarities).

Think of it this way: if you're teaching a kid to recognize fruits by showing pictures labeled "apple," "banana," etc., that's supervised. If you just hand them a basket of unlabeled fruits and ask them to sort similar ones together, that's unsupervised.

---

# Model 4: Google Gemini

## Response

**Supervised Learning**

- **Definition:** The algorithm learns from data that is already labeled with correct answers, functioning much like a student studying with an answer key.
- **Example:** Training an email filter to recognize spam by feeding it thousands of emails pre-labeled as either **spam** or **not spam**.

**Unsupervised Learning**

- **Definition:** The algorithm analyzes completely unlabeled data to discover hidden structures, similarities, or natural groupings on its own without a predefined target.
- **Example:** Grouping online store customers into distinct shopping behavior segments for targeted marketing without pre-existing categories.

---

## Collection Notes

- Same prompt used for all models.
- No follow-up prompts were provided.
- Responses were collected before evaluation.
- Responses will be assessed independently using the project's evaluation framework.

## Status

✅ Response collection completed.

Next stage: Independent evaluation and scoring.
