# 🚗 Salifort Motors – Employee Retention Prediction Project  
**A Google Advanced Data Analytics Capstone Project**  
*Predicting employee turnover and uncovering key factors influencing retention at Salifort Motors.*

---

## 📘 Overview  
Employee turnover has been rising at **Salifort Motors**, leading to significant costs in recruitment, training, and lost productivity.  
The leadership team wanted to answer a crucial question:  

> **“What’s likely to make an employee leave the company?”**

As a data analyst, my goal was to explore the HR dataset, identify key factors influencing attrition, and build predictive models that empower HR to take data-driven retention decisions.

---

## 🧩 Problem Statement  
Salifort Motors aims to improve employee retention by identifying factors that drive turnover.  
The company invests heavily in recruiting and upskilling employees, but increasing attrition rates were impacting financial performance and team morale.

---

## 🧠 Approach  
Since the target variable `left` is categorical, both statistical and machine learning models were explored:

- **Logistic Regression** (baseline)
- **Decision Tree**
- **Random Forest**
- **XGBoost**

The **Random Forest model** demonstrated the highest accuracy and reliability, slightly outperforming other models.

---

## ⚡ Impact  
The final model predicts employee departure with high accuracy and identifies the most influential features behind attrition.  
These insights enable HR and leadership to:

- Design fair workload and compensation structures  
- Recognize and reward long-term employees  
- Address dissatisfaction trends proactively  
- Optimize performance and retention policies  

---

## 💡 Key Insights & Recommendations  

✔ Cap the number of projects each employee handles to avoid burnout.  
✔ Promote or recognize employees with **4+ years** tenure; investigate dissatisfaction patterns in this group.  
✔ Compensate fairly for long working hours or revise workload expectations.  
✔ Clarify **overtime policies** to ensure transparency and employee trust.  
✔ Foster open team discussions to strengthen company culture and communication.  
✔ Avoid linking high performance ratings exclusively with 200+ work hours.  
✔ Introduce proportional rewards for contribution and consistent effort.  

---

## 📊 Exploratory Data Analysis Highlights  

### Dataset Overview  
![Dataset Info](Images/Dataset%20tables%20information%20(dataframr%20image).png)

### Correlation Heatmap  
![Correlation Heatmap](Images/Correlation%20between%20data%20(heatmap).png)

### Satisfaction Level vs Tenure  
![Satisfaction vs Tenure](Images/Satisfaction%20lvl%20vs%20time%20spend%20in%20company%20(box%20plot%20amf%20bar%20plot).png)

### Salary vs Tenure (Attrition Trends)  
![Salary vs Tenure](Images/salry%20vs%20tenure%20(greater%20and%20less%20than%205%20yrs)%20(bar%20plots).png)

### Work Hours vs Performance (Burnout Zone)  
![Work Hours vs Evaluation](Images/Monthly%20hrs%20by%20last%20evaluation%20(scatter%20plot).png)

### Average Monthly Hours vs Projects vs Attrition  
![Avg Monthly Hours vs Projects](Images/Avg%20mnthly%20hrs%20vs%20prjts%20vs%20left%20(box%20plot%20and%20barchart).png)

---

## ⚙️ Model Development & Evaluation  

**Models Built:**  
- Logistic Regression  
- Decision Tree  
- Random Forest  
- XGBoost
- 

### Feature Importance (Random Forest)
![Feature Importance](Images/Random%20forest%20feature%20importance.png)

**Top Predictors of Attrition:**  
`last_evaluation`, `number_project`, `tenure`, `overworked`, `work_accident`, and `salary_low`.

---

## 🎯 Achievements & Contribution  

- Built and compared multiple predictive models to forecast employee turnover.  
- Achieved **96% accuracy** and **0.93 AUC**, identifying the top attrition drivers.  
- Designed a **Tableau dashboard** for HR leadership to visualize and act on insights.  
- Delivered clear, data-driven recommendations for improving employee satisfaction and retention.  

---

## 📈 Tableau Dashboard  
The final insights were visualized in an **interactive Tableau dashboard**, allowing HR stakeholders to:  
- Filter by **department**, **salary**, or **tenure**  
- View predicted attrition probabilities  
- Explore satisfaction, workload, and project trends  

🖥️ Dashboard file:  
`Visualisation/Salifort Motors project Dashboard.twb`

---

## 🧰 Tools & Technologies  

**Languages:** Python, SQL  
**Libraries:** Pandas, NumPy, Scikit-learn, XGBoost, Matplotlib, Seaborn  
**Visualization:** Tableau, Power BI  
**Concepts:** EDA, Feature Engineering, Predictive Modeling, Statistical Analysis, A/B Testing  

---

## 🧾 Folder Structure  

```

Salifort-Motors-customer-churn-project/
│
├── Dataset/
│   ├── salifort_feature_importance.csv
│   ├── salifort_turnover_dashboard.csv
│
├── Images/
│   ├── Dataset tables information (dataframr image).png
│   ├── Correlation between data (heatmap).png
│   ├── Satisfaction lvl vs time spend in company (box plot amf bar plot).png
│   ├── salry vs tenure (greater and less than 5 yrs) (bar plots).png
│   ├── Monthly hrs by last evaluation (scatter plot).png
│   ├── Avg mnthly hrs vs prjts vs left (box plot and barchart).png
│   ├── Random forest feature importance.png
│
├── Lab/
│   ├── Jupyter notebooks or code files
│
├── Visualisation/
│   ├── Salifort Motors project Dashboard.twb
│
├── Course 7 PACE strategy document.docx
├── Executive summary templates.pptx
└── README.md

```

---

## 📬 Contact  

👤 **Steffin Thomas**  
📧 steffinthomas12@gmail.com  
🌐 [LinkedIn](www.linkedin.com/in/steffin-thomas-b85549260)  
💼 [Portfolio](https://steffinthomas.com)
