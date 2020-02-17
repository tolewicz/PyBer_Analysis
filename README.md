# PyBer_Analysis
Module 5 Data Visualization

## Project Overview
Conducting statistical analysis on PyBer taxi company
Investigate performance the efficiency and resources management based on fare price and number of drivers 

## Resources
-	Data source: schools_complete.csv , students_complete.csv
-	Software: Python 3.7.6, Visual studio code
- PyBer_Challenge.ipynb program 
  * Data acquisition, clean and initial processing in lines 1-73
  * Challenge calcualtion start from line 74

# PyBer Analysis Challenge


**Part 1: Analysis of the summary DataFrame  

![](/analysis/SumDataFrame.PNG)
(Table 1)

* The number of drivers scales down from urban to rural areas respectfully. 
* The largest number of drivers is in the urban area, the lowest number is in rural area. 
* The distribution of drivers, impact the average fare per driver – Pyride earning and fare per ride i.e. Pyride pricing. 
* The lowest average fare ride per ride and driver are for Urban area and the highest are for the rural area
* The ratio of drivers to rides for rural areas is ~0.6 which mean that there is not enough drivers and there is potential risk of loosing customers by skipping rides or long waiting time.
* The ratio in suburban area is ~0.8 which is the closest to optimal 1+ 
* The ratio of drivers to rides for urban areas is 1.5, which means that there is too many drivers, on the other hand there is minimal risk of missing ride or long waiting time

**Conclusion

* PyBer must balance resources by increasing number of drivers in the rural areas and decreasing number of drivers in urban areas 

**Part 2: Time trace of fare prices

(Figure 2.1)
![](/analysis/Fig7.PNG)

* The lowest Pyride income is for rural areas and the highest are for urban areas.
* Urban areas have slight drift up, which suggest potential income growth. 
* Suburban areas also have slight growth in Fares over 4 month period
* Rural areas are at constant low level without visible drift.
* Variation of fares is ~$500 for each city type
* The fares ammount chanes are the fastest the urban areas, ~$500 change every week from Feb. End to March End. 
* For suburban and rural income is more steady: suburban areas changes in fares is ~$500 per month, for rural areas is less than $500

