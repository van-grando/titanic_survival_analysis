
# Titanic Survival Analysis

This project explores the survival patterns of Titanic passengers using data cleaning, feature engineering, and visual insights.

## Objective
To answer the question:  
**Which categories of passengers were most likely to survive the Titanic disaster?**

## Workflow
1. **Data Cleaning** – handled missing values (Age, Embarked) and dropped irrelevant columns  
2. **Feature Engineering** – created FamilySize, AgeGroup, FareGroup  
3. **Exploratory Data Analysis (EDA)** – visualized survival rates by gender, class, age, fare, embarkation port, and family size  
4. **Insights and Conclusion** – summarized key survival patterns  

## Key Insights
- Women survived more often than men, especially in higher classes  
- Children (0–12 years) had higher survival chances  
- First Class passengers had the best survival rates regardless of gender  
- Passengers with small families (2–4 members) were more likely to survive  
- Passengers embarking from Cherbourg had better survival rates  

## Tools and Libraries
- Python 3.x  
- Pandas  
- NumPy  
- Seaborn and Matplotlib  

## How to Run
1. Clone this repository  
   ```bash
   git clone https://github.com/YOUR_USERNAME/titanic-survival-analysis.git
   cd titanic-survival-analysis
   ```  
2. Install dependencies  
   ```bash
   pip install -r requirements.txt
   ```  
3. Open the notebook  
   ```bash
   jupyter notebook titanic_survival_analysis.ipynb
   ```  

## Files
- `titanic_survival_analysis.ipynb` → Full notebook with cleaning, feature engineering, visualizations, and insights  
- `requirements.txt` → Dependencies to run the notebook  

This is a mini case study for practicing data cleaning, feature engineering, and visual storytelling.
