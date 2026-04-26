# Amazon Review Analysis: Detecting Suspicious Patterns

## Overview
This project analyzes Amazon food reviews to identify suspicious or potentially fake reviews using a rule-based scoring approach. The goal is to uncover patterns in user behavior, rating trends, and review characteristics.

---

## Objectives
- Detect suspicious reviews using heuristic signals  
- Analyze rating behavior and review patterns  
- Build interactive dashboards for insight generation  

---

## Tech Stack
- **Python** (Pandas, NumPy)  
- **Tableau** (Data Visualization)  
- **Excel / CSV** (Data Handling)  

---

## Dataset
- Amazon Fine Food Reviews Dataset (~500K records)  
- Includes: review text, rating, user ID, product ID, timestamps  

---

## Approach

### 1. Data Preprocessing
- Cleaned missing and duplicate values  
- Converted timestamps and structured data  

### 2. Feature Engineering
Created key indicators:
- Short Reviews  
- Extreme Ratings (1⭐ & 5⭐)  
- Excessive Exclamation Usage  
- High Review Frequency Users  
- Duplicate Reviews  

### 3. Fake Review Scoring
A rule-based score was assigned:


Fake Score = Sum of suspicious indicators


Higher score → Higher likelihood of suspicious behavior

---

## 📈 Key Insights
- Majority of reviews fall in low suspicious score ranges  
- Higher suspicious activity observed in **extreme ratings (1⭐ & 5⭐)**  
- Suspicious reviews tend to have **longer, exaggerated content**  
- Certain behavioral patterns strongly correlate with suspicious activity  

---

## Dashboards

### Overview Dashboard
- Total reviews & suspicious %  
- Rating distribution  
- Suspicious vs Normal split  
- Review trends over time  

### Analysis Dashboard
- Fake score distribution  
- Suspicious % by rating  
- Avg review length comparison  
- Feature contribution analysis  

---

## Live Dashboard
👉 

---

## Repository Structure

├── data/
├── notebook/
├── dashboards/
├── README.md


---

## Conclusion
This project demonstrates how simple heuristic-based methods can effectively identify suspicious patterns in large-scale review data, providing actionable insights for trust and quality analysis.

---
