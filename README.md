# Data Cleaning Process

* Removed duplicate records.
* Converted the dataset into an Excel Table for easier analysis.
* Used the TRIM() function to remove leading and trailing spaces from text fields.
* Checked for missing values by filtering blank cells.
* Replaced missing values in the CouponCode column with “No Coupon” since a blank value indicated that no coupon was applied.
* Corrected data types by formatting dates, text, and numeric columns appropriately.
* Verified the dataset for inconsistencies before proceeding with analysis.

## Why I Used “No Coupon”?. 
Blank values in the CouponCode column represented orders where customers did not use a coupon. Replacing blanks with “No Coupon” made the data easier to analyze and ensured these records were included in coupon usage analysis.
