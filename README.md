# 🎮 The Influence of Video Games on Physical Activity

## 📊 Project Overview

This project analyzes how active and sedentary video games influence physical activity levels, motivation, and behavioral patterns among sedentary children.

The analysis focuses on data collected at different stages of the study:

* Baseline
* 6-week intervention
* 10-week post-washout

The project uses multiple data sources, including physical activity measurements, accelerometer data, demographic information, and questionnaires.

## 🎯 Project Objectives

The main objectives of this project are to:

* Analyze the impact of active video games on children's physical activity.
* Compare active and sedentary video game behavior.
* Identify changes in physical activity over time.
* Analyze the relationship between demographic factors and activity levels.
* Explore changes in children's motivation toward physical and video-game activities.
* Investigate whether motivation for active video games is associated with increased physical activity.

## 🗂️ Data Sources

The project combines several datasets:

* **24-Hour Recall Data** — Daily activities recorded at baseline, weeks 2, 4, 6, and 10.
* **Accelerometer Data** — Physical and sedentary activity measurements collected using ActiGraph.
* **Demographic Data** — Including weight, height, gender, race, ethnicity, and birth year.
* **Questionnaire Data** — Motivation, exercise self-efficacy, and parenting behavior measurements.
* **Relative Reinforcing Value Data** — Children's preferences for physical and sedentary activities.

## 🧹 Data Preparation

The data preparation process included:

1. Handling missing values.
2. Standardizing data formats and labels.
3. Identifying and removing invalid or extreme values.
4. Merging datasets using a unique Child ID.
5. Transforming data into analysis-ready formats such as weekly activity totals.

## 🏗️ Data Modeling

The different datasets were connected using **Child ID** as the primary identifier.

A **Star Schema** was designed to organize the data and support efficient analysis and reporting.

## 📈 Dashboard

The Power BI dashboard provides visual analysis of:

* Physical activity levels during the intervention.
* Active vs. sedentary video game behavior.
* Activity trends across baseline, week 6, and week 10.
* Demographic factors and their relationship with activity levels.
* Motivation toward physical and video-game activities.

## 🔍 Key Findings

The analysis indicated that:

* Active video games were associated with increased physical activity during the intervention period.
* Some activity levels remained above baseline after the washout period.
* Higher motivation toward active video games was associated with increased physical activity.

## 🛠️ Tools & Technologies

* Power BI
* Power Query
* Data Cleaning
* Data Transformation
* Data Modeling
* Star Schema
* Data Visualization
* Exploratory Data Analysis

## 📁 Project Structure

```text
video-games-physical-activity-analysis/
│
├── README.md
├── PowerBI/
│   └── video_games_analysis.pbix
│
├── Presentation/
│   └── project_presentation.pptx
│
├── Screenshots/
│   └── dashboard.png
│
└── Data/
    └── README.md
```

## 👥 Team

* Ahmed Abd Elhalim Abd Elmonam
* Abdalluh Mohamed Aly
* Mark Michel Bushar
* Youssef Ashraf Abozaid

## 📌 Project Type

**Data Analytics | Power BI | Data Modeling | Data Visualization**

---

⭐ If you find this project useful, feel free to explore the repository.

