# Diwali-Sales-Analysis
This project focuses on analyzing **Diwali sales data** using Python libraries like **Pandas**, **NumPy**, **Matplotlib**, and **Seaborn**. The goal is to extract valuable business insights such as customer behavior, top-selling products, and sales trends across demographics, states, and product categories.
## 🔧 Tools & Technologies
- **Python**
  - Pandas
  - NumPy
  - Matplotlib
  - Seaborn
- **Jupyter Notebook**
  ## Dataset
The dataset contains sales data including customer information, product details, and purchase behavior during Diwali.

**Key Columns:**
- Gender
- Age Group
- State
- Marital Status
- Occupation
- Product Category
- Amount
- Orders

## 🔍 Data Cleaning Steps
1. **Import Data:** Loaded dataset into Jupyter Notebook using Pandas.
2. **Remove Nulls:** Dropped null values from `Status` and unnamed columns.
3. **Handle Null in Amount:** Removed rows with null values in `Amount`.
4. **Data Type Conversion:** Converted `Amount` column to integer using `.astype(int)`.
5. **Column Check:** Verified columns using `df.columns`.

## Exploratory Data Analysis (EDA)

### 1. Gender-Based Analysis
- **Insight:** Females purchased more compared to males.
- **Visualization:** Count plot and bar plot showing total sales by gender.

### 2. Age Group Analysis
- **Insight:** Most buyers are in the **26-35 years** age group.
- **Visualization:** Count plot with gender hue and sales by age group.

### 3. State-Wise Analysis
- **Top States by Orders and Amount:**
  - Uttar Pradesh
  - Maharashtra
  - Karnataka
- **Visualization:** Bar plots for top 10 states by orders and sales.

### 4. Marital Status Analysis
- **Insight:** Married women are the top buyers.
- **Visualization:** Count plot and bar plot comparing sales by marital status and gender.

### 5. Occupation Analysis
- **Top Occupations by Sales:**
  - IT
  - Healthcare
  - Aviation
- **Visualization:** Count plot and sales bar plot by occupation.

### 6. Product Category Analysis
- **Top Categories:**
  - Food
  - Clothing
  - Electronics
- **Visualization:** Count plot and bar plot by product category.

### 7. Top-Selling Products
- **Insight:** Identified top 10 products by `Product_ID` based on number of orders.
- **Visualization:** Bar chart for top 10 most sold products.

## Conclusion
**Key Buyers:**
- **Married women** aged **26–35 years**
- From **UP, Maharashtra, Karnataka**
- Working in **IT, Healthcare, Aviation**
- Prefer **Food, Clothing, and Electronics**

##  Files Included
- `Diwali_Sales_Analysis.ipynb` – https://github.com/Saniya7861515/Diwali-Sales-Analysis/blob/main/Diwali_Sales_Analysis.ipynb
- `Diwali Sales Data.csv` – https://github.com/Saniya7861515/Diwali-Sales-Analysis/blob/main/Diwali%20Sales%20Data.csv

##  Note
This project demonstrates data cleaning, analysis, and visualization skills using Python. It can help businesses target the right customer segment during festive seasons like Diwali.

