# Advertising Dataset Analysis Project

This project involved analyzing an advertising dataset to derive meaningful insights about product categories, advertising costs, and platform effectiveness. The analysis was conducted using Microsoft Excel, focusing on data cleaning, manipulation, and visualization techniques.  

**Project Timeline:**  
- **Start Date:** 19th November 2024  
- **Completion Date:** 24th November 2024  

---

## Project Workflow

### **1. Data Collection and Preparation**  
- Downloaded the dataset from Kaggle and exported it to a dedicated project folder.  
- Created a duplicate file to preserve the original dataset.  

### **2. Data Cleaning and Transformation**  
- **Added Columns:**  
  - A new column for products with different product categories.  
  - A "Total Cost" column using the SUM function to calculate the total advertising cost for each product.  
- **Formatting:**  
  - Bolded headers for better visibility.  
  - Converted cost-related columns from "General" to "Currency" format.  
- **Data Quality Checks:**  
  - Applied filters to identify blanks.  
  - Used the "Remove Duplicates" function to eliminate duplicate entries.  

### **3. Data Analysis and Functions**  
- **Subtotal Function:**  
  - Calculated subtotals for all product categories.  
  - Transferred subtotal data to a new sheet using VLOOKUP.  
- **Data Restructuring:**  
  - Transposed advertising and total cost data as columns and labeled them "Advertisement" and "Totals," respectively.  
  - Converted formulas to values using "Paste Special" to preserve static results.  

### **4. Key Analytical Questions**  
1. What is the total cost based on product category?  
2. Which product category had the highest sales?  
3. Which advertising platform had the highest overall effectiveness?  
4. What are the top 3 product categories?  
5. Which are the top 3 advertising platforms to prioritize?  

---

## Challenges Encountered  
- **Duplicate Product Categories:**  
  - Identified duplicate product categories caused by inconsistent naming (e.g., spaces).  
  - Corrected by standardizing the names, ensuring data consistency.

---

## Insights and Conclusions  
1. **Highest Sales:** Technology and Gadgets had the highest percentage of product sales (~22.00%).  
2. **Lowest Advertising Cost:** Health and Wellness had the lowest advertising cost (~19.18%).  
3. **Top Investment Category:** Technology and Gadgets received the highest advertising investment (~34.64%).  
4. **Top Advertising Platform:** Television platforms accounted for the highest advertising expenditure (~33.76%).  
5. **Most Effective Combination:** Television advertising for Technology and Gadgets proved to be the most effective.  

**Overall Conclusion:**  
The **Television advertising platform** worked exceptionally well for **Technology and Gadgets**, which also garnered the highest investment. Meanwhile, **Health and Wellness** products achieved cost efficiency with relatively lower advertising expenditure.  

---

## Recommendations  
1. Prioritize **Television** for high-investment product categories like **Technology and Gadgets**.  
2. Focus future campaigns on the top-performing platforms while monitoring cost efficiency.  
3. Standardize data collection methods to avoid inconsistencies like duplicate entries or naming discrepancies.
