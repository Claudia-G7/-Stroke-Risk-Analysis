# Stroke Risk Analysis – Exploratory Data Analysis

This project performs an exploratory data analysis (EDA) on a healthcare dataset to identify key factors associated with stroke occurrence.

The objective is to explore demographic, clinical, and lifestyle variables to understand their relationship with stroke risk and extract meaningful insights.

---

## Dataset

The dataset used in this project is publicly available on Kaggle:

https://www.kaggle.com/datasets/fedesoriano/stroke-prediction-dataset

It contains 5,110 patient records and includes demographic, clinical, and lifestyle-related variables.

---

## Objective

The main goal of this analysis is to identify patterns and relationships between patient characteristics and stroke occurrence, supporting a better understanding of potential risk factors.

---

## Data Preparation

Data preprocessing steps included:

- Handling missing values in BMI using imputation
- Removing irrelevant columns (e.g., ID)
- Verifying data types and consistency

The dataset contains both numerical and categorical variables, including a highly imbalanced target variable (stroke), with approximately 4% positive cases.

---

## Exploratory Data Analysis

The analysis was conducted using visual and statistical methods:

- Countplots for categorical variables
- Boxplots for continuous variables vs stroke
- Crosstab analysis for proportion comparison
- Distribution analysis for key features

---

## Key Insights

- Age is the strongest factor associated with stroke, with significantly higher proportions in older patients.
- Clinical conditions such as hypertension (13%) and heart disease (17%) show a strong association with stroke.
- Higher glucose levels are associated with stroke, with a noticeable shift in distribution.
- Body mass index (BMI) does not show a clear separation between stroke and non-stroke groups, suggesting a weak or non-linear relationship in this dataset.
- Former smokers show the highest proportion of stroke (7.9%), although differences between groups are moderate.
- Socio-demographic variables (work type, marital status, residence) show weak or indirect associations, often explained by age.

---

## Limitations

- The dataset is highly imbalanced (~96% no stroke, ~4% stroke)
- Some variables contain missing or ambiguous values (e.g., smoking status "Unknown")
- Observational data prevents causal inference
- Confounding variables (especially age) may influence several relationships

---

## Conclusion

This analysis identified age, hypertension, heart disease, and glucose levels as the variables most strongly associated with stroke occurrence.

Lifestyle factors such as smoking also show a moderate association, while BMI does not present a clear independent relationship with stroke in this dataset.

Socio-demographic variables appear to have limited or indirect influence, often mediated by age.

Overall, the findings are consistent with clinical knowledge and highlight the importance of combining multiple risk factors when assessing stroke risk rather than relying on single variables.

---

## Next Steps

- Build a predictive model for stroke risk
- Handle class imbalance using resampling techniques
- Perform feature importance analysis

## Tools Used

- Python (Pandas, NumPy)
- Data Visualization (Seaborn, Matplotlib)
- Jupyter Notebook (Google Colab)

---

## Repository Contents

- `stroke_analysis.ipynb` → Full exploratory data analysis notebook
- `README.md` → Project documentation
