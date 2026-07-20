# 📱 Google Play Store Data Analysis 

## 📌 Project Overview

This project analyzes the Google Play Store dataset to uncover trends in app categories, user ratings, installs, pricing models, and user engagement. The analysis focuses on transforming raw data into meaningful business insights through data cleaning, exploratory data analysis (EDA), and data visualization.

The project was developed using Python and its core data analysis libraries: Pandas, NumPy, Matplotlib, and Seaborn.

---

## 🎯 Project Objectives

- Clean and preprocess the Google Play Store dataset.
- Perform exploratory data analysis (EDA).
- Identify trends in app categories and installs.
- Analyze user ratings and engagement.
- Compare Free and Paid apps.
- Generate actionable business insights using visualizations.

---

## 🛠️ Tools & Libraries

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 📂 Dataset

**Dataset:** Google Play Store Apps Dataset

The dataset contains information about Android applications available on the Google Play Store, including:

- App Name
- Category
- Rating
- Reviews
- Size
- Installs
- Type (Free/Paid)
- Price
- Content Rating
- Genres
- Last Updated

---

## 🧹 Data Cleaning

The following preprocessing steps were performed:

- Removed duplicate records
- Handled missing values
- Removed invalid ratings
- Converted Reviews to numeric format
- Converted Installs into integer values
- Converted Price into numeric format
- Converted Size into MB
- Converted Last Updated into datetime format
- Created a clean dataset for analysis

---

## 📊 Exploratory Data Analysis (EDA)

The project answers the following business questions:

1. Which app category has the highest number of apps?
2. What is the distribution of app ratings?
3. Which categories have the highest total installs?
4. What is the percentage of Free vs Paid apps?
5. Which are the Top 10 Most Installed Apps?
6. Which are the Top 10 Most Reviewed Apps?
7. Do Paid Apps Have Better Ratings Than Free Apps?
8. Which Content Rating is Most Common?
9. Is There a Relationship Between Reviews and Ratings?
10. What is the relationship between numerical features? (Correlation Analysis)

---

## 📈 Visualizations

The project includes multiple visualizations such as:

- Horizontal Bar Charts
- Bar Charts
- Pie Charts
- Histogram
- Box Plot
- Scatter Plot
- Correlation Heatmap

---

## 💡 Key Business Insights

- The **Family** and **Game** categories contain the highest number of applications.
- Free apps dominate the Google Play Store.
- Reviews and installs have a strong positive relationship.
- A small number of applications account for the majority of installs.
- Paid apps represent only a small portion of the marketplace.
- Most applications are designed for the **Everyone** content rating.
- User engagement is reflected through high review counts rather than installs alone.

---

## 📁 Project Structure

```
Google_PlayStore_Analysis/
│
├── data/
│   └── googleplaystore.csv
│
├── images/
│   ├── apps_by_category.png
│   ├── top_categories_installs.png
│   ├── top_categories_average_rating.png
│   ├── free_vs_paid_bar.png
│   ├── free_vs_paid_pie.png
│   ├── top_10_installed_apps.png
│   ├── top_10_reviewed_apps.png
│   ├── free_vs_paid_rating_distribution.png
│   ├── reviews_vs_ratings.png
│   └── correlation_heatmap.png
│
├── Google_PlayStore_Analysis.ipynb
├── googleplaystore_cleaned.csv
├── Business_Insights.md
├── requirements.txt
└── README.md
```

---

## 🚀 How to Run the Project

1. Clone the repository

```bash
git clone https://github.com/your-username/Google_PlayStore_Analysis.git
```

2. Navigate to the project folder

```bash
cd Google_PlayStore_Analysis
```

3. Install the required libraries

```bash
pip install -r requirements.txt
```

4. Open the notebook

```bash
jupyter notebook
```

5. Run all cells to reproduce the analysis.

---

## 📌 Future Improvements

- Perform sentiment analysis using user reviews.
- Build an interactive dashboard using Power BI or Tableau.
- Create predictive models for app ratings and installs.
- Analyze trends across app genres and update frequency.

---

## 👨‍💻 Author

**Nikhil Uthaiah KR**

Aspiring Data Analyst

### Skills

- Python
- SQL
- Excel
- Power BI
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

## ⭐ If you found this project useful, consider giving it a star on GitHub!
