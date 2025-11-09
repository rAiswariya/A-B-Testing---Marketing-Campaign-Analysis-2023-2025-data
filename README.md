# 📊 A/B Testing – Facebook vs AdWords Marketing Campaign Analysis

## 🧠 Business Problem
The objective of this project is to **maximize the return on investment (ROI)** from advertising campaigns by identifying which platform — **Facebook or AdWords** — delivers better results in terms of **clicks, conversions, and cost efficiency**.  
Through statistical A/B testing and exploratory analysis, we aim to determine which platform should receive higher budget allocation to optimize marketing performance.

## 🎯 Project Objectives
- Compare performance of **Facebook Ads** and **AdWords campaigns** using key marketing metrics.
- Evaluate **conversion rates, CTR (Click-Through Rate), and CPA (Cost per Acquisition)**.
- Conduct **hypothesis testing** to assess whether observed differences between the campaigns are statistically significant.
- Recommend the **optimal marketing platform** for future investment based on quantitative evidence.

## 📁 Dataset Overview
The dataset consists of ad campaign performance metrics from both platforms.  
Key features include:
- `Date` – Campaign run date  
- `Platform` – Facebook or AdWords  
- `Impressions` – Number of times ads were displayed  
- `Clicks` – Number of times ads were clicked  
- `Spent` – Total ad spend for the day  
- `Leads` / `Conversions` – Number of successful customer conversions  
- `Revenue` – Income generated from conversions  
- Derived metrics like `CTR`, `CPC`, and `ROI` were calculated for deeper comparison.

## 🔍 Analysis Performed
1. **Data Preprocessing**
   - Cleaned missing values and corrected data types.
   - Computed derived metrics (CTR, CPC, Conversion Rate, ROI).
2. **Exploratory Data Analysis (EDA)**
   - Compared spend and revenue trends between platforms.
   - Visualized performance metrics using Seaborn and Matplotlib.
3. **Statistical Testing**
   - Conducted **t-tests** and **proportion tests** to assess if differences in conversion and ROI were statistically significant.
4. **Correlation and Regression**
   - Used linear regression to understand factors influencing ROI.
   - Checked for relationships between spend, clicks, and conversions.
5. **Insights and Interpretation**
   - Identified patterns in ad performance and conversion efficiency.
6. **Recommendations**
   - Suggested data-driven strategies for optimizing ad allocation.

## 📈 Key Insights
- **Facebook Ads** exhibited higher click-through rates but also higher cost per acquisition.  
- **AdWords** achieved better conversion efficiency at a lower cost, leading to superior overall ROI.  
- Statistical tests confirmed that the ROI difference between the two platforms was **significant** (p < 0.05).  
- Seasonal trends influenced ad performance, with spikes during promotional periods.

## 🚀 Actionable Recommendations
- Reallocate budget proportionally toward **AdWords**, especially for performance-oriented campaigns.
- Use **Facebook Ads** for brand awareness and top-of-funnel engagement rather than conversions.
- Continue **A/B testing** with variations in creatives, target audience, and ad formats to refine strategy.
- Incorporate **time-based segmentation** to leverage periods of high conversion.

## 🧮 Technologies & Libraries Used
- **Python 3**
- **pandas**, **numpy** – Data processing and analysis  
- **matplotlib**, **seaborn** – Visualization  
- **scipy**, **statsmodels** – Hypothesis testing  
- **scikit-learn** – Regression and evaluation metrics  

## ⚙️ How to Run the Project
1. Clone the repository:  
   ```bash
   git clone https://github.com/<your-username>/A-B-Testing-Marketing-Campaign-Analysis.git
   cd A-B-Testing-Marketing-Campaign-Analysis
   ```

2. Install the dependencies:  
   ```bash
   pip install -r requirements.txt
   ```

3. Launch the notebook:  
   ```bash
   jupyter notebook A_B_Tesing_Marketing_Campaign_Analysis.ipynb
   ```

## 📊 Results Summary
| Metric | Facebook | AdWords | Winner |
|:--------|:----------|:---------|:---------|
| Click-Through Rate (CTR) | Higher | Moderate | Facebook |
| Conversion Rate | Lower | Higher | AdWords |
| Cost per Acquisition (CPA) | Higher | Lower | AdWords |
| ROI | Moderate | Higher | AdWords |

✅ **Final Verdict:** AdWords is more cost-effective and delivers a better ROI.

## 👩‍💻 Author
**Aiswariya Ramachandran**  
Analytical professional skilled in leveraging data to drive marketing and business insights.

---
