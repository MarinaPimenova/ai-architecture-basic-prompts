# Self-Reflection Prompting

### What it is:

Self-reflection is when the model is asked to **review and improve its own previous answer**.

It focuses on:

* Evaluating correctness
* Identifying weaknesses
* Improving clarity or logic

It does **not** involve tools or external actions.

---

### 🔹 Simple Example

**Prompt 1:**

> What is 17 × 24?

**Model:**

> 17 × 24 = 408.

**Prompt 2 (Self-Reflection):**

> Review your previous answer. Check if it is correct and explain your reasoning.

**Model:**

> 17 × 24 = (20 × 24) − (3 × 24) = 480 − 72 = 408.
> The previous answer is correct.

👉 The model reflects on its own output and validates or improves it.

---
