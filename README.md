# A/B Testing – Facebook vs AdWords Marketing Campaign Analysis
### Comparing platform performance to optimize ad spend and conversions

---

## **Introduction**
This project compares the performance of **Facebook Ads** and **Google AdWords** using a real-world A/B testing dataset.  
The goal is to identify which platform delivers better **clicks**, **conversions**, and **cost-efficiency**, helping marketing teams make informed budget allocation decisions.

**Key highlights of the project:**  
- Performed **Exploratory Data Analysis (EDA)** to compare ad performance across platforms.  
- Computed derived metrics: **CTR (Click-Through Rate)**, **CPC (Cost per Click)**, **Conversion Rate**, and **CPA (Cost per Acquisition)**.  
- Conducted **hypothesis testing** to check for significant differences in performance metrics.  
- Visualized campaign efficiency and engagement trends using Python visualization libraries.  
- Interpreted key insights to recommend the best-performing advertising platform.

**SEO Keywords:** A/B testing, Facebook Ads, AdWords, marketing analytics, CTR, conversion rate, CPA, cost analysis, digital marketing optimization.

---

## **Complete Analysis:**
All analysis, visualizations, and results can be explored in the Jupyter Notebook:  
[A_B_Testing_Marketing_Campaign_Analysis.ipynb](A_B_Testing_Marketing_Campaign_Analysis.ipynb)


---

## **Installation & Usage**

1. **Clone the repository**
```bash
git clone https://github.com/<your-username>/A-B-Testing-Facebook-vs-AdWords.git
cd A-B-Testing-Facebook-vs-AdWords
```

2. **Set up the environment**
```bash
pip install -r requirements.txt
```

3. **Open the Notebook**
* Launch `A_B_Tesing_Marketing_Campaign_Analysis.ipynb` in [Google Colab](https://colab.research.google.com/) or Jupyter Notebook.  
* Ensure the dataset `A_B_testing_dataset_balanced.csv` is in the same directory as the notebook.

4. **Run the Notebook**
* Execute all cells to perform EDA, compute KPIs, conduct hypothesis tests, and view insights.

---

## **Results & Summary**

The following platform-level metrics were computed from the dataset:

| Metric | Facebook | AdWords | Notes |
|:-------|:---------:|:--------:|:------|
| Impressions | 2,952,716 | 4,805,139 | Total ad views |
| Clicks | 44,125 | 66,810 | Total clicks recorded |
| Conversions | 10,712 | 7,681 | Completed conversions |
| CTR | 0.0149 | 0.0139 | Clicks / Impressions |
| Avg CPC | ₹3.35 | ₹3.00 | Weighted average cost-per-click |
| Conversion Rate (conv/click) | 0.2428 | 0.1150 | Fraction of clicks that converted |
| CPA | ₹13.78 | ₹26.09 | Average cost per acquisition |

### **Interpretation & Recommendation**
- **Facebook** shows a slightly higher **CTR (1.49%)** and a significantly higher **Conversion Rate (24.3%)** than **AdWords (11.5%)**.  
- **Facebook’s CPA (₹13.78)** is nearly **half** of **AdWords (₹26.09)**, making it much more cost-efficient.  
- Based on these results, **Facebook** is the recommended platform for **conversion-focused** campaigns.  
- **AdWords** may still be effective for broader reach or awareness-based campaigns.  
- Statistical hypothesis testing (t-tests and proportion tests) confirmed that these differences are **statistically significant**.

Complete summary in [AB-Testing-Marketing-Campaign-Analysis-Report.pdf](AB-Testing-Marketing-Campaign-Analysis-Report.pdf)

---

## **Known Issues**
- **Revenue data** is not available; ROI analysis is inferred via CPA and conversion rate.  
- **External factors** like ad creatives, demographics, and time-of-day effects are not modeled.  
- **Further optimization** could include segmentation by audience or region to refine platform strategy.

---

## **Contributing**
Contributions are welcome!

- Report issues or suggest improvements through the **Issues** tab.  
- Submit pull requests for adding new visualizations, analyses, or metrics.  
- Please ensure that added code is well-documented and reproducible.

> Let’s work together to deepen data-driven marketing insights and improve decision-making!

---

## **License**
This project is licensed under the **MIT License**.  
See the [LICENSE](LICENSE) file for details.
