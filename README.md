# Real Estate Data Analysis & Price Prediction

This project analyzes a real estate dataset to uncover pricing patterns and evaluate the relationship between property features—primarily size—and market price.  
The project includes data exploration, visualization, correlation analysis, and a baseline regression model for price estimation.

---

# Project Workflow

- Data loading and initial exploration  
- Missing value and data type inspection  
- Feature relationship analysis through visualization  
- Correlation analysis  
- Linear regression modeling (Size → Price)  
- Model evaluation and trend interpretation  

---

# Key Insights


- Property size (sqft) shows the highest correlation with price  
- Price distribution is right-skewed, indicating a small number of high-value properties  
- Larger properties display a consistent upward pricing trend  
- A simple regression model provides a practical baseline for price estimation  
- Detected and removed duplicate rows  
- Identified and filtered outliers using IQR  
- Verified and inspected data types  
- The model explains ~54% of price variance (R² = 0.54), showing property size as a strong pricing indicator.  
- Cleaned dataset by applying IQR outlier removal, increasing reliability of insights.



---

# Technologies & Libraries

- Python (Pandas, NumPy)
- Seaborn & Matplotlib for visualization  
- Scikit-Learn for machine learning  
- Google Colab for development  
- GitHub for version control  

---

# Dataset Overview

| Field | Description |
|------|-------------|
| Price | Sale price of the property |
| Size | Property size in square feet |
| Bedrooms | Number of bedrooms |
| Bathrooms | Number of bathrooms |
| Location | City or area of the listing |
| Status | Listing availability/status |

---

# How to Run

Open and run the notebook file:

 `analysis.ipynb`

Compatible with Google Colab and Jupyter Notebook.


---

# Author

Elif Cetin  
Master of Science in Informatics  
University of Louisiana at Lafayette  

---

