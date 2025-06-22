
# 🎬 Investigating the TMDb Movies Dataset

## 📊 Project Overview  
This project is part of the **Level 3 Data Science & AI** course in the **Digital Egypt Cubs Initiative (DECI)** by the **Ministry of Communication and Telecommunications**. In this assignment, I analyzed the TMDb Movies dataset, explored its characteristics, and extracted insights using Python.

## 📁 Dataset Information  
The dataset used is **TMDb Movie Data**, which has been cleaned from the original **TMDb 5000 Movie Dataset** available on Kaggle. It contains information about movies such as titles, budgets, revenues, genres, release dates, and user ratings.

## 🧰 Tools and Libraries  
- **Python**  
- **NumPy**  
- **Pandas**  
- **Matplotlib**  

## 🎯 Project Goals  
- Perform exploratory data analysis (EDA) on the dataset  
- Identify trends and relationships between different movie attributes  
- Visualize key findings using graphs and charts  

## 📦 Files in This Repository  
- **`Investigate_a_Dataset.ipynb`** – The Jupyter Notebook with the analysis  
- **`tmdb-movies.csv`** – The dataset used in the project  
- **`Investigate_a_Dataset.html`** – An exported version of the analysis for easy viewing  

## 🔑 Key Findings  
1. **Top Revenue Movies**  
   - The **top 50 highest revenue-adjusted movies** frequently feature actors like **Orlando Bloom, Daniel Radcliffe, Rupert Grint, and Emma Watson**.  
   - The most common genres among top revenue movies are **Action** and **Adventure**.  
   - If someone wants to create a high-profit movie, these insights can help guide casting and genre choices.

2. **Popular Genres**  
   - **Adventure movies** have the highest average **popularity, budget, and revenue**.  
   - **Documentary movies** have the lowest averages in all three categories.

## ⚠️ Limitations  
- **Missing Data**: Many movies have `0` values for **budget** and **revenue**, affecting analysis accuracy.  
- **IMDBPy Package**: Used for retrieving missing data, but it was **slow and incomplete** for large datasets.

## 📚 References  
- **IMDBPy**: [IMDBPy GitHub Repository](https://github.com/RyanMarcus/imdbpy)  
- **Internet searches** for additional functions  
