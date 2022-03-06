# surfs_up

## Overview of the analysis:

W. Avy wants more information about temperature trends before opening the surf shop in Oahu.
Specifically, he wants temperature data for the months of June and December in Oahu, in order to determine if the surf and ice cream shop business is sustainable year-round.

## Results: 

- Using Python, Pandas functions and methods, and SQLAlchemy, I filtered the date column of the Measurements table in the Hawaii. SQLite database to retrieve all the temperatures 
for the month of June and December.
- Then convert those temperatures to a list 
- Create a Data Frame from the list 
- Generate the summary statistics.
### June Temps - Analysis and Result

- Count of 1700
- Mean of 74.94
- Std of 3.26
- Min of 64.00
- 25% of 73.00
- 50% of 75.00
- 75% of 77.00
- Max of 85.00

![June Report](https://user-images.githubusercontent.com/96403349/156871051-341027f5-bfa0-4bfd-906c-d7190c10b0a5.png)

### December Temps - Analysis and Result

- Count of 1517
- Mean of 71.04
- Std of 3.75
- Min of 56.00
- 25% of 69.00
- 50% of 71.00
- 75% of 74.00
- Max of 83.00

![December Report](https://user-images.githubusercontent.com/96403349/156871132-fc2696c1-1ace-4855-adce-f65b534666e2.png)

## Summary: 

Based on the data analysis, we can state that heat and good temp is great to consider for a surf shop. 
If we notice that Standard deviation is 3.25 in June and 3.75 in December which helps to decide where he would like to build shop.
and which areas make this location attractive to visitors and have a successful business.

