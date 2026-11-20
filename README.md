# Library-Occupancy-and-Student-Study-Patterns-in-UNI-campus
this was our DMA lab project, got the idea ourselves.. the requirement from the teacher was that we need to gather real world data and operate. So did the same... more description about it -

# 📚 Data Mining and Analysis of Library Occupancy and Student Study Patterns

## Project Overview

This project focuses on analyzing university students' library usage patterns, study habits, and perceptions of library facilities using Data Mining and Analytics techniques.

The study aims to understand how students utilize library resources, identify their preferred study timings, examine perceived crowding and seat availability, and explore relationships between library conditions and student study experiences.

By applying data analysis, statistical techniques, data visualization, and machine learning, the project seeks to identify meaningful patterns in student behaviour and provide insights that could help improve library resource management and the overall student experience.

## 🎯 Objectives

- Analyze library usage patterns across different academic years and branches.
- Identify students' preferred library study timings and visit durations.
- Examine library crowding perceptions and difficulties in finding seats.
- Investigate relationships between library conditions and student concentration.
- Analyze student satisfaction with library facilities.
- Apply clustering techniques to identify groups of students with similar study behaviours.
- Explore library occupancy trends using actual seat-occupancy observations, where available.
- Suggest possible improvements for university library management.

## 🛠️ Technologies and Tools

| Technology | Purpose |
|---|---|
| Python | Programming and analysis |
| Google Colab | Development environment |
| Pandas | Data manipulation and preprocessing |
| NumPy | Numerical operations |
| Matplotlib | Data visualization |
| Seaborn | Statistical visualization |
| SciPy | Statistical analysis |
| Scikit-learn | Machine learning and clustering |

## 📊 Dataset Description

The project uses a structured survey dataset containing information related to:

- Academic year and department
- Frequency of library visits
- Preferred study locations and timings
- Duration of library visits
- Reasons for using the library
- Perceived library crowding
- Seat availability and satisfaction
- Impact of crowding on concentration
- Overall library study environment

A separate occupancy dataset is planned to record the total number of usable seats and occupied seats at different times.

**Dataset note:** The initial 128-response dataset is synthetic/demo data used for developing and testing the analytical workflow. It must not be interpreted as genuine student survey data. Actual survey responses and direct occupancy observations are required for empirical conclusions.

## ⚙️ Project Methodology

The project follows these stages:

### 1. Data Collection
Collection of student survey responses and, where possible, manual library seat-occupancy observations.

### 2. Data Cleaning and Preprocessing
- Handling missing values
- Checking duplicate records
- Standardizing categorical responses
- Converting suitable variables into numerical formats
- Preparing data for analysis

### 3. Exploratory Data Analysis (EDA)
Using graphs, charts, frequency distributions, and descriptive statistics to understand student library usage patterns.

### 4. Statistical Analysis
Applying:
- Cross-tabulation
- Chi-square test of independence
- Cramér's V
- Spearman's rank correlation

These techniques help investigate relationships between different survey variables.

### 5. Data Mining and Machine Learning
Applying K-Means clustering to explore potential groups of students with similar library usage and study behaviour.

Cluster quality will be evaluated using suitable measures such as the Elbow Method and Silhouette Score.

### 6. Library Occupancy Analysis
Calculating occupancy rates using:

Occupancy Rate = (Occupied Seats / Total Usable Seats) × 100

Analyzing occupancy variations across different observation times.

### 7. Interpretation and Conclusion
Interpreting the analytical results, identifying limitations, and suggesting possible improvements to university library facilities.

## 📁 Repository Structure

```text
Library-Study-Pattern-Analysis/
│
├── README.md
│
├── Library_Study_DMA_Project.ipynb
│
├── data/
│   ├── survey_data.csv
│   └── occupancy_data.csv
│
├── visualizations/
│
└── report/
    └── Project_Report.pdf
```

*The repository structure will be updated as the project develops.*

## 🚀 How to Run the Project

1. Clone the repository:

```bash
git clone https://github.com/YOUR-USERNAME/Library-Study-Pattern-Analysis.git
```

2. Open the project notebook in Google Colab.

3. Upload the required dataset when prompted.

4. Execute the notebook cells sequentially, following the project stages.

## 📈 Expected Outcomes

The project aims to:

- Understand student library usage patterns.
- Identify preferred library study periods.
- Explore relationships between crowding, seat availability, and concentration.
- Discover potential student study-behaviour groups.
- Analyze actual library occupancy patterns when observations are available.
- Recommend improvements to library facilities and resource utilization.

## ⚠️ Limitations

- Survey responses may reflect individual perceptions rather than objectively measured conditions.
- Synthetic/demo data cannot establish genuine student behaviour or population-level conclusions.
- Actual occupancy analysis depends on collecting reliable seat-count observations.
- Clustering results depend on feature selection, encoding choices, and data quality.

## 👨‍💻 Project Information

**Project Domain:** Data Mining and Analytics  
**Project Title:** Data Mining and Analysis of Library Occupancy and Student Study Patterns in a University Campus  
**Development Platform:** Google Colab  
**Programming Language:** Python

---

*This project is developed for academic purposes as part of a Data Mining and Analytics course.*
