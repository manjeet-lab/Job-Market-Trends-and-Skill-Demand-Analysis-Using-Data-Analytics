# 🇮🇳 India vs USA -- Job Market Trends, Demand and Salary Analysis

An interactive **Power BI data analytics project** comparing the job
markets of India and the United States from January to June 2026. This
project explores job posting demand, monthly market trends, company
distribution, regional demand and salary patterns.

## 📌 Project Overview

The objective of this project is to analyse job market data from India
and the USA to understand:

-   How job demand differs between the two countries.
-   Which job roles and regions have the highest and lowest demand.
-   How job postings change month over month.
-   How average salaries vary across job roles, countries and experience
    levels.
-   What insights can be extracted from job market data to support
    career and business decisions.

## 🎯 Project Objectives

-   Compare job posting distribution between India and the USA.
-   Identify high-demand and low-demand job roles.
-   Analyse company and regional distribution.
-   Track monthly job posting volume and growth.
-   Compare average annual salaries across countries.
-   Evaluate salary differences by job role and experience level.
-   Build an interactive dashboard using Power BI.

## 📊 Dashboard Pages

### 1. Home Page

Provides an overview of the project, analysis period and navigation to
all dashboard sections.

![Home Page](screenshots/home-page.png)

### 2. Job Demand Analysis

Analyses job posting demand across companies, regions and job roles.

**Key analysis:**

-   Total job postings and companies covered.
-   Total regions and countries covered.
-   India vs USA job posting distribution.
-   Highest and lowest demand regions.
-   Highest and lowest demand job roles.
-   Top 10 job roles by total salary.

![Job Demand Analysis](screenshots/job-demand-analysis.png)

### 3. Job Market Trend and Growth Analysis

Explores monthly job posting patterns and compares market movements
between India and the USA.

**Key analysis:**

-   India vs USA monthly job market share.
-   Month-over-Month (MoM) job growth.
-   Monthly job posting volume.
-   Country-wise monthly posting comparison.
-   Highest and lowest job posting months.

![Job Market Trends](screenshots/job-market-trends.png)

### 4. Salary & Compensation Analysis

Examines salary patterns across job roles, countries and experience
levels.

**Key analysis:**

-   Average annual salary.
-   Highest-paying and lowest-paying job roles.
-   Highest-paying country.
-   Average salary by job role.
-   Average salary comparison between India and the USA.
-   Salary trend by month.
-   Average salary for Freshers and Experts.

![Salary Analysis](screenshots/salary-analysis.png)

## 🔍 Key Insights

Based on the dashboard results:

-   **Job demand:** Healthcare is the highest-demand job role, with
    approximately 13,909 postings.
-   **Regional demand:** California leads with approximately 11,867 job
    postings.
-   **Monthly demand:** June records the highest posting volume, with
    approximately 23,562 jobs, while March records the lowest, with
    approximately 12,553.
-   **Salary comparison:** The USA has a higher average annual salary
    than India in this dataset.
-   **Highest-paying role:** Operations, with an average salary of
    approximately \$21,664.
-   **Lowest-paying role:** Admin, with an average salary of
    approximately \$6,206.
-   **Experience comparison:** Expert-level jobs have an average salary
    of approximately \$14.01K, compared with \$10.07K for Freshers.

*Note: These findings represent the dataset and selected dashboard
filters. They should not be interpreted as official estimates of the
entire job market.*

## 🛠️ Tools & Technologies

  Tool               Purpose
  ------------------ -------------------------------------
  Power BI Desktop   Interactive dashboard development
  Power Query        Data cleaning and transformation
  DAX                Measures, KPIs and calculations
  Data Modeling      Star schema and table relationships
  Python             Data analysis and preparation

## 🧹 Data Preparation & Modeling

The project includes the following data preparation activities:

-   Data cleaning and handling missing values.
-   Removing duplicate records where appropriate.
-   Data type corrections and transformations.
-   Creating dimension tables for companies, locations, job roles,
    education and work modes.
-   Creating a date dimension for time-based analysis.
-   Building a star schema with a central fact table and related
    dimension tables.
-   Establishing relationships between fact and dimension tables.

### Data Model

The project follows a Star Schema approach:

-   **Fact Table:** `Fact_JobPostings`
-   **Dimension Tables:** `Dim_Company`, `Dim_Location`, `Dim_JobRole`,
    `Dim_Education`, `Dim_WorkMode` and `Dim_Date`.

## 📐 Key DAX Measures

Some of the calculations used in this project include:

-   Total Job Postings
-   Total Companies
-   Total Locations
-   Average Salary
-   Median Salary
-   Previous Month Jobs
-   MoM Job Growth %
-   Job Market Share %
-   Fresher Average Salary
-   Expert Average Salary
-   Highest Demand Role
-   Highest Paying Role

## 📅 Dataset Information

  Attribute         Details
  ----------------- -----------------------------------------------------
  Countries         India and USA
  Analysis Period   January -- June 2026
  Data Category     Job Postings
  Key Metrics       Job Demand, Company Distribution, Salary and Growth
  Salary Currency   USD
  Dashboard Tool    Microsoft Power BI

**Dataset Source:** Add the original dataset source link here.

## 📁 Repository Structure

``` text
Job Market Trends and Skill Demand Analysis Using Data Analytics/
│
├── screenshots/
│   ├── home-page.png
│   ├── job-demand-analysis.png
│   ├── job-market-trends.png
│   └── salary-analysis.png
│
├── dataset/
│   └── README.md
│
├── power-bi/
│   └── India-USA-Job-Market-Analysis.pbix
│
└── README.md
```

## 🚀 Project Outcomes

Through this project, I gained practical experience in:

-   Data cleaning and transformation using Power Query.
-   Designing a star schema for analytical reporting.
-   Creating DAX measures and calculated KPIs.
-   Performing comparative and time-based analysis.
-   Building interactive dashboards in Power BI.
-   Converting raw job posting data into meaningful business insights.

## 👨‍💻 Author

**Manjeet Gupta**

SY B.Sc. Artificial Intelligence & Machine Learning

Interested in Data Analytics, Data Science and Business Intelligence.

-   [LinkedIn](https://www.linkedin.com/in/manjeet-gupta-731409296/)
-   [Portfolio](https://manjeetgupta.vercel.app/)
-   [Source of Dataset](https://fliarbi.com/datasets/job-postings-2026/)

------------------------------------------------------------------------

⭐ If you find this project interesting, feel free to explore the
dashboards and share your feedback.

**#PowerBI #DataAnalytics #DAX #PowerQuery #DataVisualization
#JobMarketAnalysis #DataModeling**
