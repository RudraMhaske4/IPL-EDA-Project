# 🏏 IPL Data Analysis using Python

## Overview

This project focuses on performing Exploratory Data Analysis (EDA) on an IPL ball-by-ball dataset using Python. The objective was to explore player performances, team strategies, and match trends by analyzing historical IPL data.

Rather than jumping directly into machine learning, I wanted to first understand the data, identify patterns, and generate meaningful insights through visualization. This project helped strengthen my understanding of data preprocessing, analysis, and storytelling with data.

---

## Problem Statement

Cricket generates a huge amount of data every season, making it difficult to identify important trends through manual observation.

The goal of this project is to analyze IPL match data and answer questions such as:

- Which batsmen have scored the most runs?
- Which bowlers have taken the most wickets?
- How does scoring change across different overs?
- What patterns can be observed from historical IPL matches?

---

## Dataset

The analysis is performed on an IPL ball-by-ball dataset containing information such as:

- Match ID
- Innings
- Over
- Batting Team
- Bowling Team
- Batter
- Bowler
- Runs Scored
- Extras
- Wickets

---

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## Project Workflow

- Data Collection
- Data Cleaning
- Handling Missing Values
- Exploratory Data Analysis (EDA)
- Statistical Analysis
- Data Visualization
- Insight Generation

---

## Visualizations

### 🏏 Top 10 Batsmen by Runs

<img src="images/top_batsmen.png" width="800">
"C:\Users\hp\Desktop\Projects\IPL\Images\Heatmap.png"

---

### 🎯 Top 10 Bowlers by Wickets

<img src="images/top_bowlers.png" width="800">

---

### 📈 Runs Scored per Over

<img src="images/runs_per_over.png" width="800">

---

### 🔥 Correlation Heatmap

<img src="images/heatmap.png" width="800">

---

## Key Insights

- A small group of players consistently contribute a significant portion of total runs.
- Wicket-taking ability is concentrated among a limited number of bowlers.
- Run rates generally increase during the final overs of an innings.
- Historical match data reveals clear scoring patterns that can support future predictive analysis.

---

## Project Structure

```
IPL-Data-Analysis
│
├── data
│   ├── raw_dataset.csv
│   └── cleaned_dataset.csv
│
├── notebook
│   └── IPL_Data_Analysis.ipynb
│
├── reports
│   └── Project1 EDA.html
│
├── images
│   ├── top_batsmen.png
│   ├── top_bowlers.png
│   ├── runs_per_over.png
│   └── heatmap.png
│
├── README.md
├── requirements.txt
└── LICENSE
```

---

## How to Run

1. Clone this repository

```bash
git clone https://github.com/your-username/IPL-Data-Analysis.git
```

2. Install the required libraries

```bash
pip install -r requirements.txt
```

3. Open the notebook and run all the cells.

---

## Learning Outcomes

Working on this project helped me improve my understanding of:

- Data preprocessing
- Exploratory Data Analysis (EDA)
- Data visualization
- Feature exploration
- Pattern identification
- Extracting meaningful insights from real-world sports data

These skills form an important foundation for building machine learning models on structured datasets.

---

## Future Improvements

- Perform season-wise analysis.
- Build an interactive dashboard using Streamlit.
- Apply machine learning models to predict match outcomes.
- Develop player performance prediction models.
- Deploy the project as a web application.

---

## Author

**Rudra Mhaske**

B.Tech Artificial Intelligence & Machine Learning

If you found this project useful, consider giving it a ⭐.
