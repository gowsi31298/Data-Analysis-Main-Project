# 📊 AI & Social Media Impact on Student Health

### An Exploratory Data Analysis & Power BI Dashboard Project

## 📌 Project Overview

The **AI & Social Media Impact on Student Health** project explores how students' digital habits and daily lifestyles relate to their mental and physical well-being.

With the increasing use of social media platforms and Artificial Intelligence (AI) tools, understanding their relationship with students' health has become increasingly important.

This project analyzes a dataset of **16,000 students** to identify patterns in social media usage, AI tool usage, sleep duration, physical activity, and health scores. It combines Python-based data analysis and visualization with an interactive Power BI dashboard to communicate insights and support data-driven decision-making.

## 🎯 Problem Statement

Students spend a significant amount of time using social media and AI tools. However, the relationship between these digital habits and students' sleep, physical activity, mental health, and physical health requires further investigation.

This project aims to:

* Analyze students' daily social media and AI tool usage.
* Explore relationships between digital habits and health scores.
* Investigate sleep patterns and physical activity.
* Compare digital behavior across age groups, genders, and education levels.
* Identify student health patterns using exploratory data analysis.
* Present key findings through a Power BI dashboard.

## 🎯 Project Objectives

* Perform data cleaning and preprocessing.
* Conduct exploratory data analysis (EDA).
* Calculate descriptive statistics and aggregated metrics.
* Create meaningful visualizations to identify trends and patterns.
* Develop derived features for further analysis.
* Build a Power BI dashboard to present key performance indicators (KPIs).
* Communicate insights through data-driven storytelling.

## 🛠️ Technologies & Tools Used

| Technology       | Purpose                                  |
| ---------------- | ---------------------------------------- |
| Python           | Data analysis and preprocessing          |
| Pandas           | Data manipulation and aggregation        |
| NumPy            | Numerical operations                     |
| Matplotlib       | Data visualization                       |
| Seaborn          | Statistical visualization                |
| Jupyter Notebook | Interactive analysis and documentation   |
| Power BI         | Dashboard creation and data storytelling |
| Git & GitHub     | Version control and project hosting      |

## 📂 Dataset Information

**Dataset:** AI and Social Media Impact on Student Health and Grades

**Source:** [Kaggle Dataset](https://www.kaggle.com/datasets/srisyra02/ai-and-social-media-impact-student-health-and-grades)

**Dataset size:** 16,000 student records

**Data collection timeline:** 2025–2026, as documented in the project notebook.

### Key Features

| Feature                     | Description                         |
| --------------------------- | ----------------------------------- |
| `Student_ID`                | Unique student identifier           |
| `Age`                       | Student age                         |
| `Gender`                    | Student gender                      |
| `Education_Level`           | High School, College, or University |
| `Daily_Social_Media_Hours`  | Daily social media usage in hours   |
| `Daily_AI_Tool_Usage_Hours` | Daily AI tool usage in hours        |
| `Sleep_Hours`               | Average daily sleep duration        |
| `Physical_Activity_Hours`   | Daily physical activity in hours    |
| `Mental_Health_Score`       | Mental well-being score             |
| `Physical_Health_Score`     | Physical well-being score           |

Higher mental and physical health scores indicate better well-being according to the dataset documentation.

## ⚙️ Project Workflow

### 1. Data Loading

* Imported the dataset using Pandas.
* Inspected the dataset structure, dimensions, column names, and data types.
* Examined sample records and statistical summaries.

### 2. Data Cleaning & Preprocessing

* Checked for duplicate student IDs.
* Inspected missing values.
* Corrected categorical data types.
* Prepared the dataset for further analysis.

### 3. Feature Engineering

Created additional features to support the analysis.

**Total Screen Time**

Combines daily social media usage and daily AI tool usage:

`Total Screen Time = Social Media Hours + AI Tool Usage Hours`

**Overall Health Score**

Calculates the average of mental and physical health scores:

`Overall Health Score = (Mental Health Score + Physical Health Score) / 2`

**Age Groups**

Grouped students into four categories:

* 13–15 years
* 16–18 years
* 19–21 years
* 22–25 years

**Health Categories**

Classified students based on their overall health scores:

* At Risk
* Average
* Healthy

**Sleep Categories**

Grouped students according to sleep duration:

* Short Sleep: Less than 6 hours
* Normal Sleep: 6–8 hours
* Long Sleep: More than 8 hours

**AI Usage Groups**

Categorized students according to daily AI tool usage:

* Low: 0–1 hour
* Moderate: 1–3 hours
* High: 3–5 hours
* Very High: More than 5 hours

### 4. Exploratory Data Analysis (EDA)

Performed statistical analysis and visual exploration to understand student behavior and health patterns.

The analysis includes:

* Descriptive statistical summaries.
* Distribution of daily social media usage.
* Student health category distribution.
* Student distribution by age group.
* Student distribution by education level.
* Social media usage across education levels.
* Gender-wise mental and physical health summaries.
* Relationship between social media usage and mental health scores.

### 5. Data Visualization

Used Matplotlib and Seaborn to create:

* Histograms with density curves.
* Pie charts.
* Count plots.
* Box plots.
* Scatter plots.

These visualizations help identify distributions, compare demographic groups, and explore potential relationships between digital habits and student well-being.

### 6. Power BI Dashboard

Developed a Power BI dashboard to present key metrics and findings in an accessible visual format.

The dashboard explores:

* Total number of students.
* Average social media usage.
* Average sleep duration.
* Average overall health score.
* Overall health category distribution.
* AI tool usage groups and health scores.
* Sleep categories and overall health.
* Social media usage across age groups.
* Student distribution by education level.

### 7. Data Export

Exported the processed dataset to CSV format for reuse and further analysis.

## 📈 Key Findings

The following findings are documented in the project's Power BI dashboard summary.

### 1. Student Digital Habits

* Average daily social media usage is approximately **4.54 hours**.
* Social media usage averages approximately 4.5–4.6 hours across the analyzed age groups.
* Digital engagement is present across all student age groups.

### 2. Sleep and Overall Health

The dashboard reports the following average overall health scores:

| Sleep Category                 | Average Overall Health Score |
| ------------------------------ | ---------------------------: |
| Short Sleep: Less than 6 hours |                           77 |
| Normal Sleep: 6–8 hours        |                           81 |
| Long Sleep: More than 8 hours  |                           85 |

The dashboard indicates that students in the longer-sleep category have higher average overall health scores than students in the shorter-sleep category.

### 3. AI Tool Usage and Health

According to the dashboard summary:

* Students in the low AI usage group have an average overall health score of approximately 81.
* Students using AI tools for 5 or more hours daily have an average overall health score of approximately 79.

These figures describe the reported group averages. They do not establish that AI tool usage causes changes in health.

### 4. Student Health Categories

The dashboard reports the following distribution:

* **Healthy:** 76.25%
* **Average:** 22.87%
* **At Risk:** The remaining small proportion.

These categories are based on the project's derived overall health score.

### 5. Education-Level Comparison

The Python analysis reports the following average daily social media usage:

| Education Level | Number of Students | Average Social Media Usage |
| --------------- | -----------------: | -------------------------: |
| High School     |              6,083 |             4.57 hours/day |
| College         |              4,890 |             4.49 hours/day |
| University      |              5,027 |             4.56 hours/day |

The averages are similar across the three education levels.

*Note: Dashboard findings are descriptive and should not be interpreted as proof of causal relationships.*

## 💡 Key Insights & Recommendations

Based on the analysis documented in the project:

* **Promote healthy sleep habits:** Encourage students to maintain consistent sleep schedules and healthy daily routines.
* **Encourage responsible social media use:** Promote balanced digital habits and meaningful offline activities.
* **Support responsible AI adoption:** Encourage appropriate use of AI tools for learning and productivity.
* **Monitor student well-being:** Use health indicators to identify patterns that may warrant further investigation.
* **Use data-driven decision-making:** Help educators and institutions better understand students' digital behaviors and lifestyle patterns.

## 🚀 How to Run the Project

### Prerequisites

Install Python and the required libraries.

```bash
pip install numpy pandas matplotlib seaborn jupyter
```

### Step 1: Clone the Repository

```bash
git clone <your-github-repository-url>
```

### Step 2: Navigate to the Project Folder

```bash
cd <your-repository-name>
```

### Step 3: Add the Dataset

Download the dataset from Kaggle and place the CSV file in the same directory as the notebook.

The notebook expects the dataset filename:

`AI_SocialMedia_Student_Dataset.csv`

### Step 4: Launch Jupyter Notebook

```bash
jupyter notebook
```

### Step 5: Run the Notebook

Open `Main_Project_1.ipynb` and execute the cells in order.

**Note:** The dataset must be available locally for the notebook to run successfully. The Power BI dashboard is a separate deliverable.

## 📊 Dashboard & Documentation

The project dashboard and supporting documentation are available here:

[View Dashboard and Documentation](https://drive.google.com/drive/folders/1GHCkdPlfn_CTtmYZEKqPwgHcQQe9cwPM?usp=sharing)

## 📁 Repository Structure

A recommended repository structure is:

```text
AI-Social-Media-Student-Health/
│
├── Main_Project_1.ipynb
├── AI_SocialMedia_Student_Dataset.csv
├── social media analysis.csv
├── README.md
└── dashboard/
    └── powerbi_dashboard.pbix
```

*The structure above is a recommendation. Include the CSV files and Power BI file only if you have added them to your repository.*

## 🔮 Future Enhancements

* Perform correlation analysis to investigate relationships between digital habits and health scores.
* Apply statistical testing to evaluate differences between student groups.
* Develop and validate machine learning models to predict health scores, if suitable data and evaluation methods are available.
* Add interactive Power BI filters and drill-down visualizations.
* Investigate relationships among sleep, physical activity, digital usage, and overall health.
* Improve the analysis with additional data and validation.

## 📝 Conclusion

The **AI & Social Media Impact on Student Health** project demonstrates how Python-based data analysis and Power BI visualization can be used to explore student lifestyle patterns and health indicators.

By combining data preprocessing, feature engineering, exploratory data analysis, and dashboard-based storytelling, the project provides a structured approach to understanding student digital behavior and well-being.

The findings can help guide further investigation into healthy digital habits, sleep patterns, and student health. However, the observed relationships should not be interpreted as causal effects without additional statistical evidence.

## 👤 Author

**Your Name**

* GitHub: [Your GitHub Profile](https://github.com/)
* LinkedIn: [Your LinkedIn Profile](https://www.linkedin.com/)

---

⭐ If you find this project interesting, consider giving the repository a star!
