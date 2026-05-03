# -Stroke-Risk-Analysis
A data analysis project exploring clinical, demographic, and lifestyle factors associated with stroke risk using exploratory data analysis (EDA).

---

## 📊 Dataset

The dataset used in this project was obtained from Kaggle:

https://www.kaggle.com/datasets/fedesoriano/stroke-prediction-dataset

It contains demographic, clinical, and lifestyle information related to stroke risk.

---

## 🎯 Objective

The goal of this project is to identify key factors associated with stroke occurrence through exploratory data analysis.

---

## 🧹 Data Preparation

Basic data cleaning was performed, including handling missing values (e.g., BMI imputation) and removing irrelevant features (e.g., ID column).

---

## 🔍 Key Insights

- Age is the strongest factor associated with stroke, with higher proportions observed in older patients.
- Clinical conditions such as hypertension (approx. 13%) and heart disease (approx. 17%) show a strong association with stroke.
- Higher glucose levels are associated with stroke, with a noticeable shift in distribution.
- Former smokers show the highest proportion of stroke (7.9%), although differences between groups are moderate.
- Socio-demographic variables (work type, marital status, residence) show weak or indirect associations, often explained by age.

---

## ⚠️ Limitations

- The dataset is highly imbalanced, with a low proportion of stroke cases (~4%).
- Some variables contain missing or ambiguous values (e.g., BMI, smoking status "Unknown").
- The analysis is based on observational data, so no causal relationships can be established.
- Potential confounding variables (such as age) may influence observed associations.

---

## 🧾 Conclusion

The analysis highlights age and clinical conditions (hypertension, heart disease, and glucose levels) as the strongest factors associated with stroke risk. Lifestyle factors such as smoking also show moderate association, while socio-demographic variables appear to have limited or indirect influence.

These findings are consistent with existing medical knowledge and highlight the importance of considering multiple variables when assessing stroke risk.

---

## 🚀 Next Steps

- Develop a predictive machine learning model for stroke risk.
- Perform multivariate analysis to control for confounding variables (especially age).
- Explore feature engineering to improve predictive performance.
- Validate findings using additional datasets.

---

## 🛠️ Tools Used

- Python (Pandas, NumPy)
- Data visualization (Matplotlib, Seaborn)
- Google Colab

---

## 📁 Repository Contents

- `stroke_analysis.ipynb` → Full exploratory data analysis notebook
