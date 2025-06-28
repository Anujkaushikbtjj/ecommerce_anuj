# Customer Purchase Behavior Analysis in E-Commerce

## Overview
This project explores customer behavior in an e-commerce setting using transaction-level data. The analysis investigates patterns in purchasing, payment preferences, churn, and customer demographics to generate actionable business insights. The project also prepares data for potential machine learning use cases such as churn prediction.

---

## Data Source

The dataset used in this project was sourced from Kaggle:  
**[E-Commerce Data Science Project – Input Dataset](https://www.kaggle.com/code/yassmen/data-science-project/input)**  
Uploaded by **Yassmen Eid**.

_This dataset is used for educational and non-commercial purposes._

---

## Project Structure

- `ecommerce_submission_anuj.ipynb` – The main notebook containing the complete analysis, visualizations and insights.
- `clean_data.csv` – Cleaned dataset prepared for feature engineering and analysis.
- `submission_plots_ecommerce/` – All visual outputs saved as `.png` and `.pdf` for reference.
- `ecommerce project proposal anuj` - Project proposal file.
- `ecommerece summary anuj` - Summary of findings, insights and business recommendations.
- `README.md` – Project documentation.

---

## Key Objectives

- Understand customer purchase behavior by gender, age group
- Explore payment method preferences across demographics and over time
- Analyze customer churn patterns
- Generate actionable business recommendations based on data insights

---

## Tools & Technologies

- **Python**
  - `pandas` – Data manipulation
  - `seaborn` / `matplotlib` – Data visualization
  - `datetime` – Date formatting
- **Jupyter Notebook**
- **Data**: 250,000 transaction records with 49,000+ unique customers

---

## Major Insights

- **Gender Parity**: Male and female customers behave similarly in terms of purchases, returns, and churn.
- **Age Behavior**: Older customers (51–70) tend to spend slightly more per transaction.
- **Churn**: ~20% churn rate distributed uniformly across age and gender.
- **Payments**: Credit Card, PayPal, and Cash are used nearly equally; no clear preference trend by age or gender.

---

## Visual Analysis

Key visualizations include:
- Purchase distribution histogram
- Gender-wise comparison of churn, revenue, orders
- Age group distribution and behavior
- Payment method preferences (overall, by age, gender, year)

All visualizations are saved in the `submission_plots_ecommerce/` folder.

---

## Recommendations

- Deploy **loyalty and engagement programs** across all segments
- Use **RFM segmentation** to identify and target at-risk customers
- Maintain **equal support for all payment methods**
- Target **older age groups** with premium offers and **younger groups** with bundled discounts

---

## Future Work

- Extend to **product category analysis** to understand churn/product links
- Build a **predictive churn model** using behavioral features
- Create a **Tableau dashboard** for stakeholder-friendly reporting

---

## Author

**Anuj Anuj**  
_Data Analyst | Biotechnology Researcher | Data Storyteller | Scientific Writer | Tutor_

anuj.kaushik.btjj@gmail.com
www.linkedin.com/in/anujanujbioanalyst  

---

## License

This project is for educational and portfolio use. Feel free to fork, adapt and reference with attribution.






