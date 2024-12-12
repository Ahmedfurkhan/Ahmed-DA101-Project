# Data Analytics 101: E-commerce Performance Analysis

## Capstone Project Assignment Guide

This repository documents the E-commerce Performance Analysis capstone project, aiming to help an e-commerce marketplace understand customer behavior, sales patterns, and develop predictive models for future sales. Below, you'll find an overview of the project structure and phases.

---

## Project Overview

The project involves analyzing an e-commerce public dataset containing:

- Customer information
- Order details and status
- Product information
- Payment details
- Review ratings
- Geographic data

The analysis is structured into four phases:

1. Understanding and Preparing Your Data
2. Data Cleaning and Feature Engineering
3. Exploratory Data Analysis (EDA)
4. Statistical Analysis and Predictive Modeling

---

## Project Structure

### Phase 1: Understanding and Preparing Your Data (Part 1)

#### Part A: Initial Data Exploration
1. **Data Loading and Overview**:
   - Load and examine the structure of dataset tables.
   - Create a data dictionary.
   - Document table relationships.
   - File used: `Data Exploration.ipynb`

2. **Data Quality Assessment**:
   - Identify missing values.
   - Check for duplicates and outliers.
   - Verify column data types.
   - Document anomalies.
   - File used: `Data Exploration.ipynb`

#### Part B: Data Integration
1. **Planning Your Integration**:
   - Select tables needed for analysis.
   - Define join strategy and address potential challenges.
   - File used: `Data Exploration.ipynb`

2. **Creating Your Analytical Dataset**:
   - Combine tables with appropriate joins.
   - Verify accuracy and ensure no unintended data loss.
   - File used: `Data Exploration.ipynb`

### Phase 2: Data Cleaning and Feature Engineering (Part 2)

1. **Data Cleaning Strategy**:
   - Handle missing values, duplicates, and outliers.
   - Convert data types as required.
   - Document all decisions.
   - File used: `DataCleaning.ipynb`

2. **Feature Engineering**:
   - Create time-based, customer-centric, product-based, and geographical features.
   - Generate additional relevant features.
   - File used: `DataCleaning.ipynb`

3. **Data Validation**:
   - Ensure integrity of the cleaned dataset.
   - Verify correctness of engineered features.
   - File used: `DataCleaning.ipynb`

### Phase 3: Exploratory Data Analysis (Part 3)

1. **Temporal Analysis**:
   - Study daily, weekly, and monthly sales trends.
   - Analyze delivery times and payment patterns.
   - File used: `Exploratory Data Analysis.ipynb`

2. **Customer Analysis**:
   - Examine geographic distribution, spending habits, and review impacts.
   - File used: `Exploratory Data Analysis.ipynb`

3. **Product Analysis**:
   - Identify top-selling products/categories.
   - Analyze price distributions and product return rates.
   - File used: `Exploratory Data Analysis.ipynb`

### Phase 4: Statistical Analysis and Modeling (Part 4)

1. **Predictive Modeling**:
   - Formulate hypotheses and select target variables.
   - Build and evaluate regression models.
   - Document model development process.
   - File used: `Prediction Analysis.ipynb`

2. **Model Evaluation**:
   - Assess assumptions and interpret key metrics (R², RMSE, MAE).
   - Validate model performance on test data.
   - File used: `Prediction Analysis.ipynb`

---

## Getting Started

### Prerequisites
- Python 3.7 or above.
- Install required packages:
  ```bash
  pip install -r requirements.txt
  ```

### Running the Project
1. Clone the repository:
   ```bash
   git clone <repository_url>
   cd <repository_directory>
   ```
2. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
3. Execute notebooks in the following order:
   - `Data Exploration.ipynb`
   - `DataCleaning.ipynb`
   - `Exploratory Data Analysis.ipynb`
   - `Prediction Analysis.ipynb`

---

## Dataset Description

### Files
The dataset includes CSV files with customer, order, product, payment, review, and geographic data.

### Relationships
Documented relationships between tables:
- Customer ↔ Orders
- Orders ↔ Products
- Orders ↔ Payments
- Products ↔ Reviews

---

Feel free to reach out for any questions or suggestions!
