# 📊 Data Professional Survey Analysis: Work, Salary & Satisfaction

This Power BI project provides a comprehensive dashboard for analyzing the results of a survey conducted among data professionals. The goal is to visualize trends in job satisfaction, work-life balance, salary distributions, and key demographics within the data industry.

The dashboard is designed for aspiring data professionals, HR departments, and industry researchers to gain insights into the current state of the data workforce, including happiness metrics, popular programming languages, and important factors for job seekers.

## 📸 Dashboard Preview

![Dashboard Screenshot](Docs/Resources/Dashboard)

---

## 💾 The Dataset

The analysis is based on a single, rich dataset collected from a survey of data professionals.

* **Source:** `Power BI Final Project.xlsx - Data Professional Survey.csv` 
* **Description:** This CSV file contains 13 questions covering a wide range of topics including professional roles, compensation, industry, programming language preferences, and happiness ratings across multiple workplace dimensions. 

---

## 📖 Data Schema / Dictionary

The dataset includes the following key fields used in the analysis:

| Column Name (in CSV) | Description | Example Values |
| :--- | :--- | :--- |
| `Q1 - Which Title Best Fits your Current Role?` | The respondent's current job title.  | `Data Analyst`, `Data Engineer`, `Data Scientist`  |
| `Q3 - Current Yearly Salary (in USD)` | The respondent's annual salary range.  | `0-40k`, `66k-85k`, `150k-225k`  |
| `Q4 - What Industry do you work in?` | The industry in which the respondent is employed.  | `Healthcare`, `Finance`, `Tech`  |
| `Q5 - Favorite Programming Language` | The preferred programming language of the respondent.  | `Python`, `R`, `SQL`  |
| `Q6 - ... (Work/Life Balance)` | Happiness rating for Work/Life Balance (scale of 0-10). | `9`, `2`, `8`  |
| `Q6 - ... (Salary)` | Happiness rating for Salary (scale of 0-10). | `9`, `1`, `10`  |
| `Q6 - ... (Coworkers)` | Happiness rating for Coworkers (scale of 0-10).  | `7`, `5`, `10`  |
| `Q6 - ... (Management)` | Happiness rating for Management (scale of 0-10).  | `5`, `2`, `10`  |
| `Q8 - ... what would be the most important thing?` | The most important factor for the respondent when seeking a new job.  | `Remote Work`, `Better Salary`, `Good Culture`  |
| `Q10 - Current Age` | The age of the respondent.  | `26`, `36`, `23`  |
| `Q11 - Which Country do you live in?` | The country of residence for the respondent.  | `United States`, `Canada`, `India`  |

---

## ✨ Key Features & Analysis

This dashboard allows you to explore:

* **Job Role Deep Dive:** Analyze average salaries and satisfaction scores for different job titles like `Data Analyst`, `Data Engineer`, and `Data Scientist`. 
* **Satisfaction Metrics:** View average happiness scores for key areas like **Work/Life Balance**, **Salary**, **Management**, and **Coworkers**. 
* **Salary Distribution:** See how salaries vary across different industries, countries, and job roles. 
* **What Job Seekers Want:** Identify the most important factors for professionals when considering a new job, such as `Remote Work` and `Better Salary`. 
* **Demographic Filtering:** Interactively filter the entire report by `Country`, `Age`, `Gender`, and `Level of Education` to uncover specific insights. 
* **Programming Language Popularity:** Discover which programming languages are most favored by data professionals in different fields. 

---

## 🚀 Getting Started

You can explore this dashboard in two ways:

### 1. View the Live Interactive Report (Recommended)

The best way to experience the dashboard is through the interactive version published online.

➡️ **[View Interactive Dashboard](https://app.powerbi.com/view?r=eyJrIjoiMzVkNGM1ZDUtNDg2ZC00OGJiLThmMDYtNWZmZjMzYjQ4ODcyIiwidCI6ImQxZWY5MmUzLWNlNDMtNDY3Yi1iNjhmLTI3OGU2ZGQzMzE0ZCJ9&embedImagePlaceholder=true)**

### 2. Run Locally

You can also explore the project file on your local machine.

1.  **Clone this repository or download the files.**
2.  **Install [Power BI Desktop](https://powerbi.microsoft.com/desktop/)** (it's free).
3.  **Open the `Project.pbix` file** from this repository in Power BI Desktop.
4.  If prompted about data sources, ensure the `Data Professional Survey.csv` file is in the same folder as the `.pbix` file, or update the source path in Power BI's "Transform Data" -> "Data source settings" menu.
5.  Click the **"Refresh"** button in the "Home" tab to ensure all data is loaded.

---

## 🛠️ Tools & Technologies Used

* **Visualization & Analysis:** `Microsoft Power BI`
* **Data Source:** `CSV` 
* **Key Power BI Concepts:**
    * **Power Query:** Used for data cleaning, unpivoting the happiness-related columns, and data type correction.
    * **DAX (Data Analysis Expressions):** Used for creating measures like 'Average Salary Happiness' and 'Average Work/Life Balance Score'.
    * **Interactive Visuals:** Utilizes slicers, charts, and cards to create a dynamic and user-friendly experience.
