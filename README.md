# Udemy Courses Data Analysis

## Overview

This project involves analyzing the Udemy course dataset to extract meaningful insights about online learning trends, course performance, and student engagement. With the rapid growth of online education platforms, understanding what makes courses popular and effective can help improve offerings and learner satisfaction.

The project walks through the full data analysis pipeline — from **data loading and cleaning** to **exploratory data analysis (EDA)**, **visualization**, and **deriving actionable insights**.

## Dataset Details

The dataset used in this project is publicly available on Kaggle: [Udemy Courses Dataset](https://www.kaggle.com/datasets/ahmedashfaq6777/udemy-courses-dataset).

**Key features of the dataset include:**

* **Course Title:** Name of the Udemy course.
* **Subject:** Category of the course (e.g., Business, Web Development, Graphic Design).
* **Price:** Cost of the course in USD.
* **Number of Subscribers:** Total number of students enrolled.
* **Number of Reviews:** Student reviews available.
* **Content Duration:** Total duration of the course in hours.
* **Published Timestamp:** Date the course was launched.
* **Course Rating:** Overall average rating provided by students.

This dataset provides an opportunity to analyze factors that contribute to a course’s popularity and quality.

## Project Highlights

### 1. Data Loading

* Loaded the Udemy dataset into a Jupyter Notebook.
* Explored its structure using Pandas functions like `.head()`, `.info()`, and `.describe()`.

### 2. Data Cleaning

* Handled missing values in columns.
* Converted data types (e.g., timestamps to datetime).
* Removed unnecessary or duplicate records to ensure data consistency.

### 3. Exploratory Data Analysis (EDA)

* Summarized descriptive statistics for numerical and categorical variables.
* Explored distributions of key features such as ratings, subscribers, and course durations.
* Identified outliers that could influence analysis results.

### 4. Data Visualization

* Created bar plots, histograms, and scatter plots to visualize course characteristics.
* Compared ratings across subjects and pricing models.
* Visualized subscriber trends and engagement patterns.

### 5. Course Ratings Analysis

* Analyzed the distribution of ratings across all courses.
* Explored relationships between course ratings, number of subscribers, and course content duration.
* Identified potential factors that influence student engagement and satisfaction.

## Key Insights

* **Popularity Trends:** Courses with higher ratings generally attract more subscribers, indicating that perceived quality strongly impacts enrollments.
* **Engagement Drivers:** Longer and more comprehensive courses tend to engage students better, but excessively long courses may reduce satisfaction.
* **Pricing Impact:** Free and lower-priced courses attract significantly more subscribers, but ratings are not always correlated with price.
* **Content Relevance:** Certain subjects, particularly Web Development and Business, dominate in terms of popularity and subscriber base.

These insights can help educators and platforms design more effective and engaging courses to meet learner needs.

## Jupyter Notebook

The full analysis, including code, visualizations, and step-by-step explanations, is available in the notebook included in this repository.
