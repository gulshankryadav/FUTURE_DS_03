<h1 align="center">📊 College Event Feedback Analysis – Task 3</h1>

<p align="center">
  <img src="https://img.shields.io/badge/Python-Sentiment%20Analysis-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Data%20Visualization-Analytics-0077B5?style=for-the-badge&logo=googlecolab&logoColor=white" />
  <img src="https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge" />
</p>

<p align="center"><b>Analyzing Google Form event feedback using NLP (VADER Sentiment Analysis), ratings analytics & visual storytelling in Python.</b></p>

---

## 🎥 Project Video Demo

<p align="center">
  <a href="https://drive.google.com/file/d/1SuXjOJBZ5vBSw3aH4iVAkuNXoFXr3e6y/view">📌 Video Link Coming Soon</a>
</p>

---

## 🚀 Project Overview

This analysis helps colleges identify how students feel about campus events by studying textual feedback and ratings.

📌 Key Goals:

* Extract insights from survey data
* Find strengths & improvement areas
* Convert feedback into actionable decisions

---

## 🧹 Data Cleaning & Preparation

✔ Removed duplicates & missing values
✔ Standardized column names
✔ Converted ratings into numeric format
✔ Extracted comments for NLP

```python
import pandas as pd
from nltk.sentiment.vader import SentimentIntensityAnalyzer
```

---

## 🧠 Sentiment Analysis Using NLP

Leveraged `SentimentIntensityAnalyzer` to classify comments into:

* **Positive** 😄
* **Neutral** 😐
* **Negative** 😞

Outputs Generated:

* Sentiment Polarity Score
* Sentiment Label Column
* Sentiment Distribution Bar Chart

---

## 📊 Rating-Based Analytics

Analyzed multiple event satisfaction parameters including:

* Food Quality
* Management
* Timing
* Engagement
* Promotion & Communication

📈 Visuals Include:

* Bar Charts
* Rating Distribution Plot
* Correlation Heatmap

> (Add your screenshots here from PyCharm / Jupyter)

---

## 🔍 Insights & Recommendations

| Insight                          | Action Recommendation                  |
| -------------------------------- | -------------------------------------- |
| Food satisfaction low            | Improve vendor selection & hygiene     |
| Timing delays                    | Better scheduling & logistics planning |
| Low participation in some events | Stronger promotion & marketing         |
| Neutral engagement               | Add more fun + interactive activities  |

---

## 🛠 Tools & Technologies Used

| Tool                   | Purpose                    |
| ---------------------- | -------------------------- |
| Python                 | Data processing & analysis |
| Pandas                 | Cleaning & manipulation    |
| Matplotlib + Seaborn   | Charting & visualization   |
| NLTK – VADER           | Sentiment scoring          |
| Google Colab / PyCharm | Notebook execution         |

---

## 📁 Files in This Repository

📌 `Sentiment_Result.xlsx` — Final dataset with sentiment labels
📌 `Task3_Feedback_Analysis.ipynb` — Complete notebook

---

## ⭐ What I Learned

* Data cleaning techniques
* Natural Language Processing in Python
* Data visualization & story-driven reporting
* Transforming feedback into insights

---

## 🤝 Connect With Me

**Gulshan Yadav**
Aspiring Data Analyst | Python & Power BI Enthusiast

<p align="left">
  <a href="https://www.linkedin.com/in/gulshan-kumar-b703bb322/"><img src="https://img.shields.io/badge/LinkedIn-Connect-blue?style=for-the-badge&logo=linkedin"></a>
  <a href="mailto:m.gkyadav2006@gmail.com"><img src="https://img.shields.io/badge/Email-Contact-red?style=for-the-badge&logo=gmail"></a>
</p>

---

## ⭐ Support This Project

If this helped you, please ⭐ star the repo!
