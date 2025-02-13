# World Cup Football Data Analysis: A Comparative Study of Men's & Women's Tournaments  

## **Project Overview**  
This project explores the **2019 FIFA Women's World Cup** and the **2018 FIFA Men's World Cup**, analyzing key trends, match statistics, and scoring patterns. The analysis is focused on **comparing team performances, goal distribution, and match outcomes** between the two tournaments. The study provides insights into **scoring trends, strategic differences, and competition intensity** in international football.  

## **Dataset Details**  
- **Source:** [Kaggle - UCL, FC Barcelona (LaLiga), World Cup, and Euros Data](https://www.kaggle.com/datasets/shivamb/netflix-shows)  
- **Primary Data Files:**
  - **2019_Womens_WorldCup.json** – Match details from the 2019 FIFA Women's World Cup.  
  - **FIFA_WorldCup2018Men.json** – Match data from the 2018 FIFA Men’s World Cup.  
- **Contents:** The dataset includes match scores, team statistics, and key performance indicators (KPIs).  

## **Key Research Questions & Findings**  
### **1. What is the average number of goals per game in the Women's and Men's World Cups?**  
- The **Women’s World Cup had a higher average goal count per match (2.81 goals)** than the **Men’s World Cup (2.64 goals)**, indicating a more attacking style of play.  

### **2. What are the most common scorelines in the Women's and Men's World Cups?**  
- **Most common scoreline in Women’s WC:** **(1-2)**  
- **Most common scoreline in Men’s WC:** **(0-1)**  

### **3. How are match scorelines distributed in both tournaments?**  
- The Women’s tournament had **more high-scoring games**, whereas the Men’s tournament had **a larger number of closely contested, low-scoring matches**.  

### **4. How do team performances and match distributions compare?**  
- The **USA Women’s National Team scored the most goals (26)** in the Women’s tournament.  
- **Belgium had the highest number of home wins (4)** in the Men’s World Cup.  
- The busiest match day was **Saturday in the Men’s World Cup**, with **12 matches played**.  

## **Data Cleaning & Transformation**  
- **Converted JSON files to structured Pandas DataFrames** for better analysis.  
- **Flattened nested data structures** for efficient querying.  
- **Handled missing values and reformatted dates** for consistency.  

## **Methodology & Workflow**  
1. **Loaded data from JSON files** and converted them into structured Pandas DataFrames.  
2. **Grouped data by year, tournament, and team performance** for comparative analysis.  
3. **Computed key statistics** such as average goals per match, common scorelines, and team success rates.  
4. **Visualized findings using Matplotlib & Seaborn** for intuitive interpretation.  
5. **Exported structured insights to CSV files for further analysis.**  

## **Technology & Tools Used**  
- **Python (Pandas, NumPy, Matplotlib, Seaborn)** – Data cleaning, processing, and visualization.  
- **Jupyter Notebook** – Interactive data analysis.  
- **JSON Handling** – Extracted and processed nested data structures.  
- **CSV Reports** – Final structured output files for comparative insights.  


