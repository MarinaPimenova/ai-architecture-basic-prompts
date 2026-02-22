
# ReAct Prompting (Reason + Act)

### What it is:

ReAct combines:

* **Reasoning (Thought)**
* **Action (using a tool, search, calculator, API, etc.)**

The model alternates between thinking and performing actions to gather information.

It is typically used when:

* External data is needed
* Tools must be used
* Multi-step decision-making is required

---

### 🔹 Simple Example

**Question:**

> Who is the current president of France and how old is he?

**ReAct style response:**

Thought: I need to find the current president of France.
Action: Search “current president of France”
Observation: Emmanuel Macron

Thought: Now I need his age.
Action: Search “Emmanuel Macron age”
Observation: Born 1977

Final Answer: Emmanuel Macron is the current president of France. He was born in 1977.

👉 The model reasons, performs actions, observes results, and then continues reasoning.

---

# 🔎 Key Difference (Very Simple)

| Self-Reflection              | ReAct                                   |
| ---------------------------- | --------------------------------------- |
| Reviews its own answer       | Uses tools or external actions          |
| Improves or validates output | Alternates between thinking and acting  |
| No external interaction      | Requires external information retrieval |

---
