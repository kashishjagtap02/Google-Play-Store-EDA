# 📱 Google Play Store EDA

This project explores the Google Play Store dataset to understand app trends, user behavior, and market patterns through Exploratory Data Analysis (EDA). The analysis includes data cleaning, preprocessing, and visualization to extract meaningful insights from the dataset.

---

## Project Overview

The objective of this project is to analyze Google Play Store application data and identify patterns related to app categories, ratings, installs, pricing, and user engagement. Before performing the analysis, the dataset was cleaned by handling missing values, correcting data types, and preparing the data for visualization.

---

## Dataset

The dataset contains information about Android applications available on the Google Play Store, including:

- App Name
- Category
- Rating
- Reviews
- Size
- Installs
- Price
- App Type (Free/Paid)
- Content Rating
- Genres
- Android Version
- Last Updated

---

## Tools & Libraries

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

## Data Cleaning

The following preprocessing steps were performed before analysis:

- Removed unnecessary columns
- Checked and handled missing values
- Converted appropriate columns to numeric data types
- Converted the **Last Updated** column to datetime format
- Cleaned the **Installs** column by removing commas and '+' symbols
- Converted the **Price** column into numeric format
- Filled missing values using suitable statistical methods

---

## Exploratory Data Analysis

The project includes the following visualizations:

- Top 10 App Categories
- Distribution of App Ratings
- Free vs Paid Apps
- Top Categories by Total Installs
- Price Distribution
- Rating vs Reviews
- Correlation Heatmap
- Average Rating by Category

---

## Key Findings

- The **Family** category has the highest number of applications on the Play Store.
- Most applications available are **Free**.
- The majority of apps have ratings between **4.0 and 4.5**.
- Categories such as **Game**, **Communication**, and **Tools** receive a large number of installs.
- Most paid applications are available at relatively low prices.
- Reviews and installs show a positive relationship, indicating that popular apps generally receive more user feedback.

---

## Project Structure

```
Google-Play-Store-EDA
│
├── data
│   ├── googleplaystore.csv
│   ├── googleplaystore_user_reviews.csv
│   └── cleaned_google_play_store.csv
│
├── images
│   ├── top_categories.png
│   ├── ratings_distribution.png
│   ├── free_vs_paid.png
│   ├── top_installs.png
│   ├── price_distribution.png
│   ├── rating_vs_reviews.png
│   ├── correlation_heatmap.png
│   └── average_rating.png
│
├── Google_Play_Store_EDA.ipynb
├── README.md
└── requirements.txt
```

---

## How to Run

1. Clone this repository.

```bash
git clone https://github.com/kashishjagtap02/Google-Play-Store-EDA.git
```

2. Install the required libraries.

```bash
pip install -r requirements.txt
```

3. Open the notebook using Jupyter Notebook or Google Colab.

4. Run all cells to reproduce the analysis.

---

## Future Improvements

- Perform sentiment analysis using user reviews.
- Build an interactive dashboard with Power BI or Tableau.
- Develop a machine learning model to predict app ratings.

---

## Author

**Kashish Jagtap**


