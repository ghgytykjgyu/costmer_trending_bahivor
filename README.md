# costmer_trending_bahivor
describe costmer trending bahivor

# Consumer Shopping Trends Analysis 2026

An end-to-end exploratory data analysis (EDA) of consumer shopping behavior, covering 11,789 customers across digital habits, spending patterns, brand loyalty, and geographic purchasing trends.

---

## Project Overview

This project analyzes a real-world retail dataset to uncover actionable insights about:
- How consumers split spending between online and in-store channels
- Which demographic segments spend the most
- How digital behavior (internet usage, tech savviness) correlates with shopping preference
- City-tier differences in purchasing patterns

---

## Dataset

| Feature | Detail |
|---|---|
| Records | 11,789 consumers |
| Variables | 30 columns |
| Avg Total Spend | ₹150,217 per customer |
| Shopping Preference | Store (86.9%) / Online (10%) / Hybrid (3.1%) |
| City Tiers | Tier 1, Tier 2, Tier 3 (balanced split) |

---

## Key Findings

- **86.9%** of customers prefer in-store shopping — a signal for retailers to invest in physical experience
- Online vs. store spend is nearly equal (₹74K vs ₹75K), suggesting omnichannel strategies are critical
- Customers average **24.7 online orders/month** — loyalty programs would have high ROI
- Only **10%** shop online → massive growth opportunity with better UX and payment trust
- **Tech savvy score avg = 5.5/10** — apps and interfaces must stay simple and intuitive
- Hybrid shoppers show the highest environmental awareness — a segment for sustainable marketing

---

## Tech Stack

```python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
import plotly.express as px
import plotly.graph_objects as go
from scipy import stats
```

---

## Project Structure

```
consumer-shopping-trends/
│
├── Consumer_Shopping_Trends.ipynb   # Main analysis notebook
├── Consumer_Shopping_Trends_2026.csv  # Dataset
└── README.md
```

---

## Analysis Breakdown

### 1. Data Cleaning & Feature Engineering
- Imputed missing values
- Created: `total_spend`, `online_spend_pct`, `digital_score`, `age_group`, `income_group`

### 2. Exploratory Data Analysis (EDA)
- Distribution of age, income, gender, city tier
- Shopping preference mix (pie + bar charts)
- KPI dashboard with 10 key metrics

### 3. Digital Behavior Analysis
- Internet hours, social media usage, smartphone years
- Tech savvy & payment trust scores
- Composite digital score per customer

### 4. Spend Analysis
- Online vs. store spend distributions
- Mean/median comparisons per segment
- Income group spend breakdown

### 5. Behavioral Radar Chart
- Multi-dimensional comparison: brand loyalty, impulse buying, eco awareness, discount sensitivity
- Segmented by shopping preference (Store / Online / Hybrid)

### 6. City Tier Analysis
- Shopping preference mix per tier
- Average spend (online vs. store) across Tier 1, 2, 3

---

## Business Impact

| Insight | Action |
|---|---|
| 86.9% prefer in-store | Invest in in-store experience & staff |
| Online spend ≈ store spend | Balance marketing budget across channels |
| 24.7 orders/month avg | Build loyalty & rewards programs |
| Low online adoption (10%) | Improve digital UX & payment trust |
| City Tier 1 highest spend | Prioritize expansion in metro cities |

---

## Author

Data Analyst — Python, Pandas, Plotly, Seaborn, Machine Learning
Open to freelance projects in data analysis, dashboards, and business intelligence.
  
