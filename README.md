# Technical Assesment

Task: Job Title Classification

Objective: 
Build a solution that assigns the single best-fitting category to each job title from the provided datasets.

---

## Objective

Build a solution that assigns the single best-fitting category to each job title from the provided datasets.

---

## Datasets

**`job_titles.parquet`** — Job titles to classify

| Column | Type | Notes |
|---|---|---|
| `JOB_TITLE` | string | Title to classify |

**`categories.parquet`** — Target categories

| Column | Type | Notes |
|---|---|---|
| `JOB_CATEGORY_CODE` | string | Unique category code |
| `JOB_CATEGORY` | string | Category |
| `JOB_CATEGORY_DESCRIPTION` | string | Category description |
---

## Expected Output

Save as `predictions.parquet` (or `predictions.csv`) with the following columns:

| Column | Description |
|---|---|
| `JOB_TITLE` | From input |
| `RELEVANT_JOB_CATEGORY_CODE` | code based on the predicted category |
| `RELEVANT_JOB_CATEGORY` | Predicted category name |

---

