# 🎯 Lead Scoring & Conversion Prediction — X Education  
Machine Learning & AI Pipeline by Sahil Verma  
Built using A.I-enhanced Machine Learning techniques for modeling, analysis, and visualization.  

---

## 📘 Project Overview  
This project builds an **AI-powered Lead Scoring system** for **X Education**, an EdTech company.  
The aim is to **predict lead conversion likelihood** (whether a prospective lead becomes a paying customer) and provide **actionable business insights**.  

The pipeline covers everything from **data preprocessing, feature engineering, and dimensionality reduction** to **model building, evaluation, and interpretation**.  
The final output is a **Lead Scoring Function (0–100 scale)**, plus **business dashboards and recommendations** to boost conversions from **30% → 80%**.  

## 📈 Visualizations  
✅ Heatmap of correlations  
✅ PCA Explained Variance Curve  
✅ Confusion Matrix & ROC Curve  
✅ Precision-Recall Curve  
✅ Lead Funnel (Cold/Warm/Hot)  
✅ Coefficient Radar + Bar + Table Dashboard  
✅ Recommendations Dashboard  

📸 (Add Screenshots Here)

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

| Metric        | Business Meaning                                | Result |
|---------------|------------------------------------------------|--------|
| ⚖️ Accuracy   | Overall correctness of predictions             | ~78%   |
| 🎯 Precision  | % of predicted conversions that were correct   | ~75%   |
| 📢 Recall     | % of actual conversions successfully identified| ~82%   |
| 🔄 F1-Score   | Balance of precision & recall                  | ~78%   |
| 📈 ROC-AUC    | Discrimination ability of model                | ~85%   |

📍 (Insert Confusion Matrix, ROC Curve & Precision-Recall Curve visualizations here)

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

📍 (Insert Dashboard screenshots here)

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

---

