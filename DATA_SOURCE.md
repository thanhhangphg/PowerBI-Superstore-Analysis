# Data Source

## Overview
This project uses the **Kaggle Superstore Dataset (Final)**, which contains transactional sales data for a retail superstore from **2014 to 2017**. The dataset is widely used for analytics, visualization, and business intelligence practice.

## Source
- Platform: Kaggle  
- Dataset: *Superstore Dataset (Final)*  
- Origin: Community-contributed dataset (commonly adapted from Tableau sample data)

## Data Description
The dataset includes order-level transactional data with the following key fields:

- **Order Information**: Order ID, Order Date, Ship Date, Ship Mode  
- **Customer Information**: Customer ID, Customer Name, Segment  
- **Geography**: Country, City, State, Postal Code, Region  
- **Product Information**: Product ID, Category, Sub-Category, Product Name  
- **Sales Metrics**: Sales, Quantity, Discount, Profit  

## Data Model
The dataset was transformed into a **star schema** for Power BI:

- **Fact Table**
  - `Orders`: Contains transactional data (Sales, Profit, Quantity, Discount)

- **Dimension Tables**
  - `Customers`
  - `Products`
  - `Geography`
  - `Date`

## Data Preparation
The following preprocessing steps were applied:

- Cleaned missing or inconsistent values  
- Standardized data types (dates, numeric fields)  
- Created a dedicated **Date table** for time intelligence  
- Built calculated columns and measures using **DAX**  

## Limitations
- The dataset is **synthetic/sample data**, not from a real company  
- No external factors (e.g., macroeconomic indicators) are included  
- Static historical data (2014–2017), no real-time updates  

## Usage
This dataset is used for **educational and portfolio purposes**, showcasing:

- Data modeling (star schema design)  
- DAX and analytical calculations  
- Interactive dashboard development in Power BI  

## License
Refer to the dataset page on Kaggle for licensing and usage terms.
