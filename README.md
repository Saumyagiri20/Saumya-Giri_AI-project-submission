# 🧠 Employee Sentiment Analysis – Final Project

This project analyzes an unlabeled dataset of employee emails to detect sentiment, evaluate engagement, and identify potential flight risks. It uses NLP and machine learning techniques to uncover hidden patterns in employee communications.

##  Project Overview

- Dataset: Employee emails dataset (`test.csv`)
- Language: Python
- Tools: Jupyter Notebook, TextBlob, Matplotlib, Seaborn, Scikit-learn, Pandas
- Objective: Analyze sentiment, rank employees, identify flight risks, and build a predictive model for future sentiment trends.

## ✅ Summary Highlights

### 🔝 Top Three Positive Employees
1. kayne.coulter@enron.com  
2. don.baughman@enron.com  
3. eric.bass@enron.com 

### 📉 Top Three Negative Employees
1.   rhonda.denton@enron.com  
2.   bobette.riner@ipgdirect.com  
3.   johnny.palmer@enron.com 

### 🚨 Flight Risk Employees (≥ 4 negative emails in 30 days)
- rhonda.denton@enron.com
- eric.bass@enron.com
- lydia.delgado@enron.com
- bobette.riner@ipgdirect.com
- johnny.palmer@enron.com
- patti.thompson@enron.com
- sally.beck@enron.com
- don.baughman@enron.com
- john.arnold@enron.com

---

## 💡 Key Insights & Recommendations

- 📈 **Employee Engagement**: Positive messaging was most prevalent in Q4, suggesting higher engagement during that period.
- ⚠️ **Flight Risk Monitoring**: Several employees showed consistent negative sentiment, with patterns suggesting disengagement.
- 📊 **Predictive Modeling**: A regression model showed a moderate correlation between message length and sentiment score.
- 📌 **Recommendation**: Deploy real-time sentiment monitoring to proactively address employee concerns.

---

## 📁 Project Structure

- `Employee Sentiment Analysis.ipynb`: Main notebook with all tasks implemented
- `visualizations/`: Charts for EDA, ranking, sentiment trends, and risk visualization
- `README.md`: This summary file
- `final_report.docx`: Detailed report with methodology, results, and commentary
- `requirements.txt`  :  Required Python packages

## ✅ Deliverables Summary

- ✔️ Sentiment labeling using TextBlob
- ✔️ EDA and interactive charts
- ✔️ Employee monthly sentiment scores
- ✔️ Ranking and flight risk detection
- ✔️ Regression model for future predictions
- ✔️ Final visualizations saved
- ✔️ Report and documentation

---

> 💼 Prepared by: **Saumya Giri**