# AVENYX
# ProofData — Every Number Has a Proof

> **An AI-powered data analyst that doesn't just give you an answer — it proves it.**

ProofData is a conversational data-analysis system designed to answer questions over real-world CSV and Excel datasets while making numerical results **reproducible, executable, and verifiable**.

Unlike a traditional AI chatbot that may generate a plausible-looking answer, ProofData follows a verification pipeline:

QUESTION → INSPECT DATA → ANALYZE → GENERATE PROOF → EXECUTE → VERIFY → ANSWER / REFUSE

If the available data is insufficient, ambiguous, incompatible, or outside the requested time period, ProofData can refuse to produce an unsupported answer.

---

## 🚀 Key Features

### 1. Natural-Language Data Analysis

Users can ask questions in normal language instead of writing Pandas code.

Examples:

- What is the total revenue?
- Which product category generated the highest revenue?
- How many orders are there?
- What was the total sales in India?

---

### 2. Reproducible Proof

Every numerical answer can be accompanied by executable Python/Pandas code showing how the result was calculated.

Example:

```python
total_revenue = df["Sales"].sum()
