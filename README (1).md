# Lead Conversion Optimization for X Education

## Overview

X Education aims to improve its **lead conversion rate from 30% to 80%** by identifying high-potential leads. This project implements a **Logistic Regression model** to assign **Lead Scores (0-100)** and optimize sales efforts.

## Project Structure

```
├── data/               # Dataset used for training & evaluation
├── notebooks/          # Jupyter Notebooks for analysis & modeling
├── src/                # Python scripts for preprocessing & modeling
├── results/            # Model outputs, lead scores, and visualizations
├── README.md           # Project documentation
```

## Features

- **Data Preprocessing**
  - Handled missing values
  - Encoded categorical variables
  - Standardized numerical data
- **Logistic Regression Model**
  - Training & Testing (80-20 split)
  - Feature importance analysis
  - Lead scoring system
- **Model Evaluation**
  - Accuracy, Precision, Recall, F1-score
  - ROC-AUC score & confusion matrix
  - Lead Score distribution visualization

## Key Insights

- **Top 3 Factors Affecting Conversion:**
  1. **Total Time Spent on Website** – Higher engagement leads to higher conversion.
  2. **Lead Source** – Some channels generate better-quality leads.
  3. **Lead Origin** – The method of lead generation impacts conversion likelihood.

## Business Recommendations

- **During High-Conversion Phases:**

  - Prioritize leads **scoring above 80**.
  - Automate **email & SMS follow-ups** before direct calls.
  - Assign interns to handle **warm leads** and escalate top leads.
  - Introduce **time-sensitive offers** to encourage conversion.

- **During Low-Engagement Phases:**

  - Focus only on **leads scoring above 90**.
  - Use **email & WhatsApp engagement** instead of direct calls.
  - Shift efforts toward **upselling, referrals, and strategic marketing**.

 

## Results

- The **Logistic Regression model** effectively prioritizes leads.
- Sales teams can improve efficiency by **focusing on high-scoring leads**.
- Data-driven decision-making helps **increase conversion rates** while optimizing resources.
