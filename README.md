# Sales Data Cleaning – Excel Project

## Project Overview
This project is part of my internship at **Elevate Labs**, focused on **data cleaning and preprocessing** using **Excel**.  
The dataset included product, price, and review information, and the goal was to make it **clean, consistent, and ready for analysis**.

## Steps Performed

1. **Removed unnecessary columns**  
   - Dropped columns like `user_id`, `user_name`, `img_link`, `product_link` to keep the dataset focused.

2. **Handled missing values**  
   - Checked for blanks in key columns (`rating_count`, `rating`).  
   - Filled missing `rating_count` values with the **median** for consistency.

3. **Cleaned and standardized prices** 
   - Removed unwanted symbols (`â‚¹`) from `discounted_price` and `actual_price`.  
   - Converted text to **numeric format**.  
   - Verified and recalculated `discount_percentage` using:
   =(actual_price - discounted_price)/actual_price*100

4. **Standardized Text Columns**
   - Cleaned `category` and `product_name` using **TRIM()** to remove extra spaces.  
   - Standardized capitalization with **PROPER()**.  
   - Fixed inconsistent category names with **Find & Replace**.  

5. **Removed Duplicates**
   - Ensured each product record was unique using Excel’s **Remove Duplicates** feature.  

6. **Final Touches**
   - Renamed column headers (lowercase, no spaces).  
   - Sorted data by `category` for readability.  
   - Applied filters for easy exploration and analysis.  

## Outcome
   - A clean and structured Excel dataset.   

## Next Steps
   - This cleaned dataset can now be used for **data analysis, reporting, or further projects**.


