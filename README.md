# BlinkIT Grocery Sales Analysis

Student project (Sapphire IQ, Retail & Grocery Sales Analytics) using Python.

## What this project does
Analyses BlinkIT grocery sales data to understand:
1. The business and its sales performance
2. Whether the data is reliable (missing values, duplicates, unusual values, inconsistent labels)
3. What drives better sales (products, outlets, visibility, weight, ratings)
4. Practical suggestions for management

## Files
- `BlinkIT_Grocery_Sales_Analysis.ipynb` - the analysis notebook (code, charts and findings)
- `BlinkIT_Grocery_Data.xlsx` - the dataset (8,523 rows, 12 columns)

## Tools
Python, Pandas, NumPy, Matplotlib, Seaborn, Jupyter Notebook

## How to run
1. Keep both files in the same folder.
2. Install the libraries: `pip install pandas numpy matplotlib seaborn openpyxl notebook`
3. Run `jupyter notebook` and open `BlinkIT_Grocery_Sales_Analysis.ipynb`.

## Key findings
- Total sales are about 1.20 million; the average sale per record is about 141 and the average rating is 3.97 / 5.
- Sales depend mainly on how many products are sold, not on weight, visibility, rating or outlet size.
- The two Grocery Stores (OUT010, OUT019) sell about 40% less in total because they sell fewer products.
- Products sold in more outlets have higher total sales.
