# **About**

GoalZone is a fitness club chain in Canada.
GoalZone offers a range of fitness classes in two capacities - 25 and 15. Some classes are always fully booked. Fully booked classes often have a low attendance rate. GoalZone wants to increase the number of spaces available for classes. They want to do this by predicting whether the member will attend the class or not. If they can predict a member will not attend the class, they can make another space available.


**Features of the Dataset:**
Column Name Criteria
1. booking_id Nominal. The unique identifier of the booking. Missing values are not possible due to the database structure.
2. months_as_member Discrete. The number of months as this fitness club member, minimum 1 month. Replace missing values with the overall average month.
3. weight Continuous. The member's weight in kg, rounded to 2 decimal places. The minimum possible value is 40.00 kg. Replace missing values with the overall average weight.
4. days_before Discrete. The number of days before the class the member registered, minimum 1 day. Replace missing values with 0.
5. day_of_week Nominal. The day of the week of the class. One of “Mon”, “Tue”, “Wed”, “Thu”, “Fri”, “Sat” or “Sun”. Replace missing values with “unknown”.
6. time Ordinal. The time of day of the class. Either “AM” or “PM”. Replace missing values with “unknown”.
7. category Nominal. The category of the fitness class. One of “Yoga”, “Aqua”, “Strength”, “HIIT”, or “Cycling”. Replace missing values with “unknown”.
8. attended Nominal. Whether the member attended the class (1) or not (0). Missing values should be removed.


**Libraries Used:**

- Numpy 
- Pandas 
- Matplotlib 
- Seaborn


**Skills and Tool Used:**

Python Data cleaning, Data Manipulation and Data Wrangling. Exploratory Data Analysis (Univariate, Bivariate, Multivariate Analysis, and Visualization).


**Disclaimer:**
This dataset is gotten from datacamp practical associate exam.