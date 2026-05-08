# YouTube Trending Video Analysis

## Project Overview

This project performs Exploratory Data Analysis (EDA) on YouTube Trending Videos data using Python libraries such as Pandas, Matplotlib, and Seaborn.

The analysis helps identify:

* Top trending channels
* Most viewed videos
* Relationship between views and likes
* Popular video categories
* Correlation between engagement metrics

---

# Technologies Used

* Python
* Pandas
* Matplotlib
* Seaborn

---

# Dataset Information

Dataset Name: INvideos.csv

The dataset contains information about trending YouTube videos in India.

## Dataset Link

* Kaggle Dataset: [https://www.kaggle.com/datasets/datasnaek/youtube-new](https://www.kaggle.com/datasets/datasnaek/youtube-new)

This dataset includes:

* Video titles
* Channel names
* Views
* Likes
* Comments
* Trending dates
* Category IDs
* Publish times
* Tags

---

# Libraries Required

Install the required libraries using:

```bash
pip install pandas matplotlib seaborn
```

---

# Project Workflow

## 1. Import Libraries

```python
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns
```

## 2. Load Dataset

```python
df = pd.read_csv("INvideos.csv")
```

## 3. Data Exploration

* View first rows of dataset
* Check column names
* Check missing values
* Convert date column

## 4. Data Cleaning

```python
df.dropna()
```

## 5. Analysis Performed

### Top Viewed Videos

Finds top 10 videos with highest views.

### Top Trending Channels

Displays channels with the highest number of trending videos.

### Views vs Likes Analysis

Scatter plot showing relationship between views and likes.

### Popular Categories

Shows most common video categories.

### Correlation Analysis

Heatmap between:

* Views
* Likes
* Comment Count

---

# Visualizations Used

* Bar Plot
* Scatter Plot
* Heatmap

---

# Output

The cleaned dataset is saved as:

```bash
cleaned_youtube_data.csv
```

---

# Sample Insights

* Music channels often dominate trending lists.
* Videos with higher views generally receive more likes.
* Some categories trend more frequently than others.

---

# Conclusion

This project demonstrates how Python can be used for data analysis and visualization of YouTube trending videos. It helps understand audience engagement, trending patterns, and channel performance.

---

# Author

Revansidha Chabukswar

---

# References

* Pandas Documentation: [https://pandas.pydata.org/](https://pandas.pydata.org/)
* Matplotlib Documentation: [https://matplotlib.org/](https://matplotlib.org/)
* Seaborn Documentation: [https://seaborn.pydata.org/](https://seaborn.pydata.org/)
