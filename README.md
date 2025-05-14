# Project Title

Blinkit Analysis Dashboard

Dashboard link:https://app.powerbi.com/groups/me/reports/08db1792-7a74-4ea8-ba00-641c372d88bb/8944ef63d02e60458831?experience=power-bi

Problem Statement:

Blinkit, a fast-growing online grocery delivery platform, generates vast amounts of sales data across various regions, store sizes, and product categories. However, the lack of a centralized, visual, and interactive system to analyze this data hinders timely decision-making and limits insight into sales performance.

This project aims to develop a dynamic sales dashboard using Power BI to visualize key performance indicators (KPIs), identify trends, and derive actionable insights that support strategic business decisions and improve operational efficiency.

Solution:


To address the need for actionable insights and centralized data visualization, a comprehensive sales dashboard was developed using Microsoft Power BI. The solution involved:

Collecting sales data from reliable sources such as Excel/CSV files.

Cleaning and transforming the data using Power Query Editor to ensure accuracy and consistency.

Modeling relationships between datasets to support multi-dimensional analysis.

Utilizing DAX functions to calculate key metrics such as total sales, average order value, product-wise performance, and customer ratings.

Designing an interactive and user-friendly dashboard that allows users to explore data by category, store type, region, and time period.

This solution enables Blinkit’s stakeholders to gain a real-time understanding of sales trends, identify high-performing segments, and make data-driven decisions to enhance overall business performance.



Tools and Technologies Used:

Power BI
Used to create dashboards, show data in charts and graphs, and make reports easy to understand.

DAX (Data Analysis Expressions)
Helped in doing calculations like totals, averages, and creating new data columns.

Power Query Editor
Used to clean the data, fix errors, and get it ready for analysis.

Microsoft Excel / CSV Files
Used as the source to bring in sales data for the project.

Data Modeling in Power BI
Connected different tables together to analyze the data correctly.


### 🧩 **Data Structuring & Preparation**

1. **Data Source Integration:**

   * Integrated data from sources like Excel/CSV files into Power BI.
   * Ensured structured input for dimensions like *Outlet Location*, *Size*, *Type*, *Sales*, *Ratings*, *Items*, and *Fat Content*.

2. **Data Cleaning & Transformation:**

   * Removed unnecessary columns and duplicate entries.
   * Handled missing values.
   * Converted data types (e.g., text to numbers, dates).

3. **Data Modeling:**

   * Established relationships between tables (e.g., outlet type, size, and sales).
   * Built a logical model for cross-filtering and interactivity.

---

### 📊 **Visual Enhancements & Dashboard Elements**

1. **KPIs (Top Metrics Cards):**

   * Created visual cards for:

     * **Total Sales**: \$1.20M
     * **Average Sales**: \$141
     * **No. of Items**: 8523
     * **Average Rating**: 3.9

2. **Interactive Filters (Slicers):**

   * Added filters for:

     * Outlet Location Type
     * Outlet Size
     * Item Type

3. **Charts & Visualizations:**

   * **Fat Content Pie Chart**:

     * Shows 64.6% low-fat dominance in sales.
   * **Bar Charts for Item Type**:

     * Fruits & Vegetables and Snack Foods as top-selling categories.
   * **Fat by Outlet (Bar Chart)**:

     * Sales comparison based on fat content and outlet tier.
   * **Line Area Chart** (Outlet Establishment Year vs Revenue):

     * Peaks in revenue observed in 2018.
   * **Donut Chart (Outlet Size)**:

     * Medium-size stores contributed highest to sales.
   * **Bar Chart (Outlet Location)**:

     * Tier 3 cities lead in revenue generation.
   * **Matrix Table (Outlet Type)**:

     * Detailed analysis with Total Sales, Items, Average Sales, Ratings, and a calculated Index (Item Value Index).

---

### 🔧 **DAX and Calculation Enhancements**

* Created **measures** for:

  * Total Sales
  * Average Sales
  * Number of Items
  * Average Rating
* Used **calculated columns** for grouping item types and calculating ratios (like Fat Content %).
* Derived advanced metrics such as the **Item Value Index**.

---

### 🎯 **User Experience Enhancements**

* Used color coding to represent performance (Green-Yellow for sales, Pink/Blue for ratings and averages).
* Included switchable tabs (Total Sales, Avg Sales, No of Items, Avg Rating) to change the view dynamically.
* Applied hover effects or tooltips for interactivity.

---

### ✅ Summary of Key Changes Made:

| Change Area              | Action Taken                                                     |
| ------------------------ | ---------------------------------------------------------------- |
| **Data Cleaning**        | Handled missing values, removed duplicates, adjusted data types. |
| **Data Modeling**        | Created relationships between various data tables.               |
| **Visual Design**        | KPIs, donut charts, bar charts, matrix visuals used.             |
| **Interactivity**        | Slicers added for filters, chart interactions built-in.          |
| **Advanced Analysis**    | Used DAX for creating custom measures and calculated columns.    |
| **Insight Presentation** | Visual storytelling through clear design and smart use of space. |

---

Output:

![Image](https://github.com/user-attachments/assets/fb87e651-f246-400c-8cd2-7cc066f3231e)







    


