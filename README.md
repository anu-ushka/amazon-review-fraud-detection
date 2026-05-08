# Amazon Review Analysis: Detecting Suspicious Patterns

## Overview
This project focuses on analyzing Amazon food reviews to identify suspicious review behavior using a rule-based scoring approach. The analysis was performed on a large-scale review dataset to study patterns related to ratings, review characteristics, and user activity.

The project involved data cleaning, feature engineering, exploratory analysis, and dashboard creation to better understand how suspicious reviews differ from normal reviews.

---

## Objectives
- Analyze review and rating patterns in Amazon review data
- Identify potentially suspicious reviews using heuristic indicators
- Build interactive dashboards for trend and behavior analysis
- Derive insights from review characteristics and user activity

---

## Dataset
The project uses the Amazon Fine Food Reviews dataset containing over 500,000 reviews.

The dataset includes:
- Review text
- Review summary
- Product and user identifiers
- Ratings
- Helpfulness metrics
- Timestamps

---

## Tools & Technologies
- Python (Pandas, NumPy)
- Tableau
- CSV / Excel

---

## Methodology

### Data Preprocessing
- Cleaned missing and inconsistent values
- Structured timestamp and review-related fields
- Prepared the dataset for analysis and visualization

### Feature Engineering
Several indicators were created to identify suspicious behavior, including:
- Extreme ratings (1-star and 5-star reviews)
- Very short reviews
- Excessive punctuation usage
- Repeated user activity
- Duplicate review patterns

### Suspicious Review Scoring
A rule-based scoring system was created by combining multiple suspicious indicators into a single fake score.

Higher scores indicate a higher likelihood of suspicious review behavior.

---

## Dashboards

### Overview Dashboard
Provides a high-level view of:
- Rating distribution
- Suspicious vs normal review ratio
- Review trends over time
- Key review metrics

### Analysis Dashboard
Focused on deeper suspicious behavior analysis:
- Fake score distribution
- Suspicious activity across ratings
- Review length comparison
- Feature-based suspicious patterns

---

## Key Insights
- Most reviews fall into lower suspicious score ranges
- Extreme ratings show comparatively higher suspicious activity
- Suspicious reviews tend to contain longer and more exaggerated content
- Multiple behavioral indicators contribute to suspicious review patterns

---
## Repository Structure
```
amazon-review-fraud-detection/
│
├── data/                 # Dataset link
├── notebook/             # Python / Kaggle analysis notebook
├── dashboards/           # Tableau dashboard screenshots & link
├── README.md
```
---

## Conclusion
This project demonstrates how analytical techniques and rule-based scoring can be used to identify suspicious patterns in large-scale review data. The analysis highlights how review behavior, rating trends, and content characteristics can help detect potentially unreliable reviews.
