![Project poster](https://github.com/user-attachments/assets/3eaf58f8-b654-4717-9b41-6d486a788928)

# 🎯 Lead Scoring & Conversion Prediction
Machine Learning & AI Pipeline by Sahil Verma  
Built using A.I-enhanced Machine Learning techniques for modeling, analysis, and visualization.  

![Python](https://img.shields.io/badge/Python-3.9-blue?logo=python) 
![Jupyter Notebook](https://img.shields.io/badge/Notebook-Jupyter-orange?logo=jupyter) 
![Plotly](https://img.shields.io/badge/Visualization-Plotly-blueviolet?logo=plotly) 
![AI](https://img.shields.io/badge/Powered%20By-A.I-green) 
![License](https://img.shields.io/badge/License-MIT-lightgrey) 
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

---

## 📘 Project Overview  
This project builds an **AI-powered Lead Scoring system** for **X Education**, an EdTech company.  
The aim is to **predict lead conversion likelihood** (whether a prospective lead becomes a paying customer) and provide **actionable business insights**.  

The pipeline covers everything from **data preprocessing, feature engineering, and dimensionality reduction** to **model building, evaluation, and interpretation**.  
The final output is a **Lead Scoring Function (0–100 scale)**, plus **business dashboards and recommendations** to boost conversions from **30% → 80%**.  

## 📈 Visualizations 

✅ Lead Funnel (Cold/Warm/Hot) 
<img width="1404" height="690" alt="Screenshot 2025-09-06 191614" src="https://github.com/user-attachments/assets/4cf942e6-d0f5-4c8e-bc82-a036ddf68a12" />

---
✅ PCA reduced features correlations
<img width="1000" height="700" alt="newplot" src="https://github.com/user-attachments/assets/1ff123da-24da-48bd-b889-6a13520be0c1" />

---
✅ PCA Explained Variance Curve
<img width="1102" height="360" alt="newplot (4)" src="https://github.com/user-attachments/assets/6bc72917-c772-4013-8642-bc423c461d4c" />

---
✅ Confusion Matrix & ROC Curve
<img width="1360" height="612" alt="Screenshot 2025-09-06 192932" src="https://github.com/user-attachments/assets/8b4f58fd-d483-4cb2-9608-63156c0df397" />

---
✅ Precision-Recall Curve
<img width="1375" height="779" alt="Screenshot 2025-09-06 192048" src="https://github.com/user-attachments/assets/2d5e42c2-b43e-4728-a41e-3cedda418c8e" />

---
✅ Coefficient Radar + Bar + Table Dashboard
<img width="1340" height="474" alt="Screenshot 2025-09-06 191136" src="https://github.com/user-attachments/assets/8ec6a37e-640d-446d-9d7a-28a8874f543e" />
<img width="500" height="400" alt="newplot (2)" src="https://github.com/user-attachments/assets/59492f8c-2d97-41f2-9821-03cddd17e63f" />
<img width="500" height="400" alt="newplot (1)" src="https://github.com/user-attachments/assets/feecbdf9-5b44-4b64-a373-00d732711139" />

---
✅ Recommendations Dashboard  
<img width="1437" height="780" alt="Screenshot 2025-09-06 191437" src="https://github.com/user-attachments/assets/08942846-42de-450b-a3ab-e81aea1ba034" />
<img width="1102" height="650" alt="newplot (5)" src="https://github.com/user-attachments/assets/b5ea33f6-4505-44f0-a1fc-20284b0b8149" />

---

## ▶️ How to Run This Project  

1. Clone the repository  
2. Install dependencies:  
   ```bash
   pip install -r requirements.txt
   
---

## 🎯 Project Goals  
- Clean & preprocess CRM lead dataset with 35+ features  
- Encode categorical variables & handle missing values  
- Apply **feature reduction** (Variance Threshold, Correlation Filtering, PCA)  
- Train & evaluate **Logistic Regression (Baseline Model)**  
- Measure performance with **Accuracy, Precision, Recall, F1, ROC-AUC**  
- Build **Lead Scoring Function (0–100)**  
- Create **business dashboards** with funnel analysis, coefficient interpretation, and recommendations  
- Deliver **insights to improve conversion beyond 30%**  

---

## ⚙️ Tools & Technologies Used  

| Category            | Tools / Libraries |
|---------------------|-------------------|
| Language            | Python |
| Data Analysis       | Pandas, NumPy |
| Visualization       | Plotly, Matplotlib, Seaborn |
| Machine Learning    | Scikit-learn (Logistic Regression, PCA) |
| Documentation       | Jupyter Notebook, Markdown, Word (.docx), PowerPoint (PPT) |

---

## 🔍 AI & Machine Learning Techniques Applied  

| Technique | Purpose |
|-----------|---------|
| Variance Thresholding | Remove low-variance features |
| Correlation Filtering | Drop highly correlated predictors |
| PCA | Dimensionality reduction (retain 95% variance) |
| One-Hot Encoding | Convert categorical variables |
| Logistic Regression | Baseline predictive model |
| Class Weights | Handle imbalanced target distribution |
| Lead Scoring Function | Convert probabilities → scores (0–100) |
| Interactive Dashboards | Business-ready visualization |

---

## 📊 Key Evaluation Metrics  

| Metric        | Business Meaning                                |  Result  |
|---------------|-------------------------------------------------|----------|
| ⚖️ Accuracy   | Overall correctness of predictions             | ~90.33%   |
| 🎯 Precision  | % of predicted conversions that were correct   | ~86.10%   |
| 📢 Recall     | % of actual conversions successfully identified| ~89.33%   |
| 🔄 F1-Score   | Balance of precision & recall                  | ~87.68%   |
| 📈 ROC-AUC    | Discrimination ability of model                | ~96.20%   |

<img width="544" height="472" alt="Screenshot 2025-09-06 192139" src="https://github.com/user-attachments/assets/6ec101ca-c0c2-44cc-b6bf-0d2c3599eae3" />

---

## 🔑 Business Interpretation of Coefficients  
- ⬆️ **High Time Spent on Website** → Strong indicator of conversion  
- ⬆️ **Direct & Google Search Leads** → High likelihood of conversion  
- ⬇️ **Leads with low engagement** → Low conversion probability  

📍 (Insert Feature Importance Bar Chart + Coefficient Table here)

---

## 🎨 Business Dashboard  

- 📊 **Funnel Analysis** (Cold → Warm → Hot Leads)  
- 📈 **Radar + Bar + Table** for coefficient interpretation  
- 📌 **Recommendations Dashboard** (Sales + Marketing + Engagement strategies)  
<img width="1000" height="700" alt="newplot" src="https://github.com/user-attachments/assets/312ec439-c128-41ee-ac5d-ff58cf0ec1cb" />

---

## 💡 Key Business Recommendations  

1. 🎯 **Sales Execution** → Prioritize Hot Leads with senior reps, automate Cold Leads.  
2. 📈 **Marketing Optimization** → Double down on top-performing channels, reduce spend on weak ones.  
3. 🤝 **Customer Engagement** → Strengthen follow-ups, reminders, webinars, testimonials.  

👉 Together, these actions can push conversions from **30% → 80%**.  

---

## ✅ Key Challenges & Solutions  

| Challenge | Impact | Solution Implemented |
|-----------|--------|-----------------------|
| Missing values across categorical & numeric features | Risk of biased model | Applied median (numeric) & mode (categorical) imputations |
| Highly imbalanced target (more “Not Converted”) | Model predicted mostly negative class | Used `class_weight="balanced"` in Logistic Regression |
| Overfitting due to redundant features | Misleading coefficient interpretation | Applied Variance Threshold + Correlation Filtering + PCA |
| Logistic Regression convergence warnings | Training instability | Increased `max_iter=2000` and used `lbfgs` solver |
| Visualization overlap (labels & titles) | Poor readability for stakeholders | Redesigned layouts with Plotly subplots, shadow borders, and gradient themes |

## 🙋 Author  
**Name:** Sahil Verma  
**Role:** Data Scientist & Machine Learning Enthusiast  
**Focus:** Building professional-grade, explainable AI/ML models with actionable insights  

---
