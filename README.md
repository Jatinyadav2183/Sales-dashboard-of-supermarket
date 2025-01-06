# Sales-dashboard-of-supermarket

Sales dashboard first look

![Dashboard photo](https://github.com/user-attachments/assets/00a7792c-d535-4614-a7e4-a71fec31b305)

# Project Report: Excel Dashboard Creation Process

## 1. Introduction:

   This project focuses on the creation and organization of an Excel workbook designed for analyzing sales data and presenting insights through a visual dashboard. The workbook is divided into several sheets, each with a distinct function that contributes to the overall process of data analysis and visualization. Below is a detailed description of each sheet within the workbook and the steps involved in creating the dashboard.

## 2. Excel Sheet Organization:

  ### 2.1. Input Data sheet:

   The "Input Data" sheet serves as the foundational source of raw data necessary for performing any analysis. This sheet is typically populated with detailed transaction records, which include a variety of information that forms the basis for the calculations, trend analyses, and visuals that follow.

   **Columns in the "Input Data" sheet**

  **Date:** The date on which the transaction took place. This column allows for time-based analysis and trend tracking.
  
  **Product and Category Details:** Information about the products sold, such as:
  
   **Product ID:** Unique identifier for each product.
   **Product Name:** The name of the product.
   **Category:** The category to which the product belongs.
   **Unit of Measure (UOM):** The unit in which the product is measured, such as pieces, kilograms, or liters.
  
  **Transaction Details:** Key metrics related to the transaction, including:
  
   **Quantity:** The number of items sold.
   **Sale Type:** The type of sale, for instance, regular or promotional.
   **Payment Mode:** The method of payment used (e.g., cash, credit card).
   **Discounts:** The discounts applied to the transaction.
   **Buying Price:** The price at which the product was purchased.
   **Selling Price:** The price at which the product was sold.
  
  **Calculated Columns:**
  
   **Total Buying Value:** The total cost for each transaction (calculated by multiplying the buying price by the quantity).
   **Total Selling Value:** The total revenue from each transaction (calculated by multiplying the selling price by the quantity).
  
  **Temporal Information:**
  
   **Day:** The specific day of the transaction (often extracted from the "Date" column).
   **Month:** The month of the transaction.
   **Year:** The year in which the transaction took place.

  This sheet plays a critical role in providing the necessary data for any analysis or visual representation. By processing and manipulating this data, various business metrics such as total sales, profit margins, and product performance can be derived.

  ### 2.2 Analysis Sheet

  The "Analysis" sheet is where raw data from the "Input Data" sheet is transformed into summarized, aggregated, and calculated data. This sheet typically serves as the intermediary between the raw data and the dashboard. It contains the results of advanced calculations and trend analyses, which will be used to create insights in the dashboard.

  **Key Functions of the "Analysis" Sheet:**

  Aggregated Metrics: Metrics such as:
  
   Total Sales
   Average Discount
   Category-Wise Performance
   Profit Margins
   Sales by Product or Region

  Trend Analysis: Analysis of sales trends over time, including:

   Monthly sales growth or decline
   Seasonal variations in product sales
   Year-on-year comparisons
   
  Calculated or Derived Fields: Additional calculations, such as profit (calculated from selling and buying prices), sales per employee, or per product category.
  
This sheet serves as a central point for data aggregation, ensuring that the final data presented on the dashboard is clear and insightful.

### 2.3 Dashboard Sheet

The "Dashboard" sheet is the heart of the workbook, containing the visual elements that represent key business metrics and trends. This sheet is where data from the "Analysis" sheet is turned into graphical elements that provide insights at a glance. Dashboards in Excel often rely on the program's powerful charting tools and pivot tables to present complex data in an intuitive, visually appealing format.

**Key Features of the "Dashboard" Sheet:**

  **Charts:** Graphical representations of metrics like sales over time, product performance, and profit margins.
  **Pivot Tables:** These tables allow users to filter and summarize the data based on different variables such as time, product category, and sales region.
  **Slicers:** Interactive filters that allow users to slice the data by various dimensions like product, region, or time period.
  **KPIs:** Key Performance Indicators, such as total sales, average transaction value, and profit, presented in a concise and clear format.

The dashboard provides a high-level view of the business performance and is an essential tool for decision-makers to quickly understand trends and key metrics.

### 2.4 Master Data Sheet

The "Master Data" sheet contains reference data that supports and validates the analysis and dashboard creation process. It typically includes lookup tables or metadata necessary for accurate and consistent analysis.

**Key Components of the "Master Data" Sheet:**

  **Category Hierarchies:** A structured list of product categories and subcategories for organizing products within the dataset.
  **Product Mappings:** Cross-references between product IDs and product names, along with additional product details.
  **Validation Lists:** Predefined lists used for dropdowns or slicers in the dashboard, such as a list of regions, sales types, or payment modes.
  **Other Metadata:** Additional information that is used to validate the input data or enrich the analysis, such as currency exchange rates or discount rules.

The "Master Data" sheet ensures that the data remains consistent and validated throughout the workbook, providing a reliable foundation for analysis and visualization.

## 3. Steps to Analyze and Document the Dashboard Creation Process

### 3.1 Understanding the Dashboard Structure

The dashboard sheet is fundamentally focused on presenting key metrics and trends visually. It includes graphical representations such as:

  **Charts:** Bar charts, line graphs, pie charts, and area charts that showcase metrics like total sales, product performance, and trends over time.
  **Pivot Tables:** These are used to summarize and filter data based on various criteria, offering more granular insights.
  **Slicers:** These interactive filters enable users to view the dashboard through different lenses, such as by time period, product category, or payment method.

By analyzing how these graphical elements are linked to the data in the "Analysis" sheet, it becomes clear that the dashboard serves as a tool for visualizing aggregated and processed metrics.

### 3.2 Analyzing the Input Data Sheet

The "Input Data" sheet contains a wealth of transactional details, and by leveraging this data, numerous metrics can be calculated. Key steps include:

**Data Cleaning:** Ensure that the data is free of errors, such as missing values or inconsistent formats.
**Data Aggregation:** Summarize the data at the appropriate level (e.g., monthly sales, total sales by product) for use in the analysis sheet.
**Deriving Key Metrics:** Using Excel formulas, calculate essential business metrics, such as profit margins, total sales, and average transaction value.

### 3.3 Analyzing the "Analysis" Sheet

Once the raw data is aggregated, advanced calculations and trend analysis are carried out in the "Analysis" sheet. Here, data is processed to derive insights like:

**Trends and Growth:** Analyze how sales have grown or declined over different periods.
**Performance Metrics:** Identify which products or categories are performing the best.
**Profitability:** Calculate profit margins and identify profitable sales types or payment methods.

### 3.4 Building the Dashboard

The final step is to take the summarized data from the "Analysis" sheet and present it visually in the "Dashboard" sheet. This includes:

**Designing the Layout:** Creating a clean, user-friendly layout with well-organized sections for each key metric.
**Incorporating Visual Elements:** Using charts and pivot tables to represent the data graphically.
**Adding Interactivity:** Including slicers for easy filtering of data and dynamic updates to the charts based on user selections.

## 4. Conclusion

The process of creating an Excel dashboard involves several critical steps, starting with gathering and preparing raw data in the "Input Data" sheet. The "Analysis" sheet transforms this data into meaningful metrics, which are then visually represented in the "Dashboard" sheet. Throughout this process, the "Master Data" sheet provides reference information to ensure accuracy and consistency. By following these steps, an interactive and insightful dashboard can be created to support informed decision-making.
