#  Customer Transactions Data Analysis using Excel 2021

Hello everyone!  
I'm pleased to share my journey of conducting detailed **data analysis** on a **Customer Transactions** dataset using **Microsoft Office Excel 2021**.  
This project demonstrates how Excel can be leveraged for interactive and insightful business analysis.

---

## 🔧 Tools Used
- Microsoft Excel 2021

---

##  Steps Followed in the Analysis

### 1. 🧹 Data Cleaning
- Converted the raw dataset into a structured Table format.
- Cleaned and refined data for improved readability.
- Formatted the **Purchase Amount** column to display values in ₹ (rupees).
- Added a new column titled **"Status"** to indicate whether a purchase was made using the formula:

  ```excel
  =IF([@[Purchase Amount]]=0, "No", "Yes")
  ```

- Enabled filtering to show only the customers who made purchases (Status = "Yes").

---

### 2. 📈 Trend Analysis
- Created a **PivotTable** to summarize data trends over time.
- Placed **Dates** in the Rows field and **Purchase Amount** in the Values field.
- Added a **Line Graph** to visualize purchasing trends.
- Cleaned up the graph by hiding years and quarters for a clearer view.
- Users can filter by specific dates to drill down into customer details.

---

### 3. 👤 Person-wise Analysis
- Created a separate worksheet for individual customer analysis.
- Used Excel formulas like:
  - `COUNTIFS` – Count of transactions  
  - `SUMIFS` – Total amount spent  
  - `MAXIFS` – Highest single purchase  
- Users can input a customer name to dynamically view their transaction data.

---

### 4. 🛒 Purchase Modes Analysis
- Built a PivotTable to analyze the mode of purchase and corresponding amounts.
- Sorted the data for better interpretation.
- Used formulas such as `SUMIFS` and `COUNTIFS` for aggregations.
- Applied **Data Bars (Conditional Formatting)** for a quick visual comparison.

---

### 5. 👥 Customer Analysis by Job Title
- Categorized customers based on **Job Titles**.
- Created a PivotTable displaying **Job Title**, **Purchase Amount**, and **Time**.
- Formatted transaction amounts using the ₹ symbol.
- Applied **Color Scales (Conditional Formatting)** to show data intensity.
- Integrated **Slicers** for easy filtering and dynamic analysis.

---

## 🎯 Outcome
These techniques enabled me to perform **quick**, **interactive**, and **visually compelling** data analysis.  
This kind of insight is crucial for making informed decisions and designing effective marketing strategies.

---

## 📁 Project Structure
```
📁 Customer_Transactions_Excel_Analysis/
├── excel-for-data-analysis.xlsx
├── README.md
```

---

## 🙌 Let's Connect
If you have any feedback or want to collaborate, feel free to connect! [My LinkedIn](https://www.linkedin.com/in/mohansaipandeti)

