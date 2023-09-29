# Coffee-Sales-Project
I downloaded this dataset from Kaggle and my goal was to make a dashboard where i would be display:
- A line chart of the Total Sales Over Time.
- A bar chart of The Sales By Country.
- A bar Chart of the Top 5 Customers.

# Gathering Information
- The first thing I did was to create a Customer Name, Email and Country column in the Order worksheet and I gathered the information using the XLOOKUP function.
- Then I made the Coffee Type, Roast Type, Size and Unit Price column that I filled using the Index Match function.
- I made a Sales column and I filled it using a calculation.
- Finally I created two new column the Coffee Type Name and Roast Type Name so that I can clearly understand what the abbreaviation in the Coffee Type and Roast Type column means. I used the IF statement for that.

# Formatting 
- I firstly started by formatting the order date column from a MM/DD/YYYY to a DD-MMM-YYYY which was easier for me.
- Then I removed all the duplicate and I formatted my worksheet as table.
- After that I made Loyalty Card column in the Order worksheet and I used the XLOOKUP to fill the column.

# Pivot Table
Here I made Three Pivots Tables where i wanted to get:
- The total sales over times by coffee type.
- The Sales by country where i could see that the United States was the first country with the most sales and the coffee type that was sold the most is Arabica.
- The Top 5 customers
