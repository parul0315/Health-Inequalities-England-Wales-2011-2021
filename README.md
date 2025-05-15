# Health Inequalities in England and Wales (2011–2021)

This project presents a comprehensive analysis of regional health disparities across England and Wales using data from the 2011 and 2021 UK Census. By integrating interactive visual analytics in Tableau with predictive modeling in Python, the study uncovers socio-spatial health trends and projects health outcomes for the year 2030 using Bayesian Ridge Regression.

---

## Project Objectives

- **Visualize and compare** self-reported health outcomes across local authorities in 2011 and 2021.
- **Identify associations** between health status and key social determinants such as education, economic activity, household deprivation, and unpaid care.
- **Forecast 2030 health outcomes** using historical census data to support evidence-based regional health planning.

---

## Tools & Technologies

- **Data Visualization:** Tableau  
- **Programming & Modeling:** Python  
- **Libraries:** `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`  
- **Dimensionality Reduction:** PCA, t-SNE, UMAP  
- **Predictive Modeling:** Bayesian Ridge Regression

---

## Methodological Challenges

- **Cross-Year Standardization:** Aligning and normalizing differently structured census datasets from 2011 and 2021.  
- **Health Data Projection:** Estimating future health distributions based on limited historical data points.  
- **Visual Integration:** Designing dashboards to communicate complex multivariate patterns interactively and intuitively.

---

## Key Insights

### Regional Health Dynamics (2011–2021)

- Significant **geographic variation** was observed in changes to self-reported “Very good health.”
- Regions with **higher educational attainment** and **lower deprivation levels** consistently reported better health outcomes.
- Increased **economic inactivity** and **unpaid care responsibilities** were correlated with poorer health in multiple regions.

### 2030 Health Projections

A Bayesian Ridge Regression model was trained on local authority-level health metrics from 2011 and 2021 to forecast self-reported health outcomes in 2030.

- Local authorities with improving health indicators are expected to maintain positive trends.
- Areas exhibiting persistent health decline are projected to experience further deterioration.
- These projections offer a **data-driven foundation** for targeted health interventions and policy design at the sub-national level.

---

## Interactive Dashboard

Explore the full Tableau dashboard and interact with projections, comparisons, and spatial trends:

[View Dashboard on Tableau Public](https://public.tableau.com/shared/7FNZSZ87Z?:display_count=n&:origin=viz_share_link)

---

## Repository Contents

- `health_inequality_analysis.ipynb` – Python notebook containing data preprocessing, PCA/UMAP visualizations, and 2030 projections  
- `Dashboards.twbx` – Tableau packaged workbook containing interactive dashboards  
- `README.md` – Project documentation

---

## Conclusion

This project demonstrates the effectiveness of combining **visual analytics** with **predictive modeling** to uncover and interpret long-term public health trends. The integration of Bayesian regression for forecasting provides a practical tool for informing **regional public health strategy** and addressing systemic inequalities across England and Wales.

---

## Author & Contact

Developed as part of a postgraduate **Visual Analytics coursework project** using publicly available UK census data (2011 & 2021).

**Parul Nagar**  
Email: parulnagar1245@gmail.com 
LinkedIn: www.linkedin.com/in/parul-nagar-244894202

