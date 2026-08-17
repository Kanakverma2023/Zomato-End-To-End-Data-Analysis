# Zomato Sales & User Performance Analysis

Designed a **Zomato-themed Power BI dashboard** to analyze sales performance, user behavior, city performance, restaurant performance, and food-related trends. The dashboard transforms business data into interactive visual reports, helping users explore performance trends and analyze key business metrics from multiple perspectives.

---

## Dashboard Previews

### 1. Home Page

![Home Page](screenshots/Home_page.png)

### 2. Overview

![Overview](screenshots/overview.png)

### 3. User Performance

![User Performance](screenshots/user_performance.png)

### 4. City Analysis

![City Analysis](screenshots/city_analysis.png)

### 5. Restaurant Analysis

![Restaurant Analysis](screenshots/restaurant_analysis.png)

### 6. Insights

![Insights](screenshots/insights.png)

---

## Project Overview

This project is a **Power BI dashboard** built using Zomato-related order, user, restaurant, menu, and city data to analyze sales performance, customer behavior, restaurant performance, city-wise trends, cuisines, food types, and ratings.

The dashboard was developed using **Power BI, Power Query, DAX, and data modeling**. It combines multiple related tables and business measures into interactive reports that allow users to explore the data through KPIs, charts, slicers, filters, and navigation features.

The dashboard contains **six interactive report pages**, each designed to provide a different perspective of the data.

The project focuses on:

- Sales and order performance
- User and customer analysis
- City-wise business performance
- Restaurant performance
- Cuisine and food type analysis
- Restaurant ratings
- Menu price analysis
- Interactive reporting and data exploration

---

## Business Problem Statement

Zomato-related business data contains information across orders, users, restaurants, menus, and cities. Analyzing these datasets across multiple dimensions can make it difficult to identify performance trends and compare different business segments efficiently.

This dashboard was developed to provide an interactive analytical view and help answer questions such as:

- How does sales performance vary across different years and cities?
- Which cities have higher sales, users, orders, and ratings?
- How do user demographics relate to business performance?
- How are restaurants distributed across cities and food types?
- Which cuisines have a higher presence across restaurants?
- How does restaurant rating performance vary?
- How can interactive Power BI reporting make business analysis easier?

---

## Core Objective

The objective of this project is to transform Zomato-related business data into an interactive Power BI dashboard that enables users to analyze sales, orders, customers, cities, restaurants, cuisines, food types, and ratings.

The dashboard uses **Power Query, DAX, data modeling, KPIs, filters, and interactive visualizations** to provide a structured view of business performance and support data-driven analysis.

---

## Dataset

The project uses multiple related tables containing information about orders, users, restaurants, menus, and cities.

The data model includes tables such as:

- `orders`
- `users`
- `restaurant`
- `menu`
- `CurrYear`
- `Measure_Table`
- `RankTable`

The dataset contains fields related to:

- Order information
- User information
- City
- Restaurant
- Cuisine
- Year
- User age
- Gender
- Occupation
- Restaurant ratings
- Rating counts
- Menu price
- Food type

The dataset is stored separately in the `data` folder of the repository.

---

## Tools & Technologies

- **Power BI**
- **Power Query**
- **DAX (Data Analysis Expressions)**
- **Power BI Data Modeling**
- **Power BI Interactive Visualizations**

---

## Data Cleaning & Preparation

The data was prepared and transformed using **Power Query** and Power BI data modeling features before developing the dashboard.

### Data Preparation

- Reviewed and prepared the source tables for analysis.
- Structured multiple tables for use within the Power BI data model.
- Prepared fields required for sales, user, restaurant, city, cuisine, and rating analysis.
- Applied transformations required for reporting and visualization.
- Created relationships between relevant tables.

### DAX Calculations

DAX measures were created to calculate key business metrics, including sales, orders, users, ratings, restaurants, current-year performance, previous-year performance, and customer movement.

### Result

The prepared data model supports interactive dashboard pages with KPIs, filters, dynamic analysis, and visual comparisons across multiple business dimensions.


The dashboard contains **6 interactive report pages**, each focusing on a different area of Zomato business performance.

### 1. Home Page

- Interactive landing page
- Dashboard navigation
- Navigation buttons
- Access to different report sections

### 2. Overview

Provides a high-level view of overall business performance.

**Includes**

- Sales Value
- Order Count
- Rating Count
- Year-wise Sales Analysis
- City-wise Sales Analysis
- Top N City Analysis
- Food Type Analysis
- Quantity vs Amount Analysis
- Rating Analysis

### 3. User Performance

Analyzes customer and user-related performance.

**Includes**

- Total Users
- Active Users
- Gained Customers
- Lost Customers
- User Age Analysis
- Sales by Gender
- Sales by Occupation
- Customer Gain by Gender
- Customer Loss by Gender
- Order Count
- Rating Count

### 4. City Analysis

Compares business performance across different cities.

**Includes**

- Total Cities
- User Count by City
- Sales by City
- Rating Count by City
- Order Count by City
- Current Year Sales
- Previous Year Sales
- Gained Customers by City
- Lost Customers by City
- Detailed City Performance Analysis

### 5. Restaurant Analysis

Provides restaurant, cuisine, food type, rating, and menu analysis.

**Includes**

- Restaurant Count
- Average Rating
- Current Year Sales
- Previous Year Sales
- Restaurant Count by City
- Restaurant Count by Food Type
- Top Cuisine Categories
- Restaurant Rating Analysis
- Cuisine Analysis
- Menu Price Analysis

### 6. Insights

Provides a dedicated page for presenting observations and conclusions derived from the dashboard analysis.

---

## Interactive Features

The dashboard includes interactive Power BI features that allow users to explore the data dynamically.

- Interactive Navigation Menu
- Navigation Buttons
- Back and Home Navigation
- Dynamic Search
- Dropdown Slicers
- KPI Cards
- Cross-filtering Between Visuals
- Dynamic Top N Analysis
- Year-based Analysis
- Gender-based Analysis
- Quantity vs Amount Toggle
- Interactive City Analysis
- Interactive Restaurant Analysis
- Cuisine Analysis
- Food Type Analysis
- Rating Analysis

---

## Filters & Slicers

The dashboard includes interactive filters and slicers that allow users to analyze the data from different perspectives.

- Year
- City
- Restaurant
- Cuisine
- Food Type
- Gender
- User Age
- Occupation
- Sales Type
- Dynamic Top N Selection

These filters allow users to drill down from overall performance into specific cities, restaurants, customer segments, and food categories.

---

## Key Insights

The dashboard enables analysis of the following areas:

- Overall sales and order performance
- Current-year and previous-year sales comparison
- City-wise business performance
- User and customer activity
- Gained and lost customer analysis
- Restaurant performance
- Cuisine distribution
- Food type distribution
- Restaurant rating analysis
- Menu price analysis
- User demographic analysis

> **Note:** Specific numerical insights should be added after validating the final dashboard values and selected filters.

---

## Skills Demonstrated

- Data Cleaning & Preparation
- Data Modeling
- Power Query
- DAX
- KPI Development
- Power BI Dashboard Design
- Interactive Reporting
- Data Visualization
- Business Analysis
- Data Storytelling
- Dynamic Analysis
- Report Navigation

---

## What I Learned

- Building an interactive multi-page Power BI dashboard.
- Preparing and modeling data for business analysis.
- Creating DAX measures for KPIs and dynamic calculations.
- Designing interactive report pages with a consistent user experience.
- Using slicers, filters, navigation buttons, and cross-filtering.
- Analyzing sales, users, cities, restaurants, cuisines, food types, and ratings.
- Presenting business data through interactive visualizations.
- Applying data storytelling principles to dashboard development.

---

## Project Structure

```text
Zomato-End-To-End-Data-Analysis/
│
├── README.md
├── Zomato.pbix
│
├── data/
│   ├── README.md
│   └── Zomato_Dataset.csv
│
└── screenshots/
    ├── Home_page.png
    ├── overview.png
    ├── user_performance.png
    ├── city_analysis.png
    ├── restaurant_analysis.png
    └── insights.png
### Author

**Kanak Verma**

Aspiring Data Analyst | Power BI | DAX | Data Analytics

---

## ⭐ If you found this project helpful, consider giving it a star!
TopN_Sale
Dynamic_TopN
Dynamic_subheading


---

