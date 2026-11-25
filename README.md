
# 📈 Revenue Optimization: Hypothesis Prioritization & A/B Testing

---

## 📋 Table of Contents

- [Project Description](#project-description)
- [Objectives](#objectives)
- [Results](#results)
- [Tools & Technologies](#tools--technologies)
- [Technical Skills Developed](#technical-skills-developed)
- [Future Improvements](#future-improvements)
- [How to Run](#how-to-run)

---

## 📖 Project Description

This project focuses on **revenue optimization** for a large online retailer through a structured, data-driven decision-making process.

The project is divided into two critical stages:

- **Hypothesis Prioritization:** Using scoring frameworks (ICE and RICE) to rank business hypotheses.
- **A/B Test Execution and Analysis:** Conducting a rigorous A/B test to validate the actual impact of changes on conversion rates and revenue.

---

## 🎯 Objectives

- Strategically prioritize 9 business hypotheses.
- Demonstrate how the **Reach** parameter in the RICE framework changes priorities compared to ICE.
- Evaluate the A/B test based on statistically significant differences.
- Ensure data stability and handle outliers to support realistic analysis.

---

## 📊 Results

- **Strategic Prioritization:** Ranked hypotheses, highlighting the impact of the Reach parameter.
- **Business Decision:** Identified a statistically significant difference in conversion rates in favor of one group.
- **Data Stability:** Evaluated the convergence of cumulative metrics.
- **Outlier Treatment:** Defined technical thresholds (95th and 99th percentiles) to identify extreme orders.

---

## 🛠️ Tools & Technologies

- **Programming Language:** Python
- **Main Libraries:**
  - Pandas (data manipulation)
  - Matplotlib and Seaborn (data visualization)
  - SciPy (statistical inference)
- **Methodologies:**
  - ICE and RICE prioritization frameworks
  - Cumulative Revenue and Conversion Rate Analysis
  - Mann-Whitney U Test for non-parametric data
- **Development Environment:** VS Code / Jupyter Notebook

---

## 📚 Technical Skills Developed

- **Decision-Making Frameworks:** Applying the RICE framework to balance Impact, Confidence, Effort, and Reach.
- **A/B Testing Analysis:** Monitoring cumulative metrics to avoid premature conclusions.
- **Non-Parametric Statistics:** Applying the Mann-Whitney U test to analyze data containing outliers.
- **Anomaly Detection:** Using percentiles to filter noise and focus on actual behavioral patterns.

---

## 🚀 Future Improvements

- **Cohort Analysis:** Integrating LTV metrics to evaluate the long-term sustainability of conversion improvements.
- **Results Segmentation:** Comparing results across devices (Mobile vs. Desktop).
- **Dashboard Automation:** Developing real-time visualizations to monitor p-values and group differences.

---

## ▶️ How to Run

1. Clone the repository.
2. Install the dependencies:

   ```bash
   pip install pandas matplotlib seaborn scipy
   ```

3. Open the notebook `revenue-optimization-hypothesis-prioritization-ab-testing.ipynb` in Jupyter Notebook.
4. Execute the cells sequentially.

---

*Project developed as part of Module 9 of the Data Analytics program.*
