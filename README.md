# Global Life Expectancy Analysis Using Statistical Analysis, Clustering & Time-Series Forecasting

## 📖 Project Overview
This project presents an end-to-end analytical study of **global life expectancy trends**, combining statistical analysis, dimensionality reduction, clustering, and forecasting to uncover key drivers of longevity and project future outcomes.

The analysis emphasizes **methodological rigor, interpretability, and uncertainty-aware forecasting**, making it suitable for academic evaluation as well as policy-oriented insights.

---

## 🎯 Objectives
- Identify key socioeconomic and healthcare factors influencing life expectancy  
- Statistically validate differences across development groups  
- Reduce feature redundancy caused by multicollinearity  
- Segment countries into meaningful health–development clusters  
- Forecast life expectancy trends with validated uncertainty bounds  
- Provide country-specific projections (India: 2025–2029)

---

## 🗂 Dataset
- **Source:** World Health Organization (WHO)
- **Scope:** Multiple countries across several years
- **Key Variables:**  
  Life expectancy, adult mortality, education, income composition, GDP, immunization coverage, disease prevalence, healthcare expenditure, population indicators

---

## 🧠 Methodology
1. **Exploratory Data Analysis (EDA)**  
   - Distribution analysis and correlation assessment  
2. **Statistical Inference (ANOVA)**  
   - Tested life expectancy differences across development groups  
3. **Multicollinearity Diagnostics (VIF)**  
   - Identified redundant predictors  
4. **Principal Component Analysis (PCA)**  
   - Reduced dimensionality and extracted latent health–development factors  
5. **Clustering Analysis**  
   - Elbow method, silhouette analysis, PCA-based visualization  
   - Identified three country clusters:
     - Low Health & Low Development  
     - Developing & Transitional Health  
     - High Health & High Development  
6. **Time-Series Forecasting (Prophet)**  
   - Country-level and cluster-level forecasting  
   - 95% and 99% prediction intervals  
7. **Model Validation**  
   - Interval coverage analysis  
   - MAE and MAPE evaluation  
   - External validation using WHO actual values  
8. **Country-Specific Projection**  
   - India life expectancy projection (2025–2029) with uncertainty bounds

---

## 📊 Key Results (High-Level)
- Strong associations between life expectancy and education, income composition, immunization coverage, and adult mortality
- Statistically significant life expectancy differences across development groups
- Clear and interpretable country clusters aligned with global development patterns
- Forecasting model achieved **high accuracy and reliability**, with strong interval calibration
- India’s life expectancy is projected to show a steady upward trajectory in the medium term

---

## 📈 Model Performance
- **Mean Absolute Error (MAE):** ~1.42 years  
- **Mean Absolute Percentage Error (MAPE):** ~1.93%  
- **95% Prediction Interval Coverage:** 100% (validation sample)

---

## 🛠 Tools & Technologies
- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  
- Prophet  
- XGBoost  

---

## 🔍 Key Learnings
- Importance of addressing multicollinearity before modeling  
- Value of combining statistical inference with machine learning  
- Role of uncertainty-aware forecasting in public health analysis  
- Benefits of cluster-based interpretation for policy insights  

---

## 📌 Future Scope
- Causal modeling using panel regression techniques  
- Ensemble forecasting approaches  
- Integration of environmental and policy indicators  
- Alignment with global development targets (e.g., SDGs)

---

## 👤 Author
**Durga Prasad Govindas**  
Data Analytics & Applied Statistics  

Feel free to explore the analysis, raise issues, or suggest improvements.
