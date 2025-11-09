# A/B Testing – Facebook vs AdWords Marketing Campaign Analysis
### Comparing platform performance to optimize ad spend and conversions

---

## **Introduction**
This project compares the performance of **Facebook Ads** and **Google AdWords** using a real A/B testing dataset. The analysis quantifies which platform drives better **clicks, conversions, and cost-efficiency**, enabling data-driven budget allocation decisions for marketing teams.

**Key highlights of the project:**  
- Detailed **Exploratory Data Analysis (EDA)** to uncover platform-wise trends and delay drivers.  
- **Feature engineering** to compute derived metrics such as CTR, CPC, Conversion Rate, and CPA.  
- **Hypothesis testing** (t-tests and proportion tests) to evaluate statistical significance of observed differences.  
- **Regression analysis** to identify factors influencing conversions and cost metrics.  
- Performance evaluation using **CTR, Conversion Rate, Avg CPC, and CPA**.

**SEO Keywords:** facebook vs adwords, a/b testing, marketing analytics, conversion rate optimization, CTR analysis, CPA evaluation, hypothesis testing, regression analysis


---

## **Live App**
No live web app is included for this project. The analysis and results are available in the Jupyter Notebook: `A_B_Tesing_Marketing_Campaign_Analysis.ipynb`

---

## **Visual Representations**

### **1. Click-Through Rate (CTR) by Platform**
![CTR by Platform](Images/ctr_by_platform.png)

### **2. Conversion Count by Platform**
![Conversion Count by Platform](Images/conversions_by_platform.png)

### **3. Spend vs Conversions**
![Spend vs Conversions](Images/spend_vs_conversions.png)

### **4. Time-based Trend of Clicks and Conversions**
![Trend of Clicks and Conversions](Images/trends_clicks_conversions.png)

> Note: Save the generated plots from the notebook into the `Images/` folder with the exact filenames above if you want them displayed on GitHub.

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
* Open `A_B_Tesing_Marketing_Campaign_Analysis.ipynb` in [Google Colab](https://colab.research.google.com/) or locally in Jupyter Notebook.  
* Ensure the dataset file `A_B_testing_dataset.csv` is in the project root (same folder as the notebook).

4. **Run the Notebook**
* Execute all cells to reproduce EDA, metric calculations, hypothesis tests, and regression analysis.

---

## **Results & Summary**

The following platform-level metrics were computed from the dataset:

| Metric | Facebook | AdWords | Notes |
|:-------|:--------:|:-------:|:------|
| Impressions | 2,152,031 | 4,771,438 | Total ad views across dataset |
| Clicks | 44,196 | 60,128 | Total clicks recorded |
| Conversions | 11,975 | 5,933 | Completed conversions |
| CTR | 0.0205 | 0.0126 | Clicks / Impressions |
| Avg CPC | ₹3.5437 | ₹2.0747 | Weighted avg cost-per-click |
| Conversion Rate (conv/click) | 0.271 | 0.0987 | Fraction of clicks that converted |
| CPA | ₹13.08 | ₹21.03 | Avg cost per acquisition |

**Interpretation & Recommendation:**  
- **Facebook** demonstrates a higher **CTR** and a substantially higher **conversion rate** (≈0.271) compared to AdWords (≈0.0987).  
- **Facebook also delivers a lower CPA (₹13.08) versus AdWords (₹21.03).**  
- Based on these metrics, **Facebook** is the recommended platform for conversion-focused ad spend in this dataset, while AdWords can be leveraged for broader reach depending on campaign goals.  
- Statistical tests performed in the notebook (t-tests / proportion tests) support the significance of these differences — consult the notebook for p-values and test details.

---

## **Known Issues**

* **External signals missing:** Weather, competitor activity, and precise audience overlap are not included and could affect attribution.  
* **Revenue not available:** The dataset lacks explicit revenue per conversion, so ROI calculations are limited; recommendations rely on CPA and conversion efficiency.  
* **Causal limits:** Observational A/B allocation and potential confounders mean causal inference should be drawn carefully.

---

## **Contributing**

Contributions are welcome!

* Open issues for bugs, data quality problems, or suggested improvements.  
* Pull requests appreciated for adding segmentation analysis, revenue modeling, or additional visualizations.  
* Please ensure reproducibility and include updated `requirements.txt` entries for new libraries.

> Let’s refine this analysis together to help marketers make better budget-allocation decisions!

---

## **License**

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
