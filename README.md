# ✨ Digital Wellbeing User Analysis for MindEase App 

Mental Health & Social Media Balance Dataset | Python, Pandas, EDA 

<br>

## 📘 Project Overview
Performed **user behavior analysis** to *identify mental well-being patterns, high-risk user segments, and behavioral thresholds*, and translated them into **actionable recommendations** for a digital wellness product.  

![mindfulness-com-68Z1YR-A5b4-unsplash](https://github.com/user-attachments/assets/03f7e656-9847-41b4-8a21-139e3da4c692)

## 🎯 Business Problem 
MindEase is developing a Digital Balance Coach to provide personalized guidance on screen-time management, sleep hygiene, and digital detox habits.  

The product team lacks clarity on:  
* Which user groups are at the highest mental health risk
* Which behaviors most strongly influence stress, sleep, and well-being
* What thresholds should trigger personalized recommendations  

This analysis provides the behavioral and segment-level insights required for feature design and prioritization. 

<br>

## ❓ Business Questions  
As the data analyst, the goals are to:
1. Which behaviors (screen-time, sleep quality, addiction score) are most correlated with poor mental well-being?
2. Which user segments (age, gender, usage levels) show the highest risk of stress or low mood?
3. At what screen-time threshold do we see significant declines in mental well-being?
4. What patterns predict poor sleep or high stress?
5. What product recommendations can reduce mental health risks for each segment?

<br>

## 🔑 Key Findings

* Screen-time is the strongest driver of stress. Levels rise sharply after 6.5 hours/day.
* Sleep quality is tightly linked to stress. Poor sleep (<5) consistently predicts high stress.
* Exercise improves well-being. Users exercising ≥3 times/week show higher happiness and lower stress.
* Users with 0 disconnect days show higher stress and lower sleep.
* High-risk segments:  
    * Age 16–24: highest screen-time and stress
    * Users with >7 hrs/day screen-time
    * Low-activity users (<2 workouts/week)

<br>

## 📈 Business Recommendations

* Screen-time coaching: Trigger interventions when usage exceeds 6.5 hrs/day.
* Sleep routines: Provide wind-down tips and reduce night notifications for poor sleepers.
* Digital detox nudges: Encourage breaks for users with 0 disconnect days.
* Promote micro-activity nudges for low-exercise users.
* Activity boosters: Micro-activity reminders for users exercising <2x/week.
* Age-based personalization:  
    * 16–24: strict screen-time boundaries
    * 25–34: stress management
    * 35+: sleep optimization

<br>

# 🧰 Technical Details
This section outlines the tools, techniques, and step-by-step analysis workflow used to generate the project insights. 

<br>

## ⚙️ Dataset  
Source: Kaggle - [Mental Health & Social Media Balance Dataset](https://www.kaggle.com/datasets/prince7489/mental-health-and-social-media-balance-dataset)   
Scope : 500 users  
Key columns include:  
* Daily Screen Time (hrs)
* Sleep Quality (1–10)
* Stress Level (1–10)
* Exercise Frequency (per week)
* Days Without Social Media
* Happiness Index (1–10)
* Age, Gender, Platform


<br>

## 🧰 Tools & Techniques  

1. Python 3.10
2. Pandas, NumPy
3. Matplotlib, Seaborn
4. Correlation analysis
5. Segmentation analysis

<br>

##  ▶️ How to run the project  
1. Clone the Repository
```
git clone https://github.com/zaraaxdata/digital-wellness-app-analysis.git
cd digital-wellness-app-analysis
```
2. Create Environment
```
conda create -n eda_env python=3.10
conda activate eda_env
pip install -r requirements.txt
```
3. Launch Notebook
```
jupyter notebook
```

<br>

## 🔄 Analysis Steps  

1. **Data Inspection & Cleaning**  
  Verified data types, missing values, duplicates.
2. **Univariate Analysis**  
   Explored distributions of screen-time, stress, sleep, and exercise patterns.
3. **Bivariate Analysis**
   * Correlation heatmap
   * Screen-time vs stress
   * Sleep vs stress
   * Exercise vs happiness
   * Days without social media vs well-being etc..
4. **Segmentation Analysis**  
   * Age groups (16–24, 25–34, 35–44, 45+)
   * Gender-based behavior diffe
   * Screen-time risk tiers (low/medium/high)
5. **Answers to Business Questions**
   Converted patterns into actionable product recommendations.
   
<br>

## 🔖 Future Improvements
* Build Streamlit dashboard for product stakeholders
* Build Stress prediction model
* Build Recommendation engine

<br>
<br>

*If you find this project helpful, don’t forget to give a ⭐.*
