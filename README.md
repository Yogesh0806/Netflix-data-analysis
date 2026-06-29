# 🎬 Netflix Movies Analysis using Python

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas)
![NumPy](https://img.shields.io/badge/NumPy-013243?logo=numpy)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-orange)
![Seaborn](https://img.shields.io/badge/Seaborn-Statistical%20Plots-4C72B0)
![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Notebook-F37626?logo=jupyter)

A complete **Exploratory Data Analysis (EDA)** project on a Netflix Movies dataset using **Python**.
The project focuses on cleaning raw movie data, transforming features, creating insightful visualizations, and discovering trends in movie genres, popularity, ratings, and release years.

---

# 📌 Project Overview

This project demonstrates the complete workflow of a Data Analyst, from importing raw data to extracting meaningful business insights.

The notebook covers:

- Data Cleaning
- Data Transformation
- Feature Engineering
- Exploratory Data Analysis (EDA)
- Data Visualization
- Business Insight Generation

---

# 🎯 Objectives

The main objectives of this project are:

- Understand the structure of the dataset.
- Clean and preprocess movie data.
- Analyze genre distribution.
- Categorize movie ratings.
- Find the most and least popular movies.
- Analyze movie release trends over the years.
- Visualize important insights using charts.

---

# 📂 Dataset Information

The dataset contains information about Netflix movies, including:

- Title
- Genre
- Release Date
- Popularity
- Vote Average
- Vote Count
- Original Language
- Overview
- Poster URL

### Dataset Size

- **Rows:** 9,827
- **Columns:** 9

---

# 🛠️ Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

# 📚 Python Libraries

```python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
```

---

# 🧹 Data Cleaning

The following preprocessing steps were performed:

- Loaded the dataset
- Checked dataset information
- Removed duplicate records
- Converted `Release_Date` to datetime format
- Extracted release year
- Dropped unnecessary columns
- Removed missing values
- Split multiple genres into separate rows
- Converted Genre column into categorical datatype

---

# ⚙️ Feature Engineering

Additional features were created to improve the analysis.

### Vote Average Categories

Movies were grouped into four categories:

- Not Popular
- Below Average
- Average
- Popular

This makes rating analysis much easier.

---

# 📊 Exploratory Data Analysis (EDA)

The project answers several analytical questions, including:

### 🎭 What is the most frequent movie genre?

A count plot was created to identify the genre appearing most frequently.

---

### ⭐ Which movies have the highest vote average?

Analyzed movie ratings to understand audience preferences.

---

### 🔥 Which movie has the highest popularity?

Identified the movie with the maximum popularity score.

---

### 📉 Which movie has the lowest popularity?

Found the least popular movie in the dataset.

---

### 📅 Which year has the highest number of movie releases?

Visualized release trends using a histogram.

---

# 📈 Visualizations

The notebook includes various visualizations such as:

- Genre Distribution
- Vote Average Distribution
- Popularity Analysis
- Release Year Histogram
- Count Plots
- Distribution Charts

---

# 💡 Key Insights

Some important insights obtained from the analysis include:

- Drama is the most common movie genre.
- Movie popularity varies significantly.
- Ratings are concentrated around average values.
- Certain years experienced a much higher number of movie releases.
- Splitting multiple genres provides better genre-wise analysis.

---

# 📁 Project Structure

```
Netflix-Movies-Analysis/
│
├── movie analysis.ipynb
├── mymoviedb.csv
├── README.md
└── images/
```

---

# ▶️ How to Run

## Clone the repository

```bash
git clone https://github.com/your-username/Netflix-Movies-Analysis.git
```

---

## Navigate to project folder

```bash
cd Netflix-Movies-Analysis
```

---

## Install dependencies

```bash
pip install pandas numpy matplotlib seaborn
```

---

## Launch Jupyter Notebook

```bash
jupyter notebook
```

---

## Open

```
movie analysis.ipynb
```

Run all cells.

---

# 📷 Project Screenshots

```
images/
│
├── genre_distribution.png
├── vote_average.png
├── popularity_analysis.png
└── release_year_histogram.png
```

---

# 🎯 Skills Demonstrated

- Data Cleaning
- Data Wrangling
- Exploratory Data Analysis (EDA)
- Data Visualization
- Feature Engineering
- Data Interpretation
- Python Programming
- Statistical Analysis

---

# 🚀 Future Improvements

Possible enhancements include:

- Build an interactive Power BI dashboard.
- Create a Plotly dashboard.
- Perform sentiment analysis on movie descriptions.
- Build a movie recommendation system.
- Deploy the project as a Streamlit application.
- Add machine learning models for popularity prediction.

---

# 👨‍💻 Author

**Yogesh Yadav**

Aspiring Data Analyst passionate about solving business problems using data.

### Connect with me

- GitHub: https://github.com/Yogesh0806
- LinkedIn: www.linkedin.com/in/yogesh-yadav-b0b457330

---

# ⭐ Support

If you found this project useful, consider giving it a ⭐ on GitHub.

It motivates me to continue building more Data Analytics projects.
