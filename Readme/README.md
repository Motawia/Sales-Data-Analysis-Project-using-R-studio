This project analyzes a synthetic sales dataset to demonstrate data analysis techniques using **R**. The focus is on exploring sales performance, customer behavior, payment method preferences, and product profitability through data wrangling, statistical methods, and visualization.

---

## 📂 About the Dataset

**Source:** [Kaggle – Sales Dataset](https://www.kaggle.com/datasets/vinothkannaece/sales-dataset/data)  
**Disclaimer:** The dataset is **synthetic** and generated for **educational and practice purposes only**. It does not represent real-world sales and should not be used for business decision-making.

Each row represents a simulated sales transaction, including details on the product, customer, and sales representative.  

### Columns
1. **Product_ID** – Unique product identifier  
2. **Sale_Date** – Date of sale (2023)  
3. **Sales_Rep** – Sales representative (Alice, Bob, Charlie, David, Eve)  
4. **Region** – Region of sale (North, South, East, West)  
5. **Sales_Amount** – Total amount of sales (100–10,000 currency units)  
6. **Quantity_Sold** – Units sold (1–50)  
7. **Product_Category** – Product category (Electronics, Furniture, Clothing, Food)  
8. **Unit_Cost** – Cost per unit (50–5,000 currency units)  
9. **Unit_Price** – Selling price per unit (> Unit_Cost)  
10. **Customer_Type** – New or Returning  
11. **Discount** – Discount applied (0%–30%)  
12. **Payment_Method** – Payment method (Credit Card, Cash, Bank Transfer)  
13. **Sales_Channel** – Channel of sale (Online, Retail)  
14. **Region_and_Sales_Rep** – Combined field for tracking region × sales rep  

### Data Quality
- ✅ No missing values  
- ✅ No statistical outliers (based on IQR test)  

---

## 🛠️ Tools & Libraries

- **R** (analysis & visualization)  
- Libraries: `dplyr`, `ggplot2`, `lubridate`, `tidyr`, `readr´

---

## 📊 Analysis & Key Steps

1. **Data Cleaning**  
   - Checked for missing values  
   - Validated data types (dates, numeric values)  

2. **Exploratory Analysis**  
   - Sales trends (daily & monthly)  
   - Distribution of sales and profit  
   - Customer type behavior  
   - Payment method preferences  
   - Top profitable product categories  

3. **Statistical Check**  
   - Outlier detection using **IQR method**  
   - Confirmed no statistical outliers  

4. **Visualizations**  
   - Histograms and density plots  
   - Line charts (sales over time)  
   - Bar charts (customer type, payment methods, product profitability)  
   - Boxplots (profit distribution)  

-----

## 📈 Key Findings

- **Stable Data:** No missing values and no outliers detected.  
- **Customer Types:** Different purchase and payment preferences between New vs Returning customers.  
- **Payment Methods:** Clear variation in preferred methods (cash vs credit card, etc.).  
- **Profitability:** Certain product categories are consistently more profitable.  
- **Trends:** Daily and monthly sales follow recognizable patterns. 
