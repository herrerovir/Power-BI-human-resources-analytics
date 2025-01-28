# 👔🎯 Human resources analytics

This repository contains a human resources analysis project using Power BI.  

## Table of content
 - [Introduction](https://github.com/herrerovir/Power-BI-human-resources-analytics/blob/main/README.md#Introduction)
 - [Goal](https://github.com/herrerovir/Power-BI-human-resources-analytics/blob/main/README.md#Goal)
 - [Project overview](https://github.com/herrerovir/Power-BI-human-resources-analytics/blob/main/README.md#Project-Overview)
 - [Dependencies](https://github.com/herrerovir/Power-BI-human-resources-analytics/blob/main/README.md#Dependencies)
 - [Technical skills](https://github.com/herrerovir/Power-BI-human-resources-analytics/blob/main/README.md#Technical-skills)
 - [Dataset](https://github.com/herrerovir/Power-BI-human-resources-analytics/blob/main/README.md#Data-set)
 - [Data loading](https://github.com/herrerovir/Power-BI-human-resources-analytics/blob/main/README.md#Data-loading)
 - [Data cleaning](https://github.com/herrerovir/Power-BI-human-resources-analytics/blob/main/README.md#Data-cleaning)
 - [Data modeling](https://github.com/herrerovir/Power-BI-human-resources-analytics/blob/main/README.md#Data-exploration)
 - [Data analysis](https://github.com/herrerovir/Power-BI-human-resources-analytics/blob/main/README.md#Data-visualization)
 - [Data visualization](https://github.com/herrerovir/Power-BI-human-resources-analytics/blob/main/README.md#Insights)

## Introduction
HR analytics, or people analytics, involves the collection, analysis, and reporting of HR data to enhance business outcomes. It enables organizations to gain deeper insights into their employees, make informed, data-driven decisions, and ultimately improve overall business performance.

## Goal
The primary objective of this project is to analyze employee performance and job satisfaction at a fictitious company for the year 2024. Additionally, the project aims to visualize key performance indicators (KPIs) and other valuable insights derived from the analysis.

## Project overview
1. Data loading
2. Data cleaning
3. Data modeling
4. Data analysis
5. Data visualization

## Dependencies
The following tools are required to carry out this project:

* Power BI desktop

## Technical skills
Throughout the implementation of this project, the following skills were utilized:

* Data extraction, transformation and loading
* Data modeling
* Data analysis
* Data visualization

## Dataset
The dataset for this analysis comprises two Excel files, located in this repository as: Hr-analytics-data.xlsx and Hr-employee-data.xlsx.

## Data loading
The data is imported directly from the Excel files into Power BI.

## Data cleaning
Once the data is loaded into Power BI, it undergoes a preprocessing phase to ensure its integrity and reliability. This phase involves cleaning and transforming the data using Power Query within Power BI.

The preprocessing workflow includes renaming columns, adjusting data types, and removing null and duplicate values.

After cleaning, the dataset is loaded into Power BI for further analysis and visualization.

## Data modeling
To create consistent, high-quality structured data and achieve reliable results, the data will be modeled using a star schema. This model distinguishes between fact data, which contains measurable and quantitative information about a business, and dimension data, which includes descriptive attributes related to the facts.

In this case, the original table loaded into Power BI serves as the fact table, storing the quantitative information needed for the analysis. Four dimension tables are created to hold descriptive information: employee, education, performance rating and satisfaction.

The final step in data modeling involves establishing relationships between the dimension tables and the fact table.

The following image illustrates the entity relationship diagram for this project.

![Star Data Model](https://github.com/user-attachments/assets/e4df9113-a693-4218-83b2-c2d9922b3999)

## Data analysis
A comprehensive data analysis was conducted to gather relevant information on employee demographics, performance and turnover/attrition rates. This analysis involved the creation of multiple measures using DAX functions to improve the analysis process.

## Data visualization
Data visualization is crucial in data analysis, serving as the stage where insights and conclusions are effectively communicated. I utilized Power BI to transform this dataset into an engaging, interactive dashboard.

The dashboard features four pages: overview, demographics, attrition, and employee performance analysis. It is interactive, enabling users to select and display results for specific areas of interest.

**Dashboard preview**
This section displays the complete HR dashboard. The original file, Hr-analytics.pbix, is available in this repository for download. You can save it to your local machine and preview it directly on your computer to interact with the dashboard and fully explore its features. The panel shown here serves as a reference for my work.

![Overview](https://github.com/user-attachments/assets/453885dc-8f71-4c26-b57f-7165ab51e551)

![Demographics](https://github.com/user-attachments/assets/9862347e-94c0-423f-a283-538a9799c759)

![Attrition](https://github.com/user-attachments/assets/fbe65497-b74c-407d-974b-78112e63a197)

![Performance](https://github.com/user-attachments/assets/13981615-ac2b-4891-9f95-a2dafa780031)






