# **CausalX** v0.1.0: Uplift modeling for marketing optimization

## 1. Project overview
This project implements **CausalX**, an framework designed to optimize marketing campaigns using Causal Inference. Unlike traditional predictive modeling, CausalX identifies the **incremental impact** (Uplift) of a treatment, allowing for precise customer targeting and ROI maximization.

## 2. Key features
- **Double Machine Learning (DML):** Uses LightGBM and EconML to isolate treatment effects from confounding variables.
- **Heterogeneous Treatment Effects (CATE):** Estimates individual-level uplift to differentiate between 'Persuadables', 'Sure Things', and 'Lost Causes'.
- **Robustness Testing:** Integrates automated Placebo Refutation tests to validate causal assumptions.
- **Decision Engine:** Translates statistical scores into financial decisions based on unit costs and expected returns.

## 3. Technology stack
- **Python** (Pandas, NumPy, Matplotlib, Seaborn)
- **DoWhy:** For causal identification and refutation.
- **EconML:** For advanced CATE estimation (Causal Forests).
- **Graphviz:** For Directed Acyclic Graph (DAG) visualization.

## 4. Business impact demonstration
Using the Kevin Hillstrom dataset, CausalX demonstrated an **estimated incremental profit of $46,491.86** by filtering out customers who would have purchased regardless or who were negatively impacted by the campaign.
