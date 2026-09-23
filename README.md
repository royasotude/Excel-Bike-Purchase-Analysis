# Excel Bike Purchase Analysis Dashboard

## Project Overview

This project analyzes customer characteristics and their relationship with bike purchasing behavior using Microsoft Excel.

The dataset contains customer-level information, including demographic, financial, educational, and lifestyle-related features. The main objective of the project was to clean and transform the data, explore patterns in bike purchasing behavior, and present the findings through an interactive Excel dashboard.

## Dataset

The dataset contains the following variables:

* **ID** – Unique customer identifier
* **Marital Status** – Customer's marital status
* **Gender** – Customer gender
* **Income** – Customer income
* **Education** – Customer education level
* **Occupation** – Customer occupation
* **Home Owner** – Whether the customer owns a home
* **Cars** – Number of cars owned
* **Commute Distance** – Distance between home and workplace
* **Region** – Customer's region
* **Age** – Customer age
* **Purchased Bike** – Whether the customer purchased a bike

## Data Cleaning \& Transformation

The original dataset was copied to a separate worksheet for cleaning and preparation.

The main data preparation steps included:

* Removing duplicate records
* Standardizing categorical values
* Replacing abbreviated values with more readable labels
* Creating an **Age Bracket** column to group customers into three categories:

  * Adolescent
  * Middle Age
  * Old

Grouping age into categories made it easier to identify patterns in bike purchasing behavior across different age groups.

## Exploratory Analysis

Three Pivot Tables were created to investigate the relationship between customer characteristics and bike purchases.

### 1\. Average Income by Gender and Bike Purchase

This analysis compares the average income of customers who purchased a bike with those who did not, separated by gender.

### 2\. Bike Purchase by Commute Distance

This analysis examines bike purchasing behavior across different commute-distance categories.

### 3\. Bike Purchase by Age Bracket

This analysis compares the number of customers who purchased and did not purchase a bike across the three age brackets.

Each Pivot Table was visualized using an appropriate Excel chart.

## Dashboard

The final dashboard combines the main visualizations into a single interactive view.

It includes four slicers that allow users to filter the analysis by:

* **Marital Status**
* **Region**
* **Education**
* **Cars**

These filters make it possible to explore specific customer segments and identify differences in bike purchasing behavior.

For example, the dashboard can be used to investigate whether the average income of married male customers who purchased a bike differs from that of single male customers who purchased a bike.

### Dashboard Preview

!\[Excel Bike Purchase Dashboard](Screenshot%20%2831%29.png)

## Key Skills Demonstrated

* Data Cleaning
* Data Transformation
* Excel Pivot Tables
* Pivot Charts
* Interactive Slicers
* Conditional Categorization
* Exploratory Data Analysis
* Dashboard Design
* Business-oriented Data Visualization

## Tools

* **Microsoft Excel**

## Project Structure

```text
Excel-Bike-Purchase-Analysis/
│
├── README.md
├── Excel Project Dataset.xlsx
└── Dashboard.png
```

## Project Goal

The goal of this project was to transform a raw customer dataset into an interactive analytical dashboard that can be used to explore customer segments and understand patterns associated with bike purchasing behavior.

