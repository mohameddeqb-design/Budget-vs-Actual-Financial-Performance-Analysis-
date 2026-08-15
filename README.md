# Budget vs Actual Financial Performance Analysis Dashboard

## 📊 Project Overview

This project presents an end-to-end **financial analysis and business intelligence solution built in Microsoft Excel**.

The objective was to transform a raw Budget vs Actual financial dataset into a structured analytical model and management dashboard capable of answering key business questions:

- How much was budgeted?
- How much was actually spent?
- Are we over or under budget?
- Which departments are driving financial variance?
- Which expense categories require attention?
- Which regions are performing best or worst?
- How is spending changing over time?
- Where should management focus its resources?

The final deliverable combines **data cleaning, financial modelling, variance analysis, KPI development, data visualization and management recommendations**.

---

## 🎯 Business Problem

Organizations need to continuously monitor actual spending against approved budgets to identify financial risks, improve resource allocation and support evidence-based decision-making.

The raw dataset contained duplicate records, missing values and data-quality issues that needed to be addressed before reliable financial analysis could be performed.

This project was designed to create a repeatable analytical workflow from:

**Raw Data → Data Cleaning → Financial Calculations → Analysis → Visualization → Insights → Recommendations**

---

## 📁 Dataset

The original dataset contained:

- **10,010 financial records**
- **8 fields**
- Data covering **2021–2023**
- Department information
- Expense categories
- Regional information
- Budget amounts
- Actual spending
- Transaction IDs
- Payment methods
- Transaction dates

After data-quality treatment, the analytical dataset contained:

**10,000 clean records**

---

## 🧹 Data Cleaning & Quality Assessment

The dataset was systematically assessed before analysis.

### Data-quality checks included:

- Duplicate detection
- Missing-value analysis
- Data-type validation
- Financial-value validation
- Date validation
- Category standardization
- Department standardization
- Regional standardization
- Transaction ID validation
- Outlier analysis

### Key findings

| Data Quality Check | Result |
|---|---:|
| Original Records | 10,010 |
| Duplicate Records | 10 |
| Clean Analytical Records | 10,000 |
| Records with Missing Values | 8 |
| Negative Financial Values | 0 |
| Zero Financial Values | 0 |
| IQR Outliers in Actual Amount | 0 |

The original dataset was preserved separately from the cleaned analytical dataset.

---

## 💰 Financial Performance

The overall analysis produced the following results:

| KPI | Result |
|---|---:|
| Total Budget | 795.47M |
| Total Actual Spending | 890.27M |
| Total Variance | **94.80M** |
| Variance % | **11.9%** |
| Budget Utilization | **111.9%** |
| Transactions | **10,000** |
| Over-Budget Transactions | **5,590** |
| Under-Budget Transactions | **4,410** |

### Key finding

Actual spending exceeded the total approved budget by approximately **94.8M**, resulting in an overall budget utilization rate of **111.9%**.

This indicates a significant level of aggregate overspending that warrants further investigation into the departments, expense categories and periods contributing to the variance.

---

## 📈 Analysis Performed

### 1. Department Analysis

Departments were evaluated using:

- Total Budget
- Total Actual Spending
- Total Variance
- Variance %
- Budget Utilization %
- Transaction Count
- Average Transaction Value

The analysis identified departments with the largest budget allocations, highest spending levels and greatest financial variances.

---

### 2. Expense Category Analysis

Expense categories were evaluated to determine:

- Spending concentration
- Budget allocation
- Actual expenditure
- Budget variance
- Budget utilization
- Transaction volume

**Salaries** emerged as the largest named expense-category overspend in the analysis.

---

### 3. Regional Analysis

Regional performance was compared using:

- Budget
- Actual Spending
- Variance
- Variance %
- Utilization %
- Transaction Count

This allows management to identify regions where financial performance differs materially from expectations.

---

### 4. Time-Series Analysis

Financial performance was analyzed across the available 2021–2023 period.

The analysis examined:

- Monthly budget
- Monthly actual spending
- Monthly variance
- Monthly variance %
- Budget utilization

This provides visibility into spending patterns and periods requiring additional management attention.

---

### 5. Payment Method Analysis

Payment methods were also analyzed based on:

- Transaction volume
- Spending levels
- Average transaction value

Payment-method analysis was treated as a supporting analysis rather than forcing conclusions where the dataset did not provide a strong business insight.

---

## 📊 Dashboard

The final Excel dashboard was designed as a management-facing reporting interface.

### Dashboard KPIs

The dashboard highlights:

- **Total Budget**
- **Total Actual**
- **Total Variance**
- **Variance %**
- **Budget Utilization**
- **Transaction Count**

### Visualizations

The dashboard includes visual analysis of:

- Budget vs Actual by Department
- Monthly Budget vs Actual
- Budget Variance by Department
- Spending by Expense Category
- Regional Budget vs Actual
- Budget Utilization by Department

The design prioritizes **clarity, analytical relevance and decision-making** rather than excessive visual elements.

---

## 🧮 Financial Metrics

The analysis uses core financial performance measures including:

### Budget Variance

```text
Actual Amount − Budget Amount
