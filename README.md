# flyrank-machine-learning_week_2_ml_task_framing

# ML-03 — Frame Your Lane as an ML Task

This repository contains my solution for **ML-03: Frame Your Lane as an ML Task** from the FlyRank Machine Learning Internship (Week 2).

## Assignment Overview

The objective of this assignment is to frame my chosen lane as a machine learning problem before building any models. The notebook explains the ML task, target variable, success metric, unit of analysis, and why machine learning is more suitable than a fixed rule-based approach.

## My ML Task

- **Task Type:** Ranking (Learning-to-Rank)
- **Domain:** Search Relevance
- **Target/Proxy:** Clicked / Relevance Score
- **Success Metric:** NDCG@10
- **Business Goal:** Improve search result ranking by predicting the relevance of each query-document pair.

## Notebook Contents

The notebook includes the following sections:

1. My Lane as an ML Task
2. Target or Proxy
3. Success Metric
4. Unit of Analysis (with real dataframe)
5. Why ML Beats a Fixed Rule
6. Self-Check

## Unit of Analysis

Each row in the dataset represents a **single query-document pair**.

Example:

| Query | Document | Clicked |
|-------|----------|----------|
| running shoes | Nike Pegasus | 1 |
| running shoes | Leather Belt | 0 |

The model learns to rank documents according to their predicted relevance.

## Why Machine Learning?

Traditional rule-based ranking systems rely on manually designed rules such as keyword matching or BM25 scores. However, search relevance depends on multiple interacting features, including:

- Query-document similarity
- Historical click behavior
- Product popularity
- Semantic relevance
- User interactions

Machine learning automatically learns these relationships from data, producing more accurate and adaptable rankings.

## Technologies Used

- Python
- Pandas
- Jupyter Notebook
- FlyRank Starter Dataset

## Repository Structure

```
.
├── work/
│   └── notebooks/
│       └── w02_ml_task_framing.ipynb
├── data/
├── scripts/
└── README.md
```

## Learning Outcomes

Through this assignment, I learned how to:

- Identify the correct machine learning task.
- Define a meaningful prediction target.
- Select an appropriate evaluation metric.
- Understand the unit of analysis.
- Connect machine learning outputs to real business decisions.
- Explain why ML provides better solutions than fixed rules.

## How to Run

1. Clone the repository.

```bash
git clone <repository-url>
cd <repository-name>
```

2. Install the required dependencies.

```bash
pip install -r requirements.txt
```

3. Open the notebook.

```bash
jupyter notebook work/notebooks/w02_ml_task_framing.ipynb
```

4. Run all cells.

## Assignment Deliverable

- ✅ Completed notebook:
  `work/notebooks/w02_ml_task_framing.ipynb`

## Author

**Raunak Pantawane**

FlyRank Machine Learning Internship – Week 2
