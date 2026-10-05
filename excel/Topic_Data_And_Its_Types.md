# Topic: Data and Its Types

## 1. Definition & Explanation

**Data** is raw information that helps in making decisions — it can be numbers, text, images, or video. Before you touch a single Excel formula, it helps to know how data gets classified, because the classification determines what you can *do* with it (sum it, sort it, filter it, chart it).

There are two ways to slice data:

### A. By nature of the value

- **Qualitative (Categorical) Data** — non-numeric, describes labels or categories.
  Examples: `Red`, `Blue`, `Green` (product colors) · `Positive`, `Neutral`, `Negative` (feedback) · `HR`, `Sales`, `IT` (departments).

- **Quantitative (Numerical) Data** — numbers that can be measured or counted. This splits further:
  - **Discrete Data** — whole numbers only, cannot have decimals. *Example: Number of employees (1, 2, 3…).*
  - **Continuous Data** — can take decimal values. *Example: A person's height (5.7 ft, 6.1 ft) or a purchase amount (₹156.75).*

### B. By how it's stored/managed

- **Structured Data** — organized in a well-defined format, usually rows and columns. *Example: Excel spreadsheets, SQL databases, sales records.*
- **Unstructured Data** — no predefined format, harder to organize. *Example: emails, social media posts, videos, images.*

### How Excel stores this

Underneath all of the above, Excel itself only recognizes four storage formats for what you type into a cell:

| Excel Format         | Example                      |
|----------------------|------------------------------|
| Text (String)        | "John Doe", "Mumbai"         |
| Number               | 1500, 299.99                 |
| Date & Time          | 12/08/2023                   |
| Boolean (TRUE/FALSE) | TRUE (Paid), FALSE (Pending) |

### Usage Example

A company logs each customer purchase like this:

| Customer Name | Purchase Date | Items | Amount  | Member |
|---------------|---------------|-------|---------|--------|
| Sarah Johnson | 05/15/2023    | 3     | ₹156.75 | TRUE   |

Breaking this single row down by type:
- `"Sarah Johnson"` → **Text**, and also **Qualitative** (an identifying label, not a measurement).
- `05/15/2023` → **Date**, technically stored as **Structured** data.
- `3` (Items) → **Number**, specifically **Discrete Quantitative** (you can't buy 2.5 items).
- `₹156.75` (Amount) → **Number**, specifically **Continuous Quantitative** (money can have decimals).
- `TRUE` (Member) → **Boolean**.

This single row is also a good example of **Structured Data** overall — it lives in a well-defined table with consistent columns, unlike, say, the free-text body of a customer support email.

---

## 2. Practical Task

Below is a small dataset. For **each column**, decide: (a) is it Qualitative or Quantitative, and (b) if Quantitative, is it Discrete or Continuous. Then answer the follow-up questions.

| Order ID | City  | Rating (1–5) | Delivery Time (hrs) | Refunded |
|----------|-------|--------------|---------------------|----------|
| 5001     | Pune  | 4            | 2.5                 | FALSE    |
| 5002     | Delhi | 5            | 1.0                 | FALSE    |
| 5003     | Pune  | 2            | 4.25                | TRUE     |

**Do this, then check yourself:**

1. Classify **"City"** — Qualitative or Quantitative? Why?
2. Classify **"Rating (1–5)"** — most people instinctively call this "just a number," but think carefully: is it truly Continuous, or does it behave more like a **Discrete** or even a bounded **Categorical** scale in practice? Justify your answer.
3. Classify **"Delivery Time (hrs)"** — Discrete or Continuous? What real-world property of time makes it that type?
4. Classify **"Refunded"** — which Excel storage format does this map to, and is it Qualitative or Quantitative?
5. Now open Excel, type this table in, and format the **Rating** column as **Whole Number** using Data Validation (Data → Data Validation → Whole Number, between 1 and 5). Try typing `4.5` into a Rating cell — what happens, and why does that reinforce your answer to question 2?
