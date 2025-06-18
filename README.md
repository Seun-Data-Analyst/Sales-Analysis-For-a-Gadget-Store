# Sales-Analysis-For-a-Gadget-Store
A detailed analysis on sales for a gadget store using Excel tool 
# 📊 Gadgets Dataset Analysis Report

## 1. Introduction

The **Gadgets dataset** is a comprehensive collection of data on a wide range of electronic devices, including smartphones, headphones, laptops, tablets, and smartwatches. It provides essential insights into the technology market to assist researchers, developers, and consumers in making informed decisions and conducting in-depth analysis.

### 1.1 Objectives

I. Analyze consumer preferences and market trends  
II. Educate users about the benefits of various gadgets  
III. Determine the most preferred product type among several age groups  
IV. Identify the most preferred shipping type  
V. Analyze pricing trends over time to help consumers find the best deals and guide manufacturers in pricing strategies  
VI. Support researchers in identifying market gaps and opportunities for new product development  
VII. Present key metrics using Excel dashboards for better understanding and interpretation of the data  

### 1.2 Scope

This report specifically examines the following key variables:

- **Gadget Analysis**: Number and market representation of different gadgets  
- **Price Evaluation**: Analyze pricing range to assess market positioning and affordability  
- **Pricing Information**: Retail prices including loyalty member discounts  
- **Market Trends**: Trends in consumer preferences and technology innovations  
- **Comparative Analysis**: Compare gadgets by features, pricing, and ratings  

### 1.3 Dataset Overview

- **Data Source**: Reliable gadget industry database  
- **Size**: 8,021 rows × 19 columns  

**Key Columns:**

| Column              | Description                                            |
|---------------------|--------------------------------------------------------|
| `SKU`               | Unique identifier for each product                    |
| `AGE GROUP`         | Useful for demographic analysis                        |
| `GENDER`            | Helps understand customer profiles                     |
| `LOYALTY MEMBER`    | Indicates customer loyalty status                      |
| `PRODUCT TYPE`      | Categorizes products                                   |
| `ORDER STATUS`      | Tracks order fulfillment                               |
| `PAYMENT METHOD`    | Important for financial analysis                       |
| `SHIPPING TYPE`     | Relevant for logistics analysis                        |
| `TOTAL PRICE`       | Overall cost per order                                 |
| `UNIT PRICE`        | Price per unit item                                    |
| `QUANTITY`          | Helps analyze inventory and sales                      |
| `PURCHASE DATE`     | Key for trend analysis                                 |
| `MONTH OF PURCHASE` | Useful for seasonal analysis                           |
| `RATING`            | Indicates customer satisfaction                        |
| `ADDS ON PURCHASED` | Useful for cross-selling strategy                      |

---

## 2. Data Cleaning Process

1. **Removing Duplicates**  
   - Removed duplicates after checking key relevant columns  

2. **Standardizing Data Formats**  
   - Used Excel functions like `TEXT()` for dates, and `UPPER()`/`LOWER()` for consistent text formatting  

3. **Correcting Data Entry Errors**  
   - Corrected typos using Excel's `Find and Replace`  

4. **Added New Columns**  
   - `AGE GROUP`: For better demographic segmentation  
   - `MONTH AND YEAR OF PURCHASE`: For monthly and yearly trend analysis  
   - `FINAL TOTAL AFTER ADDS-ONS`: Total cost including accessories, warranties, etc.

---

## 3. Exploratory Data Analysis (EDA) & Visualization

### 3.1 Financial Overview

- **Base Sales Total**: `$25,317,097.24`  
- **Add-ons (Accessories, Warranties, Impulse Items)**: `$501,312.36`  
- **Final Total**: `$25,818,409.60`
- ![Screenshot 2025-06-18 133713](https://github.com/user-attachments/assets/0489a3f7-e3b0-43d5-bd73-17923afa1644)


### 3.2 Customer & Quantity Analysis

- **Total Customers**: `8,020` (4,083 males and 3,937 females)  
- **Total Quantity Ordered**: `46,661`  
- **Average Quantity per Customer**: `5.44`
- ![Screenshot 2025-06-18 134129](https://github.com/user-attachments/assets/6b2a8e3a-1c8a-481d-bc73-b1e858eaabc8)


### 3.3 Product Segmentation Analysis

- **Top-selling Product**: Smartphones  
- **Least-selling Product**: Headphones  
- **Highest Quantity Ordered**: Smartphones  
- **Lowest Quantity Ordered**: Headphones
- ![Screenshot 2025-06-18 134223](https://github.com/user-attachments/assets/c88aed5f-b3d2-4218-8c4f-e5546860c235)


### 3.4 Age Group Segmentation

- **Age Groups**: Young, Middle-aged, Old  
- **Highest Purchases & Spending**: Older age group
- ![Screenshot 2025-06-18 135719](https://github.com/user-attachments/assets/3edc7d92-f4a8-495e-a01f-6b6f2594da2c)


### 3.5 Logistics (Shipping Type) Analysis

- **Shipping Types Used**: Expedited, Express, Overnight, Same Day, Standard  
- **Most Preferred**: Standard Delivery
- ![Screenshot 2025-06-18 140109](https://github.com/user-attachments/assets/7876048d-80e4-467f-81f9-4182b68a6fd4)


### 3.6 Payment Method Analysis

- **Payment Options**: Bank Transfer, Cash, Credit Card, Debit Card, Paypal  
- **Most Preferred**: Paypal and Credit Card
- ![Screenshot 2025-06-18 140600](https://github.com/user-attachments/assets/41ea2da4-5ca9-4b9b-aeee-0e7cf53f2635)


### 3.7 Monthly and Yearly Trends

- **Sales Range**: From January 2023 to December 2024
- ![Screenshot 2025-06-18 140633](https://github.com/user-attachments/assets/ad3fc04e-7a33-4c39-9b59-7063a61ed150)


---

## 4. Key Insights from Data

### 4.1 Financial Summary

- Total sales: **$25,317,097.24**  
- Add-ons: **$501,312.36**  
- Final total revenue: **$25,818,409.60**

### 4.2 Customer & Order Quantity

- Customers: **8,020**  
- Quantity Ordered: **46,661**  
- Average per customer: **5.44**

### 4.3 Sales by Product

- **Top Seller**: Smartphones  
- **Lowest Seller**: Headphones

### 4.4 Sales by Age Group

- **Top Spend Group**: Older customers  
- **Most Active Buyers**: Older customers

### 4.5 Shipping Preferences

- Standard delivery is the most preferred shipping type

### 4.6 Payment Method Preferences

- **Top Choices**: Paypal and Credit Card

### 4.7 Temporal Trends

- Data covers two years: **2023–2024**

---

## 5. Strategic Recommendations

- **Boost Add-ons**: Promote accessories and extended warranties to increase average order value  
- **Targeted Marketing**: Tailor ads for both genders based on purchasing behavior  
- **Smartphone Focus**: Maintain visibility and marketing for high-selling smartphones  
- **Improve Headphone Sales**: Investigate poor performance and act on feedback, consider promotions  
- **Optimize Shipping**: Highlight standard shipping in promotions; ensure efficient delivery in all types  
- **Payment Incentives**: Offer discounts for less-used payment methods to encourage adoption  
- **Engaging Content**: Create blogs and videos showcasing gadget features to boost engagement  
- **Loyalty Programs**: Introduce reward systems for repeat customers to drive loyalty and retention  

---

## 6. Conclusion

In summary:

- **Smartphones** are a key revenue driver; focus marketing here  
- **Headphones** underperform; investigate and improve positioning  
- Use **customer feedback**, **targeted promotions**, and **enhanced visibility** to maximize gadget sales  
- Emphasize **standard delivery**, **popular payment methods**, and **add-on items** to optimize performance  
- Adopt **loyalty strategies** and **educational content** to increase engagement and customer retention
