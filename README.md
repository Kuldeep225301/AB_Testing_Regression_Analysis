# Advertising Efficiency Analysis: Facebook vs. AdWords Campaigns

An A/B testing and statistical analysis project comparing a full year of Facebook Ads and Google AdWords campaign performance to identify the more cost-effective advertising platform — using Python.

---

## 📌 Business Problem

As a marketing agency, our primary objective is to maximize the return on investment (ROI) for our clients' advertising campaigns. We ran two parallel ad campaigns throughout 2019 — one on **Facebook** and one on **AdWords** — and needed to determine which platform delivers better results in terms of clicks, conversions, and overall cost-effectiveness, so budget could be allocated to the stronger platform.

##  Research Question

**Which ad platform — Facebook or AdWords — is more effective in terms of conversions, clicks, and overall cost-effectiveness?**

---

##  Data Description

The dataset contains **365 daily records** (Jan 1 – Dec 31, 2019) comparing the performance of the Facebook and AdWords campaigns.

| Feature | Description |
|---|---|
| `Date` | Calendar date of the observation |
| `Ad Views` | Number of times the ad was displayed |
| `Ad Clicks` | Number of clicks received on the ad |
| `Ad Conversions` | Number of conversions resulting from the ad |
| `Cost per Ad` | Total cost incurred running the campaign that day |
| `CTR (Click-Through Rate)` | Ratio of clicks to views |
| `Conversion Rate` | Ratio of conversions to clicks |
| `CPC (Cost per Click)` | Average cost incurred per click |

---

## 🛠️ Tools & Technical Aspects

- **Language:** Python
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-Learn
- **Techniques:** A/B Testing, Hypothesis Testing, Regression Analysis

---

## 🔍 Approach

- Conducted A/B testing analysis for a marketing agency on annual Facebook and AdWords campaigns, analyzing daily data and KPIs to demonstrate the cost-effectiveness of the superior platform through statistical evidence — enabling data-driven decisions for clients.
- Applied hypothesis testing to confirm that the observed performance gap between platforms was statistically significant, not random daily variation.
- Used regression analysis to model the relationship between advertising spend and conversions, confirming a significant long-term relationship between cost and conversion outcomes.
- Compared Cost per Click (CPC) and conversion rate jointly (not in isolation) to judge true cost-effectiveness rather than just raw click/view volume.

---

## 📈 Key Results

| Outcome | Result |
|---|---|
| Higher ROI Platform | Identified via comparative analysis of clicks, conversions & cost-efficiency |
| Conversion Improvement | **30% increase** in conversions after reallocating budget |
| Cost Reduction | **15% reduction** in overall advertising cost |
| Statistical Significance | Confirmed via hypothesis testing |
| Cost–Conversion Relationship | Confirmed via regression analysis |

---

## 💡 Key Insights

- The performance gap between Facebook and AdWords was consistent across the year, not a one-off fluctuation.
- A platform with more clicks isn't automatically better — CPC and conversion rate together determine real cost-effectiveness.
- Hypothesis testing gave statistical confidence to act on the recommendation, rather than relying on a visual trend alone.
- Regression analysis confirmed a measurable, significant relationship between ad spend and conversions, supporting predictable budget planning.
- Reallocating budget toward the stronger platform translated into a **30% increase in conversions** and a **15% reduction in cost** — a direct, measurable ROI improvement for the client.

---

## 🚀 How to Use

1. Clone this repository.
2. Install dependencies: `pip install pandas numpy matplotlib seaborn scikit-learn`
3. Load the 2019 campaign dataset (Facebook & AdWords).
4. Run the analysis notebook/script to reproduce the EDA, A/B test, hypothesis test, and regression analysis.

---

## 📁 Repository Structure

```
├── AB_Testing_Analysis.ipynb   # Full analysis: EDA, A/B testing, hypothesis testing, regression
├── data/                       # Facebook & AdWords 2019 campaign dataset
└── README.md                   # Project documentation
```

---

## 🏷️ Tags

`Python` `A/B Testing` `Hypothesis Testing` `Regression Analysis` `Marketing Analytics` `Pandas` `Scikit-Learn` `Data Analysis`

---

## 📬 Connect

If you found this project useful, feel free to ⭐ the repo or connect with me for feedback and collaboration!
