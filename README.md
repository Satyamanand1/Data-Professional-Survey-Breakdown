# Data Professional Survey Breakdown Dashboard

> **An interactive Power BI dashboard analyzing survey responses from data professionals worldwide to uncover salary trends, programming language preferences, career satisfaction, and industry insights.**

![Dashboard Preview](images/dashboard-overview.png)

---

## 📌 Project Overview

The data industry is one of the fastest-growing career domains, but understanding the skills, compensation, and challenges faced by professionals requires more than isolated statistics.

This project transforms raw survey responses into an interactive Power BI dashboard that enables users to explore trends across countries, job roles, programming languages, career satisfaction, and salaries.

Using Power BI, Power Query, DAX, and Excel, the dashboard converts survey data into meaningful insights that support career planning, workforce analysis, and business intelligence.

---

# 🎯 Business Problem

Organizations, aspiring data professionals, and recruiters often need answers to questions such as:

* Which data roles offer the highest average salaries?
* Which programming languages are most preferred?
* How satisfied are professionals with their work-life balance?
* How difficult is it to break into the data industry?
* Which countries contribute the largest share of survey responses?
* How do salary and job satisfaction differ across roles?

This dashboard provides a centralized view to answer these questions through interactive visualizations.

---

# 📁 Dataset

**Dataset:** Data Professional Survey

The dataset contains survey responses from professionals working in various data-related roles across multiple countries.

### Features

* Country
* Gender
* Age
* Job Title
* Annual Salary
* Favorite Programming Language
* Work-Life Balance Rating
* Salary Satisfaction Rating
* Difficulty of Breaking into Data
* Survey Timestamp

---

# 🛠 Tools & Technologies

* **Power BI**
* **Power Query**
* **Microsoft Excel**
* **DAX (Data Analysis Expressions)**

---

# 📊 Dashboard Features

### KPI Cards

* 👥 Count of Survey Takers
* 📅 Average Age
* 😊 Happiness with Work-Life Balance
* 💰 Happiness with Salary

---

### Interactive Filters

* Country
* Gender

---

### Visualizations

* 🌍 Country-wise Survey Distribution (Treemap)
* 💼 Average Salary by Job Title (Horizontal Bar Chart)
* 💻 Favorite Programming Language (Column Chart)
* 🎯 Difficulty to Break into Data (Donut Chart)
* 😊 Work-Life Balance Gauge
* 💵 Salary Satisfaction Gauge

---

# 📐 DAX Measures Used

```DAX
Count of Survey Takers =
COUNTROWS(Data)

Average Age =
AVERAGE(Data[Current Age])

Average Salary =
AVERAGE(Data[Average Salary])

Average Work/Life Balance =
AVERAGE(Data[Work/Life Balance])

Average Salary Happiness =
AVERAGE(Data[Salary Satisfaction])
```

Additional implicit measures were used for:

* Average Salary by Job Title
* Programming Language Vote Count
* Country-wise Survey Count
* Percentage Distribution
* Dynamic filtering through slicers

---

# 📈 Key Insights

## 💰 Salary Trends

* Data Scientists reported the highest average salaries among surveyed roles.
* Data Engineers and Data Architects also demonstrated strong salary ranges.
* Students and entry-level professionals reported comparatively lower compensation.

---

## 💻 Programming Language Popularity

* Python is the dominant programming language among respondents.
* SQL/R (represented in the survey) remain important tools.
* JavaScript and Java received comparatively fewer preferences from participants.

---

## 🌎 Geographic Distribution

* The United States contributed the highest number of survey responses.
* India, Canada, and the United Kingdom also had significant participation.
* Responses from other countries provide a broader global perspective.

---

## 🎯 Breaking into Data

Survey responses indicate that entering the data profession is perceived as:

* Mostly **Neither Easy nor Difficult**
* Followed by **Difficult**
* A smaller percentage considered the transition **Very Difficult** or **Very Easy**

This highlights the importance of practical skills and continuous learning for aspiring professionals.

---

## 😊 Career Satisfaction

### Work-Life Balance

Respondents reported generally positive work-life balance, with an average score above the midpoint of the rating scale.

### Salary Satisfaction

Salary satisfaction scores were noticeably lower than work-life balance, suggesting opportunities for employers to improve compensation strategies and employee retention.

---

# 💡 Business Recommendations

* Invest in Python-based analytics training, as it remains the most preferred programming language.
* Organizations should benchmark salaries across roles to remain competitive.
* Companies can improve retention by addressing salary satisfaction alongside work-life balance.
* Career development and mentorship programs may reduce the perceived difficulty of entering the data profession.
* Geographic hiring strategies can leverage regions with growing data talent pools.

---

# 📊 Dashboard Highlights

✔ Interactive slicers for Country and Gender

✔ Dynamic KPI Cards

✔ Treemap for geographic analysis

✔ Salary comparison across job roles

✔ Programming language preference analysis

✔ Career difficulty distribution

✔ Work-Life Balance KPI

✔ Salary Satisfaction KPI

---

# 📷 Dashboard Preview

### Overall Dashboard

*(Insert Dashboard Screenshot Here)*

---

### Country Filter Analysis

*(Insert Country Filter Screenshot Here)*

---

### Gender-Based Analysis

*(Insert Gender Filter Screenshot Here)*

---

# 📚 Skills Demonstrated

* Data Cleaning
* Data Transformation
* Power Query
* Data Modeling
* DAX Measures
* KPI Development
* Dashboard Design
* Business Intelligence
* Data Visualization
* Analytical Thinking
* Interactive Reporting

---

# 🚀 Learning Outcomes

Through this project, I strengthened my understanding of the complete Power BI development workflow—from preparing raw survey data to building an interactive dashboard that communicates meaningful insights.

Key takeaways include:

* Designing user-friendly dashboards with interactive filters.
* Creating dynamic KPIs using DAX.
* Cleaning and transforming data with Power Query.
* Selecting appropriate visualizations for different analytical questions.
* Translating survey data into actionable business insights.

---

# 📂 Repository Structure

```text
Data-Professional-Survey-Breakdown/
│
├── Dashboard/
│   └── Data Professional Survey Breakdown.pbix
│
├── Dataset/
│   └── Power BI - Final Project.xlsx
│
├── Images/
│   ├── dashboard-overview.png
│   ├── country-filter.png
│   ├── female-filter.png
│   └── male-filter.png
│
└── README.md
```

---

# 👨‍💻 Author

**Anjali Sharma**

B.Tech AIDS (2023–2027)

Aspiring Data Analyst | Power BI | SQL | Python | Excel

---

## ⭐ If you found this project helpful, consider giving it a Star and sharing your feedback!
